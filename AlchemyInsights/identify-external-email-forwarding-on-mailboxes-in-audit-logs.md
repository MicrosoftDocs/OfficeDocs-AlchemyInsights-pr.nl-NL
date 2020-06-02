---
title: Externe e-mail doorsturen op postvakken identificeren in controlelogboeken
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1369"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 592eb92e4b0fe0f9da2fa20bb93ffa4fbbb76662
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 06/02/2020
ms.locfileid: "44508947"
---
# <a name="identify-when-external-email-forwarding-is-configured-on-mailboxes"></a><span data-ttu-id="b85b5-102">Identificeren wanneer externe e-mail doorsturen is geconfigureerd op postvakken</span><span class="sxs-lookup"><span data-stu-id="b85b5-102">Identify when external email forwarding is configured on mailboxes</span></span>

<span data-ttu-id="b85b5-103">Wanneer een Microsoft 365-gebruiker externe e-mail doorstuurt op een postvak, wordt de activiteit gecontroleerd als onderdeel van de cmdlet **Set-Mailbox.**</span><span class="sxs-lookup"><span data-stu-id="b85b5-103">When a Microsoft 365 user configures external email forwarding on a mailbox, the activity is audited as part of the **Set-Mailbox** cmdlet.</span></span> <span data-ttu-id="b85b5-104">U de activiteit bekijken met behulp van controlelogboekzoekopdrachten in het Security & Compliance Center.</span><span class="sxs-lookup"><span data-stu-id="b85b5-104">You can see the activity using audit log search in the Security & Compliance Center.</span></span>

1. <span data-ttu-id="b85b5-105">Meld u aan bij het [Microsoft 365 Security & Compliance Center](https://protection.office.com/).</span><span class="sxs-lookup"><span data-stu-id="b85b5-105">Log in to the [Microsoft 365 Security & Compliance Center](https://protection.office.com/).</span></span>

2. <span data-ttu-id="b85b5-106">Ga naar de zoekpagina **van het**  >  **zoekcontrolelogboek.**</span><span class="sxs-lookup"><span data-stu-id="b85b5-106">Go to the **Search** > **Audit log search** page.</span></span>

3. <span data-ttu-id="b85b5-107">Selecteer het datumbereik in de velden **Begindatum** en **Einddatum.**</span><span class="sxs-lookup"><span data-stu-id="b85b5-107">Select the date range in the **Start date** and **End date** fields.</span></span> <span data-ttu-id="b85b5-108">U hoeft geen gebruikersnaam op te geven.</span><span class="sxs-lookup"><span data-stu-id="b85b5-108">You don't need to specify a username.</span></span> <span data-ttu-id="b85b5-109">Controleer of het veld **Activiteiten** is ingesteld op **Resultaten weergeven voor alle activiteiten.**</span><span class="sxs-lookup"><span data-stu-id="b85b5-109">Verify the **Activities** field is set to **Show results for all activities**.</span></span>

4. <span data-ttu-id="b85b5-110">Klik **op Zoeken**.</span><span class="sxs-lookup"><span data-stu-id="b85b5-110">Click **Search**.</span></span>

<span data-ttu-id="b85b5-111">Klik in de resultaten op **Resultaten filteren** en typ **Set-Postvak** in het vak activiteitenfilter.</span><span class="sxs-lookup"><span data-stu-id="b85b5-111">In the results, click **Filter Results** and type **Set-Mailbox** in the activity filter box.</span></span> <span data-ttu-id="b85b5-112">Selecteer een controlerecord in de resultaten.</span><span class="sxs-lookup"><span data-stu-id="b85b5-112">Select an audit record in the results.</span></span> <span data-ttu-id="b85b5-113">Klik in de flyout **Details** op **Meer informatie**.</span><span class="sxs-lookup"><span data-stu-id="b85b5-113">In the **Details** flyout, click **More information**.</span></span> <span data-ttu-id="b85b5-114">U moet kijken naar de details van elke controlerecord om te bepalen of de activiteit gerelateerd is aan het doorsturen van e-mail.</span><span class="sxs-lookup"><span data-stu-id="b85b5-114">You have to look at the details of each audit record to determine if the activity is related to email forwarding.</span></span>

- <span data-ttu-id="b85b5-115">**ObjectId**: de aliaswaarde van het postvak dat is gewijzigd.</span><span class="sxs-lookup"><span data-stu-id="b85b5-115">**ObjectId**: The alias value of the mailbox that was modified.</span></span>

- <span data-ttu-id="b85b5-116">**Parameters**: _ForwardingSmtpAddress_ geeft het doele-mailadres aan.</span><span class="sxs-lookup"><span data-stu-id="b85b5-116">**Parameters**: _ForwardingSmtpAddress_ indicates the target email address.</span></span>

- <span data-ttu-id="b85b5-117">**UserId**: De gebruiker die e-mail doorstuurt op het postvak in het veld **ObjectId.**</span><span class="sxs-lookup"><span data-stu-id="b85b5-117">**UserId**: The user who configured email forwarding on the mailbox in the **ObjectId** field.</span></span>

<span data-ttu-id="b85b5-118">Zie [Bepalen wie e-mail doorstuurt voor een postvak voor](https://docs.microsoft.com/microsoft-365/compliance/auditing-troubleshooting-scenarios#determine-who-set-up-email-forwarding-for-a-mailbox)meer informatie.</span><span class="sxs-lookup"><span data-stu-id="b85b5-118">For more information, see [Determining who set up email forwarding for a mailbox](https://docs.microsoft.com/microsoft-365/compliance/auditing-troubleshooting-scenarios#determine-who-set-up-email-forwarding-for-a-mailbox).</span></span>
