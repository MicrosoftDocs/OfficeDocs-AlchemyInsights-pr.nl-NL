---
title: Meerdere objecten hebben hetzelfde e-mailadres als identiteit
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/27/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1834"
- "9000247"
ms.openlocfilehash: cc932aa7ecbd1e338c409a7a6525e2c4e673b232
ms.sourcegitcommit: b10cea11b4975354b91193327b58aa4740d34833
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 07/28/2020
ms.locfileid: "45438932"
---
# <a name="multiple-objects-have-the-same-email-address-as-identity"></a><span data-ttu-id="ab474-102">Meerdere objecten hebben hetzelfde e-mailadres als identiteit</span><span class="sxs-lookup"><span data-stu-id="ab474-102">Multiple objects have the same email address as identity</span></span>

<span data-ttu-id="ab474-103">**Meerdere objecten**</span><span class="sxs-lookup"><span data-stu-id="ab474-103">**Multiple objects**</span></span>

<span data-ttu-id="ab474-104">Een van de veelvoorkomende redenen van deze fout is dat u een Outlook Web Access-aanvraag niet goed kan routeren in aanwezigheid van meerdere objecten met hetzelfde e-mailadres als de identiteit.</span><span class="sxs-lookup"><span data-stu-id="ab474-104">One of the common reasons of this error is not being able to route an Outlook Web Access request properly in a presence of multiple objects having the same email address as identity.</span></span> <span data-ttu-id="ab474-105">Voer de volgende opdrachten uit om deze objecten te zoeken:</span><span class="sxs-lookup"><span data-stu-id="ab474-105">To find these objects, run the following commands:</span></span>

<span data-ttu-id="ab474-106">· Ontvanger van get-ontvanger<email address></span><span class="sxs-lookup"><span data-stu-id="ab474-106">· Get-Recipient <email address></span></span>

<span data-ttu-id="ab474-107">· Gebruiker<email address></span><span class="sxs-lookup"><span data-stu-id="ab474-107">· Get-User <email address></span></span>

<span data-ttu-id="ab474-108">· Gebruiker <email address> -SoftDeletedUser</span><span class="sxs-lookup"><span data-stu-id="ab474-108">· Get-User <email address> -SoftDeletedUser</span></span>

<span data-ttu-id="ab474-109">· Contact opnemen<email address></span><span class="sxs-lookup"><span data-stu-id="ab474-109">· Get-Contact <email address></span></span>

<span data-ttu-id="ab474-110">· Ophalen <email address> -postvak -PublicFolder</span><span class="sxs-lookup"><span data-stu-id="ab474-110">· Get-Mailbox <email address> -PublicFolder</span></span>

<span data-ttu-id="ab474-111">· Postvak ophalen <email address> -IncludeSoftDeletedMailbox</span><span class="sxs-lookup"><span data-stu-id="ab474-111">· Get-Mailbox <email address> -IncludeSoftDeletedMailbox</span></span>

<span data-ttu-id="ab474-112">· Get-Mailbox <email address> -InactiveMailboxOnly</span><span class="sxs-lookup"><span data-stu-id="ab474-112">· Get-Mailbox <email address> -InactiveMailboxOnly</span></span>

<span data-ttu-id="ab474-113">Als u het probleem wilt oplossen, verwijdert u meerdere objecten met dezelfde e-mailidentiteit en controleert u of er één object is met de specifieke e-mailidentiteit en dat het type ontvanger UserMailbox is.</span><span class="sxs-lookup"><span data-stu-id="ab474-113">To resolve the issue, remove multiple objects with the same email identity and make sure that there is a single object with the specific email identity and that its recipient type is UserMailbox.</span></span>

<span data-ttu-id="ab474-114">**Hetzelfde adres wordt gebruikt voor zakelijke en consumentenpostvakken**</span><span class="sxs-lookup"><span data-stu-id="ab474-114">**Same address is used for business and consumer mailboxes**</span></span>

<span data-ttu-id="ab474-115">Een andere oorzaak is wanneer hetzelfde adres wordt gebruikt voor zakelijke en consumentenpostvakken.</span><span class="sxs-lookup"><span data-stu-id="ab474-115">Another cause is when the same address is used for business and consumer mailboxes.</span></span> <span data-ttu-id="ab474-116">In dit geval moet de gebruiker zijn primaire consumentenalias wijzigen totdat Cafe dit scenario ondersteunt.</span><span class="sxs-lookup"><span data-stu-id="ab474-116">In this case, the user must change their primary consumer alias until Cafe supports this scenario.</span></span> <span data-ttu-id="ab474-117">Dit is een permanente fout die niet verdwijnt zonder tussenkomst.</span><span class="sxs-lookup"><span data-stu-id="ab474-117">This is a permanent error that does not go away without intervention.</span></span>

<span data-ttu-id="ab474-118">Zie Het [e-mailadres of telefoonnummer voor uw Microsoft-account wijzigen](https://support.microsoft.com/help/11545/microsoft-account-rename-your-personal-account)voor meer informatie.</span><span class="sxs-lookup"><span data-stu-id="ab474-118">For details, see [Change the email address or phone number for your Microsoft account](https://support.microsoft.com/help/11545/microsoft-account-rename-your-personal-account).</span></span>