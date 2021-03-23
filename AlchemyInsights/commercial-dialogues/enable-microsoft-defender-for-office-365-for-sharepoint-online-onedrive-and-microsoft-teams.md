---
title: Microsoft Defender inschakelen voor Office 365 voor SharePoint Online, OneDrive en Microsoft Teams
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
ms.openlocfilehash: 1c29afdcc52e7032fea22d698371677918665fa9
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 03/11/2021
ms.locfileid: "50744114"
---
# <a name="enable-microsoft-defender-for-office-365-for-sharepoint-online-onedrive-and-microsoft-teams"></a><span data-ttu-id="d4ba9-102">Microsoft Defender inschakelen voor Office 365 voor SharePoint Online, OneDrive en Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="d4ba9-102">Enable Microsoft Defender for Office 365 for SharePoint Online, OneDrive and Microsoft Teams</span></span>

1. <span data-ttu-id="d4ba9-103">Meld u aan bij het Beveiligings- en compliancecentrum van [Office 365](https://protection.office.com/)met de referenties van uw globale beheerder of beveiligingsbeheerder.</span><span class="sxs-lookup"><span data-stu-id="d4ba9-103">Using your global admin or security admin credentials, log in to the [Office 365 Security and Compliance Center](https://protection.office.com/).</span></span>
2. <span data-ttu-id="d4ba9-104">Selecteer **Bedreigingsbeheer** in het linkerdeelvenster en selecteer vervolgens   >  [Beleidsveilige bijlagen.](https://protection.office.com/safeattachment)</span><span class="sxs-lookup"><span data-stu-id="d4ba9-104">Select **Threat management** in the left pane, and then select **Policy** > [Safe attachments](https://protection.office.com/safeattachment).</span></span>
3. <span data-ttu-id="d4ba9-105">Selecteer Microsoft Defender voor Office 365 in te zetten **voor SharePoint, OneDrive en Microsoft Teams** en selecteer vervolgens **Opslaan.**</span><span class="sxs-lookup"><span data-stu-id="d4ba9-105">Select **Turn on Microsoft Defender for Office 365 for SharePoint, OneDrive, and Microsoft Teams**, and then select **Save**.</span></span>
    > [!TIP]
    >
    > - <span data-ttu-id="d4ba9-106">Voer als globale beheerder of SharePoint Online-beheerder de volgende PowerShell-cmdlet uit met de parameter **DisallowInfectedFileDownload** die is ingesteld op *waar:* [Set-SPOTenant](https://go.microsoft.com/fwlink/?linkid=2092301)</span><span class="sxs-lookup"><span data-stu-id="d4ba9-106">As a global admin or a SharePoint Online admin, run the following PowerShell cmdlet with the **DisallowInfectedFileDownload** parameter set to *true*: [Set-SPOTenant](https://go.microsoft.com/fwlink/?linkid=2092301)</span></span>
    > - [<span data-ttu-id="d4ba9-107">Waarschuwingen instellen voor gedetecteerde bestanden</span><span class="sxs-lookup"><span data-stu-id="d4ba9-107">Set up alerts for detected files</span></span>](https://go.microsoft.com/fwlink/?linkid=2092110)

<span data-ttu-id="d4ba9-108">Zie Microsoft Defender voor [Office 365 voor SharePoint, OneDrive en Microsoft Teams](https://go.microsoft.com/fwlink/?linkid=2092041)voor meer informatie.</span><span class="sxs-lookup"><span data-stu-id="d4ba9-108">For more information, see [Microsoft Defender for Office 365 for SharePoint, OneDrive, and Microsoft Teams](https://go.microsoft.com/fwlink/?linkid=2092041).</span></span>