---
title: Profielsynchronisatie
ms.author: arnek
author: arnek
ms.date: 6/20/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6b695be8-eaf5-44ff-b0ae-1e0d89e7ab36
ms.openlocfilehash: b9b90dad6c5fa41afcd4e4c9a929594735eca066
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 10/18/2019
ms.locfileid: "36554328"
---
# <a name="when-do-my-profile-changes-sync-to-the-sharepoint-user-profile-application"></a><span data-ttu-id="1cf07-102">Wanneer verandert mijn profielsynchronisatie met de SharePoint-Gebruikersprofieltoepassing?</span><span class="sxs-lookup"><span data-stu-id="1cf07-102">When do my profile changes sync to the SharePoint User Profile Application?</span></span>

<span data-ttu-id="1cf07-103">SharePoint Online gebruikt de timeropdracht voor het importeren van Active Directory (AD import) om gebruikers en groepen te importeren in de Gebruikersprofieltoepassing.</span><span class="sxs-lookup"><span data-stu-id="1cf07-103">SharePoint Online uses the Active Directory Import timer job (AD Import) to import users and groups into the User Profile Application.</span></span> 
  
1. <span data-ttu-id="1cf07-104">AD import synchroniseert wijzigingen van het SharePoint Online-adreslijstarchief naar de Gebruikersprofieltoepassing.</span><span class="sxs-lookup"><span data-stu-id="1cf07-104">AD Import syncs changes from the SharePoint Online Directory Store to the User Profile Application.</span></span> <span data-ttu-id="1cf07-105">Deze wijzigingen worden verwerkt in batches.</span><span class="sxs-lookup"><span data-stu-id="1cf07-105">These changes are processed in batches.</span></span>
    
2. <span data-ttu-id="1cf07-106">De timeropdracht wordt uitgevoerd totdat de wijzigingen zijn gesynchroniseerd.</span><span class="sxs-lookup"><span data-stu-id="1cf07-106">The timer job runs until the changes are synced.</span></span>
    
> [!NOTE]
> <span data-ttu-id="1cf07-107">De tijd die het duurt voordat de taak wordt uitgevoerd, is afhankelijk van het aantal wijzigingen dat moet worden verwerkt.</span><span class="sxs-lookup"><span data-stu-id="1cf07-107">The time it takes the job to run depends on the number of changes to process.</span></span> <span data-ttu-id="1cf07-108">Een groot aantal wijzigingen duurt langer.</span><span class="sxs-lookup"><span data-stu-id="1cf07-108">A large number of changes takes longer.</span></span> <span data-ttu-id="1cf07-109">De Service Level Agreement (SLA) staat dat een wijziging aan een gebruiker in de SharePoint Online-map wordt weergegeven in de toepassing gebruikersprofiel in 24 uur.</span><span class="sxs-lookup"><span data-stu-id="1cf07-109">The Service Level Agreement (SLA) states that a change to a user in the SharePoint Online Directory will be reflected in the User Profile Application in 24 hours.</span></span> 
  
[<span data-ttu-id="1cf07-110">Meer informatie over synchronisatie van gebruikersprofielen in SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1cf07-110">More info about user profile sync in SharePoint Online</span></span>](https://go.microsoft.com/fwlink/?linkid=875671)
  

