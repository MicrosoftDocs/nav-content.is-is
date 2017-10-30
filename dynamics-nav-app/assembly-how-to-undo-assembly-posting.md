---
title: "Hvernig á að afturkalla samsetningarbókun"
description: "Stundum gæti þurft að afturkalla bókaða samsetningarpöntun, til dæmis ef pöntunin var bókuð með mistökum sem þarf að leiðrétta, eða vegna þess að hana hefði ekki átt að bóka til að byrja með og verður því að afturkalla."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/15/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 3ba93dd182aa1591f5d24398d4b749942d38bb4b
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-undo-assembly-posting"></a><span data-ttu-id="1bdb7-103">Hvernig á að afturkalla samsetningarbókun</span><span class="sxs-lookup"><span data-stu-id="1bdb7-103">How to: Undo Assembly Posting</span></span>
<span data-ttu-id="1bdb7-104">Stundum gæti þurft að afturkalla bókaða samsetningarpöntun, til dæmis ef pöntunin var bókuð með mistökum sem þarf að leiðrétta, eða vegna þess að hana hefði ekki átt að bóka til að byrja með og verður því að afturkalla.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-104">Sometimes you may need to undo a posted assembly order, for example when the order was posted with mistakes that must be corrected, or because it should not have been posted in the first place and must be rolled back.</span></span>

<span data-ttu-id="1bdb7-105">Þegar bókuð samsetningarpöntun er bókuð er færslubunki stofnaður í birgðahöfuðbók til að snúa við upphaflegum færslum.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-105">When you undo a posted assembly order, a set of corrective item ledger entries is created to reverse the original entries.</span></span> <span data-ttu-id="1bdb7-106">Hver neikvæð frálagsfærsla fyrir samsetningaríhlutinn er bakfærð með jákvæðri frálagsfærslu.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-106">Each positive output entry for the assembly item is reversed by a negative output entry.</span></span> <span data-ttu-id="1bdb7-107">Hver neikvæð notkunarfærsla fyrir samsetningaríhlut er bakfærð með jákvæðri notkunarfærslu.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-107">Each negative consumption entry for an assembly component is reversed by a positive consumption entry.</span></span> <span data-ttu-id="1bdb7-108">Fastur kostnaður er stofnaður sjálfkrafa á milli leiðréttingarfærslna og upphaflegu færslna til að tryggja nákvæma bakfærslu kostnaðar.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-108">Fixed cost application is automatically created between the corrective and original entries to ensure exact cost reversal.</span></span>  

<span data-ttu-id="1bdb7-109">Þegar fullbókuð samsetningarpöntun er afturkölluð er hægt að velja að útbúa pöntunina aftur á upphaflegu sniði, t.d. til að gera leiðréttingar áður en hún er bókuð á ný.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-109">When you undo a fully posted assembly order, then you can choose to recreate the assembly order to its original state, for example to make corrections before reposting it.</span></span> <span data-ttu-id="1bdb7-110">Að öðrum kosti er hægt að velja að endurstofna ekki samsetningarpöntunina.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-110">Alternatively, you can choose to not recreate the assembly order.</span></span>  

<span data-ttu-id="1bdb7-111">Þegar afturkalla á hlutabókaða samsetningarpöntun verða allir tilheyrandi magnreitir, s.s. **Samsett magn** **Notað magn** og **Eftirstandandi magn** að vera færðir aftur í þau gildi sem voru áður en á bókað var.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-111">When you undo a partially posted assembly order, then all affected quantity fields, such as the **Assembled Quantity**, **Consumed Quantity**, and **Remaining Quantity** fields are restored to the values they had before the posting in question.</span></span>  

<span data-ttu-id="1bdb7-112">Til að endurheimta eða endurstofna samsetningarpantanir verða eftirfarandi skilyrði að eiga við samsetningarvöruna sem var frálag í upprunalegu bókuninni:</span><span class="sxs-lookup"><span data-stu-id="1bdb7-112">To recreate or restore assembly orders, the following conditions must apply to the assembly item that was output in the original posting:</span></span>  

-   <span data-ttu-id="1bdb7-113">Hún verður að vera enn í birgðum, þannig að hún sé ekki seld eða á annan hátt notuð af færslum á útleið.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-113">It must still be in inventory, that is, it is not sold or otherwise consumed by outbound transactions.</span></span>  
-   <span data-ttu-id="1bdb7-114">Hún má ekki vera frátekin.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-114">It must not be reserved.</span></span>  
-   <span data-ttu-id="1bdb7-115">Það verður að vera til í hólfinu sem það var sett í sem frálag.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-115">It must exist in the bin that it was output to.</span></span>  

<span data-ttu-id="1bdb7-116">Auk þess er aðeins hægt að endurheimta samsetningarpantanir ef línunúmer og línuröð í upphaflegu samsetningarpöntuninni hafa ekki breyst.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-116">In addition, existing assembly orders can only be restored if the number of lines and the sequence of lines on the original assembly order are not changed.</span></span>  

> [!TIP]  
>  <span data-ttu-id="1bdb7-117">Til að leysa úr árekstrum vegna línubreytinga er hægt að afturkalla breytingarnar á umræddum línum handvirkt áður en tengda bókaða samsetningarpöntunin er afturkölluð.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-117">To solve conflicts due to line changes, you can manually revert the changes on the lines in question before undoing the related posted assembly order.</span></span> <span data-ttu-id="1bdb7-118">Einnig er hægt að bóka samsetningarpöntunina að fullu og velja síðan að endurstofna hana þegar bókunin er afturkölluð.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-118">Alternatively, you can post the assembly order fully and then select to recreate it when undoing the posting.</span></span>  

<span data-ttu-id="1bdb7-119">Eftirfarandi ferli lýsir því hvernig eigi afturkalla bókaðar samsetningarpantanir þar sem vörurnar voru settar saman í birgðir.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-119">The following procedure describes how to undo posted assembly orders where the items were assembled to stock.</span></span> <span data-ttu-id="1bdb7-120">Eigi að afturkalla bókaðar samsetningarpantanir þar sem vörur voru settar saman í sölupöntun þarf að nota aðgerðina **Afturkalla afhendingu** í bókuðu afhendingunni sem tengist bókuðu samsetningarpöntuninni.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-120">If you want to undo posted assembly orders where the items were assembled to a sales order, then you must use the **Undo Shipment** function on the posted shipment that relates to the posted assembly order.</span></span> <span data-ttu-id="1bdb7-121">Frekari upplýsingar, sjá [Hvernig skal: Bakfæra bókanir](finance-how-reverse-journal-posting.md).</span><span class="sxs-lookup"><span data-stu-id="1bdb7-121">For more information, see [How to: Reverse Postings](finance-how-reverse-journal-posting.md).</span></span> <span data-ttu-id="1bdb7-122">Afturköllun bókaðrar samsetningarpöntunar gerist síðan sjálfkrafa eins og lýst er í þessu efnisatriði.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-122">The undoing of the posted assembly order then happens automatically in the same way as described in this topic.</span></span>  

## <a name="to-undo-posting-of-an-assembly-order"></a><span data-ttu-id="1bdb7-123">Til að afturkalla bókun samsetningarpöntunar</span><span class="sxs-lookup"><span data-stu-id="1bdb7-123">To undo posting of an assembly order</span></span>  
1.  <span data-ttu-id="1bdb7-124">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Bókaðar samsetningarpantanir** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-124">To undo a fully or partially posted assembly order, Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Posted Assembly Orders**, and choose the related link.</span></span>  

    <span data-ttu-id="1bdb7-125">Glugginn **Bókaðar samsetningarpantanir** opnast og birtir eina eða fleiri bókaðar samsetningarpantanir sem eru bókaðar úr viðkomandi samsetningarpöntun.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-125">The **Posted Assembly Orders** window opens showing one or more posted assembly orders that are posted from the assembly order in question.</span></span> <span data-ttu-id="1bdb7-126">Hverja hlutabókun stofnar aðskilda bókaða samsetningarpöntun.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-126">Each partial posting creates a separate posted assembly order.</span></span>  
2.  <span data-ttu-id="1bdb7-127">Opna bókaða samsetningarpöntun sem á að afturkalla, og velja síðan aðgerðina **Afturkalla samsetningu**.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-127">Open the posted assembly order that you want to undo, and then choose the **Undo Assembly** action.</span></span>  

    <span data-ttu-id="1bdb7-128">Ef bókuð samsetningarpöntun sem á að afturkalla tengist fullbókaðri samsetningarpöntun sem nú hefur verið eytt er hægt að endurstofna hana, yfirleitt til þess að endurvinna hana.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-128">If the posted assembly order that you want to undo relates to a fully posted assembly order that is now deleted, then you have the option to recreate it, typically because you want to reprocess it.</span></span>  
3.  <span data-ttu-id="1bdb7-129">Ef endurgera á samsetningarpöntunina skal velja hnappinn **Já**.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-129">If you want to recreate the assembly order, choose the **Yes** button.</span></span> <span data-ttu-id="1bdb7-130">Til að afturkalla bókunina án þess að endurstofna tengdu samsetningarpöntunina skal velja hnappinn **Nei**.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-130">To undo the posting without recreating the related assembly order, choose the **No** button.</span></span>  

<span data-ttu-id="1bdb7-131">**Frátekið** Svæðið í haus samsetningarpöntunar breytist í **Já**.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-131">The **Reversed** field on the assembly order header changes to **Yes**.</span></span> <span data-ttu-id="1bdb7-132">Bókun samsetningarpöntunarinnar er nú bakfærð, og hægt er að halda áfram að vinna alla samsetningarpöntunina ef valið var að endurstofna hana eða opnu samsetningarpöntunina sem hefur verið færð til baka í upphaflegt horf.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-132">The assembly order posting is now reversed, and you can proceed to process the entire assembly order if you chose to recreate it or the open assembly order that you have restored to its original state.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="1bdb7-133">Til að endurheimta magn úr mörgum hlutabókunum í samsetningarpöntun þarf að afturkalla allar bókaðar samsetningarpantanir sem um ræðir með því að fylgja skrefum 1 til 3 hér að ofan fyrir hverja bókaða samsetningarpöntun.</span><span class="sxs-lookup"><span data-stu-id="1bdb7-133">To restore quantities from multiple partial postings in an assembly order, you must undo all the posted assembly orders in question by following steps 1 through 3 above for each posted assembly order.</span></span>  

## <a name="see-also"></a><span data-ttu-id="1bdb7-134">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="1bdb7-134">See Also</span></span>  
[<span data-ttu-id="1bdb7-135">Samsetningardeild</span><span class="sxs-lookup"><span data-stu-id="1bdb7-135">Assembly Management</span></span>](assembly-assemble-items.md)  
<span data-ttu-id="1bdb7-136">[Hvernig skal: Bakfæra bókanir](finance-how-reverse-journal-posting.md).</span><span class="sxs-lookup"><span data-stu-id="1bdb7-136">[How to: Reverse Postings](finance-how-reverse-journal-posting.md)</span></span>  
<span data-ttu-id="1bdb7-137">[Meðhöndlun söluvöruskila eða afturkallana](sales-how-process-sales-returns-cancellations.md)  </span><span class="sxs-lookup"><span data-stu-id="1bdb7-137">[How to: Process Sales Returns or Cancellations](sales-how-process-sales-returns-cancellations.md)  </span></span>  
[<span data-ttu-id="1bdb7-138">Hvernig á að: Vinna með uppskriftir</span><span class="sxs-lookup"><span data-stu-id="1bdb7-138">How to: Work with Bills of Material</span></span>](inventory-how-work-BOMs.md)  
[<span data-ttu-id="1bdb7-139">Birgðir</span><span class="sxs-lookup"><span data-stu-id="1bdb7-139">Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="1bdb7-140">Hönnunarupplýsingar vöruhúsakerfi</span><span class="sxs-lookup"><span data-stu-id="1bdb7-140">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)  
<span data-ttu-id="1bdb7-141">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="1bdb7-141">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
