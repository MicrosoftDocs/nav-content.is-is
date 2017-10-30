---
title: "Hönnunarupplýsingar - Hlutverk tímaramma"
description: "Tilgangurinn með tímarammanum er að safna saman eftirspurnartilvikum innan tímagluggans til að útbúa sameiginlega birgðapöntun."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: c05bb3ca1913b1f5d0abe0bfa26248d08e080ad6
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-the-role-of-the-time-bucket"></a><span data-ttu-id="30ca4-103">Hönnunarupplýsingar: Hlutverk tímaramma</span><span class="sxs-lookup"><span data-stu-id="30ca4-103">Design Details: The Role of the Time Bucket</span></span>
<span data-ttu-id="30ca4-104">Tilgangurinn með tímarammanum er að safna saman eftirspurnartilvikum innan tímagluggans til að útbúa sameiginlega birgðapöntun.</span><span class="sxs-lookup"><span data-stu-id="30ca4-104">The purpose of the time bucket is to collect demand events within the time window in order to make a joint supply order.</span></span>  
  
 <span data-ttu-id="30ca4-105">Fyrir endurpöntunarstefnur sem nota endurpöntunarmark er hægt að skilgreina tímaramma.</span><span class="sxs-lookup"><span data-stu-id="30ca4-105">For reordering policies that use a reorder point, you can define a time bucket.</span></span> <span data-ttu-id="30ca4-106">Þetta tryggir að eftirspurn innan sama tímabils sé safnað upp áður en áhrifin á áætlaðar birgðir eru könnuð, og hvort endurpöntunarmarki hafi verið náð.</span><span class="sxs-lookup"><span data-stu-id="30ca4-106">This ensures that demand within the same time period is accumulated before checking the impact on the projected inventory and whether the reorder point has been passed.</span></span> <span data-ttu-id="30ca4-107">Ef farið er yfir endurpöntunarmarkið er ný birgðapöntun áætluð framvirkt frá lokum tímabilsins sem skilgreint er í tímarammanum.</span><span class="sxs-lookup"><span data-stu-id="30ca4-107">If the reorder point is passed, a new supply order is scheduled forward from the end of the period defined by the time bucket.</span></span> <span data-ttu-id="30ca4-108">Tímaramminn hefst á upphafsdagsetningu áætlunar.</span><span class="sxs-lookup"><span data-stu-id="30ca4-108">The time buckets begin on the planning starting date.</span></span>  
  
 <span data-ttu-id="30ca4-109">Tímaramminn endurspeglar það handvirka ferli að kanna birgðastigið oft fremur en fyrir hverja færslu.</span><span class="sxs-lookup"><span data-stu-id="30ca4-109">The time-bucketed concept reflects the manual process of checking the inventory level on a frequent basis rather than for each transaction.</span></span> <span data-ttu-id="30ca4-110">Notandinn verður að tilgreina tíðnina (tímarammann).</span><span class="sxs-lookup"><span data-stu-id="30ca4-110">The user needs to define the frequency (the time bucket).</span></span> <span data-ttu-id="30ca4-111">Til dæmis safnar notandinn saman öllum vöruþörfum frá einum lánardrottni til að leggja inn vikulega pöntun.</span><span class="sxs-lookup"><span data-stu-id="30ca4-111">For example, the user gathers all item needs from one vendor to place a weekly order.</span></span>  
  
 ![](media/nav_app_supply_planning_2_reorder_cycle.png "NAV_APP_supply_planning_2_reorder_cycle")  
  
 <span data-ttu-id="30ca4-112">Tímaramminn er vanalega notaður til að forðast keðjuverkun.</span><span class="sxs-lookup"><span data-stu-id="30ca4-112">The time bucket is generally used to avoid a cascade effect.</span></span> <span data-ttu-id="30ca4-113">Til dæmis jöfn lína framboðs og eftirspurnar þar sem fyrri eftirspurn er afturkölluð eða ný búin til.</span><span class="sxs-lookup"><span data-stu-id="30ca4-113">For example, a balanced row of demand and supply where an early demand is canceled, or a new one is created.</span></span> <span data-ttu-id="30ca4-114">Niðurstaðan ætti að vera sú að framboðspöntunin (nema sú síðasta) er enduráætluð.</span><span class="sxs-lookup"><span data-stu-id="30ca4-114">The result would be that every supply order (except the last one) is rescheduled.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="30ca4-115">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="30ca4-115">See Also</span></span>  
 <span data-ttu-id="30ca4-116">[Hönnunarupplýsingar: Endurpöntunarstefnur](design-details-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="30ca4-116">[Design Details: Reordering Policies](design-details-reordering-policies.md) </span></span>  
 <span data-ttu-id="30ca4-117">[Hönnunarupplýsingar: áætlunarfæribreyta](design-details-planning-parameters.md) </span><span class="sxs-lookup"><span data-stu-id="30ca4-117">[Design Details: Planning Parameters](design-details-planning-parameters.md) </span></span>  
 <span data-ttu-id="30ca4-118">[Hönnunarupplýsingar: Meðhöndlun endurpöntunarstefna](design-details-handling-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="30ca4-118">[Design Details: Handling Reordering Policies](design-details-handling-reordering-policies.md) </span></span>  
 [<span data-ttu-id="30ca4-119">Hönnunarupplýsingar: framboðsáætlun</span><span class="sxs-lookup"><span data-stu-id="30ca4-119">Design Details: Supply Planning</span></span>](design-details-supply-planning.md)