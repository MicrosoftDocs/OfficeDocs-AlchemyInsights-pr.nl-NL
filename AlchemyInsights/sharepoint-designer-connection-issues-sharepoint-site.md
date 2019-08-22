---
title: Problemen met SharePoint Designer
ms.author: efrene
author: efrene
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: a4aeaeaea5743c276b907c78317ff30f5610be81
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 08/22/2019
ms.locfileid: "36508418"
---
# <a name="sharepoint-designer-connection-issues"></a><span data-ttu-id="a0b1b-102">Problemen met SharePoint Designer</span><span class="sxs-lookup"><span data-stu-id="a0b1b-102">SharePoint Designer connection issues</span></span> 

<span data-ttu-id="a0b1b-103">Als u SharePoint Designer ondervindt problemen met de verbinding met de SharePoint-sites, probeert u de volgende algemene oplossingen.</span><span class="sxs-lookup"><span data-stu-id="a0b1b-103">If SharePoint Designer is experiencing connection issues to SharePoint sites, please try the following common solutions.</span></span>

<span data-ttu-id="a0b1b-104">Stap 1: Controleren of SharePoint Designer 2013 is bijgewerkt met [SharePoint Designer Service Pack 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) en [2 augustus 2016 bijwerken voor SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).</span><span class="sxs-lookup"><span data-stu-id="a0b1b-104">Step 1: Verify that SharePoint Designer 2013 is updated with [SharePoint Designer Service Pack 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) and the [August 2, 2016 Update for SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).</span></span>



<span data-ttu-id="a0b1b-105">Stap 2: Wis de bestanden in de lokale cache:</span><span class="sxs-lookup"><span data-stu-id="a0b1b-105">Step 2: Clear the local cache files:</span></span>

1. <span data-ttu-id="a0b1b-106">Sluit de SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="a0b1b-106">Close SharePoint Designer 2013.</span></span>

2. <span data-ttu-id="a0b1b-107">Verwijder alle bestanden in de volgende mappen op de lokale computer.</span><span class="sxs-lookup"><span data-stu-id="a0b1b-107">On the local computer, remove all files found in each of the following folders.</span></span>

    - <span data-ttu-id="a0b1b-108">%AppData%\Microsoft\Web server Extensions\Cache</span><span class="sxs-lookup"><span data-stu-id="a0b1b-108">%APPDATA%\Microsoft\Web Server Extensions\Cache</span></span>
    - <span data-ttu-id="a0b1b-109">%AppData%\Microsoft\SharePoint Designer\ProxyAssemblyCache</span><span class="sxs-lookup"><span data-stu-id="a0b1b-109">%APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache</span></span>
    - <span data-ttu-id="a0b1b-110">%USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span><span class="sxs-lookup"><span data-stu-id="a0b1b-110">%USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span></span>

3. <span data-ttu-id="a0b1b-111">SharePoint Designer 2013 openen en geef de account opnieuw om te zien als het werkt.</span><span class="sxs-lookup"><span data-stu-id="a0b1b-111">Open SharePoint Designer 2013 and enter the account again to see if it works.</span></span>

<span data-ttu-id="a0b1b-112">Stap 3: [moderne-verificatie inschakelen voor Office 2013 op Windows-apparaten](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide).</span><span class="sxs-lookup"><span data-stu-id="a0b1b-112">Step 3: [Enable Modern Authentication for Office 2013 on Windows Devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide).</span></span>

<span data-ttu-id="a0b1b-113">Stap 4: Beheerders moet **Toestaan aangepast Script** in de Admin Center van SharePoint instellingen voor de verbinding van SharePoint Designer toestaan.</span><span class="sxs-lookup"><span data-stu-id="a0b1b-113">Step 4: Administrators will need to **Allow Custom Script** in the SharePoint Admin Center settings to allow the SharePoint Designer connection.</span></span> <span data-ttu-id="a0b1b-114">Zie [toestaan of voorkomen van aangepast script](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) voor meer informatie.</span><span class="sxs-lookup"><span data-stu-id="a0b1b-114">See [Allow or prevent custom script](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) for more information.</span></span>


