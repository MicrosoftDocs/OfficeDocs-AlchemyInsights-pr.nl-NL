---
title: Problemen met e-mail bezorging bij openbare mappen met e-mail oplossen
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1956"
- "3500007"
ms.openlocfilehash: 74a26306766ed7952a3bbbcb06f1f0113a113024
ms.sourcegitcommit: 9fd002ce49ad9a7e58c3eb997a8063e2e1feab55
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 10/06/2020
ms.locfileid: "48366459"
---
# <a name="fix-email-delivery-issues-to-mail-enabled-public-folders"></a>Problemen met e-mail bezorging bij openbare mappen met e-mail oplossen

Als externe afzenders geen berichten kunnen verzenden naar uw openbare mappen met e-mail en de afzenders ontvangen de fout: is **niet gevonden (550 5.4.1)**, controleert u of het e-mail domein voor de openbare map is geconfigureerd als een intern doorstuur domein in plaats van een gezaghebbend domein:

1. Open het [Exchange-Beheercentrum](https://docs.microsoft.com/Exchange/exchange-admin-center).

2. Ga naar geaccepteerde **e-mail stroom** \> **domeinen**, selecteer het geaccepteerde domein en klik vervolgens op **bewerken**.

3. Als het domeintype is ingesteld op **gezaghebbend**, wijzigt u op de pagina met **Eigenschappen op de gewenste waarde en klikt** u vervolgens op **Opslaan**.

Als externe afzenders de foutmelding krijgt **dat u geen machtiging hebt (550 5.7.13)**, voert u de volgende opdracht uit in [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell) om de machtigingen voor anonieme gebruikers in de openbare map weer te geven:

`Get-PublicFolderClientPermission -Identity "<PublicFolderIdentity>" -User Anonymous` Voor `Get-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous` Beeld:

Als u wilt toestaan dat externe gebruikers e-mail verzenden naar deze openbare map, voegt u de CreateItem-toegang rechtstreeks toe aan de gebruiker. Bijvoorbeeld `Add-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous -AccessRights CreateItems`.
