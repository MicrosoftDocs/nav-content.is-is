---
title: "Bestu venjur fyrir uppsetningu altækra áætlana"
description: "Flýtiflipinn **Áætlun** í glugganum **Framleiðslugrunnur** inniheldur nokkra reiti sem skilgreina altækar reglur fyrir framboðsáætlun."
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/08/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: b6437c809af79c1c0c24126aaa38e6da6120d066
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="setup-best-practices-global-planning-setup"></a><span data-ttu-id="9d6e9-103">Uppsetning bestu venjur: Uppsetning altækra áætlanna</span><span class="sxs-lookup"><span data-stu-id="9d6e9-103">Setup Best Practices: Global Planning Setup</span></span>
<span data-ttu-id="9d6e9-104">Flýtiflipinn **Áætlun** í glugganum **Framleiðslugrunnur** inniheldur nokkra reiti sem skilgreina altækar reglur fyrir framboðsáætlun.</span><span class="sxs-lookup"><span data-stu-id="9d6e9-104">The **Planning** FastTab in the **Manufacturing Setup** window contains several fields that define global rules for supply planning.</span></span>  

 <span data-ttu-id="9d6e9-105">Eftirfarandi tafla gefur upp bestu venjur um uppsetningu valinna altækra áætlunarfæribreytareita.</span><span class="sxs-lookup"><span data-stu-id="9d6e9-105">The following table provides best practices on how to set up selected global planning parameter fields.</span></span> <span data-ttu-id="9d6e9-106">Nánari upplýsingar um reit fást með því að velja tengilinn í dálkinum **Uppsetningarreitur**.</span><span class="sxs-lookup"><span data-stu-id="9d6e9-106">For more information about a field, choose the link in the **Setup field** column.</span></span>  

|<span data-ttu-id="9d6e9-107">Uppsetning reits</span><span class="sxs-lookup"><span data-stu-id="9d6e9-107">Setup field</span></span>|<span data-ttu-id="9d6e9-108">Bestu starfsvenjur</span><span class="sxs-lookup"><span data-stu-id="9d6e9-108">Best practice</span></span>|<span data-ttu-id="9d6e9-109">Athugasemd</span><span class="sxs-lookup"><span data-stu-id="9d6e9-109">Comment</span></span>|  
|-----------------|-------------------|-------------|  
|<span data-ttu-id="9d6e9-110">Nota spá á staðsetningum</span><span class="sxs-lookup"><span data-stu-id="9d6e9-110">Use Forecast on Locations</span></span>|<span data-ttu-id="9d6e9-111">Valið ef spár eru gerðar fyrir tilteknar birgðageymslur.</span><span class="sxs-lookup"><span data-stu-id="9d6e9-111">Select if you have forecasts for specific locations.</span></span>||  
|<span data-ttu-id="9d6e9-112">Íhlutir í birgðageymslu</span><span class="sxs-lookup"><span data-stu-id="9d6e9-112">Components at Location</span></span>|<span data-ttu-id="9d6e9-113">Ef vörur eru ekki eru skilgreindar sem birgðahaldseiningar skal velja birgðageymslukóta aðalvöruhúss.</span><span class="sxs-lookup"><span data-stu-id="9d6e9-113">If items are not defined as SKUs, select the location code of your main warehouse.</span></span>|<span data-ttu-id="9d6e9-114">Þetta á einnig við ef aðeins er notuð innkaupatillögubók.</span><span class="sxs-lookup"><span data-stu-id="9d6e9-114">This also applies if you only use the requisition worksheet.</span></span>|  
|<span data-ttu-id="9d6e9-115">Autt yfirflæðisstig</span><span class="sxs-lookup"><span data-stu-id="9d6e9-115">Blank Overflow Level</span></span>|<span data-ttu-id="9d6e9-116">Velja skal **Leyfa sjálfgefinn útreikning** ef þú kemur frá Microsoft Dynamics NAV 5.0 eða eldri.</span><span class="sxs-lookup"><span data-stu-id="9d6e9-116">Select **Allow Default Calculation** if you are migrating from Microsoft Dynamics NAV 5.0 or earlier.</span></span>|<span data-ttu-id="9d6e9-117">Notist eingöngu ef leyfa á öllum eða nokkrum af vörunum að flæða yfir endurpöntunarmarkið.</span><span class="sxs-lookup"><span data-stu-id="9d6e9-117">Use only if you want to allow all or some of your items to overflow the reorder point.</span></span>|  
|<span data-ttu-id="9d6e9-118">Sjálfgefið hömlutímabil</span><span class="sxs-lookup"><span data-stu-id="9d6e9-118">Default Dampener Period</span></span>|<span data-ttu-id="9d6e9-119">Stilla á milli 1D og 5D.</span><span class="sxs-lookup"><span data-stu-id="9d6e9-119">Set between 1D and 5D.</span></span><br /><br /> <span data-ttu-id="9d6e9-120">Ef þú hefur ekki gert áætlanir áður í [!INCLUDE[d365fin](includes/d365fin_md.md)] skaltu stilla lengra tímabil.</span><span class="sxs-lookup"><span data-stu-id="9d6e9-120">If new to planning in [!INCLUDE[d365fin](includes/d365fin_md.md)], then set a longer period.</span></span>|<span data-ttu-id="9d6e9-121">Þegar notendur þekkja ólíkar ástæður aðgerðaboða betur skal stytta hömlutímabilið til að leyfa fleiri tillögur um breytingar.</span><span class="sxs-lookup"><span data-stu-id="9d6e9-121">When users are more familiar with the different reasons for action messages, then shorten the dampener period to allow more change suggestions.</span></span>|  
|<span data-ttu-id="9d6e9-122">Sjálfgefið hömlu magn</span><span class="sxs-lookup"><span data-stu-id="9d6e9-122">Default Dampener Quantity</span></span>|<span data-ttu-id="9d6e9-123">Stilla á milli 5 og 20 prósent af lotustærð vörunnar.</span><span class="sxs-lookup"><span data-stu-id="9d6e9-123">Set between 5 and 20 percent of the item’s lot size.</span></span>||  

## <a name="see-also"></a><span data-ttu-id="9d6e9-124">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="9d6e9-124">See Also</span></span>  
 <span data-ttu-id="9d6e9-125">[Uppsetning bestu venjur: Framboðsáætlun](setup-best-practices-supply-planning.md) </span><span class="sxs-lookup"><span data-stu-id="9d6e9-125">[Setup Best Practices: Supply Planning](setup-best-practices-supply-planning.md) </span></span>  
 <span data-ttu-id="9d6e9-126">[Hönnunarupplýsingar: framboðsáætlun](design-details-supply-planning.md) </span><span class="sxs-lookup"><span data-stu-id="9d6e9-126">[Design Details: Supply Planning](design-details-supply-planning.md) </span></span>  
 [<span data-ttu-id="9d6e9-127">Setja upp flókin notkunarsviðum með því að nota bestu venjur</span><span class="sxs-lookup"><span data-stu-id="9d6e9-127">Set Up Complex Application Areas Using Best Practices</span></span>](set-up-complex-application-areas-using-best-practices.md)  
 <span data-ttu-id="9d6e9-128">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="9d6e9-128">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
