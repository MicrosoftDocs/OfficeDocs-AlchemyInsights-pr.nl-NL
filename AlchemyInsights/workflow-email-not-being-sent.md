---
title: Werkstroom e-mailbericht wordt niet verzonden
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 7/25/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1586"
ms.openlocfilehash: 783bf0a5721aa5db7088432c71e06cac6dc90513
ms.sourcegitcommit: 407f6c1e82f1a0be5cf53301fbf03cd25dcbf0ee
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 08/02/2019
ms.locfileid: "36059599"
---
# <a name="workflow-email-is-not-being-sent"></a><span data-ttu-id="3e343-102">Werkstroom e-mailbericht wordt niet verzonden</span><span class="sxs-lookup"><span data-stu-id="3e343-102">Workflow email is not being sent</span></span>

1. <span data-ttu-id="3e343-103">E-mailadres van werkstromen worden niet verzonden naar alle gebruikers of alleen bepaalde gebruikers of ziet u dat de fout **het e-mailbericht kan niet worden verzonden. Controleer of het e-mailbericht heeft een geldige geadresseerde**.</span><span class="sxs-lookup"><span data-stu-id="3e343-103">Email from workflows are not sent to all users or only specific users, or you see the error **The e-mail message cannot be sent. Make sure the e-mail has a valid recipient**.</span></span>

<span data-ttu-id="3e343-104">Controleer of de gebruiker in de machtigingsgroep **Alle mensen** (lijst met gebruikersgegevens) voor die siteverzameling bestaat.</span><span class="sxs-lookup"><span data-stu-id="3e343-104">Check if the user exist in the **All People** permissions group (user information list) for that site collection.</span></span>  <span data-ttu-id="3e343-105">Voorbeeld van een directe URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx? MembershipGroupId = 0</span><span class="sxs-lookup"><span data-stu-id="3e343-105">Sample direct URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx?MembershipGroupId=0</span></span>

- <span data-ttu-id="3e343-106">Als de gebruiker niet bestaat, moet u dat de gebruiker is aangemeld op de pagina.</span><span class="sxs-lookup"><span data-stu-id="3e343-106">If the user does not exist, make sure the user is signed into the page.</span></span> 
- <span data-ttu-id="3e343-107">Zorg dat de uitnodiging is geaccepteerd als een externe gebruiker is.</span><span class="sxs-lookup"><span data-stu-id="3e343-107">If it is an external user, make sure that their invitation has been accepted.</span></span>
- <span data-ttu-id="3e343-108">Als de gebruiker in de machtigingsgroep bestaat, moet dat het e-mailadres juist is.</span><span class="sxs-lookup"><span data-stu-id="3e343-108">If the user does exist in the permissions group, make sure the email address is correct.</span></span>
- <span data-ttu-id="3e343-109">Als de gebruikers e-mailadres hier niet is ingesteld, maakt u een waarschuwing voor een monster voor die gebruiker, waardoor de synchronisatie van die account van gebruikers profielen van SharePoint voor deze siteverzameling.</span><span class="sxs-lookup"><span data-stu-id="3e343-109">If the users email address is not set here, then create a sample alert for that user which forces the sync of that user account from User Profiles of SharePoint to this site collection.</span></span>
 
2. <span data-ttu-id="3e343-110">E-mailadres van werkstromen worden verzonden naar beheerders van de siteverzameling, maar niet voor andere gebruikers en Zie de fout \*\*verboden HTTP- <spam> <spam> \*\* <spam> <spam>.</span><span class="sxs-lookup"><span data-stu-id="3e343-110">Email from Workflows are sent to the site collection administrators but not to other users and see the error **HTTP Forbidden to <spam><spam>https://URL/_vti_bin/client.xvc.sp.utilities.utility.SendEmail**<spam><spam>.</span></span>
 

<span data-ttu-id="3e343-111">Zie [De toegang geweigerd wanneer verzonden e-mail naar groepen](https://docs.microsoft.com/sharepoint/support/server-admin/access-denied-when-send-an-email-to-groups).</span><span class="sxs-lookup"><span data-stu-id="3e343-111">See [Access Denied when sent email to groups](https://docs.microsoft.com/sharepoint/support/server-admin/access-denied-when-send-an-email-to-groups).</span></span>

<span data-ttu-id="3e343-112">Controleer ook of de **modus met beperkte toegang gebruiker machtiging lockdown** siteverzamelingfunctie is niet actief.</span><span class="sxs-lookup"><span data-stu-id="3e343-112">Also, verify that the **Limited-access user permission lockdown mode** site collection feature is not active.</span></span>

## <a name="related-topics"></a><span data-ttu-id="3e343-113">Verwante onderwerpen</span><span class="sxs-lookup"><span data-stu-id="3e343-113">Related topics</span></span>
- [<span data-ttu-id="3e343-114">Stroom maken</span><span class="sxs-lookup"><span data-stu-id="3e343-114">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="3e343-115">SharePoint en stroom</span><span class="sxs-lookup"><span data-stu-id="3e343-115">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


