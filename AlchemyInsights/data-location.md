---
title: Gegevenslocatie
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "945"
- "5300023"
ms.assetid: 3bab036c-dbaa-406a-8b73-1e5f31993436
ms.openlocfilehash: c769c17796d805f88afb4d5b32adb7d4a9bb3ce0
ms.sourcegitcommit: 6bf1d945b4fd6a1fe37d00c5ea99adea7eef9910
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 04/21/2020
ms.locfileid: "43655277"
---
# <a name="data-location"></a><span data-ttu-id="4b170-102">Gegevenslocatie</span><span class="sxs-lookup"><span data-stu-id="4b170-102">Data location</span></span>

<span data-ttu-id="4b170-103">U de locatie van uw tenant bekijken in het beheercentrum of door verbinding te maken met Exchange Online via PowerShell.</span><span class="sxs-lookup"><span data-stu-id="4b170-103">You can view the location of your tenant in the admin center or by connecting to Exchange Online via PowerShell.</span></span>


<span data-ttu-id="4b170-104">**Beheercentrum:**</span><span class="sxs-lookup"><span data-stu-id="4b170-104">**Admin center:**</span></span>
1. <span data-ttu-id="4b170-105">Log in bij het [beheercentrum](https://admin.microsoft.com/Adminportal/Home).</span><span class="sxs-lookup"><span data-stu-id="4b170-105">Log in to the [admin center](https://admin.microsoft.com/Adminportal/Home).</span></span>
2. <span data-ttu-id="4b170-106">Selecteer Het profiel **van instellingenorganisatie** > **Organization profile**.</span><span class="sxs-lookup"><span data-stu-id="4b170-106">Select **Settings** > **Organization profile**.</span></span>
3. <span data-ttu-id="4b170-107">Selecteer **onder Gegevenslocatie**de optie **Details weergeven**.</span><span class="sxs-lookup"><span data-stu-id="4b170-107">Under **Data location**, select **View details**.</span></span>


<span data-ttu-id="4b170-108">**Powershell:**</span><span class="sxs-lookup"><span data-stu-id="4b170-108">**PowerShell:**</span></span>
1. <span data-ttu-id="4b170-109">Maak verbinding met Exchange Online met Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="4b170-109">Connect to Exchange Online by using Windows PowerShell.</span></span>
2. <span data-ttu-id="4b170-110">Voer de cmdlet [Get-OrganizationalUnit](https://docs.microsoft.com/powershell/module/exchange/active-directory/get-organizationalunit) uit om een lijst met de eigenschappen van uw tenant weer te geven.</span><span class="sxs-lookup"><span data-stu-id="4b170-110">Execute the [Get-OrganizationalUnit](https://docs.microsoft.com/powershell/module/exchange/active-directory/get-organizationalunit) cmdlet to display a list of your tenant's properties.</span></span> 
3. <span data-ttu-id="4b170-111">Kijk naar de OrganizationId eigendom.</span><span class="sxs-lookup"><span data-stu-id="4b170-111">Look at the OrganizationId property.</span></span>

<span data-ttu-id="4b170-112">Wanneer u de gegevenslocatie voor EXO en SPO hebt, u de gegevenslocatie bepalen voor andere services die u gebruiken vanaf [de plaats waar uw gegevens zich bevinden.](https://products.office.com/where-is-your-data-located)</span><span class="sxs-lookup"><span data-stu-id="4b170-112">When you have the data location for EXO and SPO, you can determine the data location for other services you may use from [Where your data is located](https://products.office.com/where-is-your-data-located).</span></span>