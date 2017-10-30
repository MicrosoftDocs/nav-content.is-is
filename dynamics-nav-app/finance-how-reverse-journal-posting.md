---
title: "Afturkalla bókun með bókun bakfærslu"
description: "Ef þú hefur framkvæmt ranga bókun í færslubók, geturðu notað bakfærsluaðgerðina til að afturkalla bókunina með réttri endurskoðunarslóð."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: reimbursement
ms.date: 08/03/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 2970914c36f892a5610509e9dc4015d0fb159642
ms.contentlocale: is-is
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-reverse-postings"></a><span data-ttu-id="a1ee3-103">Hvernig skal: Bakfæra bókanir.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-103">How to: Reverse Postings</span></span>
<span data-ttu-id="a1ee3-104">Til að afturkalla ranga bókun færslubókar skal velja færsluna og búa til bakfærslu (færsla sem er alveg eins og upphaflega færslan en með andstæðu tákni í reitnum fyrir upphæð) með sama skjalanúmeri og bókunardagsetningu og upphaflega færslan.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-104">To undo an erroneous journal posting, you select the entry and create a reverse entry (entries identical to the original entry but with opposite sign in the amount field) with the same document number and posting date as the original entry.</span></span> <span data-ttu-id="a1ee3-105">Þegar færsla hefur verið bakfærð þarf að búa til rétta færslu.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-105">After reversing an entry, you must make the correct entry.</span></span>

<span data-ttu-id="a1ee3-106">Aðeins er hægt að bakfæra færslu sem er bókuð frá færslubókarlínu.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-106">You can only reverse entries that are posted from a general journal line.</span></span> <span data-ttu-id="a1ee3-107">Færslu er einungis hægt að bakfæra einu sinni.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-107">An entry can only be reversed once.</span></span>

<span data-ttu-id="a1ee3-108">Frekari upplýsingar um bókun frá færslubók, sjá [Hvernig skal: Bóka færslur beint í fjárhag](finance-how-post-transactions-directly.md)</span><span class="sxs-lookup"><span data-stu-id="a1ee3-108">For more information about posting from a general journal, see [How to: Post Transactions Directly to the General Ledger](finance-how-post-transactions-directly.md).</span></span>

<span data-ttu-id="a1ee3-109">Ef magn hefur verið ranglega neikvætt bókað, t.d. ef innkaupapöntun hefur verið gerð með röngum stykkjafjölda og síðan bókað sem móttekið en ekki reikningsfært, er hægt að ógilda bókunina.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-109">If you have made an incorrect negative quantity posting, such as a purchase order with the wrong number of items and posted it as received but not invoiced, then you can undo the posting.</span></span>

<span data-ttu-id="a1ee3-110">Ef magn hefur verið ranglega jákvætt bókað, t.d. ef innkaupaskilapöntun hefur verið gerð með röngum stykkjafjölda og síðan bókað sem afgreitt en ekki reikningsfært, er hægt að ógilda bókunina.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-110">If you have made an incorrect positive quantity posting, such as a purchase return order with the wrong number of items and posted it as shipped but not invoiced, then you can undo the posting.</span></span>   

## <a name="to-reverse-the-journal-posting-of-a-general-ledger-entry"></a><span data-ttu-id="a1ee3-111">Að bakfæra færslubókarbókun fjárhagsfærslu</span><span class="sxs-lookup"><span data-stu-id="a1ee3-111">To reverse the journal posting of a general ledger entry</span></span>
<span data-ttu-id="a1ee3-112">Hægt er að bakfæra færslur úr öllum **Fjárhagsfærslur** gluggum.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-112">You can reverse entries from all **Ledger Entries** windows.</span></span> <span data-ttu-id="a1ee3-113">Eftirfarandi ferli byggist á **Fjárhagsfærslur** glugganum.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-113">The following procedure is based on the **General Ledger Entries** window.</span></span>
1. <span data-ttu-id="a1ee3-114">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Fjárhagsfærslur** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-114">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **General Ledger Entries**, and then choose the related link.</span></span>
2. <span data-ttu-id="a1ee3-115">Veljið færsluna sem á að bakfæra og veljið síðna aðgerðina **Bakfæra færslu**.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-115">Select the entry that you want to reverse, and then choose the **Reverse Transaction** action.</span></span> <span data-ttu-id="a1ee3-116">Athugið að þetta verður að koma úr bókun færslubókar.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-116">Note that is must originate from a journal posting.</span></span>
3. <span data-ttu-id="a1ee3-117">Í glugganum **Bakfærðar viðskiptafærslur** skal velja viðeigandi línu og svo aðgerðina **Bakfæra**.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-117">In the **Reverse Transaction Entries** window, select the relevant entry, and then choose the **Reverse** action.</span></span>
4. <span data-ttu-id="a1ee3-118">Velja hnappinn **Já** á staðfestingarskilaboðunum.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-118">Choose the **Yes** button on the confirmation message.</span></span>

## <a name="to-undo-a-quantity-posting-on-a-posted-purchase-receipt"></a><span data-ttu-id="a1ee3-119">Að afturkalla magnbókun í bókuðum innkaupamóttökum</span><span class="sxs-lookup"><span data-stu-id="a1ee3-119">To undo a quantity posting on a posted purchase receipt</span></span>  

1.  <span data-ttu-id="a1ee3-120">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **bókað innkaupamóttaka** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-120">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Posted Purchase Receipts**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="a1ee3-121">Opna bókuðu móttökuna sem á að afturkalla.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-121">Open the posted receipt that you want to undo.</span></span>  
3.  <span data-ttu-id="a1ee3-122">Velja skal línuna eða línurnar sem þú vilt afturkalla.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-122">Select the line or lines that you want to undo.</span></span>  
4.  <span data-ttu-id="a1ee3-123">Veldu **Afturkalla móttöku** aðgerðina.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-123">Choose **Undo Receipt** action.</span></span>

    <span data-ttu-id="a1ee3-124">Leiðréttingarlína er sett inn undir völdu móttökulínuna.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-124">A corrective line is inserted under the selected receipt line.</span></span>  

    <span data-ttu-id="a1ee3-125">Ef magnið móttekið í vöruhúsamóttöku er leiðréttingarlínan sett inn í bókuðu vöruhúsamóttökuna.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-125">If the quantity was received in a warehouse receipt, then a corrective line is inserted in the posted warehouse receipt.</span></span>  

    <span data-ttu-id="a1ee3-126">Reitirnir **Móttekið magn** og **Móttekið magn, óreikningsfært** svæði í tengdri innkaupapöntun eru stilltir á núll.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-126">The **Quantity Received** and **Qty. Rcd. Not Invoiced** fields on the related purchase order are set to zero.</span></span>

## <a name="to-undo-and-then-redo-a-quantity-posting-on-a-posted-return-shipment"></a><span data-ttu-id="a1ee3-127">Hvernig skal afturkalla og endurgera magnbókun á bókaða skilaafhendingu.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-127">To undo and then redo a quantity posting on a posted return shipment</span></span>

1.  <span data-ttu-id="a1ee3-128">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **bókað skilaafhending** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-128">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Posted Return Shipments**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="a1ee3-129">Opna bókuðu skilaafhendinguna sem á að afturkalla.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-129">Open the posted return shipment that you want to undo.</span></span>
3. <span data-ttu-id="a1ee3-130">Velja skal línuna eða línurnar sem þú vilt afturkalla.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-130">Select the line or lines you want to undo.</span></span>  

4.  <span data-ttu-id="a1ee3-131">Velja skal aðgerðina **Afturkalla vöruskilaafhendingu**.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-131">Choose the **Undo Return Shipment** action.</span></span>  

    <span data-ttu-id="a1ee3-132">Leiðréttingarlína er sett í bókaða fylgiskjalið og reitirnir **Skilamagn afhent** og **Skilaupph. afhent óreikningsf.** í innkaupabeiðninni eru settir á núll.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-132">A corrective line is inserted in the posted document, and the **Return Qty. Shipped** and **Return Shpd. Not Invd.** fields on the return order are set to zero.</span></span>  

    <span data-ttu-id="a1ee3-133">Farið nú aftur í innkaupaskilapöntunina til að endurtaka bókunina.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-133">Now go back to the purchase return order to redo the posting.</span></span>  

5.  <span data-ttu-id="a1ee3-134">Í glugganum **Bókuð skilaafhending** takið mið af tölunni á svæðinu **Skilapöntun nr**.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-134">In the **Posted Return Shipment** window, take a note of the number in the **Return Order No.**</span></span> <span data-ttu-id="a1ee3-135">.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-135">field.</span></span>  
6.  <span data-ttu-id="a1ee3-136">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Vöruskilapöntun innkaupa** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-136">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Purchase Return Orders**, and then choose the related link.</span></span>  
7.  <span data-ttu-id="a1ee3-137">Opna skilapöntunina sem um ræðir og velja síðan **Enduropna** aðgerðina.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-137">Open the return order in question, and then choose the **Reopen** action.</span></span>  
8.  <span data-ttu-id="a1ee3-138">Leiðrétta færsluna í **Magn** reitnum og bóka skilapöntun innkaupa aftur.</span><span class="sxs-lookup"><span data-stu-id="a1ee3-138">Correct the entry in the **Quantity** field and post the purchase return order again.</span></span>  

## <a name="see-also"></a><span data-ttu-id="a1ee3-139">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="a1ee3-139">See Also</span></span>
[<span data-ttu-id="a1ee3-140">Hvernig skal: Bóka færslu beint í Fjárhag</span><span class="sxs-lookup"><span data-stu-id="a1ee3-140">How to: Post Transactions Directly to the General Ledger</span></span>](finance-how-post-transactions-directly.md)  
[<span data-ttu-id="a1ee3-141">Vinna í færslubókum</span><span class="sxs-lookup"><span data-stu-id="a1ee3-141">Working with General Journals</span></span>](ui-work-general-journals.md)  
[<span data-ttu-id="a1ee3-142">Fjármál</span><span class="sxs-lookup"><span data-stu-id="a1ee3-142">Finance</span></span>](finance.md)  
<span data-ttu-id="a1ee3-143">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="a1ee3-143">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  
