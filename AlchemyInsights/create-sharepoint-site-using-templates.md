---
title: Een site maken in SharePoint Online
ms.author: pebaum
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 84f2b70e-2b23-4039-8305-85783798feed
ms.openlocfilehash: 42430c8dadc17b87dc7741f3fa045ba7c25fab84
ms.sourcegitcommit: a65d196d00adb70045af5caca9828fe44b951f61
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 09/04/2019
ms.locfileid: "36755303"
---
# <a name="create-sharepoint-sites-using-templates"></a><span data-ttu-id="2fc09-102">SharePoint-sites maken met behulp van sjablonen</span><span class="sxs-lookup"><span data-stu-id="2fc09-102">Create SharePoint sites using templates</span></span>

<span data-ttu-id="2fc09-103">SharePoint-sitesjablonen zijn vooraf gedefinieerde definities die zijn ontworpen rond een bepaalde zakelijke behoefte.</span><span class="sxs-lookup"><span data-stu-id="2fc09-103">SharePoint site templates are prebuilt definitions designed around a particular business need.</span></span> <span data-ttu-id="2fc09-104">Zie [sjablonen gebruiken om verschillende soorten SharePoint-sites te maken](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4)voor meer informatie.</span><span class="sxs-lookup"><span data-stu-id="2fc09-104">For more information, see [Using templates to create different kinds of SharePoint sites](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).</span></span>

<span data-ttu-id="2fc09-105">Hier volgen enkele veelvoorkomende problemen/oplossingen met betrekking tot het opslaan van een site of lijst als een sjabloon in SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="2fc09-105">Here are some common issues/solutions regarding Saving a Site or List as a template in Sharepoint Online.</span></span> 

<span data-ttu-id="2fc09-106">**De knop site/lijstsjabloon opslaan is niet beschikbaar of ontbreekt**</span><span class="sxs-lookup"><span data-stu-id="2fc09-106">**Save site/list template button is not available or missing**</span></span>

<span data-ttu-id="2fc09-107">Beheerders moeten het aangepaste script toestaan om de sjabloonfuncties in te schakelen.</span><span class="sxs-lookup"><span data-stu-id="2fc09-107">Administrators will need to Allow Custom Script to enable the template features.</span></span> <span data-ttu-id="2fc09-108">Zie voor gedetailleerde stappen, voorbeelden en overwegingen</span><span class="sxs-lookup"><span data-stu-id="2fc09-108">For detailed steps, examples and considerations see</span></span> 

- [<span data-ttu-id="2fc09-109">Aangepast script toestaan of voorkomen</span><span class="sxs-lookup"><span data-stu-id="2fc09-109">Allow or prevent custom script</span></span>](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script)

- <span data-ttu-id="2fc09-110">De opdracht site opslaan als sjabloon wordt niet ondersteund en kan problemen veroorzaken op sites die gebruikmaken van de SharePoint Server Publishing-infrastructuur.</span><span class="sxs-lookup"><span data-stu-id="2fc09-110">The Save site as template command is not supported and can cause problems on sites that use the SharePoint Server Publishing Infrastructure.</span></span>

<span data-ttu-id="2fc09-111">**De sitesjabloon kan niet worden gemaakt of werkt niet correct**</span><span class="sxs-lookup"><span data-stu-id="2fc09-111">**The site template cannot be created or does not work correctly**</span></span>

<span data-ttu-id="2fc09-112">De sjabloon ontbreekt mogelijk een [functie](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) en wordt niet geactiveerd.</span><span class="sxs-lookup"><span data-stu-id="2fc09-112">The template may be missing a [feature](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) and won't activate.</span></span> <span data-ttu-id="2fc09-113">Als de functie niet beschikbaar is om te activeren in de huidige siteverzameling, u de sitesjabloon niet gebruiken om een site te maken.</span><span class="sxs-lookup"><span data-stu-id="2fc09-113">If the feature is not available to activate in the current site collection, you cannot use the site template to create a site.</span></span>

- <span data-ttu-id="2fc09-114">Controleer of er lijsten of bibliotheken zijn die de [limiet drempel voor lijstweergave](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) van 5000 items overschrijden, omdat hierdoor het maken van een sitesjabloon kan worden geblokkeerd.</span><span class="sxs-lookup"><span data-stu-id="2fc09-114">Check to see if any lists or libraries exceed the [List View Limit Threshold](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) of 5000 items as this can block creation of a site template.</span></span>

- <span data-ttu-id="2fc09-115">De site kan worden gebruikt te veel bronnen en daarom de sitesjabloon overschrijdt de limiet van 50 MB.</span><span class="sxs-lookup"><span data-stu-id="2fc09-115">The site may be using too many resources and therefore the site template exceeds the 50 MB limit.</span></span>


- <span data-ttu-id="2fc09-116">Er zijn problemen met het weergeven van gegevens uit een lijst die gebruikmaakt van een opzoekkolom.</span><span class="sxs-lookup"><span data-stu-id="2fc09-116">There are problems displaying data from a list that uses a lookup column.</span></span> <span data-ttu-id="2fc09-117">Zie voor meer informatie, [sjabloon gegenereerde lijstgegevens uit de juiste opzoeklijst in SharePoint Online niet weergegeven](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).</span><span class="sxs-lookup"><span data-stu-id="2fc09-117">For more information, see [Template-generated list doesn't display data from the correct lookup list in SharePoint Online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).</span></span>

<span data-ttu-id="2fc09-118">Voor meer gedetailleerde informatie over veelvoorkomende problemen en oplossingen raadpleegt u [sitesjablonen maken en gebruiken](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span><span class="sxs-lookup"><span data-stu-id="2fc09-118">For more detailed information on common problems and solutions, please check [Create and use site templates](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span></span>



