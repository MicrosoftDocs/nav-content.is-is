---
title: "Hönnunarupplýsingar - Hámarksmagn"
description: "Reglan um hámarksmag er ein leið til að viðhalda birgðum með því að nota endurpöntunarmark."
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
ms.openlocfilehash: eb2dfa933cd80400e3143c2c0b5bc44691170baf
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-maximum-qty"></a><span data-ttu-id="ece4e-103">Hönnunarupplýsingar: Hámarksmagn</span><span class="sxs-lookup"><span data-stu-id="ece4e-103">Design Details: Maximum Qty.</span></span>
<span data-ttu-id="ece4e-104">Reglan um hámarksmag er ein leið til að viðhalda birgðum með því að nota endurpöntunarmark.</span><span class="sxs-lookup"><span data-stu-id="ece4e-104">The Maximum Quantity policy is a way to maintain inventory using a reorder point.</span></span>  
  
 <span data-ttu-id="ece4e-105">Allt sem gildir um stefnu endurpöntunarmagns gildir einnig um þessa stefnu.</span><span class="sxs-lookup"><span data-stu-id="ece4e-105">Everything regarding the Fixed Reorder Qty. policy also applies to this policy.</span></span> <span data-ttu-id="ece4e-106">Eini munurinn er magnið sem lagt er til sem framboð.</span><span class="sxs-lookup"><span data-stu-id="ece4e-106">The only difference is the quantity of the suggested supply.</span></span> <span data-ttu-id="ece4e-107">Þegar reglan um hámarksmagn rer notuð verður endurpöntunarmagnið skilgrein á virkan hátt samkvæmt ætluðu birgðastigi og verður því yfirleitt mismunandi eftir pöntunum.</span><span class="sxs-lookup"><span data-stu-id="ece4e-107">When using the maximum quantity policy, the reorder quantity will be defined dynamically based on the projected inventory level and will therefore usually differ from order to order.</span></span>  
  
## <a name="calculated-per-time-bucket"></a><span data-ttu-id="ece4e-108">Reiknuð fyrir hvern tímaramma</span><span class="sxs-lookup"><span data-stu-id="ece4e-108">Calculated per Time Bucket</span></span>  
 <span data-ttu-id="ece4e-109">Endurpöntunarmarkið er ákvarðað á þeim tímapunkti (við lok tímaramma) þegar áætlanakerfið greinir að farið hefur verið yfir endurpöntunarmark.</span><span class="sxs-lookup"><span data-stu-id="ece4e-109">The reorder quantity is determined at the point of time (the end of a time bucket) when the planning system detects that the reorder point has been crossed.</span></span> <span data-ttu-id="ece4e-110">Á þessum tíma mælir kerfið bilið frá núverandi áætlaðar birgðum upp að tilteknum hámarksbirgðum.</span><span class="sxs-lookup"><span data-stu-id="ece4e-110">At this time, the system measures the gap from the current projected inventory level up to the specified maximum inventory.</span></span> <span data-ttu-id="ece4e-111">Þetta stendur fyrir magnið sem þarf að endurpanta.</span><span class="sxs-lookup"><span data-stu-id="ece4e-111">This constitutes the quantity that should be reordered.</span></span> <span data-ttu-id="ece4e-112">Kerfið kannar þá hvort birgðir hafi þegar verið pantaðar annars staðar þannig að þær berist innan afhendingartímans og, ef svo er, minnkar magn nýju birgðapöntunarinnar í samræmi við það magn sem þegar hefur verið pantað.</span><span class="sxs-lookup"><span data-stu-id="ece4e-112">The system then checks if supply has already been ordered elsewhere to be received within the lead time and, if so, reduces the quantity of the new supply order by already ordered quantities.</span></span>  
  
 <span data-ttu-id="ece4e-113">Kerfið tryggir að áætlaðar birgðir nái a.m.k. endurpöntunarmarkinu - ef vera skyldi að notandinn hafi gleymt að tilgreina hámarksbirgðagildi.</span><span class="sxs-lookup"><span data-stu-id="ece4e-113">The system will ensure that the projected inventory at least reaches the reorder point level – in case the user has forgotten to specify a maximum inventory quantity.</span></span>  
  
## <a name="combines-with-order-modifiers"></a><span data-ttu-id="ece4e-114">Samsett við Breytingalykla</span><span class="sxs-lookup"><span data-stu-id="ece4e-114">Combines with Order Modifiers</span></span>  
 <span data-ttu-id="ece4e-115">Það fer eftir uppsetningu, getur það verið best að sameina það hámarksmagn stefnu með breytingalyklum til að tryggja lágmarksupphæð þess magn eða sléttun innkaupaeiningar, eða kljúfa það í fleiri lotur samkvæmt skilgreiningu hámarksmagns.</span><span class="sxs-lookup"><span data-stu-id="ece4e-115">Depending on the setup, it may be best to combine the Maximum Quantity policy with order modifiers to ensure a minimum order quantity or round it to an integer number of purchase units of measure, or split it into more lots as defined by the maximum order quantity.</span></span>  
  
## <a name="combines-with-calendars"></a><span data-ttu-id="ece4e-116">Sameinast dagbók</span><span class="sxs-lookup"><span data-stu-id="ece4e-116">Combines with Calendars</span></span>  
 <span data-ttu-id="ece4e-117">Áður en ný birgðapöntun er lögð til til að mæta endurpöntunarmarki, kannar áætlanakerfið hvort pöntunin sé áætluð á frídegi, samkvæmt öllum dagatölum sem eru skilgreind í **Grunndagatalskóði** reitnum í gluggunum **Fyrirtækjaupplýsingar** og **Birgðageymslukort**</span><span class="sxs-lookup"><span data-stu-id="ece4e-117">Before suggesting a new supply order to meet a reorder point, the planning system checks if the order is scheduled for a non-working day, according to any calendars that are  defined in the **Base Calendar Code** field in the **Company Information** and **Location Card** windows.</span></span>  
  
 <span data-ttu-id="ece4e-118">Ef fyrirhuguð dagsetning er frídagur, færir áætlanakerfið pöntunina áfram á næsta virka dag.</span><span class="sxs-lookup"><span data-stu-id="ece4e-118">If the scheduled date is a non-working day, the planning system moves the order forward to the nearest working date.</span></span> <span data-ttu-id="ece4e-119">Þetta getur orsakað pöntun sem uppfyllir endurpöntunarmark en uppfyllir ekki einhverja tiltekna eftirspurn.</span><span class="sxs-lookup"><span data-stu-id="ece4e-119">This may result in an order that meets a reorder point but does not meet some specific demand.</span></span> <span data-ttu-id="ece4e-120">Fyrir svona ójafna eftirspurn, býr áætlanakerfið til auka framboð.</span><span class="sxs-lookup"><span data-stu-id="ece4e-120">For such unbalanced demand, the planning system creates an extra supply.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="ece4e-121">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="ece4e-121">See Also</span></span>  
 <span data-ttu-id="ece4e-122">[Hönnunarupplýsingar: Endurpöntunarstefnur](design-details-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="ece4e-122">[Design Details: Reordering Policies](design-details-reordering-policies.md) </span></span>  
 <span data-ttu-id="ece4e-123">[Hönnunarupplýsingar: áætlunarfæribreyta](design-details-planning-parameters.md) </span><span class="sxs-lookup"><span data-stu-id="ece4e-123">[Design Details: Planning Parameters](design-details-planning-parameters.md) </span></span>  
 <span data-ttu-id="ece4e-124">[Hönnunarupplýsingar: Meðhöndlun endurpöntunarstefna](design-details-handling-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="ece4e-124">[Design Details: Handling Reordering Policies](design-details-handling-reordering-policies.md) </span></span>  
 [<span data-ttu-id="ece4e-125">Hönnunarupplýsingar: framboðsáætlun</span><span class="sxs-lookup"><span data-stu-id="ece4e-125">Design Details: Supply Planning</span></span>](design-details-supply-planning.md)