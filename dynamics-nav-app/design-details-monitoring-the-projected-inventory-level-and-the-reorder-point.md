---
title: "Hönnunarupplýsingar - Vöktun áætlaðar birgðastigs og endurpöntunarmark"
description: "Lærðu hvernig birgðaáætlun greinir á milli áætlaðar birgða og áætlaðra tiltækra birgðar."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: design, supply, inventory, planning
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: ef99b84a635a8403c62c38b8a66e77166bbf2883
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-monitoring-the-projected-inventory-level-and-the-reorder-point"></a><span data-ttu-id="b5929-103">Hönnunarupplýsingar Vöktun áætlaðar birgðastigs og endurpöntunarmark</span><span class="sxs-lookup"><span data-stu-id="b5929-103">Design Details: Monitoring the Projected Inventory Level and the Reorder Point</span></span>
<span data-ttu-id="b5929-104">Birgðir eru tegund af framboði, en fyrir birgðaáætlanagerð, greinir áætlanakerfið milli tveggja birgðastiga:</span><span class="sxs-lookup"><span data-stu-id="b5929-104">Inventory is a type of supply, but for inventory planning, the planning system distinguishes between two inventory levels:</span></span>  

* <span data-ttu-id="b5929-105">Áætlaðar birgðir</span><span class="sxs-lookup"><span data-stu-id="b5929-105">Projected inventory</span></span>  
* <span data-ttu-id="b5929-106">Áætlaðar tiltækar birgðir</span><span class="sxs-lookup"><span data-stu-id="b5929-106">Projected available inventory</span></span>  

## <a name="projected-inventory"></a><span data-ttu-id="b5929-107">Áætlaðar birgðir</span><span class="sxs-lookup"><span data-stu-id="b5929-107">Projected Inventory</span></span>  
<span data-ttu-id="b5929-108">Upphaflega áætlað birgðir er magn af vergri birgðum, þ.mt framboð og eftirspurn í fortíðinni, jafnvel þótt ekki bókað, þegar áætlanagerð er ræst.</span><span class="sxs-lookup"><span data-stu-id="b5929-108">Initially, projected inventory is the quantity of gross inventory, including supply and demand in the past even if not posted, when starting the planning process.</span></span> <span data-ttu-id="b5929-109">Í framtíðinni, verður þetta færanlegar áætlaðar birgðastig sem er viðhaldið af vergu magni frá síðara framboð og eftirspurn vegna þess að þeir eru kynnt eftir tímalínu (hvort sem er fráteknar eða öðrum hætti úthlutað).</span><span class="sxs-lookup"><span data-stu-id="b5929-109">In the future, this becomes a moving projected inventory level that is maintained by gross quantities from future supply and demand because those are introduced along the time line (whether reserved or in other ways allocated).</span></span>  

<span data-ttu-id="b5929-110">Áætlaðar birgðir skal nota af áætlanakerfinu þegar eftirlit er haft með endurpöntunarmarki og til að ákvarða endurpöntunarmang þegar endurpöntunarstefnan Hámarksmagn er notuð.</span><span class="sxs-lookup"><span data-stu-id="b5929-110">The projected inventory is used by the planning system to monitor the reorder point and to determine the reorder quantity when using the Maximum Qty. reordering policy.</span></span>  

## <a name="projected-available-inventory"></a><span data-ttu-id="b5929-111">Áætlaðar tiltækar birgðir</span><span class="sxs-lookup"><span data-stu-id="b5929-111">Projected Available Inventory</span></span>  
<span data-ttu-id="b5929-112">Áætlaðar tiltækar birgðir eru hluti af áætluðum birgðum sem eru tiltækar á einhverjum tilteknum tíma til að mæta eftirspurn.</span><span class="sxs-lookup"><span data-stu-id="b5929-112">The projected available inventory is the part of the projected inventory that at a given point in time is available to fulfill demand.</span></span> <span data-ttu-id="b5929-113">Áætlaðar tiltækar birgðir skal nota af áætlanakerfinu þegar eftirlit er haft með öryggisbirgðum.</span><span class="sxs-lookup"><span data-stu-id="b5929-113">The projected available inventory is used by the planning engine when monitoring the safety stock level.</span></span>  

<span data-ttu-id="b5929-114">Áætlaðar tiltækar birgðir skal nota af áætlanakerfinu þegar eftirlit er haft með öryggisbirgðum, þar sem öryggisbirgðir þurfa alltaf að vera tiltækar til að mæta óvæntri eftirspurn.</span><span class="sxs-lookup"><span data-stu-id="b5929-114">The projected available inventory is used by the planning system to monitor the safety stock level, since the safety stock must always be available to serve unexpected demand.</span></span>  

## <a name="time-buckets"></a><span data-ttu-id="b5929-115">Tímarammar</span><span class="sxs-lookup"><span data-stu-id="b5929-115">Time Buckets</span></span>  
<span data-ttu-id="b5929-116">Góð stjórna á áætluðum birgðum er lykilatriði þegar greina á hvenær endurpöntunarmarki er náð og farið er yfir það og til að ákvarða rétt endurpöntunarmagn þegar endurpöntunarstefnan Hámarksmagn er notuð.</span><span class="sxs-lookup"><span data-stu-id="b5929-116">Having a tight control of the projected inventory is crucial to detect when the reorder point is reached or crossed and to calculate the right order quantity when using the Maximum Qty. reordering policy.</span></span>  

<span data-ttu-id="b5929-117">Eins og fyrr segir er áætlað birgðastig reiknað í upphafi áætlunartímabilsins.</span><span class="sxs-lookup"><span data-stu-id="b5929-117">As stated earlier, the projected inventory level is calculated at the start of the planning period.</span></span> <span data-ttu-id="b5929-118">Það er brúttó stig sem tekur ekki tillit til frátekninga og svipa‘ðra úthlutun.</span><span class="sxs-lookup"><span data-stu-id="b5929-118">It is a gross level that does not consider reservations and similar allocations.</span></span> <span data-ttu-id="b5929-119">Til að fylgjast með þessu birgðastig á áætlunarröð, kerfið fylgist uppsöfnuðum breytingar yfir a tímabil , tímarammi.</span><span class="sxs-lookup"><span data-stu-id="b5929-119">To monitor this inventory level during the planning sequence, the system monitors the aggregated changes over a period of time, a time bucket.</span></span> <span data-ttu-id="b5929-120">Kerfið tryggir að tímaramminn sé a.m.k. einn dagur þar sem það er nákvæmasta tímaeiningin fyrir birgðir eða eftirspurn.</span><span class="sxs-lookup"><span data-stu-id="b5929-120">The system ensures that the time bucket is at least one day since it is the most precise unit of time for a demand or supply event.</span></span>  

## <a name="determining-the-projected-inventory-level"></a><span data-ttu-id="b5929-121">Ákvarða áætlaðar birgðir</span><span class="sxs-lookup"><span data-stu-id="b5929-121">Determining the Projected Inventory Level</span></span>  
<span data-ttu-id="b5929-122">Eftirfarandi röð lýsir því hvernig áætlað birgðastig er ákvarðað:</span><span class="sxs-lookup"><span data-stu-id="b5929-122">The following sequence describes how the projected inventory level is determined:</span></span>  

* <span data-ttu-id="b5929-123">Þegar framboðstilvik, svo sem innkaupapöntun, hefur verið algerlega skipulögð, mun það auka áætlaðar birgðir á skiladegi.</span><span class="sxs-lookup"><span data-stu-id="b5929-123">When a supply event, such as a purchase order has been totally planned, it will increase the projected inventory on its due date.</span></span>  
* <span data-ttu-id="b5929-124">Þegar eftirspurnartilvik hefur verið að fullu uppfyllt, mun það ekki minnka áætlaðar birgðir strax.</span><span class="sxs-lookup"><span data-stu-id="b5929-124">When a demand event has been fully satisfied, it will not decrease the projected inventory right away.</span></span> <span data-ttu-id="b5929-125">Í staðinn, bókar það minnkunaráminningu, sem er innri skrá sem geymir dagsetningu og magn af framlagi þess til áætlaðra birgða.</span><span class="sxs-lookup"><span data-stu-id="b5929-125">Instead, it posts a decrease reminder, which is an internal record that holds the date and quantity of the contribution to the projected inventory.</span></span>  
* <span data-ttu-id="b5929-126">Þegar síðara framboðstilvik er skipulögð og sett á tímalínu, eru bókaðar minnkunaráminningar rannsakaðar eitt af öðru fram til fyrirhuguðum degi framboðs meðan áætlaðar birgðir eru uppfærðar.</span><span class="sxs-lookup"><span data-stu-id="b5929-126">When a subsequent supply event is planned and placed on the time line, the posted decrease reminders are investigated one by one up until the planned date of the supply while updating the projected inventory.</span></span> <span data-ttu-id="b5929-127">Á meðan á þessu ferli getur endurpöntunarmarki innri aukningaráminningar verið náð eða farið yfir það.</span><span class="sxs-lookup"><span data-stu-id="b5929-127">During this process, the reorder point level of the internal increase reminder may be reached or crossed.</span></span>  
* <span data-ttu-id="b5929-128">Ef ný birgðapöntun er innleidd athugar kerfið hvort hún sé færð inn á undan núverandi birgðum.</span><span class="sxs-lookup"><span data-stu-id="b5929-128">If a new supply order is introduced, the system checks if it is entered before the current supply.</span></span> <span data-ttu-id="b5929-129">Ef svo er verður nýja framboðið núverandi framboð og mótreikningsaðferðin hefst upp á nýtt.</span><span class="sxs-lookup"><span data-stu-id="b5929-129">If it is, the new supply becomes current supply and the balancing procedure starts over.</span></span>  

<span data-ttu-id="b5929-130">Eftirfarandi sýnir mynd af þessari meginreglu:</span><span class="sxs-lookup"><span data-stu-id="b5929-130">The following shows a graphical illustration of this principle:</span></span>  

![](media/nav_app_supply_planning_2_projected_inventory.png "NAV_APP_supply_planning_2_projected_inventory")  

1. <span data-ttu-id="b5929-131">Framboð **Sa** af 4 (fast) lokar Eftirspurn **Da** af -3.</span><span class="sxs-lookup"><span data-stu-id="b5929-131">Supply **Sa** of 4 (fixed) closes Demand **Da** of -3.</span></span>  
2. <span data-ttu-id="b5929-132">CloseDemand: Búa til lækkunaráminningu -3 (ekki sýnt).</span><span class="sxs-lookup"><span data-stu-id="b5929-132">CloseDemand: Create a decrease reminder of -3 (not shown).</span></span>  
3. <span data-ttu-id="b5929-133">Framboð **Sa** er lokað með afgangi upp á 1 (engin frekari eftirspurn er til).</span><span class="sxs-lookup"><span data-stu-id="b5929-133">Supply **Sa** is closed with a surplus of 1 (no more demand exists).</span></span>  

     <span data-ttu-id="b5929-134">Þetta eykur áætlað birgðastig í +4, á sama tíma og áætlaðar tiltækar birgðir **í boði** verða -1.</span><span class="sxs-lookup"><span data-stu-id="b5929-134">This increases the projected inventory level to +4, while the projected **available** inventory becomes -1.</span></span>  

4. <span data-ttu-id="b5929-135">Næsta eftirspurn **Sb** af 2 (önnur pöntun) hefur þegar verið sett á tímalínuna.</span><span class="sxs-lookup"><span data-stu-id="b5929-135">The next supply **Sb** of 2 (another order) has already been placed on the timeline.</span></span>  
5. <span data-ttu-id="b5929-136">Kerfið athugar hvort það sé einhver minnkunaráminning á undan **Sb** (það er ekki, þannig að ekki er gripið til aðgerða).</span><span class="sxs-lookup"><span data-stu-id="b5929-136">System checks if there is any decrease reminder preceding **Sb** (there is not, so no action is taken).</span></span>  
6. <span data-ttu-id="b5929-137">Kerfið lokar framboði **Sb** (ekki fleiri eftirspurn) -annað hvort A: með því að minnka það til 0 hætta við eða B: með því að skilja eftir eins og er.</span><span class="sxs-lookup"><span data-stu-id="b5929-137">System closes supply **Sb** (no more demand exists)—either A: by reducing it to 0 (cancel) or B: by leaving as is.</span></span>  

     <span data-ttu-id="b5929-138">Þetta eykur áætlað birgðastig (A: +0 => +4 eða B: +2 = +6).</span><span class="sxs-lookup"><span data-stu-id="b5929-138">This increases the projected inventory level (A: +0 => +4 or B: +2 = +6).</span></span>  

7. <span data-ttu-id="b5929-139">Kerfið gerir endanlega athugum: Er einhver minnkunaráminning?</span><span class="sxs-lookup"><span data-stu-id="b5929-139">System makes a final check: Is there any decrease reminder?</span></span> <span data-ttu-id="b5929-140">Já, það er eitt á dagsetningunni **Da**.</span><span class="sxs-lookup"><span data-stu-id="b5929-140">Yes, there is one on the date of **Da**.</span></span>  
8. <span data-ttu-id="b5929-141">Kerfi bætir við minnkunaráminningu -3 við áætlað birgðastig, annað hvort A: +4 -3 = 1 eða B: +6 -3 = +3.</span><span class="sxs-lookup"><span data-stu-id="b5929-141">System adds the decrease reminder of -3 reminder to the projected inventory level, either A: +4 -3 = 1 or B: +6 -3 = +3.</span></span>  
9. <span data-ttu-id="b5929-142">Í tilviki A býr kerfið til framvirkt áætlaða pöntun sem hefst á degi **Da**</span><span class="sxs-lookup"><span data-stu-id="b5929-142">In case of A, the system creates a forward-scheduled order starting on date **Da**.</span></span>  

     <span data-ttu-id="b5929-143">Í tilviki B er pöntunarmarki náð og ný pöntun er stofnuð.</span><span class="sxs-lookup"><span data-stu-id="b5929-143">In case of B, the reorder point is reached and a new order is created.</span></span>  

## <a name="see-also"></a><span data-ttu-id="b5929-144">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="b5929-144">See Also</span></span>  
<span data-ttu-id="b5929-145">[Hönnunarupplýsingar: Endurpöntunarstefnur](design-details-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="b5929-145">[Design Details: Reordering Policies](design-details-reordering-policies.md) </span></span>  
<span data-ttu-id="b5929-146">[Hönnunarupplýsingar: áætlunarfæribreyta](design-details-planning-parameters.md) </span><span class="sxs-lookup"><span data-stu-id="b5929-146">[Design Details: Planning Parameters](design-details-planning-parameters.md) </span></span>  
<span data-ttu-id="b5929-147">[Hönnunarupplýsingar: Meðhöndlun endurpöntunarstefna](design-details-handling-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="b5929-147">[Design Details: Handling Reordering Policies](design-details-handling-reordering-policies.md) </span></span>  
[<span data-ttu-id="b5929-148">Hönnunarupplýsingar: framboðsáætlun</span><span class="sxs-lookup"><span data-stu-id="b5929-148">Design Details: Supply Planning</span></span>](design-details-supply-planning.md)
