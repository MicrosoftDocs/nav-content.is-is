---
title: "Hönnunarupplýsingar - áætlunartafla"
description: "Þetta efnisatriði veitir innsýn í hvað gerist þegar því hvernig vörur eru áætlaðar er breytt."
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
ms.openlocfilehash: 4de661000de46293eaeec22ce6a6243f0efaa630
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-planning-assignment-table"></a><span data-ttu-id="85e94-103">Hönnunarupplýsingar: áætlunartafla</span><span class="sxs-lookup"><span data-stu-id="85e94-103">Design Details: Planning Assignment Table</span></span>
<span data-ttu-id="85e94-104">Allar vörur ættu að vera áætlaðar en aftur á móti er engin ástæða til að reikna áætlun fyrir vöru nema eftirspurnar- eða framboðsmynstur hafi breyst síðan áætlun var síðast reiknuð.</span><span class="sxs-lookup"><span data-stu-id="85e94-104">All items should be planned for, however, there is no reason to calculate a plan for an item unless there has been a change in the demand or supply pattern since the last time a plan was calculated.</span></span>  
  
<span data-ttu-id="85e94-105">Ef notandi hefur slegið inn nýja sölupöntun eða breytt pöntun sem fyrir er er ástæða til að endurreikna áætlunina.</span><span class="sxs-lookup"><span data-stu-id="85e94-105">If the user has entered a new sales order or changed an existing one, there is reason to recalculate the plan.</span></span> <span data-ttu-id="85e94-106">Aðrar ástæður eru m.a. breytingar á spá eða viðeigandi magn í öryggisbirgðum.</span><span class="sxs-lookup"><span data-stu-id="85e94-106">Other reasons include a change in forecast or the desired safety stock quantity.</span></span> <span data-ttu-id="85e94-107">Breyting á uppskrift með því að bæta við eða fjarlægja íhlut myndi líklega gefa til kynna breytingu, en aðeins fyrir hlut vöru.</span><span class="sxs-lookup"><span data-stu-id="85e94-107">Changing a bill of material by adding or removing a component would most likely indicate a change, but for the component item only.</span></span>  
  
<span data-ttu-id="85e94-108">Fyrir margar staðsetningar fer úthlutunin fram á vörustigi hverrar samsetningar staðsetningar.</span><span class="sxs-lookup"><span data-stu-id="85e94-108">For multiple locations, the assignment takes place at the level of item per location combination.</span></span> <span data-ttu-id="85e94-109">Ef, til dæmis, sölupöntun hefur verið búin til á aðeins einum stað, úthlutar forritið vörunni  á þeim tiltekna stað fyrir áætlanagerð.</span><span class="sxs-lookup"><span data-stu-id="85e94-109">If, for example, a sales order has been created at only one location, the program will assign the item at that specific location for planning.</span></span>  
  
<span data-ttu-id="85e94-110">Ástæðan fyrir að velja vörur fyrir áætlun grundvallast á afköstum kerfisins.</span><span class="sxs-lookup"><span data-stu-id="85e94-110">The reason for selecting items for planning is a matter of system performance.</span></span> <span data-ttu-id="85e94-111">Ef engin breyting hefur orðið á framboðs- og eftirspurnarmynstri vörunnar leggur áætlanakerfið ekki til neinar ráðstafanir.</span><span class="sxs-lookup"><span data-stu-id="85e94-111">If no change in an item’s demand-supply pattern has occurred, the planning system will not suggest any actions to be taken.</span></span> <span data-ttu-id="85e94-112">Ef áætlun væri ekki úthlutað yrði kerfið að gera útreikninga fyrir allar vörur til að finna út hvernig á að áætla og það myndi ganga um of á kerfið.</span><span class="sxs-lookup"><span data-stu-id="85e94-112">Without the planning assignment, the system would have to perform the calculations for all items in order to find out what to plan for, and that would drain system resources.</span></span>  
  
<span data-ttu-id="85e94-113">Taflan **Áætlunarmat** Fylgist með tilvikum eftirspurnar og framboðs og úthlutar viðeigandi vörum til að gera áætlun.</span><span class="sxs-lookup"><span data-stu-id="85e94-113">The **Planning Assignment** table monitors demand and supply events and assigns the appropriate items for planning.</span></span> <span data-ttu-id="85e94-114">Fylgst er með eftirfarandi tilvikum:</span><span class="sxs-lookup"><span data-stu-id="85e94-114">The following events are monitored:</span></span>  
  
* <span data-ttu-id="85e94-115">Ný sölupöntun, spá, íhlutur, innkaupapöntun, framleiðslupöntun, samsetningarpöntun eða flutningspöntun.</span><span class="sxs-lookup"><span data-stu-id="85e94-115">A new sales order, forecast, component, purchase order, production order, assembly order, or transfer order.</span></span>  
* <span data-ttu-id="85e94-116">Breyting vöru, magns, staðsetningar, afbrigðis eða dagsetningu á sölupöntun, spá, íhlutur, innkaupapöntun, framleiðslupöntun, samsetningarpöntun eða flutningspöntun.</span><span class="sxs-lookup"><span data-stu-id="85e94-116">Change of item, quantity, location, variant, or date on a sales order, forecast, component, purchase order, production order, assembly order, or transfer order.</span></span>  
* <span data-ttu-id="85e94-117">Afturköllun sölupöntunar , spá, íhlutur, innkaupapöntun, framleiðslupöntunar, samsetningarpöntunar eða flutningspöntunar.</span><span class="sxs-lookup"><span data-stu-id="85e94-117">Cancellation of a sales order, forecast, component, purchase order, production order, assembly order, or transfer order.</span></span>  
* <span data-ttu-id="85e94-118">Notkun á vöru annarri en áætlaðri.</span><span class="sxs-lookup"><span data-stu-id="85e94-118">Consumption of items other than planned.</span></span>  
* <span data-ttu-id="85e94-119">Frálag annarra vara en áætlaðra.</span><span class="sxs-lookup"><span data-stu-id="85e94-119">Output of items other than planned.</span></span>  
* <span data-ttu-id="85e94-120">Óáætlaðar breytingar á birgðum.</span><span class="sxs-lookup"><span data-stu-id="85e94-120">Unplanned changes in inventory.</span></span>  
  
<span data-ttu-id="85e94-121">Yfir þessar beinu tilfærslur á framboði/eftirspurn halda pöntunarrakningar- og aðgerðaboðakerfið áætlunarúthlutunartöflu og tilgreinir áætlunarástæðu sem aðgerðaboð.</span><span class="sxs-lookup"><span data-stu-id="85e94-121">For these direct supply-demand displacements, the order tracking and action messaging system maintains the Planning Assignment table and states a planning reason as an action message.</span></span>  
  
<span data-ttu-id="85e94-122">Eftirfarandi breytingar í aðalgögnum geta einnig valdið ójafnvægi í áætlanagerð:</span><span class="sxs-lookup"><span data-stu-id="85e94-122">The following changes in master data can also cause a planning imbalance:</span></span>  
  
* <span data-ttu-id="85e94-123">Breyting á stöðu í vottað í framleiðsluuppskrift haus (fyrir öll atriði með því haus).</span><span class="sxs-lookup"><span data-stu-id="85e94-123">Change of status to Certified in the production BOM header (for all items using that header).</span></span>  
* <span data-ttu-id="85e94-124">Eyddar línur (undireining).</span><span class="sxs-lookup"><span data-stu-id="85e94-124">Deleted line (child item).</span></span>  
* <span data-ttu-id="85e94-125">Breyting á stöðu við vottað í leiðarhaus (fyrir öll atriði með því haus).</span><span class="sxs-lookup"><span data-stu-id="85e94-125">Change of status to Certified in the routing header (for all items using that routing).</span></span>  
* <span data-ttu-id="85e94-126">Breytingar á eftirfarandi birgðaspjaldsreitum.</span><span class="sxs-lookup"><span data-stu-id="85e94-126">Changes in the following item card fields.</span></span>  
* <span data-ttu-id="85e94-127">Öryggisbirgðamagn eða öryggis afhendingartími.</span><span class="sxs-lookup"><span data-stu-id="85e94-127">Safety Stock Quantity or Safety Lead Time.</span></span>  
* <span data-ttu-id="85e94-128">Útreikn. afhendingartíma</span><span class="sxs-lookup"><span data-stu-id="85e94-128">Lead Time Calculation.</span></span>  
* <span data-ttu-id="85e94-129">Endurpöntunarmark.</span><span class="sxs-lookup"><span data-stu-id="85e94-129">Reorder Point.</span></span>  
* <span data-ttu-id="85e94-130">Framleiðsluuppskrift nr. (og allar undireiningar gamalla uppskriftatilvísana).</span><span class="sxs-lookup"><span data-stu-id="85e94-130">Production BOM No. (and all children of old BOM reference).</span></span>  
* <span data-ttu-id="85e94-131">Leiðarnr.</span><span class="sxs-lookup"><span data-stu-id="85e94-131">Routing No.</span></span>  
* <span data-ttu-id="85e94-132">Endurpöntunarstefna.</span><span class="sxs-lookup"><span data-stu-id="85e94-132">Reordering Policy.</span></span>  
  
<span data-ttu-id="85e94-133">Í þessum tilvikum, nýr eiginleiki, Úthlutunarstjórnun Áætlunar, heldur töflunni og segir áætlanagerðarástæðu sem nettóbreyting.</span><span class="sxs-lookup"><span data-stu-id="85e94-133">In these cases, a new function, Planning Assignment Management, maintains the table and states the planning reason as Net Change.</span></span>  
  
<span data-ttu-id="85e94-134">Eftirfarandi breytingar valda ekki úthlutun áætlanagerðar:</span><span class="sxs-lookup"><span data-stu-id="85e94-134">The following changes do not cause a planning assignment:</span></span>  
  
* <span data-ttu-id="85e94-135">Dagbækur</span><span class="sxs-lookup"><span data-stu-id="85e94-135">Calendars</span></span>  
* <span data-ttu-id="85e94-136">Aðrar áætlunarfæribreytur á birgðaspjaldinu</span><span class="sxs-lookup"><span data-stu-id="85e94-136">Other planning parameters on the item card</span></span>  
  
<span data-ttu-id="85e94-137">Við útreikning á MPS eða MRP, gilda eftirfarandi takmarkanir:</span><span class="sxs-lookup"><span data-stu-id="85e94-137">When calculating an MPS or an MRP, the following restrictions apply:</span></span>  
  
* <span data-ttu-id="85e94-138">MPS: Áætlunarkerfið athugar hvort varan er með framleiðsluspá eða sölupöntun.</span><span class="sxs-lookup"><span data-stu-id="85e94-138">MPS: The planning system checks that the item carries a production forecast or a sales order.</span></span> <span data-ttu-id="85e94-139">Ef ekki er varan ekki tekin með í áætluninni.</span><span class="sxs-lookup"><span data-stu-id="85e94-139">If not, the item is not included in the plan.</span></span>  
* <span data-ttu-id="85e94-140">MRP: Ef áætlanakerfið greinir að verið sé að fylla á vöruna með MPS-áætlunarlínu eða MPS-framboðspötnun verður varan ekki höfð með í áætlun.</span><span class="sxs-lookup"><span data-stu-id="85e94-140">MRP: If the planning system detects that the item is being replenished by an MPS planning line or MPS supply order, the item will be left out of the planning.</span></span> <span data-ttu-id="85e94-141">Hins vegar verða allar eftirspurnir frá viðkomandi íhlutum innifaldar.</span><span class="sxs-lookup"><span data-stu-id="85e94-141">However, any demand from relevant components is included.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="85e94-142">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="85e94-142">See Also</span></span>  
<span data-ttu-id="85e94-143">[Hönnunarupplýsingar: Jöfnun eftirspurnar og framboðs](design-details-balancing-demand-and-supply.md) </span><span class="sxs-lookup"><span data-stu-id="85e94-143">[Design Details: Balancing Demand and Supply](design-details-balancing-demand-and-supply.md) </span></span>  
<span data-ttu-id="85e94-144">[Hönnunarupplýsingar: Meðhöndlun endurpöntunarstefna](design-details-handling-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="85e94-144">[Design Details: Handling Reordering Policies](design-details-handling-reordering-policies.md) </span></span>  
<span data-ttu-id="85e94-145">[Hönnunarupplýsingar: Flutningur í áætlun](design-details-transfers-in-planning.md) </span><span class="sxs-lookup"><span data-stu-id="85e94-145">[Design Details: Transfers in Planning](design-details-transfers-in-planning.md) </span></span>  
[<span data-ttu-id="85e94-146">Hönnunarupplýsingar: áætlunarfæribreyta</span><span class="sxs-lookup"><span data-stu-id="85e94-146">Design Details: Planning Parameters</span></span>](design-details-planning-parameters.md)  
