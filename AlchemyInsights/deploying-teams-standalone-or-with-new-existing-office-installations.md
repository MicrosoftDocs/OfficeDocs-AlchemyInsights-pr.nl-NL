---
title: Teams implementeren als zelfstandige versie of met nieuwe of bestaande Office-installaties
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000660"
- "2509"
ms.openlocfilehash: c3ca4365abc41509ccf602c5b9046655706840fc
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 09/15/2020
ms.locfileid: "47806754"
---
# <a name="deploying-teams-as-standalone-or-with-new-or-existing-office-installations"></a>Teams implementeren als zelfstandige versie of met nieuwe of bestaande Office-installaties

Microsoft teams maakt nu deel uit van ***nieuwe installaties*** van microsoft 365-apps voor Enterprise, microsoft 365-apps voor bedrijven en Office voor Mac. Zie [Wanneer maakt Microsoft teams in de nieuwe installaties van Office?](https://docs.microsoft.com/deployoffice/teams-install#when-will-microsoft-teams-start-being-included-with-new-installations-of-microsoft-365-apps) voor meer informatie.

Ook als u vanaf versie 1906 in het huidige kanaal gaat, worden teams ***toegevoegd aan bestaande installaties*** van microsoft 365-apps voor Enterprise-en microsoft 365-apps voor bedrijven op apparaten met Windows wanneer u de bestaande installatie bijwerkt naar de nieuwste versie. Zie [Wat gebeurt er met bestaande installaties van Office?](https://docs.microsoft.com/deployoffice/teams-install#what-about-existing-installations-of-microsoft-365-apps) voor meer informatie.

> [!NOTE]
> Als u niet wilt wachten op dit implementatie schema, kunt u teams voor uw gebruikers implementeren met behulp van de [volgende instructies](https://docs.microsoft.com/MicrosoftTeams/msi-deployment)   of u kunt voorkomen dat uw gebruikers teams voor zichzelf installeren  [https://teams.microsoft.com/downloads](https://teams.microsoft.com/downloads) .

Als uw organisatie niet gereed is om teams te implementeren, kunnen we de stappen uitvoeren om ***teams*** uit te sluiten van [nieuwe](https://docs.microsoft.com/deployoffice/teams-install#how-to-exclude-microsoft-teams-from-new-installations-of-microsoft-365-apps) of [bestaande](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-control-the-installation-of-microsoft-teams) installaties van Office. Zie [voorkomen dat Microsoft teams automatisch wordt gestart na de installatie](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-prevent-microsoft-teams-from-starting-automatically-after-installation)als u teams wilt installeren, maar niet wilt dat teams automatisch worden gestart voor de gebruiker nadat deze is geïnstalleerd.

Zie [Microsoft teams verwijderen](https://support.office.com/article/3b159754-3c26-4952-abe7-57d27f5f4c81)voor informatie over het ***verwijderen van teams*** op een apparaat met Windows. Zie [opschoning van de implementatie van Microsoft teams](https://docs.microsoft.com/microsoftteams/scripts/powershell-script-teams-deployment-clean-up)voor meer informatie over het opschonen van Microsoft teams.

Zie [gedeelde computer en VDI-omgevingen met Microsoft teams voor informatie over](https://docs.microsoft.com/deployoffice/teams-install#shared-computer-and-vdi-environments-with-microsoft-teams)het gebruik van gedeelde computers, Remote Desktop Services (RDS), of VDI (Virtual Desktop Infrastructure).

Als u Office voor Mac gebruikt, raadpleegt u [Microsoft teams-installaties op een Mac](https://docs.microsoft.com/deployoffice/teams-install#microsoft-teams-installations-on-a-mac).

> [!NOTE]
> Wanneer teams is geïnstalleerd, wordt dit na het installeren [automatisch bijgewerkt](https://docs.microsoft.com/deployoffice/teams-install#feature-and-quality-updates-for-microsoft-teams) met de nieuwe functies en kwaliteitsupdates. 