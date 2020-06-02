---
title: Verbindingsproblemen met SharePoint Designer
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: 01ccc6bc28148f397fb6cd2b7a0eaaeb5b51973f
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 06/02/2020
ms.locfileid: "44511539"
---
# <a name="sharepoint-designer-connection-issues"></a><span data-ttu-id="82d1d-102">Verbindingsproblemen met SharePoint Designer</span><span class="sxs-lookup"><span data-stu-id="82d1d-102">SharePoint Designer connection issues</span></span> 

<span data-ttu-id="82d1d-103">Als SharePoint Designer verbindingsproblemen ondervindt met SharePoint-sites, probeert u de volgende algemene oplossingen.</span><span class="sxs-lookup"><span data-stu-id="82d1d-103">If SharePoint Designer is experiencing connection issues to SharePoint sites, please try the following common solutions.</span></span>

<span data-ttu-id="82d1d-104">Stap 1: Controleer of SharePoint Designer 2013 is bijgewerkt met [SharePoint Designer Service Pack 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) en de [update van 2 augustus 2016 voor SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).</span><span class="sxs-lookup"><span data-stu-id="82d1d-104">Step 1: Verify that SharePoint Designer 2013 is updated with [SharePoint Designer Service Pack 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) and the [August 2, 2016 Update for SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).</span></span>



<span data-ttu-id="82d1d-105">Stap 2: De lokale cachebestanden wissen:</span><span class="sxs-lookup"><span data-stu-id="82d1d-105">Step 2: Clear the local cache files:</span></span>

1. <span data-ttu-id="82d1d-106">Sluit SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="82d1d-106">Close SharePoint Designer 2013.</span></span>

2. <span data-ttu-id="82d1d-107">Verwijder op de lokale computer alle bestanden die in elk van de volgende mappen worden gevonden.</span><span class="sxs-lookup"><span data-stu-id="82d1d-107">On the local computer, remove all files found in each of the following folders.</span></span>

    - <span data-ttu-id="82d1d-108">%APPDATA%\Microsoft\Webserverextensies\Cache</span><span class="sxs-lookup"><span data-stu-id="82d1d-108">%APPDATA%\Microsoft\Web Server Extensions\Cache</span></span>
    - <span data-ttu-id="82d1d-109">%APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache</span><span class="sxs-lookup"><span data-stu-id="82d1d-109">%APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache</span></span>
    - <span data-ttu-id="82d1d-110">%USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span><span class="sxs-lookup"><span data-stu-id="82d1d-110">%USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span></span>

3. <span data-ttu-id="82d1d-111">Open SharePoint Designer 2013 en voer het account opnieuw in om te zien of het werkt.</span><span class="sxs-lookup"><span data-stu-id="82d1d-111">Open SharePoint Designer 2013 and enter the account again to see if it works.</span></span>

<span data-ttu-id="82d1d-112">Stap 3: [Moderne verificatie voor Office 2013 inschakelen op Windows-apparaten](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).</span><span class="sxs-lookup"><span data-stu-id="82d1d-112">Step 3: [Enable Modern Authentication for Office 2013 on Windows Devices](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).</span></span>

<span data-ttu-id="82d1d-113">Stap 4: Beheerders moeten **aangepast script toestaan** in de instellingen van het SharePoint-beheercentrum om de SharePoint Designer-verbinding toe te staan.</span><span class="sxs-lookup"><span data-stu-id="82d1d-113">Step 4: Administrators will need to **Allow Custom Script** in the SharePoint Admin Center settings to allow the SharePoint Designer connection.</span></span> <span data-ttu-id="82d1d-114">Zie [Aangepast script toestaan of voorkomen](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) voor meer informatie.</span><span class="sxs-lookup"><span data-stu-id="82d1d-114">See [Allow or prevent custom script](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) for more information.</span></span>


