---
title: "Hvernig á að birgðaskrá íhluti samkvæmt frálagi aðgerða"
description: "Fyrir vörur sem hafa verið settar upp með afturvirkri birgðaskráningu er sjálfgefin virkni að reikna út og bóka notkun íhluta þegar stöðu útgefinnar framleiðslupöntunar er breytt í **Lokið**. Frekari upplýsingar eru í Birgðaskráningaraðferð."
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
ms.openlocfilehash: 48645ff5d943b2f7093224289ff3cad6cfa6537e
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-flush-components-according-to-operation-output"></a><span data-ttu-id="c5238-104">Hvernig á að birgðaskrá íhluti samkvæmt frálagi aðgerða</span><span class="sxs-lookup"><span data-stu-id="c5238-104">How to: Flush Components According to Operation Output</span></span>
<span data-ttu-id="c5238-105">Fyrir vörur sem hafa verið settar upp með afturvirkri birgðaskráningu er sjálfgefin virkni að reikna út og bóka notkun íhluta þegar stöðu útgefinnar framleiðslupöntunar er breytt í **Lokið**.</span><span class="sxs-lookup"><span data-stu-id="c5238-105">For items that are set up with backward flushing method, the default behavior is to calculate and post component consumption when you change the status of a released production order to **Finished**.</span></span>  

<span data-ttu-id="c5238-106">Ef leiðartengilskótar eru einnig skilgreindir verður reiknað og bókað eftir hverja aðgerð og magnið sem var raunverulega notað í aðgerðinni bókað.</span><span class="sxs-lookup"><span data-stu-id="c5238-106">If you also define routing link codes, then calculation and posting occurs when each operation is finished, and the quantity that was actually consumed in the operation is posted.</span></span> <span data-ttu-id="c5238-107">Frekari upplýsingar, sjá [Hvernig skal: Stofna leiðir](production-how-to-create-routings.md).</span><span class="sxs-lookup"><span data-stu-id="c5238-107">For more information, see [How to: Create Routings](production-how-to-create-routings.md).</span></span>  

<span data-ttu-id="c5238-108">Til dæmis ef framleiðslupöntun um að framleiða 800 metra krefst 8 kg af íhlut, og ef 200 metrar eru bókaðir sem frálag, bókast 2 kg sjálfkrafa sem notkun.</span><span class="sxs-lookup"><span data-stu-id="c5238-108">For example, if a production order to produce 800 meters requires 8 kg of a component, then when you post 200 meters as output, 2 kg are automatically posted as consumption.</span></span>  

<span data-ttu-id="c5238-109">Þessi aðgerð er gagnleg af eftirfarandi ástæðum:</span><span class="sxs-lookup"><span data-stu-id="c5238-109">This functionality is useful for the following reasons:</span></span>  

-   <span data-ttu-id="c5238-110">**Birgðir - Verðmæti** - Virðisfærslur fyrir frálag og notkun eru stofnaðar samhliða framleiðslupöntun í vinnslu.</span><span class="sxs-lookup"><span data-stu-id="c5238-110">**Inventory Valuation** - Value entries for output and consumption are created in parallel as the production order progresses.</span></span> <span data-ttu-id="c5238-111">Án leiðartengilskóða munu birgðagildi hækka þar sem afköst eru bókuð og svo minnka síðar meir þegar gildi íhlutanotkunar er bókuð ásamt lokinni framleiðslupöntun.</span><span class="sxs-lookup"><span data-stu-id="c5238-111">Without routing link codes, the inventory value will increase as output is posted and then decrease at a later point in time when the value of component consumption is posted together with the finished production order.</span></span>  
-   <span data-ttu-id="c5238-112">**Birgðir til ráðstöfunar** - með stöðugri notkunarbókun er betur uppfært hvort íhlutir eru til ráðstöfunar, sem er mikilvægt til að viðhalda innra jafnvægi á milli eftirspurnar og framboðs.</span><span class="sxs-lookup"><span data-stu-id="c5238-112">**Inventory Availability** - With gradual consumption posting, the availability of component items is more up-to-date, which is important to maintain the internal balance between demand and supply.</span></span> <span data-ttu-id="c5238-113">Án leiðartengilskóta kunna aðrar eftirspurnir eftir íhlutnum að líta svo á að hann sé laus, svo framarlega sem hann bíður seinkaðrar notkunarbókunar.</span><span class="sxs-lookup"><span data-stu-id="c5238-113">Without routing link codes, other demands for the component may believe that it is available as long as it is pending a delayed consumption posting.</span></span>  
-   <span data-ttu-id="c5238-114">**Tímanleg** – þegar hægt er að sérstilla afurðir eftir beiðni viðskiptamanna er hægt að draga úr rýrnun með því að tryggja að breytingar á verkum og kerfisbreytingar eigi sér aðeins stað þegar þess þarf.</span><span class="sxs-lookup"><span data-stu-id="c5238-114">**Just-in-Time** – With the ability to customize products to customer requests, you can minimize waste by making sure that work and system changes only occur when it is necessary.</span></span>  

<span data-ttu-id="c5238-115">Eftirfarandi ferli sýnir hvernig eigi að sameina afturvirka birgðaskráningu og kóta leiðartengils þannig að magnið sem er skráð fyrir hverja aðgerð sé í samræmi við raunverulegan frálag lokinna aðgerða.</span><span class="sxs-lookup"><span data-stu-id="c5238-115">The following procedure shows how to combine backward flushing and routing link codes so that the quantity that is flushed for each operation is proportional to the actual output of the finished operation.</span></span>  

## <a name="to-flush-components-according-to-operation-output"></a><span data-ttu-id="c5238-116">Til að birgðaskrá íhluti samkvæmt frálagi aðgerðar</span><span class="sxs-lookup"><span data-stu-id="c5238-116">To flush components according to operation output</span></span>  
1.  <span data-ttu-id="c5238-117">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Vörur** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="c5238-117">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Items**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="c5238-118">Veldu aðgerðina **Breyta**.</span><span class="sxs-lookup"><span data-stu-id="c5238-118">Choose the **Edit** action.</span></span>  
3.  <span data-ttu-id="c5238-119">Á flýtiflipanum **Áfylling**, í reitnum **Birgðaskráningaraðferð**, skal velja **Framsenda**.</span><span class="sxs-lookup"><span data-stu-id="c5238-119">On the **Replenishment** FastTab, in the **Flushing Method** field, select **Forward**.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="c5238-120">Veljið **Tínsla + Áfram** ef íhluturinn er notaður í birgðageymslu sem er sett upp fyrir beinan frágang og tínslu.</span><span class="sxs-lookup"><span data-stu-id="c5238-120">Select **Pick+ Forward** if the component is used in a location that is set up for directed put-away and pick.</span></span>  

4.  <span data-ttu-id="c5238-121">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **leiðir** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="c5238-121">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Routings**, and then choose the related link.</span></span>  
5.  <span data-ttu-id="c5238-122">Skilgreina leiðartengilskóða fyrir hverja aðgerð sem notar íhlutinn.</span><span class="sxs-lookup"><span data-stu-id="c5238-122">Define routing link codes for every operation that consumes the component.</span></span> <span data-ttu-id="c5238-123">Frekari upplýsingar, sjá [Hvernig skal: Stofna leiðir](production-how-to-create-routings.md).</span><span class="sxs-lookup"><span data-stu-id="c5238-123">For more information, see [How to: Create Routings ](production-how-to-create-routings.md).</span></span>  
6.  <span data-ttu-id="c5238-124">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Framleiðsluuppskrift** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="c5238-124">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Production BOM**, and then choose the related link.</span></span>  
7.  <span data-ttu-id="c5238-125">Skilgreina leiðartengilskóta úr hverju íhlutstilviki við aðgerðina þar sem hann er notaður.</span><span class="sxs-lookup"><span data-stu-id="c5238-125">Define routing link codes from each instance of the component to the operation where it is consumed.</span></span>

    > [!IMPORTANT]  
    >  <span data-ttu-id="c5238-126">Íhluturinn verður að hafa leiðartengil við síðustu aðgerð leiðarinnar.</span><span class="sxs-lookup"><span data-stu-id="c5238-126">The component must have a routing link to the last operation in the routing.</span></span>  

## <a name="see-also"></a><span data-ttu-id="c5238-127">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="c5238-127">See Also</span></span>  
[<span data-ttu-id="c5238-128">Hvernig á að stofna nýjar framl.uppskriftir</span><span class="sxs-lookup"><span data-stu-id="c5238-128">How to: Create Production BOMs</span></span>](production-how-to-create-production-boms.md)  
[<span data-ttu-id="c5238-129">Uppsetning framleiðslu</span><span class="sxs-lookup"><span data-stu-id="c5238-129">Setting Up Manufacturing</span></span>](production-configure-production-processes.md)  
<span data-ttu-id="c5238-130">[Framleiðsla](production-manage-manufacturing.md)  </span><span class="sxs-lookup"><span data-stu-id="c5238-130">[Manufacturing](production-manage-manufacturing.md)  </span></span>  
<span data-ttu-id="c5238-131">[Áætlun](production-planning.md) </span><span class="sxs-lookup"><span data-stu-id="c5238-131">[Planning](production-planning.md) </span></span>  
[<span data-ttu-id="c5238-132">Birgðir</span><span class="sxs-lookup"><span data-stu-id="c5238-132">Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="c5238-133">Innkaup</span><span class="sxs-lookup"><span data-stu-id="c5238-133">Purchasing</span></span>](purchasing-manage-purchasing.md)  
<span data-ttu-id="c5238-134">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="c5238-134">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
