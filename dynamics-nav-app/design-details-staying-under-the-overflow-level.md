---
title: "Hönnunarupplýsingar - undir yfirflæðisstigi"
description: "Þegar hámarksmagn og fast endurpöntunarmagn er notað einblínir áætlanakerfið aðeins á ætlaðar birgðir í tilgreindum tímaramma. Þetta þýðir að áætlanakerfið geta stinga upp á óþarfa framboð þegar neikvæð eftirspurn eða jákvæðar breytingar á framboð koma fram utan ákveðins tímaramma."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: bd4d3a9abb6b13ba305abf8ad437294e94b67318
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-staying-under-the-overflow-level"></a><span data-ttu-id="f5b65-104">Hönnunarupplýsingar: undir yfirflæðisstigi</span><span class="sxs-lookup"><span data-stu-id="f5b65-104">Design Details: Staying under the Overflow Level</span></span>
<span data-ttu-id="f5b65-105">Þegar reglur um hámarksmagn og fast endurpöntunarmagn eru notaðar einblínir áætlanakerfið aðeins á ætlaðar birgðir í tilgreindum tímaramma.</span><span class="sxs-lookup"><span data-stu-id="f5b65-105">When using the Maximum Qty. and Fixed Reorder Qty. policies, the planning system focuses on the projected inventory in the given time-bucket only.</span></span> <span data-ttu-id="f5b65-106">Þetta þýðir að áætlanakerfið geta stinga upp á óþarfa framboð þegar neikvæð eftirspurn eða jákvæðar breytingar á framboð koma fram utan ákveðins tímaramma.</span><span class="sxs-lookup"><span data-stu-id="f5b65-106">This means that the planning system may suggest superfluous supply when negative demand or positive supply changes occur outside of the given time bucket.</span></span> <span data-ttu-id="f5b65-107">Ef, af þessum sökum, umframframboð er stungið upp á, reiknar áætlanagerðarkerfið hvaða magn framboðið skal minnka í (eða eytt) til að forðast umframframboð.</span><span class="sxs-lookup"><span data-stu-id="f5b65-107">If, for this reason, a superfluous supply is suggested, the planning system calculates which quantity the supply should be decreased to (or deleted) to avoid the superfluous supply.</span></span> <span data-ttu-id="f5b65-108">Þetta magn er kallað „yfirflæðisstig“.</span><span class="sxs-lookup"><span data-stu-id="f5b65-108">This quantity is called the “overflow level.”</span></span> <span data-ttu-id="f5b65-109">Yfirflæðið er miðlað sem áætlanalína með **Breyta magni (Lækkun)** eða **Hætta við** aðgerð og eftirfarandi viðvörun skilaboð:</span><span class="sxs-lookup"><span data-stu-id="f5b65-109">The overflow is communicated as a planning line with a **Change Qty. (Decrease)** or **Cancel** action and the following warning message:</span></span>  

<span data-ttu-id="f5b65-110">*Athugið: Áætlaðar birgðir [xx] er hærra en yfirflæðisstig [xx] á gjalddaga [xx].*</span><span class="sxs-lookup"><span data-stu-id="f5b65-110">*Attention: The projected inventory [xx] is higher than the overflow level [xx] on the Due Date [xx].*</span></span>  

<span data-ttu-id="f5b65-111">![Yfirflæðisstig birgða](media/supplyplanning_2_overflow1_new.png "framboðsáætlun_2_yfirflæði1_nýtt")</span><span class="sxs-lookup"><span data-stu-id="f5b65-111">![Inventory overflow level](media/supplyplanning_2_overflow1_new.png "supplyplanning_2_overflow1_new")</span></span>  

##  <a name="calculating-the-overflow-level"></a><span data-ttu-id="f5b65-112">Reiknar yfirflæðisstig</span><span class="sxs-lookup"><span data-stu-id="f5b65-112">Calculating the Overflow Level</span></span>  
<span data-ttu-id="f5b65-113">Yfirflæðisstigið er reiknað út á mismunandi hátt, allt eftir uppsetningu áætlana.</span><span class="sxs-lookup"><span data-stu-id="f5b65-113">The overflow level is calculated in different ways depending on planning setup.</span></span>  

### <a name="maximum-qty-reordering-policy"></a><span data-ttu-id="f5b65-114">Endurpöntunarstefna fyrir Hámarksmagn</span><span class="sxs-lookup"><span data-stu-id="f5b65-114">Maximum Qty. reordering policy</span></span>  
<span data-ttu-id="f5b65-115">Yfirflæðisstig = Hámarksbirgðir</span><span class="sxs-lookup"><span data-stu-id="f5b65-115">Overflow level = Maximum Inventory</span></span>  

> [!NOTE]  
>  <span data-ttu-id="f5b65-116">Ef lágmarkspöntunarmagn er til, þá verður því bætt við eins og hér segir: Yfirflæðisstig = Hámarksbirgðir + lágmarkspöntunarmagn.</span><span class="sxs-lookup"><span data-stu-id="f5b65-116">If a minimum order quantity exists, then it will be added as follows: Overflow level = Maximum Inventory + Minimum Order Quantity.</span></span>  

### <a name="fixed-reorder-qty-reordering-policy"></a><span data-ttu-id="f5b65-117">Endurpöntunarstefna fasts endurpöntunarmagn</span><span class="sxs-lookup"><span data-stu-id="f5b65-117">Fixed Reorder Qty. reordering policy</span></span>  
<span data-ttu-id="f5b65-118">Yfirflæðisstig = Endurpöntunarmagn + Endurpöntunarmark</span><span class="sxs-lookup"><span data-stu-id="f5b65-118">Overflow level = Reorder Quantity + Reorder Point</span></span>  

> [!NOTE]  
>  <span data-ttu-id="f5b65-119">Ef lágmarkspöntunarmagn er yfir endurpöntunarmarkinu er því skipt út eins og hér segir: Yfirflæðisstig = Endurpöntunarmagn + lágmarkspöntunarmagn</span><span class="sxs-lookup"><span data-stu-id="f5b65-119">If the minimum order quantity is higher than the reorder point, then it will replace as follows: Overflow Level = Reorder Quantity + Minimum Order Quantity</span></span>  

### <a name="order-multiple"></a><span data-ttu-id="f5b65-120">Margföld pöntun</span><span class="sxs-lookup"><span data-stu-id="f5b65-120">Order Multiple</span></span>  
<span data-ttu-id="f5b65-121">Ef margföld pöntun er til mun hún leiðrétta yfirflæðisstigið fyrir endurpöntunarstefnurnar fyrir bæði hámarksmagn og fast endurpöntunarmagn.</span><span class="sxs-lookup"><span data-stu-id="f5b65-121">If an order multiple exists, then it will adjust the overflow level for both Maximum Qty. and Fixed Reorder Qty. reordering policies.</span></span>  

##  <a name="creating-the-planning-line-with-overflow-warning"></a><span data-ttu-id="f5b65-122">Stofna áætlunarlínu með yfirfallsviðvörun</span><span class="sxs-lookup"><span data-stu-id="f5b65-122">Creating the Planning Line with Overflow Warning</span></span>  
<span data-ttu-id="f5b65-123">Þegar núverandi framboð veldur því að áætlaðar birgðir eru meiri en yfirflæðisstigið við lok tímaramma er búin til áætlunarlína.</span><span class="sxs-lookup"><span data-stu-id="f5b65-123">When an existing supply causes the projected inventory to be higher than the overflow level at the end of a time bucket, a planning line is created.</span></span> <span data-ttu-id="f5b65-124">Til að vara við hugsanlega óþarft framboð, er áætlunarlínan með viðvörunarboð, **Samþykkja aðgerðaboð** reiturinn er ekki valinn, og aðgerðaboð eru annaðhvort Hætta við eða Breyta Magni.</span><span class="sxs-lookup"><span data-stu-id="f5b65-124">To warn about the potential superfluous supply, the planning line has a warning message, the **Accept Action Message** field is not selected, and the action message is either Cancel or Change Qty.</span></span>  

### <a name="calculating-the-planning-line-quantity"></a><span data-ttu-id="f5b65-125">Reiknar magn áætlunarlínu</span><span class="sxs-lookup"><span data-stu-id="f5b65-125">Calculating the Planning Line Quantity</span></span>  
<span data-ttu-id="f5b65-126">Magn áætlunarlínu = Núverandi framboðsmagn – (Áætlaðar birgðir – Yfirflæðisstig)</span><span class="sxs-lookup"><span data-stu-id="f5b65-126">Planning Line Quantity = Current Supply Quantity – (Projected Inventory – Overflow Level)</span></span>  

> [!NOTE]  
>  <span data-ttu-id="f5b65-127">Eins og í öllum viðvörunarlínum verður hámarks-/lágmarkspöntunarmagn eða endurtekin pöntun hundsuð.</span><span class="sxs-lookup"><span data-stu-id="f5b65-127">As with all warning lines, any maximum/minimum order quantity or order multiple will be ignored.</span></span>  

### <a name="defining-the-action-message-type"></a><span data-ttu-id="f5b65-128">Skilgreina tegund aðgerðaboða</span><span class="sxs-lookup"><span data-stu-id="f5b65-128">Defining the Action Message Type</span></span>  

-   <span data-ttu-id="f5b65-129">Ef magn áætlunarlínu er meira en 0 eru aðgerðaboðin Breyta magni.</span><span class="sxs-lookup"><span data-stu-id="f5b65-129">If the planning line quantity is higher than 0, then the action message is Change Qty.</span></span>  
-   <span data-ttu-id="f5b65-130">Ef magn áætlunarlínu er jafnt og eða minna en 0 eru aðgerðaboðin Hætta við.</span><span class="sxs-lookup"><span data-stu-id="f5b65-130">If the planning line quantity is equal to or lower than 0, then the action message is Cancel</span></span>  

### <a name="composing-the-warning-message"></a><span data-ttu-id="f5b65-131">Semja viðvörunarmerkið</span><span class="sxs-lookup"><span data-stu-id="f5b65-131">Composing the Warning Message</span></span>  
<span data-ttu-id="f5b65-132">Í tilviki yfirflæðis birtir glugginn **Óraktar áætlunareiningar** viðvörun skilaboð með eftirfarandi upplýsingum:</span><span class="sxs-lookup"><span data-stu-id="f5b65-132">In case of overflow, the **Untracked Planning Elements** window displays a warning message with the following information:</span></span>  

-   <span data-ttu-id="f5b65-133">Áætlað birgðastig sem setti af stað viðvörunina.</span><span class="sxs-lookup"><span data-stu-id="f5b65-133">The projected inventory level that triggered the warning</span></span>  
-   <span data-ttu-id="f5b65-134">Reiknaða yfirflæðisstigið</span><span class="sxs-lookup"><span data-stu-id="f5b65-134">The calculated overflow level</span></span>  
-   <span data-ttu-id="f5b65-135">Lokadagur framboðstilviks.</span><span class="sxs-lookup"><span data-stu-id="f5b65-135">The due date of the supply event.</span></span>  

<span data-ttu-id="f5b65-136">Dæmi Áætlaðar birgðir 120 eru meiri en yfirflæðisstigið 60 á 28-01-11</span><span class="sxs-lookup"><span data-stu-id="f5b65-136">Example: “The projected inventory 120 is higher than the overflow level 60 on 28-01-11”</span></span>  

## <a name="scenario"></a><span data-ttu-id="f5b65-137">Aðstæður</span><span class="sxs-lookup"><span data-stu-id="f5b65-137">Scenario</span></span>  
<span data-ttu-id="f5b65-138">Í þessari atburðarás, breytir viðskiptamaður sölupöntun frá 70 í 40 stykki milli tveggja áætlunarkeyrslna.</span><span class="sxs-lookup"><span data-stu-id="f5b65-138">In this scenario, a customer changes a sales order from 70 to 40 pieces between two planning runs.</span></span> <span data-ttu-id="f5b65-139">Yfirflæðisbúnaðurinn grípur inn í til að draga úr innkaupunum sem lögð voru til fyrir upphaflega sölumagnið.</span><span class="sxs-lookup"><span data-stu-id="f5b65-139">The overflow feature sets in to reduce the purchase that was suggested for the initial sales quantity.</span></span>  

### <a name="item-setup"></a><span data-ttu-id="f5b65-140">Vöruuppsetning</span><span class="sxs-lookup"><span data-stu-id="f5b65-140">Item setup</span></span>  

|<span data-ttu-id="f5b65-141">Endurpöntunarstefna</span><span class="sxs-lookup"><span data-stu-id="f5b65-141">Reordering Policy</span></span>|<span data-ttu-id="f5b65-142">Hámarksmagn</span><span class="sxs-lookup"><span data-stu-id="f5b65-142">Maximum Qty.</span></span>|  
|-----------------------|------------------|  
|<span data-ttu-id="f5b65-143">Hámarksmagn pöntunar</span><span class="sxs-lookup"><span data-stu-id="f5b65-143">Maximum Order Quantity</span></span>|<span data-ttu-id="f5b65-144">100%</span><span class="sxs-lookup"><span data-stu-id="f5b65-144">100</span></span>|  
|<span data-ttu-id="f5b65-145">Endurpöntunarmark</span><span class="sxs-lookup"><span data-stu-id="f5b65-145">Reorder Point</span></span>|<span data-ttu-id="f5b65-146">50</span><span class="sxs-lookup"><span data-stu-id="f5b65-146">50</span></span>|  
|<span data-ttu-id="f5b65-147">Birgðir</span><span class="sxs-lookup"><span data-stu-id="f5b65-147">Inventory</span></span>|<span data-ttu-id="f5b65-148">80</span><span class="sxs-lookup"><span data-stu-id="f5b65-148">80</span></span>|  

### <a name="situation-before-sales-decrease"></a><span data-ttu-id="f5b65-149">Staða fyrir söluminnkun</span><span class="sxs-lookup"><span data-stu-id="f5b65-149">Situation before sales decrease</span></span>  

|<span data-ttu-id="f5b65-150">Atburður</span><span class="sxs-lookup"><span data-stu-id="f5b65-150">Event</span></span>|<span data-ttu-id="f5b65-151">Breyta magni</span><span class="sxs-lookup"><span data-stu-id="f5b65-151">Change Qty.</span></span>|<span data-ttu-id="f5b65-152">Áætlaðar birgðir</span><span class="sxs-lookup"><span data-stu-id="f5b65-152">Projected Inventory</span></span>|  
|-----------|-----------------|-------------------------|  
|<span data-ttu-id="f5b65-153">Dagur eitt</span><span class="sxs-lookup"><span data-stu-id="f5b65-153">Day one</span></span>|<span data-ttu-id="f5b65-154">Ekkert</span><span class="sxs-lookup"><span data-stu-id="f5b65-154">None</span></span>|<span data-ttu-id="f5b65-155">80</span><span class="sxs-lookup"><span data-stu-id="f5b65-155">80</span></span>|  
|<span data-ttu-id="f5b65-156">Sala</span><span class="sxs-lookup"><span data-stu-id="f5b65-156">Sale</span></span>|<span data-ttu-id="f5b65-157">-70</span><span class="sxs-lookup"><span data-stu-id="f5b65-157">-70</span></span>|<span data-ttu-id="f5b65-158">10</span><span class="sxs-lookup"><span data-stu-id="f5b65-158">10</span></span>|  
|<span data-ttu-id="f5b65-159">Lok tímaramma</span><span class="sxs-lookup"><span data-stu-id="f5b65-159">End of time bucket</span></span>|<span data-ttu-id="f5b65-160">Ekkert</span><span class="sxs-lookup"><span data-stu-id="f5b65-160">None</span></span>|<span data-ttu-id="f5b65-161">10</span><span class="sxs-lookup"><span data-stu-id="f5b65-161">10</span></span>|  
|<span data-ttu-id="f5b65-162">Leggja til nýja innkaupapöntun</span><span class="sxs-lookup"><span data-stu-id="f5b65-162">Suggest new purchase order</span></span>|<span data-ttu-id="f5b65-163">+90</span><span class="sxs-lookup"><span data-stu-id="f5b65-163">+90</span></span>|<span data-ttu-id="f5b65-164">100%</span><span class="sxs-lookup"><span data-stu-id="f5b65-164">100</span></span>|  

### <a name="situation-after-sales-decrease"></a><span data-ttu-id="f5b65-165">Staða eftir söluminnkun</span><span class="sxs-lookup"><span data-stu-id="f5b65-165">Situation after sales decrease</span></span>  

|<span data-ttu-id="f5b65-166">Breyting</span><span class="sxs-lookup"><span data-stu-id="f5b65-166">Change</span></span>|<span data-ttu-id="f5b65-167">Breyta magni</span><span class="sxs-lookup"><span data-stu-id="f5b65-167">Change Qty.</span></span>|<span data-ttu-id="f5b65-168">Áætlaðar birgðir</span><span class="sxs-lookup"><span data-stu-id="f5b65-168">Projected Inventory</span></span>|  
|------------|-----------------|-------------------------|  
|<span data-ttu-id="f5b65-169">Dagur eitt</span><span class="sxs-lookup"><span data-stu-id="f5b65-169">Day one</span></span>|<span data-ttu-id="f5b65-170">Ekkert</span><span class="sxs-lookup"><span data-stu-id="f5b65-170">None</span></span>|<span data-ttu-id="f5b65-171">80</span><span class="sxs-lookup"><span data-stu-id="f5b65-171">80</span></span>|  
|<span data-ttu-id="f5b65-172">Sala</span><span class="sxs-lookup"><span data-stu-id="f5b65-172">Sale</span></span>|<span data-ttu-id="f5b65-173">-40</span><span class="sxs-lookup"><span data-stu-id="f5b65-173">-40</span></span>|<span data-ttu-id="f5b65-174">40</span><span class="sxs-lookup"><span data-stu-id="f5b65-174">40</span></span>|  
|<span data-ttu-id="f5b65-175">Innkaup</span><span class="sxs-lookup"><span data-stu-id="f5b65-175">Purchase</span></span>|<span data-ttu-id="f5b65-176">+90</span><span class="sxs-lookup"><span data-stu-id="f5b65-176">+90</span></span>|<span data-ttu-id="f5b65-177">130</span><span class="sxs-lookup"><span data-stu-id="f5b65-177">130</span></span>|  
|<span data-ttu-id="f5b65-178">Lok tímaramma</span><span class="sxs-lookup"><span data-stu-id="f5b65-178">End of time bucket</span></span>|<span data-ttu-id="f5b65-179">Ekkert</span><span class="sxs-lookup"><span data-stu-id="f5b65-179">None</span></span>|<span data-ttu-id="f5b65-180">130</span><span class="sxs-lookup"><span data-stu-id="f5b65-180">130</span></span>|  
|<span data-ttu-id="f5b65-181">Stinga upp á að minnka innkaup</span><span class="sxs-lookup"><span data-stu-id="f5b65-181">Suggest to decrease purchase</span></span><br /><br /> <span data-ttu-id="f5b65-182">panta frá 90 til 60</span><span class="sxs-lookup"><span data-stu-id="f5b65-182">order from 90 to 60</span></span>|<span data-ttu-id="f5b65-183">-30</span><span class="sxs-lookup"><span data-stu-id="f5b65-183">-30</span></span>|<span data-ttu-id="f5b65-184">100%</span><span class="sxs-lookup"><span data-stu-id="f5b65-184">100</span></span>|  

### <a name="resulting-planning-lines"></a><span data-ttu-id="f5b65-185">Áætlunarlínur</span><span class="sxs-lookup"><span data-stu-id="f5b65-185">Resulting Planning Lines</span></span>  
 <span data-ttu-id="f5b65-186">Ein áætlunarlína (viðvörun) er stofnuð til að draga úr innkaupum um 30 úr 90 í 60 til að halda áætluðum birgðum í 100 samkvæmt yfirflæðisstiginu.</span><span class="sxs-lookup"><span data-stu-id="f5b65-186">One planning line (warning) is created to reduce the purchase with 30 from 90 to 60 to keep the projected inventory on 100 according to the overflow level.</span></span>  

<span data-ttu-id="f5b65-187">![áætla samkvæmt yfirflæðisstigi](media/nav_app_supply_planning_2_overflow2.png "nav_app_framboðsáætlun_2_yfirflæði2")</span><span class="sxs-lookup"><span data-stu-id="f5b65-187">![Plan according to overflow level](media/nav_app_supply_planning_2_overflow2.png "nav_app_supply_planning_2_overflow2")</span></span>  

> [!NOTE]  
>  <span data-ttu-id="f5b65-188">Ef búnaðurinn Yfirfall er ekki til staðar er ekki stofnuð nein viðvörun ef áætlaðar birgðir eru meiri en hámarksbirgðir.</span><span class="sxs-lookup"><span data-stu-id="f5b65-188">Without the Overflow feature, no warning is created if the projected inventory level is above maximum inventory.</span></span> <span data-ttu-id="f5b65-189">Þetta kann að valda óþörfu framboði upp á 30.</span><span class="sxs-lookup"><span data-stu-id="f5b65-189">This could cause a superfluous supply of 30.</span></span>  

## <a name="see-also"></a><span data-ttu-id="f5b65-190">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="f5b65-190">See Also</span></span>  
<span data-ttu-id="f5b65-191">[Hönnunarupplýsingar: Endurpöntunarstefnur](design-details-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="f5b65-191">[Design Details: Reordering Policies](design-details-reordering-policies.md) </span></span>  
<span data-ttu-id="f5b65-192">[Hönnunarupplýsingar: Áætlunarfæribreytur](design-details-planning-parameters.md) </span><span class="sxs-lookup"><span data-stu-id="f5b65-192">[Design Details: Planning Parameters](design-details-planning-parameters.md) </span></span>  
<span data-ttu-id="f5b65-193">[Hönnunarupplýsingar: Meðhöndlun endurpöntunarstefna](design-details-handling-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="f5b65-193">[Design Details: Handling Reordering Policies](design-details-handling-reordering-policies.md) </span></span>  
[<span data-ttu-id="f5b65-194">Hönnunarupplýsingar: framboðsáætlun</span><span class="sxs-lookup"><span data-stu-id="f5b65-194">Design Details: Supply Planning</span></span>](design-details-supply-planning.md)

