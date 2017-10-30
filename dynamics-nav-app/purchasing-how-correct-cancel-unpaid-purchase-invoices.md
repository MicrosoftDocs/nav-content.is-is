---
title: "Breyta eða hætta við ógreidda innkaupareikninga | Microsoft Docs"
description: "Útskýrir hvernig á að leiðrétta, hætta við, eða afturkalla bókaðan innkaupareikning og stofna sjálfvirkt innkaupakreditreikning."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: undo, credit memo, return
ms.date: 08/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 294094f8483f9b51d47ad614b8702b289b9d1862
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-correct-or-cancel-unpaid-purchase-invoices"></a><span data-ttu-id="09ffd-103">Leiðrétta eða afturkalla ógreidda innkaupareikninga</span><span class="sxs-lookup"><span data-stu-id="09ffd-103">How to: Correct or Cancel Unpaid Purchase Invoices</span></span>
<span data-ttu-id="09ffd-104">Hægt er að leiðrétta eða afturkalla bókaðan innkaupareikning.</span><span class="sxs-lookup"><span data-stu-id="09ffd-104">You can correct or cancel a posted purchase invoice.</span></span> <span data-ttu-id="09ffd-105">Þetta er gagnlegt þegar leiðrétta á innsláttarmistök eða breyta kaupunum snemma í pöntunarferlinu.</span><span class="sxs-lookup"><span data-stu-id="09ffd-105">This is useful if you want to correct a typing mistake, or if you want to change the purchase early in the order process.</span></span>

<span data-ttu-id="09ffd-106">Ef þegar hefur verið greitt fyrir vörur á bókuðum innkaupareikningi er ekki hægt að leiðrétta eða hætta við úr bókaða innkaupareikningnum.</span><span class="sxs-lookup"><span data-stu-id="09ffd-106">If you have already paid for products on the posted purchase invoice, you cannot correct or cancel it from the posted purchase invoice itself.</span></span> <span data-ttu-id="09ffd-107">Þess í stað verður þú að handvirkt skapa innkaupakreditreikning til að snúa við innkaup, valfrjálst stjórnað með vöruskilapöntun innkaupa.</span><span class="sxs-lookup"><span data-stu-id="09ffd-107">Instead, you must manually create a purchase credit memo to reverse the purchase, optionally managed with a purchase return order.</span></span> <span data-ttu-id="09ffd-108">Nánari upplýsingar er að finna í [Hvernig á að: Vinna úr innkaupaskilum eða afturköllunum](purchasing-how-process-purchase-returns-cancellations.md).</span><span class="sxs-lookup"><span data-stu-id="09ffd-108">For more information, see [How to: Process Purchase Returns or Cancellations](purchasing-how-process-purchase-returns-cancellations.md).</span></span>

<span data-ttu-id="09ffd-109">Í glugganum **Bókaður innkaupareikningur** er hægt að velja hnappinn **Leiðrétting** eða hnappinn **Hætta við**.</span><span class="sxs-lookup"><span data-stu-id="09ffd-109">In the **Posted Purchase Invoice** window, you can choose the **Correct** button or the **Cancel** button.</span></span> <span data-ttu-id="09ffd-110">Þegar bókaður innkaupareikningur er leiðréttur eða afturkallaður, er bókaður innkaupakreditreikningur jafnaður við allar fjárhags- og raunbirgðafærslur sem búnar voru til við bókun hins upphaflega innkaupareiknings.</span><span class="sxs-lookup"><span data-stu-id="09ffd-110">When you correct or cancel a posted purchase invoice, the corrective purchase credit memo is applied to all general ledger and inventory ledger entries that were created when the initial purchase invoice was posted.</span></span> <span data-ttu-id="09ffd-111">Þetta bakfærir hinn bókaða innkaupareikning í fjárhagslegum færslum og lætur hina leiðréttu bókaða innkaupakreditreikninga í endurskoðunarrakninguna.</span><span class="sxs-lookup"><span data-stu-id="09ffd-111">This reverses the posted purchase invoice in your financial records and leaves the corrective posted purchase credit memo for your audit trail.</span></span> <span data-ttu-id="09ffd-112">Hér á eftir er notkun **Leiðrétting** og **Hætta við**lýst.</span><span class="sxs-lookup"><span data-stu-id="09ffd-112">In the following the use of **Correct** and **Cancel** is described.</span></span>

## <a name="to-correct-a-posted-purchase-invoice"></a><span data-ttu-id="09ffd-113">Til að leiðrétta bókaðan innkaupareikning.</span><span class="sxs-lookup"><span data-stu-id="09ffd-113">To correct a posted purchase invoice</span></span>
1. <span data-ttu-id="09ffd-114">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **bókaðir innkaupareikningar** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="09ffd-114">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Posted Purchase Invoices**, and then choose the related link.</span></span>  
2. <span data-ttu-id="09ffd-115">Veljið bókaða innkaupareikninginn sem á að leiðrétta.</span><span class="sxs-lookup"><span data-stu-id="09ffd-115">Select the posted purchase invoice that you want to correct.</span></span>  

    > [!NOTE]  
>   <span data-ttu-id="09ffd-116">Ef gátreiturinn **Hætta við** er valinn, er ekki hægt að leiðrétta þennan bókaða sölureikning þar sem hann hefur þegar verið leiðréttur eða afturkallaður.</span><span class="sxs-lookup"><span data-stu-id="09ffd-116">If the **Canceled** check box is selected, then you cannot correct the posted purchase invoice because it has already been corrected or canceled.</span></span>
3. <span data-ttu-id="09ffd-117">Í glugganum **Bókaður innkaupareikningur** skal velja **Rétt**.</span><span class="sxs-lookup"><span data-stu-id="09ffd-117">In the **Posted Purchase Invoice** window, choose **Correct**.</span></span>

    <span data-ttu-id="09ffd-118">Nýr sölureikningur með sömu upplýsingum er stofnaður þar sem hægt er að gera leiðréttinguna.</span><span class="sxs-lookup"><span data-stu-id="09ffd-118">A new purchase invoice with the same information is created where you can make the correction.</span></span> <span data-ttu-id="09ffd-119">Nánari upplýsingar eru í [Hvernig á að: Skrá innkaup](purchasing-how-record-purchases.md).</span><span class="sxs-lookup"><span data-stu-id="09ffd-119">For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).</span></span> <span data-ttu-id="09ffd-120">Reiturinn **Hætt við** á hinum upphaflega bókaða sölureikningi er breytt í **Já**.</span><span class="sxs-lookup"><span data-stu-id="09ffd-120">The **Canceled** field on the initial posted purchase invoice is changed to **Yes**.</span></span>

    <span data-ttu-id="09ffd-121">Leiðréttur sölukreditreikningur er búinn til sjálfkrafa og bókaður til að ógilda upphaflega bókaða sölureikninginn.</span><span class="sxs-lookup"><span data-stu-id="09ffd-121">A purchase credit memo is automatically created and posted to void the initial posted purchase invoice.</span></span>
4. <span data-ttu-id="09ffd-122">Veljið **Sýna leiðréttan kreditreikning** til að skoða bókaða sölukreditreikninginn sem ógildir upphaflega bókaða sölureikninginn.</span><span class="sxs-lookup"><span data-stu-id="09ffd-122">Choose **Show Corrective Credit Memo** to view the posted purchase credit memo that voids the initial posted purchase invoice.</span></span>

## <a name="to-cancel-a-posted-purchase-invoice"></a><span data-ttu-id="09ffd-123">Til að afturkalla bókaðan innkaupareikning.</span><span class="sxs-lookup"><span data-stu-id="09ffd-123">To cancel a posted purchase invoice</span></span>
1. <span data-ttu-id="09ffd-124">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **bókaðir innkaupareikningar** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="09ffd-124">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Posted Purchase Invoices**, and then choose the related link.</span></span>  
2. <span data-ttu-id="09ffd-125">Veljið bókaða innkaupareikninginn sem á að afturkalla.</span><span class="sxs-lookup"><span data-stu-id="09ffd-125">Select the posted purchase invoice that you want to cancel.</span></span>

    > [!NOTE]  
>   <span data-ttu-id="09ffd-126">Ef gátreiturinn **Afturkalla** er valinn, er ekki hægt að afturkalla þennan bókaða sölureikning þar sem hann hefur þegar verið leiðréttur eða afturkallaður.</span><span class="sxs-lookup"><span data-stu-id="09ffd-126">If the **Canceled** check box is selected, then you cannot cancel the posted purchase invoice because it has already been canceled or corrected.</span></span>
3. <span data-ttu-id="09ffd-127">Í glugganum **Bókaður innkaupareikningur** skal velja **Afturkalla**.</span><span class="sxs-lookup"><span data-stu-id="09ffd-127">In the **Posted Purchase Invoice** window, choose **Cancel**.</span></span>

    <span data-ttu-id="09ffd-128">Leiðréttur sölukreditreikningur er búinn til sjálfkrafa og bókaður til að ógilda upphaflega bókaða sölureikninginn.</span><span class="sxs-lookup"><span data-stu-id="09ffd-128">A purchase credit memo is automatically created and posted to void the initial posted purchase invoice.</span></span> <span data-ttu-id="09ffd-129">Reiturinn **Hætt við** á hinum upphaflega bókaða sölureikningi er breytt í **Já**.</span><span class="sxs-lookup"><span data-stu-id="09ffd-129">The **Canceled** field on the initial posted purchase invoice is changed to **Yes**.</span></span>
4. <span data-ttu-id="09ffd-130">Veljið **Sýna leiðréttan kreditreikning** til að skoða bókaða sölukreditreikninginn sem ógildir upphaflega bókaða sölureikninginn.</span><span class="sxs-lookup"><span data-stu-id="09ffd-130">Choose **Show Corrective Credit Memo** to view the posted purchase credit memo that voids the initial posted purchase invoice.</span></span>

## <a name="see-also"></a><span data-ttu-id="09ffd-131">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="09ffd-131">See Also</span></span>
[<span data-ttu-id="09ffd-132">Innkaup</span><span class="sxs-lookup"><span data-stu-id="09ffd-132">Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="09ffd-133">Hvernig á að skrá kaup</span><span class="sxs-lookup"><span data-stu-id="09ffd-133">How to: Record Purchases</span></span>](purchasing-how-record-purchases.md)  
<span data-ttu-id="09ffd-134">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="09ffd-134">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
