---
title: Berichten aan Microsoft 365-groep niet door alle leden ontvangen
ms.author: pebaum
author: pebaum
manager: mnirkhe
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9003200"
- "5995"
ms.openlocfilehash: 39a4f8115a4742947b3e6394396be5ce3b01e772
ms.sourcegitcommit: 379e132c4d21ecf703d5506484ec96a767fdda39
ms.translationtype: HT
ms.contentlocale: nl-NL
ms.lasthandoff: 03/04/2021
ms.locfileid: "50430678"
---
# <a name="messages-sent-to-a-microsoft-365-group-are-not-received-by-all-members"></a>Berichten aan een Microsoft 365-groep worden niet door alle leden ontvangen

Controleer of alle groepsleden zich op de e-mails hebben geabonneerd. Zie [Een groep volgen in Outlook](https://support.microsoft.com/office/e147fc19-f548-4cd2-834f-80c6235b7c36).  

Voer de volgende opdracht uit in [EXO PowerShell](https://docs.microsoft.com/powershell/exchange/connect-to-exchange-online-powershell?view=exchange-ps&preserve-view=true) om de berichtstatus van leden die zich op groeps-e-mailberichten hebben geabonneerd te controleren:

`Get-UnifiedGroup <GroupName> | Get-UnifiedGroupLinks -LinkType Subscribers`

Gebruik de volgende EXO PowerShell-opdracht om alle groepsleden zo te configureren dat ze e-mails aan een Microsoft 365-groep in hun Postvak IN ontvangen:

`$Group = "Address of [Microsoft 365 Groups]"Get-UnifiedGroupLinks $Group -LinkType Member | % {Add-UnifiedGroupLinks -Identity $Group -LinkType subscriber -Links $_.Guid.toString() -Confirm:$false}`