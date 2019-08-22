---
title: Office installeren op een Terminal Server - licentie
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "917"
- "2000020"
ms.assetid: b1074430-489e-4d49-bfe4-3d8783d8073c
ms.openlocfilehash: edac051840594f13b22ccd83f5cd6e3da5f84cbc
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 08/22/2019
ms.locfileid: "36498410"
---
# <a name="installing-office-on-a-terminal-server"></a><span data-ttu-id="4ad9d-102">Office installeren op een Terminal-Server</span><span class="sxs-lookup"><span data-stu-id="4ad9d-102">Installing Office on a Terminal Server</span></span>

<span data-ttu-id="4ad9d-103">Voorheen Terminal Services voor het implementeren van Office 365 ProPlus op een Windows-Server met behulp van extern bureaublad-Services (RDS):</span><span class="sxs-lookup"><span data-stu-id="4ad9d-103">For deploying Office 365 ProPlus on a Windows Server using Remote Desktop Services (RDS), formerly named Terminal Services:</span></span>
  
- <span data-ttu-id="4ad9d-104">U hebt een plan Office 365 met Office 365 ProPlus, zoals Office 365 Enterprise E3 of Enterprise E5.</span><span class="sxs-lookup"><span data-stu-id="4ad9d-104">You must have an Office 365 plan that includes Office 365 ProPlus, such as Office 365 Enterprise E3 or Enterprise E5.</span></span> <span data-ttu-id="4ad9d-105">De Office 365 Business en Office 365 Business Premium plannen bevatten geen Office 365 ProPlus.</span><span class="sxs-lookup"><span data-stu-id="4ad9d-105">The Office 365 Business and Office 365 Business Premium plans do not include Office 365 ProPlus.</span></span>

- <span data-ttu-id="4ad9d-106">U moet [gedeelde computer activeren](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus)inschakelen.</span><span class="sxs-lookup"><span data-stu-id="4ad9d-106">You need to enable [shared computer activation](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).</span></span>

<span data-ttu-id="4ad9d-107">Als u wilt dat Office 365 ProPlus installeren op RDS vanuit Office 365 portal ***waarin standaardinstellingen voor de installatie worden gebruikt***, als volgt te werk:</span><span class="sxs-lookup"><span data-stu-id="4ad9d-107">If you want to install Office 365 ProPlus on RDS from the Office 365 portal, ***which uses default installation settings***, follow these steps:</span></span>
  
1. <span data-ttu-id="4ad9d-108">Controleer wat u hebt Office 365-plan.</span><span class="sxs-lookup"><span data-stu-id="4ad9d-108">Check what Office 365 plan you have.</span></span> [<span data-ttu-id="4ad9d-109">Meer informatie over hoe</span><span class="sxs-lookup"><span data-stu-id="4ad9d-109">Learn how</span></span>](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)

2. <span data-ttu-id="4ad9d-110">Indien nodig, overschakelen naar een ander Office 365 plan.</span><span class="sxs-lookup"><span data-stu-id="4ad9d-110">If necessary, switch to a different Office 365 plan.</span></span> [<span data-ttu-id="4ad9d-111">Meer informatie over hoe</span><span class="sxs-lookup"><span data-stu-id="4ad9d-111">Learn how</span></span>](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)

3. <span data-ttu-id="4ad9d-112">Als Office al is geïnstalleerd op de RDS-server met behulp van Office 365 plannen, verwijderen.</span><span class="sxs-lookup"><span data-stu-id="4ad9d-112">If Office is already installed on the RDS server using any other Office 365 plans, uninstall it.</span></span> <span data-ttu-id="4ad9d-113">Bijvoorbeeld door te gaan naar het Configuratiescherm \> een programma verwijderen.</span><span class="sxs-lookup"><span data-stu-id="4ad9d-113">For example, by going to Control Panel \> Uninstall a program.</span></span> <span data-ttu-id="4ad9d-114">Verwijderen met behulp van [Microsoft-ondersteuning en herstel-assistent](https://aka.ms/SARA-OfficeUninstall-Alchemy) als u in de problemen.</span><span class="sxs-lookup"><span data-stu-id="4ad9d-114">Uninstall using [Microsoft Support and Recovery Assistant](https://aka.ms/SARA-OfficeUninstall-Alchemy) if you're running into issues.</span></span>

4. <span data-ttu-id="4ad9d-115">Log in op de RDS-server aan met uw administrator-account en het [installeren van Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx)Office 365 portal.</span><span class="sxs-lookup"><span data-stu-id="4ad9d-115">On the RDS server, sign in to the Office 365 portal with your administrator account and [install Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).</span></span>

5. <span data-ttu-id="4ad9d-116">Nadat Office is geïnstalleerd, ***niet openen of log in*** om alle Office-toepassingen.</span><span class="sxs-lookup"><span data-stu-id="4ad9d-116">After Office is installed, ***don't open or sign in*** to any Office applications.</span></span>

6. <span data-ttu-id="4ad9d-117">Inschakelen op de server met RDS gedeelde computer activeren door het bewerken van het register door de volgende stappen:</span><span class="sxs-lookup"><span data-stu-id="4ad9d-117">On the RDS server, enable shared computer activation by editing the registry by following these steps:</span></span>

1. <span data-ttu-id="4ad9d-118">Klik met de rechtermuisknop op de Windows-knop in de linkerbenedenhoek van het scherm en selecteer uitvoeren.</span><span class="sxs-lookup"><span data-stu-id="4ad9d-118">Right-click the Windows button in the lower left-hand corner of your screen and select Run.</span></span> <span data-ttu-id="4ad9d-119">Typ **regedit**in het vak openen en klik vervolgens op OK.</span><span class="sxs-lookup"><span data-stu-id="4ad9d-119">In the Open box, type **regedit**, and then select OK.</span></span>

2. <span data-ttu-id="4ad9d-120">Selecteer Ja wanneer u wordt gevraagd om de Register-Editor om uw apparaat te wijzigen.</span><span class="sxs-lookup"><span data-stu-id="4ad9d-120">Select Yes when prompted to allow Registry Editor to make changes to your device.</span></span>

3. <span data-ttu-id="4ad9d-121">Een string-waarde van **SharedComputerLicensing** in de Register-Editor toevoegen met de waarde 1 onder HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.</span><span class="sxs-lookup"><span data-stu-id="4ad9d-121">In the Registry Editor, add a string value of **SharedComputerLicensing** with a setting of 1 under HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.</span></span>

7. <span data-ttu-id="4ad9d-122">RDS-server, ***als een gebruiker zich aanmeldt*** en [Controleer of gedeelde computer activeren voor Office 365 ProPlus is ingeschakeld](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).</span><span class="sxs-lookup"><span data-stu-id="4ad9d-122">On the RDS server, ***sign in as an end user*** and [verify that shared computer activation is enabled for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).</span></span>

<span data-ttu-id="4ad9d-123">Zie [Implementatie van Office 365 ProPlus met behulp van extern bureaublad-Services](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services)voor meer informatie over vereisten, installatie-instructies en richtlijnen voor aangepaste installaties met behulp van de Office Deployment Tool.</span><span class="sxs-lookup"><span data-stu-id="4ad9d-123">For more details on prerequisites, setup instructions and guidance on customized installations by using the Office Deployment Tool, please see [Deploy Office 365 ProPlus by using Remote Desktop Services](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).</span></span>
  
<span data-ttu-id="4ad9d-124">Voor het oplossen van fouten met betrekking tot de gedeelde computer activeren, Zie [problemen oplossen met het activeren van Office 365 ProPlus gedeelde computer](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).</span><span class="sxs-lookup"><span data-stu-id="4ad9d-124">To fix errors related to shared computer activation, please see [Troubleshoot issues with shared computer activation for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).</span></span>
  