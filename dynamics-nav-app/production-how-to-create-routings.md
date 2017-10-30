---
title: "Hvernig á að stofna leiðir"
description: "Leið hefur að geyma aðalgögn sem skráir ferlisþarfir vara. Þegar framleiðslupöntun er búin til fyrir vöru stjórnar leið hennar áætlanagerð yfir aðgerðir eins og sýnt er í glugganum **Leið framl.pöntunar** í framleiðslupöntuninni."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/04/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 49cce1f32f1d66dc17c0d9758937541ef1baaae7
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-routings"></a><span data-ttu-id="c777c-104">Hvernig á að stofna Nýjar leiðir</span><span class="sxs-lookup"><span data-stu-id="c777c-104">How to: Create Routings</span></span>
<span data-ttu-id="c777c-105">Framleiðslufyrirtæki nota leiðir til að stýra framleiðsluferlinu og gera sýnilegt.</span><span class="sxs-lookup"><span data-stu-id="c777c-105">Manufacturing companies use routings to visualize and direct the manufacturing process.</span></span>

<span data-ttu-id="c777c-106">Leiðin er grunnurinn að vinnsluáætlun, áætlun um afköst og áætlaðri úthlutun á efnisþörf og framleiðsluskjölum.</span><span class="sxs-lookup"><span data-stu-id="c777c-106">The routing is the basis of process scheduling, capacity scheduling, scheduled assignment of material needs, and manufacturing documents.</span></span>  

<span data-ttu-id="c777c-107">Varðandi framleiðsluuppskriftir, er leiðunum úthlutað til endanlegrar framleiddrar vöru.</span><span class="sxs-lookup"><span data-stu-id="c777c-107">As for production BOMs, the routings are assigned to the manufacturing end item.</span></span> <span data-ttu-id="c777c-108">Leið hefur að geyma aðalgögn sem skráir ferlisþarfir vara.</span><span class="sxs-lookup"><span data-stu-id="c777c-108">A routing holds master data that captures the process requirements of a given produced item.</span></span> <span data-ttu-id="c777c-109">Þegar framleiðslupöntun er búin til fyrir vöru stjórnar leið hennar áætlanagerð yfir aðgerðir eins og sýnt er í glugganum **Leið framl.pöntunar** í framleiðslupöntuninni.</span><span class="sxs-lookup"><span data-stu-id="c777c-109">Once a production order is created for that item, its routing will govern the scheduling of operations as represented in the **Prod. Order Routing** window under the production order.</span></span>  

<span data-ttu-id="c777c-110">Áður en þú getur sett upp leið verður eftirfarandi að vera á réttum stað:</span><span class="sxs-lookup"><span data-stu-id="c777c-110">Before you can set up a routing, the following must be in place:</span></span>  

- <span data-ttu-id="c777c-111">Birgðaspjöld er búin til fyrir yfirvörur sem taka þátt í framleiðslu.</span><span class="sxs-lookup"><span data-stu-id="c777c-111">Item cards are created for parent items that take part in manufacturing.</span></span> <span data-ttu-id="c777c-112">Nánari upplýsingar eru í [Hvernig á að: Skrá nýjar vörur](inventory-how-register-new-items.md).</span><span class="sxs-lookup"><span data-stu-id="c777c-112">For more information, see [How to: Register New Items](inventory-how-register-new-items.md).</span></span>
- <span data-ttu-id="c777c-113">Framleiðsluforði eru uppsettur.</span><span class="sxs-lookup"><span data-stu-id="c777c-113">Production resources are set up.</span></span> <span data-ttu-id="c777c-114">Nánari upplýsingar er að finna í [Hvernig á að setja upp vinnustöðvar og vélastöðvar](production-how-to-set-up-work-and-machine-centers.md).</span><span class="sxs-lookup"><span data-stu-id="c777c-114">For more information, see [How to: Set Up Work Centers and Machine Centers](production-how-to-set-up-work-and-machine-centers.md).</span></span>

## <a name="to-create-a-routing"></a><span data-ttu-id="c777c-115">Stofna leið</span><span class="sxs-lookup"><span data-stu-id="c777c-115">To create a routing</span></span>  
1.  <span data-ttu-id="c777c-116">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **leiðir** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="c777c-116">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Routings**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="c777c-117">Valið er **Nýtt** aðgerð.</span><span class="sxs-lookup"><span data-stu-id="c777c-117">Choose the **New** action.</span></span>  
3. <span data-ttu-id="c777c-118">Fyllið inn í reitina eftir þörfum.</span><span class="sxs-lookup"><span data-stu-id="c777c-118">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4.  <span data-ttu-id="c777c-119">Í reitnum **Tegund**, veljið **Í röð** til að reikna framl. leiðina samkvæmt gildinu í reitnum **Aðgerðarnr.**.</span><span class="sxs-lookup"><span data-stu-id="c777c-119">In the **Type** field, select **Serial** to calculate the production routing according to the value in the **Operation No.**</span></span> <span data-ttu-id="c777c-120">.</span><span class="sxs-lookup"><span data-stu-id="c777c-120">field.</span></span>   
    <span data-ttu-id="c777c-121">Veljið **Samhliða** til að reikna aðgerðir samkvæmt gildinu í reitnum **Næsta aðgerðarnr.**</span><span class="sxs-lookup"><span data-stu-id="c777c-121">Select **Parallel** to calculate the operations according to the value in the **Next Operation No.**</span></span> <span data-ttu-id="c777c-122">.</span><span class="sxs-lookup"><span data-stu-id="c777c-122">field.</span></span>  
5.  <span data-ttu-id="c777c-123">Reiturinn **Staða** verður að vera stilltur á **Ný** eða **Í þróun** svo hægt sé að breyta leið.</span><span class="sxs-lookup"><span data-stu-id="c777c-123">To edit the routing, set the **Status** field to **New** or **Under Development**.</span></span> <span data-ttu-id="c777c-124">Til að ræsa hana þarf að stilla **Staða** á **Vottað**.</span><span class="sxs-lookup"><span data-stu-id="c777c-124">To activate it, set the **Status** field to **Certified**.</span></span>  

    <span data-ttu-id="c777c-125">Halda áfram til að fylla út í leiðarlínur.</span><span class="sxs-lookup"><span data-stu-id="c777c-125">Proceed to fill in the routing lines.</span></span>
6.  <span data-ttu-id="c777c-126">Í **Aðgerð Nr.**.</span><span class="sxs-lookup"><span data-stu-id="c777c-126">In the **Operation No.**</span></span> <span data-ttu-id="c777c-127">reitinn er fært inn númer fyrstu aðgerðarinnar, t.d. **10**.</span><span class="sxs-lookup"><span data-stu-id="c777c-127">field, enter the number of the first operation, for example,  **10**.</span></span>  
7.  <span data-ttu-id="c777c-128">Í reitnum **Tegund** er valið hvers konar forði er notaður, t.d. **Vinnustöð**.</span><span class="sxs-lookup"><span data-stu-id="c777c-128">In the **Type** field, specify which kind of resource is used, for example, **Work Center**.</span></span>  
8.  <span data-ttu-id="c777c-129">Í reitnum **númer**</span><span class="sxs-lookup"><span data-stu-id="c777c-129">In the **No.**</span></span> <span data-ttu-id="c777c-130">er forðinn sem á að nota valinn eða hann sleginn inn í reitinn.</span><span class="sxs-lookup"><span data-stu-id="c777c-130">field, select the resource to be used, or type it in the field.</span></span>  
9.  <span data-ttu-id="c777c-131">Í reitnum **Leiðartengilskóti** er hægt að slá inn kóta til að tengja íhlut við ákveðna aðgerð.</span><span class="sxs-lookup"><span data-stu-id="c777c-131">In the **Routing Link Code** field, enter a code to connect the component to a specific operation.</span></span> <span data-ttu-id="c777c-132">Frekari upplýsingar, sjá hlutann „Stofna leiðartengla“.</span><span class="sxs-lookup"><span data-stu-id="c777c-132">For more information, see the "To create routing links" section.</span></span>
10.  <span data-ttu-id="c777c-133">Í reitunum **Keyrslutími** og **Uppsetn.tími** er færðir inn þeir vinnslutímar þarf til að framkvæma aðgerð.</span><span class="sxs-lookup"><span data-stu-id="c777c-133">In the **Run Time** and **Setup Time** fields, enter the process times needed to perform the operation.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="c777c-134">Uppsetningartími er reiknaður fyrir hverja framleiðslupöntun en keyrslutími fyrir hverja framleidda vöru.</span><span class="sxs-lookup"><span data-stu-id="c777c-134">Setup time is calculated per production order, whereas run time is calculated per produced item.</span></span>  

11.  <span data-ttu-id="c777c-135">Í reitnum **Samþætt afkastageta** er tilgreint hversu margar einingar valda forðans eru notaðar til að framkvæma aðgerð.</span><span class="sxs-lookup"><span data-stu-id="c777c-135">In the **Concurrent Capacities** field, specify how many units of the selected resource are used to perform the operation.</span></span> <span data-ttu-id="c777c-136">Til dæmis helminga tveir einstaklingar úthlutaðir á eina pökkunaraðgerð keyrslutímann.</span><span class="sxs-lookup"><span data-stu-id="c777c-136">For example, two people allocated to one packing operation will halve the run time.</span></span>  
12.  <span data-ttu-id="c777c-137">Haldið er áfram að fylla út línur fyrir allar aðgerðir sem koma við sögu í framleiðslu viðkomandi vöru.</span><span class="sxs-lookup"><span data-stu-id="c777c-137">Continue to fill in lines for all operations involved in producing the item in question.</span></span>  
13.  <span data-ttu-id="c777c-138">Línur úr fyrirliggjandi leið eru afritaðar með því að smella á **Afrita leiðir** aðgerðina til að velja línur sem eru til.</span><span class="sxs-lookup"><span data-stu-id="c777c-138">To copy lines from an existing routing, choose the **Copy Routing** action to select existing lines.</span></span>  
14. <span data-ttu-id="c777c-139">Leiðin vottuð.</span><span class="sxs-lookup"><span data-stu-id="c777c-139">Certify the routing.</span></span>  
15. <span data-ttu-id="c777c-140">Nú er hægt að hengja nýju leiðina við spjald viðkomandi framleiðsluvöru, með því að fylla upp í reitinn **Leið nr.**.</span><span class="sxs-lookup"><span data-stu-id="c777c-140">You can now attach the new routing to the card of the production item in question, by filling in the **Routing No.** field.</span></span> <span data-ttu-id="c777c-141">Nánari upplýsingar eru í [Hvernig á að: Skrá nýjar vörur](inventory-how-register-new-items.md).</span><span class="sxs-lookup"><span data-stu-id="c777c-141">For more information, see [How to: Register New Items](inventory-how-register-new-items.md).</span></span>  

> [!NOTE]  
>  <span data-ttu-id="c777c-142">Mundu líka að endurreikna staðlað kostnaðarverð vörunnar úr **birgða** spjaldinu: velja **Framleiða** aðgerðina, og síðan smellt á **Reikna staðlað kostn.verð** aðgerðina og veljið síðan **Öll stig** aðgerðina.</span><span class="sxs-lookup"><span data-stu-id="c777c-142">Remember also to recalculate the item’s standard cost from the **Item** card: Choose the **Manufacturing** action, select the **Calc. Standard Cost** action, and then select the **All Levels** action.</span></span>  

## <a name="to-create-routing-links"></a><span data-ttu-id="c777c-143">Leiðartenglar stofnaðir</span><span class="sxs-lookup"><span data-stu-id="c777c-143">To create routing links</span></span>
<span data-ttu-id="c777c-144">Hægt að búa til leiðartengla til að tengja íhluti við ákveðnar aðgerðir til að viðhalda sambandi þeirra jafnvel þótt framleiðsluuppskrift eða leið sé breytt.</span><span class="sxs-lookup"><span data-stu-id="c777c-144">You can create routing links to connect components to specific operations in order to retain their relationship even though the production BOM or routing is modified.</span></span> <span data-ttu-id="c777c-145">Þeir auðvelda einnig bráða birgðaskráningu íhluta þegar ákveðin tengd aðgerð hefst, ekki þegar öll framleiðslupöntunin er gefin út.</span><span class="sxs-lookup"><span data-stu-id="c777c-145">It also facilitates just-in-time flushing of components, namely when the specific linked operation starts, not when the complete production order is released.</span></span> <span data-ttu-id="c777c-146">Nánari upplýsingar eru í [Hvernig á að birgðaskrá íhluti samkvæmt frálagi aðgerða](production-how-to-flush-components-according-to-operation-output.md).</span><span class="sxs-lookup"><span data-stu-id="c777c-146">For more information see [How to: Flush Components According to Operation Output](production-how-to-flush-components-according-to-operation-output.md).</span></span>  

<span data-ttu-id="c777c-147">Annar mikilvægur kostur er sá að tenging íhluta og aðgerða er birt í rökrænni uppbyggingu framvindu þegar **framleiðslubókin** er notuð í bókanir frálags og notkunar.</span><span class="sxs-lookup"><span data-stu-id="c777c-147">Another important benefit is that linked components and operations are displayed in a logical process structure when you use the **Production Journal** window for output and consumption posting.</span></span>  

1.  <span data-ttu-id="c777c-148">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **leiðir** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="c777c-148">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Routings**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="c777c-149">Opna skal leiðina með aðgerðunum sem á að tengja.</span><span class="sxs-lookup"><span data-stu-id="c777c-149">Open the routing that contains the operations that you want to link.</span></span>  

    <span data-ttu-id="c777c-150">Tryggja þarf að staða leiðar sé **Í þróun**.</span><span class="sxs-lookup"><span data-stu-id="c777c-150">Make sure the routing status is **Under Development**.</span></span>  

3.  <span data-ttu-id="c777c-151">Á viðkomandi leiðarlínu í reitnum **Leiðartengilskóti** skal velja kóta.</span><span class="sxs-lookup"><span data-stu-id="c777c-151">On the relevant routing line, in the **Routing Link Code** field, select a code.</span></span>  
4.  <span data-ttu-id="c777c-152">Því næst er bætt við öðruvísi leiðartengilskótum á aðrar aðgerðir í leiðinni, ef það á við.</span><span class="sxs-lookup"><span data-stu-id="c777c-152">Proceed to add different routing link codes to other operations in the routing, if relevant.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="c777c-153">Ekki skal nota sama leiðartengilskótann í mismunandi aðgerðir í leið þar sem hætta er á að tengja íhlut fyrir mistök við tvær mismunandi aðgerðir og þar með nota hann tvisvar.</span><span class="sxs-lookup"><span data-stu-id="c777c-153">You should not use the same routing link code in different operations on a routing because you may incorrectly link a component to two different operations, so that it is consumed two times.</span></span>  
    >   
    >  <span data-ttu-id="c777c-154">Góð regla er að nefna leiðartengilskótann eftir aðgerðinni til að tryggja sértæka leiðartengla í aðgerðir.</span><span class="sxs-lookup"><span data-stu-id="c777c-154">It is a good idea to name the routing link code after the operation in order to ensure operation-specific routing links.</span></span>

5.  <span data-ttu-id="c777c-155">Staða leiðar er stillt á **Vottað**.</span><span class="sxs-lookup"><span data-stu-id="c777c-155">Set the routing status to **Certified**.</span></span>  

    <span data-ttu-id="c777c-156">Leiðartenglakótar eru nú tengdir við aðgerðir.</span><span class="sxs-lookup"><span data-stu-id="c777c-156">Routing link codes are now assigned to operations.</span></span> <span data-ttu-id="c777c-157">Næst skal stofna sjálfan tengilinn með því að úthluta sömu kótum á tiltekna íhluti í viðeigandi framleiðsluuppskrift.</span><span class="sxs-lookup"><span data-stu-id="c777c-157">Next, you must create the actual link by assigning the same codes to specific components in the relevant production BOM.</span></span>  

6.  <span data-ttu-id="c777c-158">Opna skal **framleiðsluuppskriftina** sem inniheldur íhlutina sem á að tengja við ofantaldar aðgerðir.</span><span class="sxs-lookup"><span data-stu-id="c777c-158">Open the **Production BOM** that contains the components that you want to link to the above operations.</span></span> <span data-ttu-id="c777c-159">Frekari upplýsingar, sjá [Hvernig skal: Stofna framleiðsluuppskriftir](production-how-to-create-production-boms.md).</span><span class="sxs-lookup"><span data-stu-id="c777c-159">For more information, see [How to: Create Production BOMs](production-how-to-create-production-boms.md).</span></span>
7.  <span data-ttu-id="c777c-160">Tryggja þarf að uppskriftin sé stillt á **Í þróun**.</span><span class="sxs-lookup"><span data-stu-id="c777c-160">Make sure the BOM status is **Under Development**.</span></span>  
8.  <span data-ttu-id="c777c-161">Á viðkomandi framleiðsluuppskriftarlínu í reitnum **Leiðartengilskóti** skal velja kótann sem úthlutað hefur verið á viðeigandi aðgerð.</span><span class="sxs-lookup"><span data-stu-id="c777c-161">On the relevant production BOM line, in the **Routing Link Code** field, select the code that you have just assigned to the relevant operation.</span></span>  
9. <span data-ttu-id="c777c-162">Því næst er leiðartengilskótum bætt við aðra íhluti eftir því í hvaða aðgerðum þeir kótar eru notaðir.</span><span class="sxs-lookup"><span data-stu-id="c777c-162">Proceed to add routing link codes to other components according to the unique operations where they are used.</span></span>  
10. <span data-ttu-id="c777c-163">Staða framleiðsluuppskriftar er stillt á **Vottað**.</span><span class="sxs-lookup"><span data-stu-id="c777c-163">Set the production BOM status to **Certified**.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="c777c-164">Til að virkja leiðartengla í framleiðslupöntun sem þegar er til þarf fyrst að endurnýja hana.</span><span class="sxs-lookup"><span data-stu-id="c777c-164">To enable the routing links on an existing production order, you must refresh the productio1n order.</span></span> <span data-ttu-id="c777c-165">Frekari upplýsingar, sjá [Hvernig skal: Stofna framleiðslupantanir](production-how-to-create-production-orders.md).</span><span class="sxs-lookup"><span data-stu-id="c777c-165">For more information, see [How to: Create Production Orders](production-how-to-create-production-orders.md).</span></span>  

<span data-ttu-id="c777c-166">Valdir íhlutir verða nú tengdir við valdar aðgerðir þegar framleiðslupöntun er búin til eða endurnýjuð með umræddri framleiðsluuppskrift og leið.</span><span class="sxs-lookup"><span data-stu-id="c777c-166">The selected components will now be linked to the selected operations when you create or refresh a production order using the production BOM and routing in question.</span></span> <span data-ttu-id="c777c-167">Hægt er að skoða þetta í glugganum **Íhlutir framleiðslupöntunar** undir framleiðslupöntuninni og í honum er einnig hægt að fjarlægja og bæta við tilgreindum leiðartengilskótum hvenær sem er.</span><span class="sxs-lookup"><span data-stu-id="c777c-167">This is visible in the **Prod. Order Components** window under the production order, and here you can also remove and add the defined routing link codes at any time.</span></span>

## <a name="to-assign-personnel-tools-and-quality-measures-to-routing-operations"></a><span data-ttu-id="c777c-168">Úthluta starfsmönnum, verkfærum og gæðaráðstöfunum til leiðaraðgerðir.</span><span class="sxs-lookup"><span data-stu-id="c777c-168">To assign personnel, tools, and quality measures to routing operations.</span></span>
<span data-ttu-id="c777c-169">Ef krafist er starfsmanna með sérþekkingu eða sérstaka heimild fyrir aðgerðinni má úthluta viðkomandi starfsmönnum á aðgerðina.</span><span class="sxs-lookup"><span data-stu-id="c777c-169">If you require personnel with qualifications, special knowledge, or special authorization for an operation, you can assign these personnel to the operation.</span></span> <span data-ttu-id="c777c-170">Að auki geturðu úthlutað verkfærum og gæðaráðstöfunum til aðgerðarinnar.</span><span class="sxs-lookup"><span data-stu-id="c777c-170">In addition, you can assign tools and quality requirements to the operation.</span></span> <span data-ttu-id="c777c-171">Þetta ferli lýsir því hvernig skal úthluta starfsmönnum.</span><span class="sxs-lookup"><span data-stu-id="c777c-171">This procedure describes how to assign personnel.</span></span> <span data-ttu-id="c777c-172">Skrefin eru svipuð fyrir aðrar gerðir aðgerðaupplýsinga.</span><span class="sxs-lookup"><span data-stu-id="c777c-172">The steps are similar for other types of operation information.</span></span>

1.  <span data-ttu-id="c777c-173">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **leiðir** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="c777c-173">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Routings**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="c777c-174">Viðeigandi leið er opnuð.</span><span class="sxs-lookup"><span data-stu-id="c777c-174">Open the relevant routing.</span></span>  
3.  <span data-ttu-id="c777c-175">Á flýtiflipanum **Línur** skal velja línuna sem á að vinna úr og svo velja aðgerðina **Starfsmenn**.</span><span class="sxs-lookup"><span data-stu-id="c777c-175">On the **Lines** FastTab, select the line that you want to process, and then choose the **Personnel** action.</span></span>  
4.  <span data-ttu-id="c777c-176">Reitirnir í glugganum **Starfsmenn leiðar** eru fylltir út.</span><span class="sxs-lookup"><span data-stu-id="c777c-176">Fill in the fields in the **Routing Personnel** window.</span></span>  
5.  <span data-ttu-id="c777c-177">Velja hnappinn **Í lagi** til að hætta í glugganum.</span><span class="sxs-lookup"><span data-stu-id="c777c-177">Choose the **OK** button to exit the window.</span></span> <span data-ttu-id="c777c-178">Innfærð gildi eru afrituð og úthlutuð aðgerðinni.</span><span class="sxs-lookup"><span data-stu-id="c777c-178">The entered values are copied and assigned to the operation.</span></span>    

## <a name="to-create-a-new-versions-of-a-routing"></a><span data-ttu-id="c777c-179">Gerð nýrra útgáfa af leiðum:</span><span class="sxs-lookup"><span data-stu-id="c777c-179">To create a new versions of a routing</span></span>  
<span data-ttu-id="c777c-180">Með útgáfureglunni er hægt að fást við margar útgáfur.</span><span class="sxs-lookup"><span data-stu-id="c777c-180">The version principle enables you to manage several versions of a routing.</span></span> <span data-ttu-id="c777c-181">Skipulag leiðaútgáfunnar samsvarar skipulagi leiðarinnar sem felur í sér leiðaútgáfuhaus og leiðaútgáfulínur.</span><span class="sxs-lookup"><span data-stu-id="c777c-181">The structure of the routing version corresponds to the structure of the routing consisting of the routing version header and the routing version lines.</span></span> <span data-ttu-id="c777c-182">Aðalmunurinn ræðst af upphafsdagsetningunni.</span><span class="sxs-lookup"><span data-stu-id="c777c-182">The basic difference is defined by the starting date.</span></span>  

1.  <span data-ttu-id="c777c-183">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **leiðir** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="c777c-183">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Routings**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="c777c-184">Leið sem á að afrita er valin og svo er aðgerðin **Útgáfur** valin.</span><span class="sxs-lookup"><span data-stu-id="c777c-184">Select the routing to be copied, and then choose the **Versions** action.</span></span>  
3. <span data-ttu-id="c777c-185">Í glugganum **Leiðarútgáfur** skal velja aðgerðina **Nýtt**.</span><span class="sxs-lookup"><span data-stu-id="c777c-185">In the **Routing Versions** window, choose the **New** action.</span></span>
4. <span data-ttu-id="c777c-186">Fyllið inn í reitina eftir þörfum.</span><span class="sxs-lookup"><span data-stu-id="c777c-186">Fill in the fields as necessary.</span></span>
5.  <span data-ttu-id="c777c-187">Einstakt auðkenni útgáfunnar er fært inn í reitinn **Útgáfukóti**.</span><span class="sxs-lookup"><span data-stu-id="c777c-187">In the **Version Code** field, enter the unique identification of the version.</span></span> <span data-ttu-id="c777c-188">Hvaða samsetning af tölum og bókstöfum er leyfileg.</span><span class="sxs-lookup"><span data-stu-id="c777c-188">Any combination of numbers and letters is permitted.</span></span>  

    <span data-ttu-id="c777c-189">Nýja útgáfan sem búin var til fær sjálfkrafa stöðuna **Ný.**</span><span class="sxs-lookup"><span data-stu-id="c777c-189">The newly created version is automatically assigned the status **New**.</span></span>  
6.  <span data-ttu-id="c777c-190">Til að búa til aðgerðarlínur, skal velja fyrstu auðu línuna og svo fylla inn í **Aðgerð nr.**</span><span class="sxs-lookup"><span data-stu-id="c777c-190">To create operation lines, select the first blank line, and then fill in the **Operation No.**</span></span> <span data-ttu-id="c777c-191">reitinn eftir aðgerðaröðinni.</span><span class="sxs-lookup"><span data-stu-id="c777c-191">field according to the sequence of operations.</span></span>

    <span data-ttu-id="c777c-192">Aðgerðalínunum er raðað í hækkandi röð eftir aðgerðanúmerum.</span><span class="sxs-lookup"><span data-stu-id="c777c-192">The operation lines are sorted in ascending order by operation numbers.</span></span> <span data-ttu-id="c777c-193">Til að hægt sé að gera breytingar síðar er mælt með því að nægilegt bil sé haft milli stiga.</span><span class="sxs-lookup"><span data-stu-id="c777c-193">To be able to make changes later, we recommend you to select adequate step widths.</span></span> <span data-ttu-id="c777c-194">**Næsta aðgerðarnr.**</span><span class="sxs-lookup"><span data-stu-id="c777c-194">The **Next Operation No.**</span></span> <span data-ttu-id="c777c-195">reiturinn vísar í eftirfarandi aðgerð.</span><span class="sxs-lookup"><span data-stu-id="c777c-195">field refers to the following operation.</span></span> <span data-ttu-id="c777c-196">Hægt er að færa aðgerðarnúmerið inn beint.</span><span class="sxs-lookup"><span data-stu-id="c777c-196">The number of the operation can be entered directly.</span></span>

7. <span data-ttu-id="c777c-197">Þegar leiðarútgáfunni er lokið, setja **Staða** reitinn á **Vottað**.</span><span class="sxs-lookup"><span data-stu-id="c777c-197">When the routing version is completed, setting the **Status** field to **Certified**.</span></span>

<span data-ttu-id="c777c-198">Gildistími útgáfunnar er tilgreindur í reitnum **Upphafsdagsetning**.</span><span class="sxs-lookup"><span data-stu-id="c777c-198">The time validity of the version is specified by the **Starting Date** field.</span></span>  

## <a name="see-also"></a><span data-ttu-id="c777c-199">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="c777c-199">See Also</span></span>  
[<span data-ttu-id="c777c-200">Hvernig á að stofna nýjar framl.uppskriftir</span><span class="sxs-lookup"><span data-stu-id="c777c-200">How to: Create Production BOMs</span></span>](production-how-to-create-production-boms.md)  
[<span data-ttu-id="c777c-201">Uppsetning framleiðslu</span><span class="sxs-lookup"><span data-stu-id="c777c-201">Setting Up Manufacturing</span></span>](production-configure-production-processes.md)  
<span data-ttu-id="c777c-202">[Framleiðsla](production-manage-manufacturing.md)  </span><span class="sxs-lookup"><span data-stu-id="c777c-202">[Manufacturing](production-manage-manufacturing.md)  </span></span>  
<span data-ttu-id="c777c-203">[Áætlun](production-planning.md) </span><span class="sxs-lookup"><span data-stu-id="c777c-203">[Planning](production-planning.md) </span></span>  
[<span data-ttu-id="c777c-204">Birgðir</span><span class="sxs-lookup"><span data-stu-id="c777c-204">Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="c777c-205">Innkaup</span><span class="sxs-lookup"><span data-stu-id="c777c-205">Purchasing</span></span>](purchasing-manage-purchasing.md)  
<span data-ttu-id="c777c-206">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="c777c-206">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
