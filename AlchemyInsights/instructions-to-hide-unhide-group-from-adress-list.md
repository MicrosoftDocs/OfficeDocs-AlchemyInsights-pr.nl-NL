---
title: Instructies om groep te verbergen/zichtbaar te maken uit adreslijst
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "3161"
ms.openlocfilehash: 61ba34e6d554831da712a92401f26fabb02c26b7
ms.sourcegitcommit: 286000b588adef1bbbb28337a9d9e087ec783fa2
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 04/27/2020
ms.locfileid: "43908339"
---
# <a name="hide-microsoft-365-group-from-address-list-gal"></a><span data-ttu-id="6f125-102">Microsoft 365-groep verbergen voor adreslijst (GAL)</span><span class="sxs-lookup"><span data-stu-id="6f125-102">Hide Microsoft 365 group from address list (GAL)</span></span>

<span data-ttu-id="6f125-103">Als u een Microsoft 365-groep wilt verbergen voor adreslijsten (GAL) van Exchange-clients (zoals Outlook of OWA), gebruikt u de volgende opdracht in de exo-shell:</span><span class="sxs-lookup"><span data-stu-id="6f125-103">To hide an Microsoft 365 group from address lists (GAL) of Exchange clients (such as Outlook or OWA), use the following command in EXO shell:</span></span>

`Set-UnifiedGroup -Identity GroupName -HiddenFromAddressListsEnabled:$true`

<span data-ttu-id="6f125-104">Als u wilt voorkomen dat de Microsoft 365-groep zichtbaar is voor Exchange-clients, gebruikt u de volgende opdracht in de exo-shell:</span><span class="sxs-lookup"><span data-stu-id="6f125-104">To hide the Microsoft 365 group from being visible to Exchange clients, use the following command in EXO shell:</span></span>

`Set-unifiedGroup -Identity GroupName -HiddenFromExchangeClientsEnabled:$true
Check this article for detailed instructions`

