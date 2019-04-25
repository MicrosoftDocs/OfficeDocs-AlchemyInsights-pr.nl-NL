---
title: Synchronisatie van het profiel
ms.author: arnek
author: arnek
ms.date: 6/20/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6b695be8-eaf5-44ff-b0ae-1e0d89e7ab36
ms.openlocfilehash: d1a72a85767e36fefbfa8eee266befcaf2e48af0
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 04/23/2019
ms.locfileid: "32371979"
---
# <a name="when-do-my-profile-changes-sync-to-the-sharepoint-user-profile-application"></a><span data-ttu-id="6104f-102">Wanneer mijn profielwijzigingen synchroniseren met de SharePoint-profiel van toepassing?</span><span class="sxs-lookup"><span data-stu-id="6104f-102">When do my profile changes sync to the SharePoint User Profile Application?</span></span>

<span data-ttu-id="6104f-103">SharePoint Online maakt gebruik van de timeropdracht Active Directory importeren (AD importeren) importeren van gebruikers en groepen in de gebruikersprofieltoepassing.</span><span class="sxs-lookup"><span data-stu-id="6104f-103">SharePoint Online uses the Active Directory Import timer job (AD Import) to import users and groups into the User Profile Application.</span></span> 
  
1. <span data-ttu-id="6104f-104">AD importeren wordt gesynchroniseerd wijzigingen van toepassing voor het gebruikersprofiel van de opslag van SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="6104f-104">AD Import syncs changes from the SharePoint Online Directory Store to the User Profile Application.</span></span> <span data-ttu-id="6104f-105">Deze wijzigingen worden verwerkt in batches.</span><span class="sxs-lookup"><span data-stu-id="6104f-105">These changes are processed in batches.</span></span>
    
2. <span data-ttu-id="6104f-106">De timeropdracht wordt uitgevoerd totdat de wijzigingen worden gesynchroniseerd.</span><span class="sxs-lookup"><span data-stu-id="6104f-106">The timer job runs until the changes are synced.</span></span>
    
> [!NOTE]
> <span data-ttu-id="6104f-107">Duurt de taak wilt uitvoeren, is afhankelijk van het aantal wijzigingen te verwerken.</span><span class="sxs-lookup"><span data-stu-id="6104f-107">The time it takes the job to run depends on the number of changes to process.</span></span> <span data-ttu-id="6104f-108">Een groot aantal wijzigingen duurt langer.</span><span class="sxs-lookup"><span data-stu-id="6104f-108">A large number of changes takes longer.</span></span> <span data-ttu-id="6104f-109">Service niveau overeenkomst (SLA) geeft aan dat een wijziging van een gebruiker in de SharePoint Online-map worden weergegeven in de toepassing voor gebruikersprofiel in 24 uur.</span><span class="sxs-lookup"><span data-stu-id="6104f-109">The Service Level Agreement (SLA) states that a change to a user in the SharePoint Online Directory will be reflected in the User Profile Application in 24 hours.</span></span> 
  
[<span data-ttu-id="6104f-110">Meer informatie over synchronisatie van gebruikersprofielen in SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="6104f-110">More info about user profile sync in SharePoint Online</span></span>](https://go.microsoft.com/fwlink/?linkid=875671)
  

