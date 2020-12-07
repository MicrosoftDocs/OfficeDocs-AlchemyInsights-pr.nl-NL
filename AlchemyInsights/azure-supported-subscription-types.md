---
title: Ondersteunde abonnements typen
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9003560"
- "6675"
ms.openlocfilehash: 46bc60435c3f8477e9f274d90c39d0f1c6a523c6
ms.sourcegitcommit: f8b41ecda6db0b8f64fe0c51f1e8e6619f504d61
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 10/28/2020
ms.locfileid: "48807361"
---
# <a name="supported-subscription-types"></a><span data-ttu-id="99f28-102">Ondersteunde abonnements typen</span><span class="sxs-lookup"><span data-stu-id="99f28-102">Supported subscription types</span></span>

<span data-ttu-id="99f28-103">Controleer de ondersteunde abonnements typen om verder te gaan.</span><span class="sxs-lookup"><span data-stu-id="99f28-103">Please review the supported subscription types to proceed further.</span></span>

[<span data-ttu-id="99f28-104">Ondersteunde abonnements typen</span><span class="sxs-lookup"><span data-stu-id="99f28-104">Supported subscription types</span></span>](https://docs.microsoft.com/azure/billing/billing-subscription-transfer?WT.mc_id=Portal-Microsoft_Azure_Support#supported-subscription-types)

<span data-ttu-id="99f28-105">**Facturering van eigendom overzetten**</span><span class="sxs-lookup"><span data-stu-id="99f28-105">**Transfer billing ownership**</span></span>

<span data-ttu-id="99f28-106">Azure-portal als [account beheerder](https://ms.portal.azure.com/) van het factuur account met het abonnement dat u wilt overzetten</span><span class="sxs-lookup"><span data-stu-id="99f28-106">Azure portal as the [Account Admin](https://ms.portal.azure.com/) of the billing account that has the subscription you want to transfer</span></span>

- <span data-ttu-id="99f28-107">Zoek op **kostenbeheer + facturering** .</span><span class="sxs-lookup"><span data-stu-id="99f28-107">Search on **Cost Management + Billing** .</span></span> <span data-ttu-id="99f28-108">Selecteer **abonnementen** in het linkerdeelvenster.</span><span class="sxs-lookup"><span data-stu-id="99f28-108">Select **Subscriptions** from left-pane.</span></span> <span data-ttu-id="99f28-109">Afhankelijk van de toegang moet u mogelijk een factuur bereik selecteren en vervolgens **abonnementen** of **Azure-abonnementen** .</span><span class="sxs-lookup"><span data-stu-id="99f28-109">Depending on the access, you may need to select a billing scope and then **Subscriptions** or **Azure subscriptions** .</span></span>
- <span data-ttu-id="99f28-110">Selecteer het eigendom van de facturering voor het abonnement dat u wilt overzetten</span><span class="sxs-lookup"><span data-stu-id="99f28-110">Select Transfer billing ownership for the subscription you want to transfer</span></span>
- <span data-ttu-id="99f28-111">Voer het e-mailadres in van een gebruiker die een factureringsbeheerder is van het account dat de nieuwe eigenaar wordt van het abonnement en selecteer vervolgens **overdrachtsaanvraag verzenden** .</span><span class="sxs-lookup"><span data-stu-id="99f28-111">Enter the email address of a user who's a billing administrator of the account that will be the new owner for the subscription and then select **send transfer request**</span></span>
- <span data-ttu-id="99f28-112">De gebruiker ontvangt een e-mail met instructies om uw overdrachtsaanvraag te controleren.</span><span class="sxs-lookup"><span data-stu-id="99f28-112">The user gets an email with instructions to review your transfer request.</span></span> <span data-ttu-id="99f28-113">De gebruiker kan de koppeling in het e-mailbericht selecteren en de instructies volgen om de overdrachtsaanvraag goed te keuren.</span><span class="sxs-lookup"><span data-stu-id="99f28-113">To approve the transfer request, the user selects the link in the email and follows the instructions.</span></span>

<span data-ttu-id="99f28-114">Opmerking: als u het eigendom van uw abonnement overdraagt naar het account van een gebruiker in een andere Azure AD-Tenant, worden alle toewijzingen met [toegangsbeheer voor rollen (RBAC)](https://docs.microsoft.com/azure/role-based-access-control/overview?WT.mc_id=Portal-Microsoft_Azure_Support) voor het beheren van resources in het abonnement blijvend verwijderd.</span><span class="sxs-lookup"><span data-stu-id="99f28-114">Note: If you transfer billing ownership of your subscription to a user's account in another Azure AD tenant, all [role-based access control (RBAC)](https://docs.microsoft.com/azure/role-based-access-control/overview?WT.mc_id=Portal-Microsoft_Azure_Support) assignments to manage resources in the subscription are permanently removed.</span></span> <span data-ttu-id="99f28-115">Alleen de nieuwe eigenaar kan de bronnen in het abonnement beheren.</span><span class="sxs-lookup"><span data-stu-id="99f28-115">Only the new owner will have access to manage resources in the subscription.</span></span> <span data-ttu-id="99f28-116">Zie voor meer informatie [een abonnement overzetten naar een gebruiker in een andere Azure AD-Tenant](https://docs.microsoft.com/azure/active-directory/managed-identities-azure-resources/known-issues?WT.mc_id=Portal-Microsoft_Azure_Support).</span><span class="sxs-lookup"><span data-stu-id="99f28-116">For more information, see [Transferring subscription to a user in another Azure AD tenant](https://docs.microsoft.com/azure/active-directory/managed-identities-azure-resources/known-issues?WT.mc_id=Portal-Microsoft_Azure_Support).</span></span>

<span data-ttu-id="99f28-117">**Eigendom van een abonnement overzetten**</span><span class="sxs-lookup"><span data-stu-id="99f28-117">**Transfer Ownership of Subscription**</span></span>

<span data-ttu-id="99f28-118">Eigenaar van het abonnement overzetten op basis van toegang (RBAC) voor het beheren van resources in het abonnement, verliezen hun toegang.</span><span class="sxs-lookup"><span data-stu-id="99f28-118">Subscription Ownership Transfer prerequisites role based access (RBAC) to manage resources in the subscription lose their access.</span></span> <span data-ttu-id="99f28-119">Zie [een Azure-abonnement koppelen of toevoegen aan Azure Active Directory](https://docs.microsoft.com/azure/active-directory/fundamentals/active-directory-how-subscriptions-associated-directory?WT.mc_id=Portal-Microsoft_Azure_Support)voor meer informatie over het toevoegen van een bestaand abonnement aan een Tenant.</span><span class="sxs-lookup"><span data-stu-id="99f28-119">For more information about adding an existing subscription to a tenant, see [Associate or add an Azure subscription to Azure Active Directory](https://docs.microsoft.com/azure/active-directory/fundamentals/active-directory-how-subscriptions-associated-directory?WT.mc_id=Portal-Microsoft_Azure_Support).</span></span>

- <span data-ttu-id="99f28-120">Abonnements overschrijving met een bestaand openstaand bedrag van de huidige factureringscyclus wordt niet overgezet naar het nieuwe betaal instrument in het nieuwe account.</span><span class="sxs-lookup"><span data-stu-id="99f28-120">Subscription Transfer with an existing outstanding amount from the current billing cycle will not be transferred to the new payment instrument in the new account.</span></span> <span data-ttu-id="99f28-121">De enige voor de gebruikers in het nieuwe account beschikbare gegevens zijn de kosten van de afgelopen maand voor uw abonnement.</span><span class="sxs-lookup"><span data-stu-id="99f28-121">The only information available to the users in new account is the last month's cost for your subscription.</span></span> <span data-ttu-id="99f28-122">De rest van de gebruiks-en factureringsgeschiedenis wordt niet met het abonnement overgebracht.</span><span class="sxs-lookup"><span data-stu-id="99f28-122">The rest of the usage and billing history does not transfer with the subscription.</span></span>
- <span data-ttu-id="99f28-123">Het overdragen van facturerings machtigingen van Enterprise Agreement (EA) wordt momenteel ondersteund in de portal voor Enterprise Agreement</span><span class="sxs-lookup"><span data-stu-id="99f28-123">Transfer billing ownership of Enterprise Agreement (EA) subscriptions is currently supported in the Enterprise Agreement Portal only</span></span>
- <span data-ttu-id="99f28-124">Voor het overzetten van een abonnement op een krediet, zoals Visual Studio, BizSpark, Microsoft-partnernetwerk, moet een nieuwe gebruiker een netwerk licentie voor Visual Studio/Microsoft-partners hebben om de overdrachtsaanvraag te accepteren</span><span class="sxs-lookup"><span data-stu-id="99f28-124">Transferring a credit-oriented subscription like Visual Studio, BizSpark, Microsoft Partner Network to a new user requires to have a Visual Studio/Microsoft partner network license to accept the transfer request</span></span>
- <span data-ttu-id="99f28-125">Alle bronnen zoals virtuele machines, schijven en websites worden overschreven naar het nieuwe account.</span><span class="sxs-lookup"><span data-stu-id="99f28-125">All resources like Virtual Machines, disks, and websites transfer to the new account successfully.</span></span> <span data-ttu-id="99f28-126">De volgende bronnen kunnen worden beïnvloed in een overdracht van een ander Tenant abonnement:</span><span class="sxs-lookup"><span data-stu-id="99f28-126">The following resources could be affected in a cross-tenant subscription transfer:</span></span>

<span data-ttu-id="99f28-127">**Azure AD Domain Services**</span><span class="sxs-lookup"><span data-stu-id="99f28-127">**Azure AD Domain Services**</span></span>

<span data-ttu-id="99f28-128">Azure-sleutel kluizen</span><span class="sxs-lookup"><span data-stu-id="99f28-128">Azure Key Vaults</span></span>

- <span data-ttu-id="99f28-129">[SQL-gerelateerde gebruikers en-databases](https://docs.microsoft.com/azure/sql-database/sql-database-aad-authentication-configure?WT.mc_id=Portal-Microsoft_Azure_Support) kunnen worden beïnvloed, met name als de klant met een Azure Active Directory gerelateerde verificatie werkt.</span><span class="sxs-lookup"><span data-stu-id="99f28-129">[SQL related users and databases](https://docs.microsoft.com/azure/sql-database/sql-database-aad-authentication-configure?WT.mc_id=Portal-Microsoft_Azure_Support) could be impacted, especially if the customer uses an Azure Active Directory related authentication</span></span>
- <span data-ttu-id="99f28-130">**App-Services** die zijn geconfigureerd met Azure Active Directory-verificatie, kunnen worden beïnvloed</span><span class="sxs-lookup"><span data-stu-id="99f28-130">**App Services** configured with Azure Active Directory authentication could be impacted</span></span>
- <span data-ttu-id="99f28-131">**Visual Studio Team** Services-accounts die zijn gekoppeld aan Azure-abonnementen, verliezen mogelijk tijdelijk toegang als het verbonden Azure-abonnement is geannuleerd</span><span class="sxs-lookup"><span data-stu-id="99f28-131">**Visual Studio Team** Services accounts connected to Azure subscriptions may temporarily lose access when the connected Azure subscription is cancelled</span></span>

<span data-ttu-id="99f28-132">**Aanbevolen documenten**</span><span class="sxs-lookup"><span data-stu-id="99f28-132">**Recommended Documents**</span></span>

<span data-ttu-id="99f28-133">Stappen na het accepteren van het eigendom van de factuur:</span><span class="sxs-lookup"><span data-stu-id="99f28-133">Steps after accepting billing ownership:</span></span>

- <span data-ttu-id="99f28-134">Als u het eigendom van de factuur wilt behouden, maar het type abonnement wilt wijzigen, raadpleegt u: [een abonnement op uw Azure-abonnement omzetten in een andere aanbieding](https://docs.microsoft.com/azure/billing/billing-how-to-switch-azure-offer?WT.mc_id=Portal-Microsoft_Azure_Support)</span><span class="sxs-lookup"><span data-stu-id="99f28-134">To retain billing ownership, but change the type of your subscription, refer: [Switch your Azure subscription to another offer](https://docs.microsoft.com/azure/billing/billing-how-to-switch-azure-offer?WT.mc_id=Portal-Microsoft_Azure_Support)</span></span>
- [<span data-ttu-id="99f28-135">De overdracht van Visual Studio, Microsoft Partner Network (MPN) en betalen naar gebruik-ontwikkelaars/proefabonnementen</span><span class="sxs-lookup"><span data-stu-id="99f28-135">Transferring Visual Studio, Microsoft Partner Network (MPN) and Pay as you go Dev/Test subscriptions</span></span>](https://docs.microsoft.com/azure/billing/billing-subscription-transfer?WT.mc_id=Portal-Microsoft_Azure_Support#transferring-visual-studio-microsoft-partner-network-mpn-and-pay-as-you-go-devtest-subscriptions)
- [<span data-ttu-id="99f28-136">Facturerings machtigingen van een Enterprise Agreement-abonnement (EA) overdragen</span><span class="sxs-lookup"><span data-stu-id="99f28-136">Transfer billing ownership of Enterprise Agreement (EA) subscriptions</span></span>](https://docs.microsoft.com/azure/billing/billing-subscription-transfer?WT.mc_id=Portal-Microsoft_Azure_Support#transfer-billing-ownership-of-enterprise-agreement-ea-subscriptions)
- [<span data-ttu-id="99f28-137">Veelgestelde vragen over het overdragen van eigendom</span><span class="sxs-lookup"><span data-stu-id="99f28-137">Transfer Ownership FAQ</span></span>](https://docs.microsoft.com/azure/billing/billing-subscription-transfer?WT.mc_id=Portal-Microsoft_Azure_Support#frequently-asked-questions-faq-for-senders)
- [<span data-ttu-id="99f28-138">Problemen met de overdracht van eigendom oplossen</span><span class="sxs-lookup"><span data-stu-id="99f28-138">Troubleshoot Transfer ownership issues</span></span>](https://docs.microsoft.com/azure/billing/billing-subscription-transfer?WT.mc_id=Portal-Microsoft_Azure_Support#troubleshooting)