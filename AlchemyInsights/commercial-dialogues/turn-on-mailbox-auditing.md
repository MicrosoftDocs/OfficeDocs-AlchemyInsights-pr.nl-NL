---
title: Postvakcontrole in-
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 02/26/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3100005"
- "7327"
ms.openlocfilehash: aa0ff925ae891d28e31394ec66eb17c2d9710008
ms.sourcegitcommit: 251e2e82571fb3bb1fbe3dbf7bfca30e004b3373
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 03/05/2021
ms.locfileid: "50481651"
---
# <a name="turn-on-mailbox-auditing"></a>Postvakcontrole in-

Voer de volgende cmdlets uit vanuit externe PowerShell om postvakcontrole voor één gebruiker of de hele organisatie in te voeren:

- **Eén gebruiker:** Set-Mailbox -Identity "Jane Dow" -AuditEnabled $true
- **Organisatie**: Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true

Zie Postvak controleren beheren [voor meer informatie.](https://go.microsoft.com/fwlink/?linkid=2103668)