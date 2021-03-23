---
title: Voorbeeld van anti-phishingbeleid van Microsoft Defender voor Office 365
ms.author: v-jmathew
author: v-jmathew
manager: dansimp
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000760"
- "7391"
ms.openlocfilehash: eabff70c22b641627d3ab6c0b2f8846a0be2f49e
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 03/11/2021
ms.locfileid: "50744895"
---
# <a name="example-microsoft-defender-for-office-365-anti-phishing-policy"></a><span data-ttu-id="b6d4c-102">Voorbeeld van anti-phishingbeleid van Microsoft Defender voor Office 365</span><span class="sxs-lookup"><span data-stu-id="b6d4c-102">Example Microsoft Defender for Office 365 anti-phishing policy</span></span>

<span data-ttu-id="b6d4c-103">Met deze instellingen kunt u een beleid met de naam *Domein en CEO inschakelen.*</span><span class="sxs-lookup"><span data-stu-id="b6d4c-103">These settings enable a policy called *Domain and CEO*.</span></span> <span data-ttu-id="b6d4c-104">Dit beleid biedt zowel gebruikers- als domeinbescherming tegen imitatie en past vervolgens het beleid toe op alle e-mail die gebruikers binnen het domein ontvangen.</span><span class="sxs-lookup"><span data-stu-id="b6d4c-104">This policy provides both user and domain protection from impersonation and then applies the policy to all email received by users within the domain.</span></span> <span data-ttu-id="b6d4c-105">Voeg eerst de volgende gegevens toe om het beleid te maken:</span><span class="sxs-lookup"><span data-stu-id="b6d4c-105">First, add the following information to create the policy:</span></span>

- <span data-ttu-id="b6d4c-106">**Naam:** Beschrijving van domein **en** CEO: zorgt ervoor dat de CEO en uw domein niet worden nagebootsd.</span><span class="sxs-lookup"><span data-stu-id="b6d4c-106">**Name**: Domain and CEO **Description**: Ensures that the CEO and your domain are not being impersonated.</span></span>
  <span data-ttu-id="b6d4c-107">**Toegepast op**: Selecteer **Het domein van de geadresseerde is**.</span><span class="sxs-lookup"><span data-stu-id="b6d4c-107">**Applied to**: Select **The recipient domain is**.</span></span> <span data-ttu-id="b6d4c-108">Selecteer **onder Een van deze** opties De optie **Kiezen** en selecteer vervolgens een domein.</span><span class="sxs-lookup"><span data-stu-id="b6d4c-108">Under **Any of these**, select **Choose**, and then select a domain.</span></span> <span data-ttu-id="b6d4c-109">Selecteer **+ Toevoegen.**</span><span class="sxs-lookup"><span data-stu-id="b6d4c-109">Select **+ Add**.</span></span> <span data-ttu-id="b6d4c-110">Schakel het selectievakje in naast de naam van het domein in de lijst (bijvoorbeeld *contoso.com)* en selecteer **toevoegen.**</span><span class="sxs-lookup"><span data-stu-id="b6d4c-110">Select the check box next to the name of the domain in the list (for example, *contoso.com*), and then select **Add**.</span></span> <span data-ttu-id="b6d4c-111">Selecteer **Gereed**.</span><span class="sxs-lookup"><span data-stu-id="b6d4c-111">Select **Done**.</span></span>
- <span data-ttu-id="b6d4c-112">Nadat het beleid is gemaakt, kunt u het beleid verder afstemmen met de volgende opties:</span><span class="sxs-lookup"><span data-stu-id="b6d4c-112">After the policy is created, you can fine-tune the policy by using the following options:</span></span>
  - <span data-ttu-id="b6d4c-113">**Gebruikers toevoegen om ze te beveiligen:** Voeg in dit voorbeeld minimaal het e-mailadres van de CEO toe.</span><span class="sxs-lookup"><span data-stu-id="b6d4c-113">**Add users to protect:** For this example, add the CEO's email address, at a minimum.</span></span>
  - <span data-ttu-id="b6d4c-114">**Domeinen toevoegen om te beveiligen:** Voeg het organisatiedomein toe dat het kantoor van de CEO omvat.</span><span class="sxs-lookup"><span data-stu-id="b6d4c-114">**Add domains to protect**: Add the organizational domain that includes the office of the CEO.</span></span>
  - <span data-ttu-id="b6d4c-115">**Acties kiezen:** **Als** e-mail wordt verzonden door een nagebootste gebruiker, selecteert u Bericht omleiden naar een ander e-mailadres **en** voert u vervolgens het e-mailadres van de beveiligingsbeheerder *in (bijvoorbeeld securityadmin@contoso.com).*</span><span class="sxs-lookup"><span data-stu-id="b6d4c-115">**Choose actions**: For **If email is sent by an impersonated user**, select **Redirect message to another email address**, and then enter the email address of the security administrator (for example, *securityadmin@contoso.com*).</span></span> <span data-ttu-id="b6d4c-116">Als **e-mail wordt verzonden door een nagebootsd domein,** selecteert u **Het bericht in quarantaine plaatsen.**</span><span class="sxs-lookup"><span data-stu-id="b6d4c-116">For **If email is sent by an impersonated domain**, select **Quarantine the message**.</span></span>
  - <span data-ttu-id="b6d4c-117">**Postvakinformatie:** Deze optie is standaard geselecteerd wanneer u een nieuw anti-phishingbeleid maakt.</span><span class="sxs-lookup"><span data-stu-id="b6d4c-117">**Mailbox intelligence**: By default, this option is selected when you create a new anti-phishing policy.</span></span> <span data-ttu-id="b6d4c-118">Laat deze instelling **aan voor** de beste resultaten.</span><span class="sxs-lookup"><span data-stu-id="b6d4c-118">Leave this setting **On** for best results.</span></span>
  - <span data-ttu-id="b6d4c-119">**Vertrouwde afzenders en domeinen toevoegen:** Definieer in dit voorbeeld geen overschrijvingen.</span><span class="sxs-lookup"><span data-stu-id="b6d4c-119">**Add trusted senders and domains:** For this example, don't define any overrides.</span></span>
- <span data-ttu-id="b6d4c-120">Nadat u de instellingen hebt gecontroleerd, **selecteert** u Dit beleid maken of **Opslaan,** naar eigen goed.</span><span class="sxs-lookup"><span data-stu-id="b6d4c-120">Once you've reviewed your settings, select **Create this policy** or **Save**, as appropriate.</span></span>

<span data-ttu-id="b6d4c-121">Zie [Anti-phishingbeleid in Microsoft 365](https://go.microsoft.com/fwlink/?linkid=2092235)voor meer informatie.</span><span class="sxs-lookup"><span data-stu-id="b6d4c-121">To learn more, see [Anti-phishing policies in Microsoft 365](https://go.microsoft.com/fwlink/?linkid=2092235).</span></span>