---
title: Dubbele apparaatrecord in de portal
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9001495"
- "4386"
ms.openlocfilehash: e6f477807823e68965ce966faf0a6f50f9472f3d
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: HT
ms.contentlocale: nl-NL
ms.lasthandoff: 04/15/2021
ms.locfileid: "51814511"
---
# <a name="duplicate-device-record-in-the-portal"></a>Dubbele apparaatrecord in de portal

U kunt twee records zien voor een apparaat in de portal als de status van het co-beheer niet correct wordt gerapporteerd voor de site van Configuration Manager. Voor het controleren van de status van het co-beheer van apparaat, raadpleegt u de kolom **Met co-beheer** van het apparaat in de Configuration Manager-console. Als de kolom niet zichtbaar is, kunt u deze toevoegen door met de rechtermuisknop op een van de kolomkoppen te klikken en deze in de lijst te selecteren.

De waarde Met co-beheer moet **Ja** zijn. Als de waarde **Nee** is, opent u de applet Configuration Manager-client op het clientapparaat en controleert u de eigenschap **Co-beheer** op het tabblad Algemeen.

- Als de waarde **Ingeschakeld** is, duidt dit op problemen met clientcommunicatie met het beheerpunt. Bekijk **CcmMessaging.log** op het apparaat om mogelijke verbindingsproblemen te onderzoeken.

- Als de waarde **Ingeschakeld** is en het apparaat is geregistreerd bij intune, controleert u of het apparaat het beleid voor co-beheer heeft ontvangen door **CoManagementHandler.log** op het apparaat te bekijken.
