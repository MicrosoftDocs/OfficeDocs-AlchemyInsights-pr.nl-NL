---
title: Problemen met gebruikersbeheer
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 03/19/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9209"
- "9005371"
ms.openlocfilehash: 4b61686381de0cafa38857ca7a96b3a81aa191ec
ms.sourcegitcommit: c08bed4071baa3bb5879496df3ed44fb828c8367
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 03/19/2021
ms.locfileid: "51035530"
---
# <a name="user-management-issues"></a><span data-ttu-id="a7fec-102">Problemen met gebruikersbeheer</span><span class="sxs-lookup"><span data-stu-id="a7fec-102">User management issues</span></span>

<span data-ttu-id="a7fec-103">**Wat gebeurt er met huidige toegewezen gebruikers aan de toepassing als ik de eigenschap 'Gebruikerstoewijzing vereist' uit schakel (deze eigenschap instellen op Nee)?**</span><span class="sxs-lookup"><span data-stu-id="a7fec-103">**What happens to current assigned users to the application if I disable the property ‘User assignment required’ (set this property to No)?**</span></span>

<span data-ttu-id="a7fec-104">Het uitschakelen van **de vereiste gebruikerstoewijzing** heeft GEEN invloed op de momenteel toegewezen gebruikers.</span><span class="sxs-lookup"><span data-stu-id="a7fec-104">Disabling **User assignment required** does NOT affect the currently assigned users.</span></span> <span data-ttu-id="a7fec-105">Als u deze eigenschap uit kunt uitschakelen, hebben alleen alle gebruikers toegang tot de toepassing.</span><span class="sxs-lookup"><span data-stu-id="a7fec-105">Disabling this property will only allow all users to access the application.</span></span> <span data-ttu-id="a7fec-106">Alle vermelde gebruikers en gebruikers die aan groepen in de toepassing zijn toegewezen, blijven geldig.</span><span class="sxs-lookup"><span data-stu-id="a7fec-106">All the listed users and those users assigned to groups in the application will still be valid.</span></span>

- <span data-ttu-id="a7fec-107">Zie - Azure AD-app beperken tot een set gebruikers [- Microsoft identity platform | Microsoft Docs](https://docs.microsoft.com/azure/active-directory/develop/howto-restrict-your-app-to-a-set-of-users#:~:text=Select%20the%20application%20you%20want%2cand%20set%20it%20to%20Yes.).</span><span class="sxs-lookup"><span data-stu-id="a7fec-107">To restrict your app to specific set of users, see - [Restrict Azure AD app to a set of users - Microsoft identity platform | Microsoft Docs](https://docs.microsoft.com/azure/active-directory/develop/howto-restrict-your-app-to-a-set-of-users#:~:text=Select%20the%20application%20you%20want%2cand%20set%20it%20to%20Yes.).</span></span>
- <span data-ttu-id="a7fec-108">Zie Gebruikerstoewijzing beheren voor een app in Azure Active Directory als u gebruikers en groepen wilt toewijzen aan ondernemingstoepassingen in Azure Active Directory [(Azure](https://docs.microsoft.com/azure/active-directory/manage-apps/assign-user-or-group-access-portal)AD), vanuit de Azure-portal of met PowerShell.</span><span class="sxs-lookup"><span data-stu-id="a7fec-108">To assign users and groups, to enterprise applications in Azure Active Directory (Azure AD), either from within the Azure portal or by using PowerShell, see [Manage user assignment for an app in Azure Active Directory](https://docs.microsoft.com/azure/active-directory/manage-apps/assign-user-or-group-access-portal).</span></span>
- <span data-ttu-id="a7fec-109">Als u machtigingen voor het maken en beheren van toepassingen wilt delegeren, zie Machtigingen voor beheerders van [toepassingsbeheer gedelegeerden - Azure AD | Microsoft Docs](https://docs.microsoft.com/azure/active-directory/roles/delegate-app-roles).</span><span class="sxs-lookup"><span data-stu-id="a7fec-109">To delegate Application creation and management permissions, see [Delegate application management administrator permissions - Azure AD | Microsoft Docs](https://docs.microsoft.com/azure/active-directory/roles/delegate-app-roles).</span></span>
- <span data-ttu-id="a7fec-110">**Specifieke enterprise-apps verbergen voor gebruikers:** gebruik de volgende stappen om alle Microsoft 365-apps te verbergen in het **MyApps-deelvenster.**</span><span class="sxs-lookup"><span data-stu-id="a7fec-110">**Hide specific enterprise apps from users** - Use the following steps to hide all Microsoft 365 apps from the **MyApps** panel.</span></span> <span data-ttu-id="a7fec-111">De apps zijn nog steeds zichtbaar in de Office 365-portal.</span><span class="sxs-lookup"><span data-stu-id="a7fec-111">The apps will still be visible in the Office 365 portal.</span></span>

 1. <span data-ttu-id="a7fec-112">Meld u aan bij de Azure-portal als globale beheerder voor uw adreslijst.</span><span class="sxs-lookup"><span data-stu-id="a7fec-112">Sign-in to the Azure portal as a global administrator for your directory.</span></span> 
 2. <span data-ttu-id="a7fec-113">Selecteer **Azure Active Directory**.</span><span class="sxs-lookup"><span data-stu-id="a7fec-113">Select **Azure Active Directory**.</span></span> 
 3. <span data-ttu-id="a7fec-114">Selecteer **Gebruikers**.</span><span class="sxs-lookup"><span data-stu-id="a7fec-114">Select **Users**.</span></span> 
 4. <span data-ttu-id="a7fec-115">Selecteer **Gebruikersinstellingen.**</span><span class="sxs-lookup"><span data-stu-id="a7fec-115">Select **User settings**.</span></span> 
 5. <span data-ttu-id="a7fec-116">Klik **onder Enterprise-toepassingen** op Beheren hoe eindgebruikers hun toepassingen **starten en weergeven.**</span><span class="sxs-lookup"><span data-stu-id="a7fec-116">Under **Enterprise applications**, click **Manage how end users launch and view their applications**.</span></span> 
 6. <span data-ttu-id="a7fec-117">Voor **gebruikers kunnen alleen Office 365-apps in de Office 365-portal zien,** klikt u op **Ja.**</span><span class="sxs-lookup"><span data-stu-id="a7fec-117">For **Users can only see Office 365 apps in the Office 365 portal**, click **Yes**.</span></span> 
 7. <span data-ttu-id="a7fec-118">Klik op **Opslaan**.</span><span class="sxs-lookup"><span data-stu-id="a7fec-118">Click **Save**.</span></span> 
 8. <span data-ttu-id="a7fec-119">Zie Een Enterprise-toepassing verbergen vanuit de gebruikerservaring [in Azure AD-| Microsoft Docs](https://docs.microsoft.com/azure/active-directory/manage-apps/hide-application-from-user-portal#:~:text=%20Hide%20an%20application%20from%20the%20end%20user,6%20Click%20Properties.%207%20Click%20Save.%20See%20More.)</span><span class="sxs-lookup"><span data-stu-id="a7fec-119">For more details, see [Hide an Enterprise application from user's experience in Azure AD | Microsoft Docs](https://docs.microsoft.com/azure/active-directory/manage-apps/hide-application-from-user-portal#:~:text=%20Hide%20an%20application%20from%20the%20end%20user,6%20Click%20Properties.%207%20Click%20Save.%20See%20More.)</span></span>

- <span data-ttu-id="a7fec-120">Als u een SaaS-app (Software as a Service) aan veel organisaties aanbiedt, kunt u uw app zo configureren dat aanmeldingen worden geaccepteerd vanuit een Azure Active Directory -tenant (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="a7fec-120">If you offer a Software as a Service (SaaS) app to many organizations, you can configure your app to accept sign-ins from any Azure Active Directory (Azure AD) tenant.</span></span> <span data-ttu-id="a7fec-121">Deze configuratie wordt 'uw toepassing multi-tenant maken' genoemd.</span><span class="sxs-lookup"><span data-stu-id="a7fec-121">This configuration is called "making your application multi-tenant".</span></span> <span data-ttu-id="a7fec-122">Gebruikers in een Azure AD-tenant kunnen zich aanmelden bij uw app nadat ze hebben ingestemd met het gebruik van hun account met uw app.</span><span class="sxs-lookup"><span data-stu-id="a7fec-122">Users in any Azure AD tenant will be able to sign-in to your app after consenting to use their account with your app.</span></span> <span data-ttu-id="a7fec-123">Zie Apps maken die zich aanmelden [bij Azure AD-gebruikers - Microsoft identity platform | Microsoft Docs](https://docs.microsoft.com/azure/active-directory/develop/howto-convert-app-to-be-multi-tenant).</span><span class="sxs-lookup"><span data-stu-id="a7fec-123">For more information, see [Build apps that sign in Azure AD users - Microsoft identity platform | Microsoft Docs](https://docs.microsoft.com/azure/active-directory/develop/howto-convert-app-to-be-multi-tenant).</span></span>

- <span data-ttu-id="a7fec-124">**Hoe kan een eindgebruiker toegang krijgen tot de toepassing nadat deze aan de toepassing is toegewezen?**</span><span class="sxs-lookup"><span data-stu-id="a7fec-124">**How can an end user access the application once he/she is assigned to the application?**</span></span>

<span data-ttu-id="a7fec-125">Elke app in enterprise application blade heeft een koppeling voor eindgebruikers om toegang te krijgen.</span><span class="sxs-lookup"><span data-stu-id="a7fec-125">Each app in Enterprise application blade has a link for end users to access.</span></span> <span data-ttu-id="a7fec-126">Gebruikers kunnen de app ook op een eenvoudige manier openen via **de Myapps-portal.**</span><span class="sxs-lookup"><span data-stu-id="a7fec-126">Users can also access the app through **Myapps** portal in an easy way.</span></span>

- <span data-ttu-id="a7fec-127">**Wilt u weten welke toepassingen en typen toepassingen door gebruikers worden gebruikt?**</span><span class="sxs-lookup"><span data-stu-id="a7fec-127">**Want to know which applications and type of applications are being used by users?**</span></span>

<span data-ttu-id="a7fec-128">U kunt aanmeldingsrapporten voor de afgelopen 30 dagen downloaden **van portal.azure.com > Azure Active directory> Signins> downloadrapporten.**</span><span class="sxs-lookup"><span data-stu-id="a7fec-128">You can download sign-in reports for the last 30 days from **portal.azure.com > Azure Active directory> Signins> download reports**.</span></span>

- <span data-ttu-id="a7fec-129">Lees hoe u [tenantbrede beheerders toestemming verleent voor een toepassing](https://docs.microsoft.com/azure/active-directory/manage-apps/grant-admin-consent) en [Configureren hoe eindgebruikers toestemming geven voor toepassingen.](https://docs.microsoft.com/azure/active-directory/manage-apps/configure-user-consent)</span><span class="sxs-lookup"><span data-stu-id="a7fec-129">Learn how to [Grant tenant wide admin consent to an application](https://docs.microsoft.com/azure/active-directory/manage-apps/grant-admin-consent) and [Configure how end users consent to applications](https://docs.microsoft.com/azure/active-directory/manage-apps/configure-user-consent).</span></span>

- <span data-ttu-id="a7fec-130">Meer [inzicht in de manier waarop toestemming werkt](https://docs.microsoft.com/azure/active-directory/develop/v2-permissions-and-consent) en Toestemming voor toepassingen [beheren.](https://docs.microsoft.com/azure/active-directory/manage-apps/manage-consent-requests)</span><span class="sxs-lookup"><span data-stu-id="a7fec-130">Understand [how consent works](https://docs.microsoft.com/azure/active-directory/develop/v2-permissions-and-consent) and [Manage consent to applications](https://docs.microsoft.com/azure/active-directory/manage-apps/manage-consent-requests).</span></span>

