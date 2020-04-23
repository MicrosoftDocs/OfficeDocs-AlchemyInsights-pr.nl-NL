---
title: Profielsynchronisatie
ms.author: arnek
author: arnek
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6b695be8-eaf5-44ff-b0ae-1e0d89e7ab36
ms.openlocfilehash: dc6e0280961d14aa3e6bd466afbe0cbe89418d17
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 04/22/2020
ms.locfileid: "43768108"
---
# <a name="when-do-my-profile-changes-sync-to-the-sharepoint-user-profile-application"></a><span data-ttu-id="ccb3a-102">Wanneer worden mijn profielwijzigingen gesynchroniseerd met de SharePoint-gebruikersprofieltoepassing?</span><span class="sxs-lookup"><span data-stu-id="ccb3a-102">When do my profile changes sync to the SharePoint User Profile Application?</span></span>

<span data-ttu-id="ccb3a-103">SharePoint Online gebruikt de timertaak Active Directory Import (AD Import) om gebruikers en groepen te importeren in de gebruikersprofieltoepassing.</span><span class="sxs-lookup"><span data-stu-id="ccb3a-103">SharePoint Online uses the Active Directory Import timer job (AD Import) to import users and groups into the User Profile Application.</span></span> 
  
1. <span data-ttu-id="ccb3a-104">Ad Import synchroniseert wijzigingen van de SharePoint Online Directory Store naar de gebruikersprofieltoepassing.</span><span class="sxs-lookup"><span data-stu-id="ccb3a-104">AD Import syncs changes from the SharePoint Online Directory Store to the User Profile Application.</span></span> <span data-ttu-id="ccb3a-105">Deze wijzigingen worden in batches verwerkt.</span><span class="sxs-lookup"><span data-stu-id="ccb3a-105">These changes are processed in batches.</span></span>
    
2. <span data-ttu-id="ccb3a-106">De timertaak wordt uitgevoerd totdat de wijzigingen zijn gesynchroniseerd.</span><span class="sxs-lookup"><span data-stu-id="ccb3a-106">The timer job runs until the changes are synced.</span></span>
    
> [!NOTE]
> <span data-ttu-id="ccb3a-107">De tijd die de taak nodig heeft om uit te voeren, is afhankelijk van het aantal wijzigingen dat moet worden verwerkt.</span><span class="sxs-lookup"><span data-stu-id="ccb3a-107">The time it takes the job to run depends on the number of changes to process.</span></span> <span data-ttu-id="ccb3a-108">Een groot aantal wijzigingen duurt langer.</span><span class="sxs-lookup"><span data-stu-id="ccb3a-108">A large number of changes takes longer.</span></span> <span data-ttu-id="ccb3a-109">In de SLA (Service Level Agreement) staat dat een wijziging in de SharePoint Online-map binnen 24 uur wordt weergegeven in de gebruikersprofieltoepassing.</span><span class="sxs-lookup"><span data-stu-id="ccb3a-109">The Service Level Agreement (SLA) states that a change to a user in the SharePoint Online Directory will be reflected in the User Profile Application in 24 hours.</span></span> 
  
[<span data-ttu-id="ccb3a-110">Meer informatie over synchronisatie van gebruikersprofielen in SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="ccb3a-110">More info about user profile sync in SharePoint Online</span></span>](https://go.microsoft.com/fwlink/?linkid=875671)
  

