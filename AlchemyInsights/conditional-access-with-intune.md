---
title: Voorwaardelijke toegang met intune
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: aecba7c5-e86d-4ec8-9d44-679f5a3d659d
ms.openlocfilehash: 5eec5982118b4f0246afadf2af219b2d5f32f95c
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 09/15/2020
ms.locfileid: "47807654"
---
# <a name="conditional-access-with-intune"></a><span data-ttu-id="ff870-102">Voorwaardelijke toegang met intune</span><span class="sxs-lookup"><span data-stu-id="ff870-102">Conditional Access with Intune</span></span>

<span data-ttu-id="ff870-103">Voor  **voorwaardelijke toegang**  met intune zijn drie stappen nodig:</span><span class="sxs-lookup"><span data-stu-id="ff870-103">Using  **Conditional Access**  with Intune requires 3 steps:</span></span>

- <span data-ttu-id="ff870-104">Maak een  **nalevingsbeleid**  ([Android](https://docs.microsoft.com/intune/compliance-policy-create-android),  [IOS](https://docs.microsoft.com/intune/compliance-policy-create-ios),  [Windows](https://docs.microsoft.com//intune/compliance-policy-create-windows)) om te bepalen welke instellingen moeten voldoen voordat het apparaat als compatibel wordt beschouwd.</span><span class="sxs-lookup"><span data-stu-id="ff870-104">Create a  **Compliance Policy**  ([Android](https://docs.microsoft.com/intune/compliance-policy-create-android),  [iOS](https://docs.microsoft.com/intune/compliance-policy-create-ios),  [Windows](https://docs.microsoft.com//intune/compliance-policy-create-windows)) to define settings that must be met before the device is considered compliant.</span></span> <span data-ttu-id="ff870-105">Een apparaat moet bijvoorbeeld een pincode van minimaal 6 cijfers hebben voordat deze als compatibel wordt beschouwd.</span><span class="sxs-lookup"><span data-stu-id="ff870-105">For example, a device must have a pin of at least 6 digits before it is considered compliant.</span></span>
- <span data-ttu-id="ff870-106">Maak een **voorwaardelijk toegangsbeleid**  om te bepalen welke bronnen worden beveiligd, en aan welke voorwaarden moet worden voldaan om toegang te krijgen tot de bronnen.</span><span class="sxs-lookup"><span data-stu-id="ff870-106">Create a **Conditional Access Policy**  that defines what resources are being protected, and what conditions need to be met to access those resources.</span></span>  <span data-ttu-id="ff870-107">Een apparaat moet [bijvoorbeeld](https://docs.microsoft.com/intune/tutorial-protect-email-on-unmanaged-devices#create-conditional-access-policies) voldoen voordat u zakelijke e-mail opent.</span><span class="sxs-lookup"><span data-stu-id="ff870-107">[For example,](https://docs.microsoft.com/intune/tutorial-protect-email-on-unmanaged-devices#create-conditional-access-policies)  a device must be compliant before accessing corporate email.</span></span>
- <span data-ttu-id="ff870-108">Zorg ervoor dat zowel **nalevingsbeleid**  als  **beleid voor voorwaardelijke toegang**  is bedoeld voor de gewenste groepen gebruikers.</span><span class="sxs-lookup"><span data-stu-id="ff870-108">Ensure both **Compliance Policies**  and  **Conditional Access Policies**  are targeted to the desired groups of users.</span></span> <span data-ttu-id="ff870-109">Daarom moet u mogelijk specifieke groepen gebruikers maken in azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="ff870-109">This may require creating specific groups of users in Azure Active Directory.</span></span>

<span data-ttu-id="ff870-110">**Handige koppelingen:**</span><span class="sxs-lookup"><span data-stu-id="ff870-110">**Helpful links:**</span></span>

[<span data-ttu-id="ff870-111">Overzicht van apparaatcompatibiliteit</span><span class="sxs-lookup"><span data-stu-id="ff870-111">Device compliance overview</span></span>](https://docs.microsoft.com/intune/device-compliance-get-started)

[<span data-ttu-id="ff870-112">Oplossing van een certificeringsinstantie</span><span class="sxs-lookup"><span data-stu-id="ff870-112">Troubleshooting CA</span></span>](https://docs.microsoft.com/intune/troubleshoot-conditional-access)

[<span data-ttu-id="ff870-113">Beleid voor probleemoplossing</span><span class="sxs-lookup"><span data-stu-id="ff870-113">Troubleshooting policy</span></span>](https://docs.microsoft.com/intune/troubleshoot-policies-in-microsoft-intune)

<span data-ttu-id="ff870-114">Als u E-mail (Exchange Online) van Access wilt beschermen tegen niet-compatibele apparaten, moet u beide documenten volgen:</span><span class="sxs-lookup"><span data-stu-id="ff870-114">To protect Email (Exchange online) from access by noncompliant devices, both documents must be followed:</span></span>

1. [<span data-ttu-id="ff870-115">E-mail toegang beschermen tegen apparaten met EAS</span><span class="sxs-lookup"><span data-stu-id="ff870-115">Protect email access from devices using EAS</span></span>](https://docs.microsoft.com/intune/tutorial-protect-email-on-unmanaged-devices)
2. [<span data-ttu-id="ff870-116">E-mail toegang beschermen tegen apparaten met moderne verificatie-clients, zoals Outlook</span><span class="sxs-lookup"><span data-stu-id="ff870-116">Protect email access from devices using modern authentication clients like Outlook</span></span>](https://docs.microsoft.com/intune/tutorial-protect-email-on-enrolled-devices)