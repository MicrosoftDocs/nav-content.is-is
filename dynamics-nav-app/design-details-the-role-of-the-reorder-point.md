---
title: "Hönnunarupplýsingar - Hlutverk endurpöntunarmarks"
description: "Þetta efnisatriði fjallar um mikilvægi þess að setja upp endurpöntunarmark, svo þú vitir hvenær skal panta frekari birgðir."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: desigh, reorder, demand, supply
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 8035a670077e53981e9c366d22bdb20df06d8c1b
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-the-role-of-the-reorder-point"></a><span data-ttu-id="01a1e-103">Hönnunarupplýsingar: Hlutverk endurpöntunarmarks</span><span class="sxs-lookup"><span data-stu-id="01a1e-103">Design Details: The Role of the Reorder Point</span></span>
<span data-ttu-id="01a1e-104">Í viðbót við almenna jafnvægi á framboð og eftirspurn, áætlanagerð kerfi verður einnig fylgjast birgðastigum fyrir viðkomandi vöru að virða skilgreind endurröðun stefnu.</span><span class="sxs-lookup"><span data-stu-id="01a1e-104">In addition to the general balancing of supply and demand, the planning system must also monitor inventory levels for the affected items to respect the defined reordering policies.</span></span>  
  
<span data-ttu-id="01a1e-105">Endurpöntunarmark stendur fyrir eftirspurn á afhendingartíma.</span><span class="sxs-lookup"><span data-stu-id="01a1e-105">A reorder point represents demand during lead time.</span></span> <span data-ttu-id="01a1e-106">Þegar áætlaðar birgðir fara undir birgðastigið sem endurpöntunarmark skilgreinir er kominn tími til að panta meira magn.</span><span class="sxs-lookup"><span data-stu-id="01a1e-106">When the projected inventory passes below the inventory level defined by the reorder point, it is time to order more quantity.</span></span> <span data-ttu-id="01a1e-107">Á meðan eiga birgðir smám saman að minnka og mögulega ná núlli (eða öryggisbirgðastigi), þar til fyllt er á.</span><span class="sxs-lookup"><span data-stu-id="01a1e-107">Meanwhile, the inventory is expected to decrease gradually and possibly reach zero (or the safety stock level), until the replenishment arrives.</span></span>  
  
<span data-ttu-id="01a1e-108">Í samræmi mun áætlunarkerfið stinga upp á framboðspöntun sem er dagsett í framtíðinni á þeim tíma þegar áætlaðar birgðir fara undir endurpöntunarmark.</span><span class="sxs-lookup"><span data-stu-id="01a1e-108">Accordingly, the planning system will suggest a forward-scheduled supply order at the point when the projected inventory passes below the reorder point.</span></span>  
  
<span data-ttu-id="01a1e-109">Endurpöntunarmarkið endurspeglar tiltekið birgðastig.</span><span class="sxs-lookup"><span data-stu-id="01a1e-109">The reorder point reflects a certain inventory level.</span></span> <span data-ttu-id="01a1e-110">Hins vegar geta birgðastig hreyfst töluvert innan tímarammans og þess vegna verður áætlanakerfið að fylgjast stöðugt með áætluðum tiltækum birgðum.</span><span class="sxs-lookup"><span data-stu-id="01a1e-110">However, inventory levels can move significantly during the time bucket and, therefore, the planning system must constantly monitor the projected available inventory.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="01a1e-111">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="01a1e-111">See Also</span></span>  
<span data-ttu-id="01a1e-112">[Hönnunarupplýsingar: Endurpöntunarstefnur](design-details-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="01a1e-112">[Design Details: Reordering Policies](design-details-reordering-policies.md) </span></span>  
<span data-ttu-id="01a1e-113">[Hönnunarupplýsingar: áætlunarfæribreyta](design-details-planning-parameters.md) </span><span class="sxs-lookup"><span data-stu-id="01a1e-113">[Design Details: Planning Parameters](design-details-planning-parameters.md) </span></span>  
<span data-ttu-id="01a1e-114">[Hönnunarupplýsingar: Meðhöndlun endurpöntunarstefna](design-details-handling-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="01a1e-114">[Design Details: Handling Reordering Policies](design-details-handling-reordering-policies.md) </span></span>  
[<span data-ttu-id="01a1e-115">Hönnunarupplýsingar: framboðsáætlun</span><span class="sxs-lookup"><span data-stu-id="01a1e-115">Design Details: Supply Planning</span></span>](design-details-supply-planning.md)