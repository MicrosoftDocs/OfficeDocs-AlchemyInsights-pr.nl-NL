---
title: Microvertragingen of beperkingen in Exchange Online PowerShell
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3500011"
- "5106"
ms.openlocfilehash: 7ab4e7f18b7b8edf08098af8fe9674f66b1b81f4
ms.sourcegitcommit: fbaa2ce2cfb4d56d8c4cf2fa2d95489bdfcb7ff0
ms.translationtype: HT
ms.contentlocale: nl-NL
ms.lasthandoff: 04/30/2020
ms.locfileid: "43947834"
---
# <a name="micro-delays-or-throttling-in-exchange-online-powershell"></a><span data-ttu-id="5faed-102">Microvertragingen of beperkingen in Exchange Online PowerShell</span><span class="sxs-lookup"><span data-stu-id="5faed-102">Micro delays or throttling in Exchange Online PowerShell</span></span>

<span data-ttu-id="5faed-103">U ziet mogelijk waarschuwingen of vertragingen van het type 'Micro delay applied' bij het uitvoeren van scripts en cmdlets in Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="5faed-103">You might see "Micro delay applied" warnings or delays when you run scripts and cmdlets in Exchange Online.</span></span> <span data-ttu-id="5faed-104">In verband hiermee zijn er twee suggesties:</span><span class="sxs-lookup"><span data-stu-id="5faed-104">Here are two suggestions related to this:</span></span>

- <span data-ttu-id="5faed-105">U kunt proberen om de [Exchange Online v2 PowerShell-module](https://docs.microsoft.com/powershell/exchange/exchange-online/exchange-online-powershell-v2/exchange-online-powershell-v2?view=exchange-ps) te gebruiken, die cmdlets bevat die zijn gebaseerd op REST API en aanzienlijk beter worden uitgevoerd.</span><span class="sxs-lookup"><span data-stu-id="5faed-105">You might want to try using the [Exchange Online v2 PowerShell module](https://docs.microsoft.com/powershell/exchange/exchange-online/exchange-online-powershell-v2/exchange-online-powershell-v2?view=exchange-ps), which includes CMDlets that are based on REST API and are significantly more performant.</span></span> <span data-ttu-id="5faed-106">Dit kan een geweldige oplossing zijn voor veel Get-cmdlets die vaak worden gebruikt.</span><span class="sxs-lookup"><span data-stu-id="5faed-106">This might be a great solution for a lot of Get- CMDlets that are frequently used.</span></span>
- <span data-ttu-id="5faed-107">Als u cmdlets wilt gebruiken die nog niet in de v2-module voorkomen, raadpleegt u [Running PowerShell cmdlets for large numbers of users in Office 365](https://techcommunity.microsoft.com/t5/exchange-team-blog/updated-running-powershell-cmdlets-for-large-numbers-of-users-in/ba-p/1000628#) (PowerShell-cmdlets uitvoeren voor een groot aantal gebruikers in Office 365). Hier wordt uitgelegd hoe u de verwachte limieten met betrekking tot PowerShell-beperking in Exchange Online kunt omzeilen.</span><span class="sxs-lookup"><span data-stu-id="5faed-107">If you need to use CMDlets that are not covered in the v2 module yet, please see [Running PowerShell cmdlets for large numbers of users in Office 365](https://techcommunity.microsoft.com/t5/exchange-team-blog/updated-running-powershell-cmdlets-for-large-numbers-of-users-in/ba-p/1000628#), which talks about how to get around expected PowerShell throttling limits in Exchange Online.</span></span>