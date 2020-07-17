---
title: hetzelfde als bestandsnaam is het beste
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: bd2901580acdb1dc17f3e14a7a9356b07e70f910
ms.sourcegitcommit: bf6a0e80d09aebae19b9e993c2552b88e49177c9
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 06/16/2020
ms.locfileid: "44750965"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a><span data-ttu-id="5c800-102">"Vereiste Alchemie Header H1, H2's werken niet."</span><span class="sxs-lookup"><span data-stu-id="5c800-102">"Required Alchemy Header H1, H2's dont work."</span></span>
<span data-ttu-id="5c800-103">Aanbevolen procedures en richtlijnen voor het schrijven van alchemie:</span><span class="sxs-lookup"><span data-stu-id="5c800-103">Best Practices and guidelines for Alchemy authoring:</span></span>

1. <span data-ttu-id="5c800-104">**Nest geen Alchemy Insights in mappen**- dit zal de url-structuur breken.</span><span class="sxs-lookup"><span data-stu-id="5c800-104">**Do not nest Alchemy Insights in folders**- this will break the url structure.</span></span> <span data-ttu-id="5c800-105">We onderzoeken het repareren van dit.</span><span class="sxs-lookup"><span data-stu-id="5c800-105">We're looking into fixing this.</span></span>
1. <span data-ttu-id="5c800-106">Bestanden in de map **AlchemyInsights** moeten kleine bestandsnamen hebben met koppeltekens voor spaties ex.</span><span class="sxs-lookup"><span data-stu-id="5c800-106">Files in the **AlchemyInsights** folder should have lowercase filenames with hyphens for spaces ex.</span></span> <span data-ttu-id="5c800-107">***how-to-enable-litigation-hold***.</span><span class="sxs-lookup"><span data-stu-id="5c800-107">***how-to-enable-litigation-hold***.</span></span>
    1. <span data-ttu-id="5c800-108">Neem de regel-id of bucket-id op uit de [Alchemy Partner-portal](https://alchemyportal.azurewebsites.net) in het veld ms.custom.</span><span class="sxs-lookup"><span data-stu-id="5c800-108">Include the Rule ID or bucket ID from the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) in the ms.custom field.</span></span> <span data-ttu-id="5c800-109">Ex.</span><span class="sxs-lookup"><span data-stu-id="5c800-109">ex.</span></span> <span data-ttu-id="5c800-110">***ms.custom: 100021***</span><span class="sxs-lookup"><span data-stu-id="5c800-110">***ms.custom: 100021***</span></span>
1. <span data-ttu-id="5c800-111">Gebruik de rest van de metagegevens boven aan dit bestand als sjabloon.</span><span class="sxs-lookup"><span data-stu-id="5c800-111">Use the rest of the metadata at the top of this file as your template.</span></span>
1. <span data-ttu-id="5c800-112">Navigeer in de [Alchemy Partner-portal](https://alchemyportal.azurewebsites.net)naar de sectie **Customer Insight Title:** en gebruik die als uitgangspunt voor uw H1-titel voor het inzicht.</span><span class="sxs-lookup"><span data-stu-id="5c800-112">In the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net), navigate down to the section **Customer Insight Title:** and use that as a starting point for your H1 title for the insight.</span></span> 
    > [!NOTE]
    > <span data-ttu-id="5c800-113">Alchemie Insights MOET slechts een enkele H1 aan de top hebben of ze zullen breken in de productie.</span><span class="sxs-lookup"><span data-stu-id="5c800-113">Alchemy Insights MUST have only a single H1 at the top or they will break in production.</span></span> <span data-ttu-id="5c800-114">H2's maken geen gebruik van, dus gebruik **vet** of andere conventies om afzonderlijke secties aan te geven.</span><span class="sxs-lookup"><span data-stu-id="5c800-114">H2s dont render either so use **bold** or other conventions to signify separate sections.</span></span>
1. <span data-ttu-id="5c800-115">Vul vervolgens de hoofdtekst in met het conceptmateriaal in de sectie Customer Insights van de pagina Alchemieregel</span><span class="sxs-lookup"><span data-stu-id="5c800-115">Next, fill in the body text using the draft material in the Customer Insights section of the Alchemy Rule page</span></span>
    1. <span data-ttu-id="5c800-116">Lijsten met opsommingstekens zijn prima</span><span class="sxs-lookup"><span data-stu-id="5c800-116">Bulleted lists are fine</span></span>
    1. <span data-ttu-id="5c800-117">Ook genummerde lijsten</span><span class="sxs-lookup"><span data-stu-id="5c800-117">Numbered lists too</span></span>
    1. <span data-ttu-id="5c800-118">**Vet** en *cursisch* zijn a-ok</span><span class="sxs-lookup"><span data-stu-id="5c800-118">**Bold** and *italic* are a-ok</span></span>
    1. <span data-ttu-id="5c800-119">Links moeten altijd ofwel **"links naar web" / externe** of **deep-links naar UI-elementen,** niet interne links.</span><span class="sxs-lookup"><span data-stu-id="5c800-119">Links should always be either **"links to web"/external** OR **deep-links to UI elements**, not internal links.</span></span>
    1. <span data-ttu-id="5c800-120">Foto's worden op dit moment niet officieel ondersteund, maar het staat wel op de roadmap.</span><span class="sxs-lookup"><span data-stu-id="5c800-120">Pictures are not officially supported at this time, but it's on the roadmap.</span></span>

<span data-ttu-id="5c800-121">En dit is echt al een beetje te lang.</span><span class="sxs-lookup"><span data-stu-id="5c800-121">And this is really already a bit too long.</span></span> <span data-ttu-id="5c800-122">Best practice is ongeveer 400 tekens ---------------------------------</span><span class="sxs-lookup"><span data-stu-id="5c800-122">Best practice is about 400 characters ---------------------------------</span></span>

<span data-ttu-id="5c800-123">Zodra uw inhoud klaar is, trekt u deze naar de live branch.</span><span class="sxs-lookup"><span data-stu-id="5c800-123">Once your content is ready, pull it to the live branch.</span></span> <span data-ttu-id="5c800-124">Ga vervolgens naar de [Portal Alchemy Partner](https://alchemyportal.azurewebsites.net) en voer de bestandsnaam in het url-veld in.</span><span class="sxs-lookup"><span data-stu-id="5c800-124">Then, go to the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) and enter the filename into the url field.</span></span> 