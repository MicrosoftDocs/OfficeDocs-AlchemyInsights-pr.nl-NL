---
title: Kan niet verwijderen van items in SharePoint of OneDrive
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 21d7b928fade48a6729c120e6ea33b16dafe799e
ms.sourcegitcommit: 22ce2315c8cf643137ab3420cdc1cda41433d44a
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 05/14/2019
ms.locfileid: "34057696"
---
# <a name="unable-to-delete-items"></a>Kan geen items verwijderen

Hebt u problemen items verwijderen?

- Controleer altijd of u beschikt over de [juiste machtigingen](https://docs.microsoft.com/en-us/sharepoint/default-sharepoint-groups) te verwijderen van het item of een poging tot [beheerder van de siteverzameling](https://docs.microsoft.com/en-us/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) het item verwijderen.

- Zorg ervoor dat er niet een [bewaarbeleid](https://docs.microsoft.com/en-us/office365/securitycompliance/retention-policies) instellen op het item.

- Controleer dat het item niet is [uitgecheckt door](https://support.office.com/en-us/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) een andere gebruiker.

- Ten slotte kunnen beheerders gebruiken [SharePoint patronen en werkwijzen](https://docs.microsoft.com/en-us/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP) met een bibliotheek met PowerShell-opdrachten waarmee u acties uit te voeren complexe management, zoals force stubborn items verwijderen. 
- [PNP-bestand verwijderen](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [PNP-map verwijderen](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [Met PNP-lijstitem verwijderen](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [Plug en Play lijst verwijderen](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [Verwijderen van PNP-veld (kolom)](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)