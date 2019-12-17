---
title: Dagelijkse e-mail limiet overschreden. Werkstroom is onderbroken.
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1227"
ms.openlocfilehash: 3cad5d8305da0a5db9a85888793350a062e6aed6
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 12/15/2019
ms.locfileid: "40053112"
---
# <a name="daily-email-limit-exceeded-workflow-is-suspended"></a><span data-ttu-id="c6ba6-103">Dagelijkse e-mail limiet overschreden.</span><span class="sxs-lookup"><span data-stu-id="c6ba6-103">Daily email Limit Exceeded.</span></span> <span data-ttu-id="c6ba6-104">Werkstroom is onderbroken.</span><span class="sxs-lookup"><span data-stu-id="c6ba6-104">Workflow is suspended.</span></span>

<span data-ttu-id="c6ba6-105">Deze fout kan worden ontvangen in de volgende scenario's:</span><span class="sxs-lookup"><span data-stu-id="c6ba6-105">This error may be received in the following scenarios:</span></span>

- <span data-ttu-id="c6ba6-106">U hebt een werkstroom in SharePoint Online die gebruikmaakt van het type SharePoint 2010 of SharePoint 2013 werkstroom platform.</span><span class="sxs-lookup"><span data-stu-id="c6ba6-106">You have a workflow in SharePoint Online that's using the SharePoint 2010 or SharePoint 2013 workflow platform type.</span></span>
- <span data-ttu-id="c6ba6-107">De werkstroom is geconfigureerd voor het verzenden van een aangepast e-mail bericht naar meer dan 200 gebruikers tegelijk, meer dan 10.000 geadresseerden per dag of meer dan 30 berichten per minuut.</span><span class="sxs-lookup"><span data-stu-id="c6ba6-107">The workflow is configured to send a custom email message to more than 200 users at a time, more than 10,000 recipients per day, or more than 30 messages per minute.</span></span>
- <span data-ttu-id="c6ba6-108">Wanneer u de werkstroom uitvoert, wordt het e-mail bericht niet verzonden en ziet u het volgende gedrag:</span><span class="sxs-lookup"><span data-stu-id="c6ba6-108">When you run the workflow, the email message isn't sent, and you notice the following behavior:</span></span>
    - <span data-ttu-id="c6ba6-109">Voor een werkstroom met behulp van het platformtype SharePoint 2013, bladert u naar de pagina **Workflowstatus** .</span><span class="sxs-lookup"><span data-stu-id="c6ba6-109">For a workflow using the SharePoint 2013 platform type, you browse to the **Workflow Status** page.</span></span> <span data-ttu-id="c6ba6-110">Op de pagina Workflowstatus wordt de **interne status** ingesteld op **gestart**en wordt de informatieballon **niet verzonden naar een geadresseerde**.</span><span class="sxs-lookup"><span data-stu-id="c6ba6-110">On the Workflow Status page, the **Internal Status** is set to **Started**, and the information balloon displays **Unable to send to a recipient**.</span></span>

<span data-ttu-id="c6ba6-111">U dit probleem omzeilen, configureert u uw werkstroom voor het verzenden van e-mail berichten zonder overschrijding van de [limieten voor Exchange Online-afzender](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#recipientlimits).</span><span class="sxs-lookup"><span data-stu-id="c6ba6-111">To work around this issue, configure your workflow to send email messages without exceeding the [Exchange Online sender limits](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#recipientlimits).</span></span> <span data-ttu-id="c6ba6-112">Gebruik bijvoorbeeld een pauze in de werkstroom, stuur het e-mail bericht naar een groep van Office 365, een distributiegroep of een beveiligingsgroep met e-mailadres, of verzend de berichten naar minder dan 200 geadresseerden tegelijk.</span><span class="sxs-lookup"><span data-stu-id="c6ba6-112">For example, use a pause in the workflow, send the email to an Office 365 group, a distribution group or mail enabled security group, or send the message to fewer than 200 recipients at a time.</span></span>


<span data-ttu-id="c6ba6-113">Zie het volgende [artikel](https://support.microsoft.com/help/3150442/daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or)voor meer informatie.</span><span class="sxs-lookup"><span data-stu-id="c6ba6-113">For more information, see the following [article](https://support.microsoft.com/help/3150442/daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or).</span></span>

## <a name="related-topics"></a><span data-ttu-id="c6ba6-114">Verwante onderwerpen</span><span class="sxs-lookup"><span data-stu-id="c6ba6-114">Related topics</span></span>
- [<span data-ttu-id="c6ba6-115">Stroom maken</span><span class="sxs-lookup"><span data-stu-id="c6ba6-115">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="c6ba6-116">SharePoint en flow</span><span class="sxs-lookup"><span data-stu-id="c6ba6-116">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 