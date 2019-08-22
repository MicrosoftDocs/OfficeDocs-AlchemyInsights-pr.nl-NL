---
title: 902 (synchronisatiefouten als gevolg van dubbele objecten)
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 5/30/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 902
ms.assetid: 9d9277a5-c825-4512-8d54-7138b2ee0c40
ms.openlocfilehash: 777c2d8d530d03d58180f43b362ee065439b56b3
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 08/22/2019
ms.locfileid: "36507410"
---
# <a name="sync-errors-due-to-duplicate-objects"></a><span data-ttu-id="4a673-102">Synchronisatiefouten als gevolg van dubbele objecten</span><span class="sxs-lookup"><span data-stu-id="4a673-102">Sync errors due to duplicate objects</span></span>

<span data-ttu-id="4a673-103">Mogelijk wordt een van de volgende foutberichten weergegeven wanneer adreslijstsynchronisatie is voltooid in Office 365:</span><span class="sxs-lookup"><span data-stu-id="4a673-103">You might receive one of the following error messages when directory synchronization finishes in Office 365:</span></span>

- <span data-ttu-id="4a673-104">Kan dit object in Microsoft Online Services niet bijwerken omdat de volgende kenmerken die zijn gekoppeld aan dit object zijn waarden die al gekoppeld aan een ander object in uw lokale map zijn.</span><span class="sxs-lookup"><span data-stu-id="4a673-104">Unable to update this object in Microsoft Online Services because the following attributes associated with this object have values that may already be associated with another object in your local directory.</span></span>

- <span data-ttu-id="4a673-105">Een gesynchroniseerde-object met dezelfde proxyadres bestaat al in de map Microsoft Online Services.</span><span class="sxs-lookup"><span data-stu-id="4a673-105">A synchronized object with the same proxy address already exists in your Microsoft Online Services directory.</span></span>

- <span data-ttu-id="4a673-106">Kan dit object niet bijwerken omdat de volgende kenmerken die zijn gekoppeld aan dit object al gekoppeld aan een ander object in uw lokale Active Directory zijn kunnen waarden hebben: UserPrincipalName.</span><span class="sxs-lookup"><span data-stu-id="4a673-106">Unable to update this object because the following attributes associated with this object have values that may already be associated with another object in your local directory services: UserPrincipalName.</span></span>

<span data-ttu-id="4a673-107">Identificeren en oplossen van het probleem, downloaden en uitvoeren van het [IdFix DirSync fout herstel Tool](https://www.microsoft.com/download/details.aspx?id=36832).</span><span class="sxs-lookup"><span data-stu-id="4a673-107">To identify and fix the issue, download and run the [IdFix DirSync Error Remediation Tool](https://www.microsoft.com/download/details.aspx?id=36832).</span></span>

<span data-ttu-id="4a673-108">Zie [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o)voor meer informatie.</span><span class="sxs-lookup"><span data-stu-id="4a673-108">For more information, see [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).</span></span>
