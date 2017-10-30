---
title: "Fá yfirlit yfir tiltækileika"
description: "Hægt er að fá upplýsingar um tiltækar vörur milli birgðageymslna fyrir hverja sölu eða innkaupa atburðir, eftir tímabili eða eftir staðsetningu vörunnar í samsetningu Uppskriftar."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: stock
ms.date: 08/15/2017
ms.author: SorenGP
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 81872839df11a13489bbc192ad97dae04976ebb0
ms.contentlocale: is-is
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-view-the-availability-of-items"></a><span data-ttu-id="5fd76-103">Hvernig skal: Skoða tiltækileika vöru</span><span class="sxs-lookup"><span data-stu-id="5fd76-103">How to: View the Availability of Items</span></span>
<span data-ttu-id="5fd76-104">Þegar um er að ræða viðskiptatengd verkefni er hægt að fá ítarlegar upplýsingar um hvenær og hvar vara er fáanleg, til dæmis þegar verið er að ræða við viðskiptavin um afhendingardag.</span><span class="sxs-lookup"><span data-stu-id="5fd76-104">From the context of a business task, you can get advanced information about when and where an item is available, such as when talking to a customer about a delivery date.</span></span>

<span data-ttu-id="5fd76-105">Hægt er að skoða tiltækileika alla vara eftir staðsetningu, og hægt er að skoða tiltækileika hverrar vöru eftir atburði, tímabili eða staðsetningu.</span><span class="sxs-lookup"><span data-stu-id="5fd76-105">You can view the availability of all items per location, and you can view the availability of each item by event, by period, or by location.</span></span> <span data-ttu-id="5fd76-106">Með atburði er átt við allar áætlaðar vörufærslur, svo sem söluafhendingu eða flutningsinnhreyfingu á innleið.</span><span class="sxs-lookup"><span data-stu-id="5fd76-106">An event is any scheduled item transaction, such as a sales shipment or an inbound transfer receipt.</span></span>

> [!NOTE]  
>   <span data-ttu-id="5fd76-107">Ef óskað er eftir að sjá tiltækileika eftir staðsetningu þarf að hafa birgðir á fleiri en einum stað.</span><span class="sxs-lookup"><span data-stu-id="5fd76-107">Availability views by location require that you maintain inventory at more than one location.</span></span> <span data-ttu-id="5fd76-108">Nánari upplýsingar er að finna í [Hvernig á að: Setja upp staðsetningar](inventory-how-setup-locations.md).</span><span class="sxs-lookup"><span data-stu-id="5fd76-108">For more information, see [How to: Set Up Locations](inventory-how-setup-locations.md).</span></span>

<span data-ttu-id="5fd76-109">Í [!INCLUDE[d365fin](includes/d365fin_md.md)], eru tölur um framboð sýndar í tveimur mismunandi reitum, hvor um sig með mismunandi skilgreiningu:</span><span class="sxs-lookup"><span data-stu-id="5fd76-109">In [!INCLUDE[d365fin](includes/d365fin_md.md)], availability figures are shown in two different fields, each with a different definition:</span></span>

* <span data-ttu-id="5fd76-110">Svæðið **Magn á lager** sýnir raunverulegt magn dagsins í dag samkvæmt bókuðum birgðafærslum.</span><span class="sxs-lookup"><span data-stu-id="5fd76-110">The **Quantity on Hand** field shows the actual quantity today according to posted item ledger entries.</span></span>
* <span data-ttu-id="5fd76-111">Svæðið **Áætluð staða til ráðstöfunar** er reiknað út og sýnir magn á lager ásamt tímasettum móttökum að frádreginni brúttóþörf.</span><span class="sxs-lookup"><span data-stu-id="5fd76-111">The **Projected Available Balance** field is calculated and shows the quantity on hand plus scheduled receipts minus gross requirements.</span></span> <span data-ttu-id="5fd76-112">(Í [!INCLUDE[d365fin](includes/d365fin_md.md)], fela tímasettar móttökur í sér magn á innkaupapöntun og flutningspantanir á innleið.</span><span class="sxs-lookup"><span data-stu-id="5fd76-112">(In [!INCLUDE[d365fin](includes/d365fin_md.md)], scheduled receipts include quantities on purchase orders and inbound transfer orders.</span></span> <span data-ttu-id="5fd76-113">Brúttóþörf felur í sér magn á sölupöntunum og flutningspantanir á útleið.)</span><span class="sxs-lookup"><span data-stu-id="5fd76-113">Gross requirements include quantities on sales orders and outbound transfer orders.)</span></span>

> [!TIP]  
>   <span data-ttu-id="5fd76-114">Sérstaklega mikilvægt er að skoða Áætlaða stöðu til ráðstöfunar í gluggunum **Tiltækileiki vöru eftir tímabili** og **Tiltækileiki vöru eftir atviki** þar sem þeir innihalda dagsetningarvíddirnar.</span><span class="sxs-lookup"><span data-stu-id="5fd76-114">The projected available balance is especially relevant to view in the **Item Availability by Periods** and **Item Availability by Event** windows as they contain the date dimension.</span></span>  

> [!NOTE]  
>   <span data-ttu-id="5fd76-115">Eftirfarandi ferli lýsa því hvernig á að skoða ítarlegar upplýsingar um tiltækileika á birgðalista og birgðaspjaldi.</span><span class="sxs-lookup"><span data-stu-id="5fd76-115">The following procedures describe how to view advanced availability information from the items list and item card.</span></span> <span data-ttu-id="5fd76-116">Einnig er hægt að nálgast upplýsingarnar úr söluskjalslínum, fyrir vöruna sem tilheyrir þeirri línu.</span><span class="sxs-lookup"><span data-stu-id="5fd76-116">You can also access the information from sales document lines, for the item on the line.</span></span> <span data-ttu-id="5fd76-117">Nánari upplýsingar eru í [Hvernig á að: selja vörur.](sales-how-sell-products.md)</span><span class="sxs-lookup"><span data-stu-id="5fd76-117">For more information, see [How to: Sell Products](sales-how-sell-products.md).</span></span>

## <a name="to-view-the-availability-of-an-item-according-to-when-it-will-be-received-or-shipped"></a><span data-ttu-id="5fd76-118">Að skoða tiltækileika vöru samkvæmt því hvenær hún berst eða verður afgreidd</span><span class="sxs-lookup"><span data-stu-id="5fd76-118">To view the availability of an item according to when it will be received or shipped</span></span>
<span data-ttu-id="5fd76-119">Hægt er að skoða tiltækileika vöru samkvæmt áætluðum vörufærslum í glugganum **Til ráðstöfunar eftir atviki**.</span><span class="sxs-lookup"><span data-stu-id="5fd76-119">You view the availability of an item according to scheduled item transactions in the **Availability by Event** window.</span></span>

1. <span data-ttu-id="5fd76-120">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Vörur** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="5fd76-120">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Items**, and then choose the related link.</span></span>
2. <span data-ttu-id="5fd76-121">Opnið spjald þeirrar vöru sem á að skoða ráðstöfun fyrir.</span><span class="sxs-lookup"><span data-stu-id="5fd76-121">Open the card of an item that you want to view availability for.</span></span>
3. <span data-ttu-id="5fd76-122">Veljið aðgerðina **Vara til ráðstöfunar eftir** og veljið svo aðgerðina **Atvik**.</span><span class="sxs-lookup"><span data-stu-id="5fd76-122">Choose the **Item Availability by** action, and then choose the **Event** action.</span></span>

    <span data-ttu-id="5fd76-123">Glugginn **Vara til ráðstöfunar eftir atviki** sýnir hvernig birgðamagn vöru þróast yfir tíma samkvæmt áætluðum sendingum og innhreyfingarskjölum.</span><span class="sxs-lookup"><span data-stu-id="5fd76-123">The **Item Availability by Event** window shows how the inventory quantity of the item will develop over time according scheduled shipment and receipt events.</span></span> <span data-ttu-id="5fd76-124">Glugginn býður upp á samantekið yfirlit sem birtir eina línu af uppsöfnuðum upplýsingum fyrir hvert tímabil þar sem birgðamagn breytist.</span><span class="sxs-lookup"><span data-stu-id="5fd76-124">The window gives a condensed view that shows one line of accumulated information per time interval in which inventory quantities change.</span></span> <span data-ttu-id="5fd76-125">Tímabil þar sem ekkert tilvik varð eru ekki sýndar.</span><span class="sxs-lookup"><span data-stu-id="5fd76-125">Time intervals where no events occurred are not shown.</span></span> <span data-ttu-id="5fd76-126">Hægt er að stækka hverja línu svo hún sýni upplýsingar um tilvik sem valdið hafa uppsöfnuðu magni í línunni.</span><span class="sxs-lookup"><span data-stu-id="5fd76-126">You can expand each line to show details about the event or events that caused the accumulated quantity on the line.</span></span>
4. <span data-ttu-id="5fd76-127">Veljið gildið á svæðinu **Áætluð staða til ráðstöfunar** til að skoða birgðafærslur eða opna skjöl sem mynda gildið.</span><span class="sxs-lookup"><span data-stu-id="5fd76-127">Choose the value in the **Projected Available Balance** field to view the item ledger entries or open documents that make up the value.</span></span>

## <a name="to-view-the-availability-of-an-item-in-different-periods"></a><span data-ttu-id="5fd76-128">Að skoða tiltækileika vöru á mismunandi tímabilum</span><span class="sxs-lookup"><span data-stu-id="5fd76-128">To view the availability of an item in different periods</span></span>
<span data-ttu-id="5fd76-129">Hægt er að skoða tiltækileika vöru samkvæmt tilgreindum tímabilum í glugganum **Til ráðstöfunar eftir tímabilum**.</span><span class="sxs-lookup"><span data-stu-id="5fd76-129">You view the availability of an item over time for specified time periods in the **Item Availability by Periods** window.</span></span>

1. <span data-ttu-id="5fd76-130">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Vörur** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="5fd76-130">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Items**, and then choose the related link.</span></span>
2. <span data-ttu-id="5fd76-131">Opnið spjald þeirrar vöru sem á að skoða ráðstöfun fyrir.</span><span class="sxs-lookup"><span data-stu-id="5fd76-131">Open the card of an item that you want to view availability for.</span></span>
3. <span data-ttu-id="5fd76-132">Veljið aðgerðina **Vara til ráðstöfunar eftir** og veljið svo aðgerðina **Tímabil**.</span><span class="sxs-lookup"><span data-stu-id="5fd76-132">Choose the **Item Availability by** action, and then choose the **Period** action.</span></span>

    <span data-ttu-id="5fd76-133">Glugginn **Vara til ráðstöfunar eftir tímabilum** sýnir hvernig birgðamagn vöru þróast yfir tíma, sett upp eftir því tímabili sem valið er, svo sem dagur, vika eða ársfjórðungur.</span><span class="sxs-lookup"><span data-stu-id="5fd76-133">The **Item Availability by Periods** window shows how the inventory quantity of the item will develop over time, shown for a period that you select, such as Day, Week, or Quarter.</span></span>
4. <span data-ttu-id="5fd76-134">Veljið gildið á svæðinu **Áætluð staða til ráðstöfunar** til að skoða birgðafærslur eða opna skjöl sem mynda gildið.</span><span class="sxs-lookup"><span data-stu-id="5fd76-134">Choose the value in the **Projected Available Balance** field to view the item ledger entries or open documents that make up the value.</span></span>

## <a name="to-view-the-availability-of-an-item-at-the-locations-where-it-is-stored"></a><span data-ttu-id="5fd76-135">Að skoða tiltækileika vöru eftir staðsetningunni sem hún er geymd á</span><span class="sxs-lookup"><span data-stu-id="5fd76-135">To view the availability of an item at the locations where it is stored</span></span>
<span data-ttu-id="5fd76-136">Tiltækileika vöru eftir staðsetningunni sem hún er geymd á má sjá í glugganum **Vara til ráðstöfunar eftir staðsetningu**.</span><span class="sxs-lookup"><span data-stu-id="5fd76-136">You view the availability of an item at the different places where it is stored in the **Item Availability by Location** window.</span></span>

1. <span data-ttu-id="5fd76-137">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Vörur** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="5fd76-137">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Items**, and then choose the related link.</span></span>
2. <span data-ttu-id="5fd76-138">Opnið spjald þeirrar vöru sem á að skoða ráðstöfun fyrir.</span><span class="sxs-lookup"><span data-stu-id="5fd76-138">Open the card of an item that you want to view availability for.</span></span>
3. <span data-ttu-id="5fd76-139">Veljið aðgerðina **Vara til ráðstöfunar eftir** og veljið svo aðgerðina **Staðsetning**.</span><span class="sxs-lookup"><span data-stu-id="5fd76-139">Choose the **Item Availability by** action, and then choose the **Location** action.</span></span>

    <span data-ttu-id="5fd76-140">Glugginn **Vara til ráðstöfunar eftir staðsetningu** sýnir hvernig birgðamagn vöru þróast yfir tíma á hverjum stað sem hún er geymd.</span><span class="sxs-lookup"><span data-stu-id="5fd76-140">The **Item Availability by Location** window shows how the inventory quantity of the item will develop in the future, shown for each location where it is stored.</span></span>
4. <span data-ttu-id="5fd76-141">Veljið gildið á svæðinu **Magn á lager** til að skoða birgðafærslur sem mynda gildið.</span><span class="sxs-lookup"><span data-stu-id="5fd76-141">Choose the value in the **Qty. on Hand** field to view the item ledger entries that make up the value.</span></span>
5. <span data-ttu-id="5fd76-142">Veljið gildið á svæðinu **Áætluð staða til ráðstöfunar** til að skoða birgðafærslur eða opna skjöl sem mynda gildið.</span><span class="sxs-lookup"><span data-stu-id="5fd76-142">Choose the value in the **Projected Available Balance** field to view the item ledger entries or open documents that make up the value.</span></span>

## <a name="to-view-the-availability-of-all-items-by-the-location-where-they-are-stored"></a><span data-ttu-id="5fd76-143">Að skoða tiltækileika allra vara eftir staðsetningunni sem þær eru geymdar á</span><span class="sxs-lookup"><span data-stu-id="5fd76-143">To view the availability of all items by the location where they are stored</span></span>
<span data-ttu-id="5fd76-144">Hægt er að sjá tiltækileika allra vara á öllum stöðum í glugganum **Vörur eftir staðsetningu**.</span><span class="sxs-lookup"><span data-stu-id="5fd76-144">You view the availability of all your items across all your locations in the **Items by Location** window.</span></span>

1. <span data-ttu-id="5fd76-145">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Vörur** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="5fd76-145">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Items**, and then choose the related link.</span></span>
2. <span data-ttu-id="5fd76-146">Veljið aðgerðina **Vörur eftir staðsetningu**.</span><span class="sxs-lookup"><span data-stu-id="5fd76-146">Choose the **Items by Location** action.</span></span>

    <span data-ttu-id="5fd76-147">Glugginn **Vörur eftir staðsetningu** sýnir hve margar vörur af hverri tegund fyrir sig eru tiltækar á öllum staðsetningum.</span><span class="sxs-lookup"><span data-stu-id="5fd76-147">The **Items by Location** window shows for all your items how many are available at each location.</span></span>
3. <span data-ttu-id="5fd76-148">Veljið gildið á svæðinu **Magn á lager** til að skoða birgðafærslur sem mynda gildið.</span><span class="sxs-lookup"><span data-stu-id="5fd76-148">Choose the value in the **Qty. on Hand** field to view the item ledger entries that make up the value.</span></span>

## <a name="to-view-the-availability-of-an-item-by-its-use-in-assembly-or-production-boms"></a><span data-ttu-id="5fd76-149">Að skoða framboð vöru eftir notkun hennar í samsetningu eða uppskrifta</span><span class="sxs-lookup"><span data-stu-id="5fd76-149">To view the availability of an item by its use in assembly or production BOMs</span></span>
<span data-ttu-id="5fd76-150">Ef til er vara í samsetningu eða Uppskriftir, annaðhvort sem yfirvöru eða íhlutur, þá er hægt að skoða hversu margar einingar af henni sé krafist í **Framboð vöru eftir Uppskriftarstigi** glugganum.</span><span class="sxs-lookup"><span data-stu-id="5fd76-150">If an item exists in assembly or production BOMs, either as a parent item or as a component, then you can view how many units of its are required in the **Item Availability by BOM Level** window.</span></span> <span data-ttu-id="5fd76-151">Glugginn sýnir hve margar einingar af yfirvöru er hægt að gera á grundvelli framboðs undirvara á undirliggjandi línum.</span><span class="sxs-lookup"><span data-stu-id="5fd76-151">The window shows how many units of a parent you can make based on the availability of child items on underlying lines.</span></span> <span data-ttu-id="5fd76-152">Allar vörur sem hafa samsetningu eða uppskriftarinnar birtast í glugganum sem samanbrjótanleg línu.</span><span class="sxs-lookup"><span data-stu-id="5fd76-152">Any item that has an assembly or production BOM is shown in the window as a collapsible line.</span></span> <span data-ttu-id="5fd76-153">Hægt er að stækka línuna til að birta undirliggjandi íhluti og undirsamsetningar á lægri stigum ásamt eigin uppskriftum.</span><span class="sxs-lookup"><span data-stu-id="5fd76-153">You can expand this line to see the underlying components and lower-level subassemblies with their own BOMs.</span></span>

<span data-ttu-id="5fd76-154">Hægt er að nota þennan glugga til að athuga hvort hægt sé að anna sölupöntun fyrir vöru á tiltekinni dagsetningu með því að skoða núverandi framboð ásamt magni sem íhlutir hennar geta annað.</span><span class="sxs-lookup"><span data-stu-id="5fd76-154">You can use the window to find out whether you can fulfill a sales order for an item on a specified date by looking at its current availability and the quantities that can be supplied by its components.</span></span> <span data-ttu-id="5fd76-155">Einnig er hægt að nota gluggann til að auðkenna flöskuhálsa í tengdum uppskriftum.</span><span class="sxs-lookup"><span data-stu-id="5fd76-155">You can also use the window to identify bottlenecks in related BOMs.</span></span>

<span data-ttu-id="5fd76-156">Í hverri línu í glugganum fyrir bæði yfir- og undirvörur, tilgreinið tölur til ráðstöfunar i eftirfarandi lykilsvæðum.</span><span class="sxs-lookup"><span data-stu-id="5fd76-156">On each line in the window for both parent items and child items, the following key fields specify the availability figures.</span></span> <span data-ttu-id="5fd76-157">Hægt er að nota þessar tölur til að gefa fyrirheit um hversu margar einingar af yfirvöru hægt er að afhenda ef tengt samsetningarferli er ræst.</span><span class="sxs-lookup"><span data-stu-id="5fd76-157">You can use these figures to promise how many units of a parent you can supply if you start the related assembly process.</span></span>

|<span data-ttu-id="5fd76-158">Svæði</span><span class="sxs-lookup"><span data-stu-id="5fd76-158">Field</span></span>|<span data-ttu-id="5fd76-159">Lýsing</span><span class="sxs-lookup"><span data-stu-id="5fd76-159">Description</span></span>|
|------|-----------|
|<span data-ttu-id="5fd76-160">**Get gert yfirmerki**</span><span class="sxs-lookup"><span data-stu-id="5fd76-160">**Able to Make Parent**</span></span>|<span data-ttu-id="5fd76-161">Sýnir hversu margar einingar hægt er að gera í undirsamsetningum í efstu vörunni.</span><span class="sxs-lookup"><span data-stu-id="5fd76-161">Shows how many units of any subassembly in the top item you can make.</span></span> <span data-ttu-id="5fd76-162">Reiturinn tilgreinir hversu margar tafarlausar yfireiningar hægt er að setja saman.</span><span class="sxs-lookup"><span data-stu-id="5fd76-162">The field specifies how many immediate parent units you can assemble.</span></span> <span data-ttu-id="5fd76-163">Gildið er samkvæmt framboði vörunnar í línunni.</span><span class="sxs-lookup"><span data-stu-id="5fd76-163">The value is based on availability of the item on the line.</span></span>|
|<span data-ttu-id="5fd76-164">**Get gert aðalvöru**</span><span class="sxs-lookup"><span data-stu-id="5fd76-164">**Able to Make Top Item**</span></span>|<span data-ttu-id="5fd76-165">Sýnir hversu margar einingar efstu vörunnar hægt er að gera.</span><span class="sxs-lookup"><span data-stu-id="5fd76-165">Shows how many units of the top item you can make.</span></span> <span data-ttu-id="5fd76-166">Reiturinn tilgreinir hversu margar einingar af aðaluppskriftarvöru hægt er að setja saman.</span><span class="sxs-lookup"><span data-stu-id="5fd76-166">The field specifies how many units of the top-line BOM item you can assemble.</span></span> <span data-ttu-id="5fd76-167">Gildið er samkvæmt framboði vörunnar í línunni.</span><span class="sxs-lookup"><span data-stu-id="5fd76-167">The value is based on availability of the item on the line.</span></span>|

### <a name="item-availability-by-bom-level-window"></a><span data-ttu-id="5fd76-168">Til ráðstöfunar e. uppskriftarstigi gluggi</span><span class="sxs-lookup"><span data-stu-id="5fd76-168">Item Availability by BOM Level Window</span></span>
<span data-ttu-id="5fd76-169">**Framboð vöru eftir uppskriftarstigi** glugginn sýnir upplýsingar um vöruna á línu spjalds eða skjals sem glugginn er opnaður fyrir.</span><span class="sxs-lookup"><span data-stu-id="5fd76-169">The **Item Availability by BOM Level** window shows information for the item on the card or document line that the window is opened for.</span></span> <span data-ttu-id="5fd76-170">Varan er alltaf sýnd í efstu línunni.</span><span class="sxs-lookup"><span data-stu-id="5fd76-170">The item is always shown on the top line.</span></span> <span data-ttu-id="5fd76-171">Hægt er að skoða upplýsingar um aðrar vörur eða allar vörur með því að breyta gildinu í **Afmörkun vöru** reitnum.</span><span class="sxs-lookup"><span data-stu-id="5fd76-171">You can view information for other items or for all items by changing the value in the **Item Filter** field.</span></span>

> [!NOTE]  
>   <span data-ttu-id="5fd76-172">Sjálfgefið sýna ráðstöfunartölur á línunum heildarráðstöfun allra vara undir söluhæstu vörunni</span><span class="sxs-lookup"><span data-stu-id="5fd76-172">By default, availability figures on the lines show the total availability of all items under the top item.</span></span> <span data-ttu-id="5fd76-173">Þessar tölur eru birtar í **Framboðsmagn** reitnum, og áherslan er á aðalvöruna.</span><span class="sxs-lookup"><span data-stu-id="5fd76-173">These figures are displayed in the **Available Quantity** field, and the focus is on the top item.</span></span> <span data-ttu-id="5fd76-174">Hins vegar geta upplýsingar um hversu margar millivörur er hægt að búa til verið misvísandi.</span><span class="sxs-lookup"><span data-stu-id="5fd76-174">However, information about how many subassemblies you can make may be skewed.</span></span> <span data-ttu-id="5fd76-175">Til að fá raunverulega mynd af því hversu margar af birtum undirsamsetningum er hægt að búa til, þarf að hreinsa **Sýna heildarframboð** gátreitinn og skoða svo töluna í **Get gert yfirmerki** reitnum .</span><span class="sxs-lookup"><span data-stu-id="5fd76-175">To get a true indication of how many of the shown subassemblies you can make, you must clear the **Show Total Availability** chack box and then see the figure in the **Able to Make Parent** field.</span></span>

<span data-ttu-id="5fd76-176">Reiturinn **Flöskuháls** tilgreinir hvaða vara í skipulagi uppskriftarinnar kemur í veg fyrir að gert sé meira magn en það sem sýnt er í reitnum **Get gert aðalvöru**.</span><span class="sxs-lookup"><span data-stu-id="5fd76-176">The **Bottleneck** field specifies which item in the BOM structure restricts you from making a larger quantity than the quantity that is shown in the **Able to Make Top Item** field.</span></span> <span data-ttu-id="5fd76-177">Til dæmis getur flöskuhálsvaran verið innkeyptur íhlutur með áætlaðri móttökudagsetningu sem er kemur of seint til að gera viðbótareiningar af aðalvörunni fyrir dagsetninguna í reitnum **Verður að vera tilbúið fyrir þessa dagsetningu**.</span><span class="sxs-lookup"><span data-stu-id="5fd76-177">For example, the bottleneck item can be a purchased component with an expected receipt date that is too late to make additional units of the top item by the date in the **Needed by Date** field.</span></span>

## <a name="assembly-availability-window"></a><span data-ttu-id="5fd76-178">Samsetningaráðstöfun gluggi </span><span class="sxs-lookup"><span data-stu-id="5fd76-178">Assembly Availability Window</span></span>
<span data-ttu-id="5fd76-179">Glugginn **Samsetningaráðstöfun** birtir sundurliðaðar ráðstöfunarupplýsingarnar fyrir samsetningaríhluti.</span><span class="sxs-lookup"><span data-stu-id="5fd76-179">The **Assembly Availability** window shows detailed availability information for the assembly item.</span></span> <span data-ttu-id="5fd76-180">Það opnast:</span><span class="sxs-lookup"><span data-stu-id="5fd76-180">It opens:</span></span>

- <span data-ttu-id="5fd76-181">Sjálfkrafa úr sölupöntunarlínu í samsetningarpöntunaraðstæður þegar magn er fært inn sem veldur vandamálum með ráðstöfun íhlutar.</span><span class="sxs-lookup"><span data-stu-id="5fd76-181">Automatically from a sales order line in assemble-to-order scenarios when you enter a quantity that causes a component availability issue.</span></span>
- <span data-ttu-id="5fd76-182">Sjálfkrafa úr samsetningarpöntunarhaus þegar gildi er fært inn í reitinn Magn sem veldur vandamálum með ráðstöfun íhlutar.</span><span class="sxs-lookup"><span data-stu-id="5fd76-182">Automatically from an assembly order header when you enter a value in the Quantity field that causes a component availability issue.</span></span>
- <span data-ttu-id="5fd76-183">Handvirkt þegar hann er opnaður í samsetningarpöntun.</span><span class="sxs-lookup"><span data-stu-id="5fd76-183">Manually when you open it from an assembly order.</span></span> <span data-ttu-id="5fd76-184">Í flipanum Aðgerðir inni í flokknum Eiginleikar skal velja Sýna framboð.</span><span class="sxs-lookup"><span data-stu-id="5fd76-184">On the Actions tab, in the Functions group, choose Show Availability.</span></span>

<span data-ttu-id="5fd76-185">Flýtiflipinn **Upplýsingar** sýnir sundurliðaðar ráðstöfunarupplýsingarnar fyrir samsetningarvöruna, þar með talið hversu mikið af samsetningarpöntuninni er hægt að setja saman fyrir skiladagsetninguna út frá nauðsynlegum íhlutum til ráðstöfunar.</span><span class="sxs-lookup"><span data-stu-id="5fd76-185">The **Details** FastTab shows detailed availability information for the assembly item, including how many of the assembly order quantity can be assembled by the due date based on availability of the required components.</span></span> <span data-ttu-id="5fd76-186">Þetta birtist í reitnum Hægt að setja saman í flýtiflipanum Upplýsingar.</span><span class="sxs-lookup"><span data-stu-id="5fd76-186">This is shown in the Able to Assemble field on the Details FastTab.</span></span>

<span data-ttu-id="5fd76-187">Gildið í reitnum **Hægt að setja saman** er með rauðu letri ef magnið er undir magninu í reitnum **Eftirstandandi magn** sem gefur til kynna að ekki eru nógu margir íhlutir tiltækir til að setja saman fullt magn.</span><span class="sxs-lookup"><span data-stu-id="5fd76-187">The value in the **Able to Assemble** field is shown in red font if the quantity is lower than the quantity in the **Remaining Quantity** field, indicating that there are not enough components available to assemble the full quantity.</span></span>

<span data-ttu-id="5fd76-188">Flýtiflipinn **Línur** birtir sundurliðaðar ráðstöfunarupplýsingarnar fyrir samsetningaríhluti.</span><span class="sxs-lookup"><span data-stu-id="5fd76-188">The **Lines** FastTab shows detailed availability information for the assembly components.</span></span>

<span data-ttu-id="5fd76-189">Ef einn eða fleiri samsetningaríhlutir eru ekki tiltækir endurspeglast það í reitnum **Hægt að setja saman** í viðkomandi línu sem magn sem er minna en magnið í **Eftirstöðvar (magn)** á flýtiflipanum **Upplýsingar**.</span><span class="sxs-lookup"><span data-stu-id="5fd76-189">If one or more assembly components are not available, then this is reflected in the **Able to Assemble** field on the line in question as a quantity less than the quantity in the **Remaining Quantity** field on the **Details** FastTab.</span></span>

## <a name="see-also"></a><span data-ttu-id="5fd76-190">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="5fd76-190">See Also</span></span>
[<span data-ttu-id="5fd76-191">Stjórna birgðum</span><span class="sxs-lookup"><span data-stu-id="5fd76-191">Manage Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="5fd76-192">Samsetningardeild</span><span class="sxs-lookup"><span data-stu-id="5fd76-192">Assembly Management</span></span>](assembly-assemble-items.md)  
<span data-ttu-id="5fd76-193">[Hvernig á að: Vinna með uppskriftir](inventory-how-work-BOMs.md)  </span><span class="sxs-lookup"><span data-stu-id="5fd76-193">[How to: Work with Bills of Materials](inventory-how-work-BOMs.md)  </span></span>  
[<span data-ttu-id="5fd76-194">Hvernig á að: Setja upp birgðageymslur</span><span class="sxs-lookup"><span data-stu-id="5fd76-194">How to: Set Up Locations</span></span>](inventory-how-setup-locations.md)  
[<span data-ttu-id="5fd76-195">Hvernig á að: Flytja birgðir milli birgðageymslna</span><span class="sxs-lookup"><span data-stu-id="5fd76-195">How to: Transfer Inventory Between Locations</span></span>](inventory-how-transfer-between-locations.md)  
<span data-ttu-id="5fd76-196">[Hvernig á að: Selja vörur](sales-how-sell-products.md)    </span><span class="sxs-lookup"><span data-stu-id="5fd76-196">[How to: Sell Products](sales-how-sell-products.md)    </span></span>  
[<span data-ttu-id="5fd76-197">Unnið með Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="5fd76-197">Working with Dynamics NAV</span></span>](ui-work-product.md)  
[<span data-ttu-id="5fd76-198">Almenn viðskiptavirkni</span><span class="sxs-lookup"><span data-stu-id="5fd76-198">General Business Functionality</span></span>](ui-across-business-areas.md)
