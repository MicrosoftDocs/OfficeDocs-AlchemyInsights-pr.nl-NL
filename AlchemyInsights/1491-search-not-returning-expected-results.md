---
title: 1491-Search-Not-Returning-Expected-Results
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: ''
ms.openlocfilehash: 881a579d7098578452c994b7ac66fe22a1d90dc2
ms.sourcegitcommit: 5182c9a73641079be59740e4524434b2e8be613a
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 02/12/2019
ms.locfileid: "29964839"
---
# <a name="content-search-not-returning-expected-results"></a>Zoeken in inhoud niet verwachte resultaten retourneren

Bij het uitvoeren van zoekopdrachten naar de inhoud van het Office 365-beveiliging & conformiteit, wordt u onverwachte resultaten. Houd rekening met de volgende dingen die je zoekresultaten kunnen beïnvloeden:

- **Locaties van inhoud en zoekcriteria**: Zorg ervoor dat u de juiste plaats inhoud hebt geselecteerd en zoekcriteria. Als u een grote zoekactie (met veel locaties) hebt uitgevoerd, kunt u het opsplitsen in meerdere zoekacties.

- **Gedeeltelijk geïndexeerde items**: [gedeeltelijk geïndexeerde items](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) van postbussen zijn opgenomen in de geschatte zoekresultaten. Echter zijn niet gedeeltelijk geïndexeerde items van sites in SharePoint en OneDrive opgenomen in de raming zoeken.

- **Fouten zoeken**: bij het zoeken naar een groot aantal postvakken (meer dan 100.000 postvakken), krijgt u mogelijk fouten zoeken met foutcodes als CS008-009- en CS012-002). In dat geval opnieuw proberen de zoekopdracht alleen locaties van de mislukte inhoud. Raadpleeg [dit artikel](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) voor meer informatie.