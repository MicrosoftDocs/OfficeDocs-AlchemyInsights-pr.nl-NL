---
title: Inhoud zoeken zonder resultaten
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000661"
- "2527"
ms.openlocfilehash: 0267286ca5967ee891e65343d49adf776f0322a6
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 04/15/2021
ms.locfileid: "51816843"
---
# <a name="no-results-from-content-searchexports"></a>Geen resultaten van Inhoud zoeken/exporteren

Problemen met Inhoud zoeken/exporteren die geen gegevens retourneren, kunnen het gevolg zijn van bepaalde compliancebeveiligingsfilters die zijn ingesteld door een specifieke beheerder en die niet aan alle beheerders zijn door te geven.

Als u dit wilt oplossen, controleert u of er compliancebeveiligingsfilters zijn die dit kunnen veroorzaken:
1. Verbinding maken met Powershell voor beveiligings- en compliancecentrum
2. Voer de volgende opdrachtlets uit:
<br>$org = "yourdomain.com"
<br>Get-ComplianceSecurityFilter -Organisatie $org