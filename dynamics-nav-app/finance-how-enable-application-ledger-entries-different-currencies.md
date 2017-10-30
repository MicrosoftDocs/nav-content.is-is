---
title: "Jafna færslur í mismunandi gjaldmiðlum"
description: "Ef viðskiptamaður selur t.d. í einum gjaldmiðli og fær greitt í öðrum er hægt að jafna fjárhagsfærsluna í mismunandi gjaldmiðlum."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: multiple currencies, payment, reconcile
ms.date: 06/02/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: f323b98472f3e2ef0f28000f8a9140b066206945
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-enable-application-of-ledger-entries-in-different-currencies"></a><span data-ttu-id="560bb-103">Hvernig á að: Leyfa jöfnun fjárhagsfærslna í mismunandi gjaldmiðlum</span><span class="sxs-lookup"><span data-stu-id="560bb-103">How to: Enable Application of Ledger Entries in Different Currencies</span></span>
<span data-ttu-id="560bb-104">Ef keypt er af lánardrottni í einum gjaldmiðli og greitt í öðrum gjaldmiðli er hægt að jafna greiðsluna innkaupunum.</span><span class="sxs-lookup"><span data-stu-id="560bb-104">If you purchase from a vendor in one currency and submit payment in another currency, you can apply the payment to the purchase.</span></span>

<span data-ttu-id="560bb-105">Á sama hátt, kaupi viðskiptamaður í einum gjaldmiðli og greiði í öðrum er hægt að jafna greiðsluna við sölureikninginn.</span><span class="sxs-lookup"><span data-stu-id="560bb-105">Likewise, if you sell to a customer in one currency and receive payment in another currency, you can apply the payment to the sales invoice.</span></span>

<span data-ttu-id="560bb-106">Eftirfarandi ferli sýnir hvernig á að setja þetta upp fyrir lánardrottnafærslur í glugganum **Uppsetning innkaupa og viðskiptaskulda**.</span><span class="sxs-lookup"><span data-stu-id="560bb-106">The following procedure describes how to set this up for vendor ledger entries in the **Purchases & Payables Setup** window.</span></span> <span data-ttu-id="560bb-107">Uppsetningin er svipuð og færslur í viðskiptamannabók í glugganum **Uppsetning sölu og viðskiptakrafna**.</span><span class="sxs-lookup"><span data-stu-id="560bb-107">The setup is similar for customer ledger entries in the **Sales & Receivables Setup** window.</span></span>

## <a name="to-enable-application-of-vendor-ledger-entries-in-different-currencies"></a><span data-ttu-id="560bb-108">Til að virkja jöfnun lánardrottnafærslna í mismunandi gjaldmiðlum</span><span class="sxs-lookup"><span data-stu-id="560bb-108">To enable application of vendor ledger entries in different currencies</span></span>
1. <span data-ttu-id="560bb-109">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Uppsetning innkaupa og viðskiptaskulda** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="560bb-109">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Purchases & Payables Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="560bb-110">Í reitnum **Jöfnun milli gjaldmiðla** skal velja einn eftirtalinna valkosta.</span><span class="sxs-lookup"><span data-stu-id="560bb-110">In the **Appln. between Currencies** field, select one of the following options.</span></span>

| <span data-ttu-id="560bb-111">Valkostur</span><span class="sxs-lookup"><span data-stu-id="560bb-111">Option</span></span> | <span data-ttu-id="560bb-112">Lýsing</span><span class="sxs-lookup"><span data-stu-id="560bb-112">Description</span></span> |
| --- | --- |
| <span data-ttu-id="560bb-113">Engin</span><span class="sxs-lookup"><span data-stu-id="560bb-113">None</span></span> |<span data-ttu-id="560bb-114">Jöfnun milli gjaldmiðla er ekki leyfð.</span><span class="sxs-lookup"><span data-stu-id="560bb-114">Application between currencies is not allowed.</span></span> |
| <span data-ttu-id="560bb-115">EMU</span><span class="sxs-lookup"><span data-stu-id="560bb-115">EMU</span></span> |<span data-ttu-id="560bb-116">Jöfnun milli EMU-gjaldmiðla er leyfð.</span><span class="sxs-lookup"><span data-stu-id="560bb-116">Application between EMU currencies is allowed.</span></span> |
| <span data-ttu-id="560bb-117">Allt</span><span class="sxs-lookup"><span data-stu-id="560bb-117">All</span></span> |<span data-ttu-id="560bb-118">Jöfnun milli allra gjaldmiðla er leyfð.</span><span class="sxs-lookup"><span data-stu-id="560bb-118">Application between all currencies is allowed.</span></span> |

## <a name="to-set-up-gl-accounts-for-currency-application-rounding-differences"></a><span data-ttu-id="560bb-119">Uppsetning fjárhagsreikninga fyrir gjaldmiðilsaðgerð sléttunarmismunar</span><span class="sxs-lookup"><span data-stu-id="560bb-119">To set up G/L accounts for currency application rounding differences</span></span>  
<span data-ttu-id="560bb-120">Eigi að jafna færslur í mismunandi gjaldmiðlum þarf að setja upp fjárhagsreikninga þar sem á að bóka sléttunarmismun.</span><span class="sxs-lookup"><span data-stu-id="560bb-120">If you apply entries in different currencies, you must set up the general ledger accounts to which you want to post rounding differences.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="560bb-121">Setja verður upp fjárhagsreikningana áður en lokið er við verkið.</span><span class="sxs-lookup"><span data-stu-id="560bb-121">You must set up the general ledger accounts before you complete the task.</span></span> <span data-ttu-id="560bb-122">Frekari upplýsingar er að finna í [Að skilja fjárhag og bókhaldslykla](finance-general-ledger.md).</span><span class="sxs-lookup"><span data-stu-id="560bb-122">For more information, see [Understanding the General Ledger and the Chart of Accounts](finance-general-ledger.md).</span></span>

1. <span data-ttu-id="560bb-123">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Bókunarflokkar viðskiptamanns** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="560bb-123">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Customer Posting Groups**, and then choose the related link.</span></span>  
2. <span data-ttu-id="560bb-124">Í reitunum **Debet gjaldm.jöfn.slétt.reikn** og **Kreditreikn. gjaldeyrisjöfn.** er fært inn viðkomandi fjárhagsreikningsnúmer til að bóka sléttunarmismun.</span><span class="sxs-lookup"><span data-stu-id="560bb-124">In the **Debit Curr. Appln. Rndg. Acc.** and **Credit Curr. Appln. Rndg. Acc.** fields, enter the relevant general ledger accounts to post rounding differences.</span></span>  
3. <span data-ttu-id="560bb-125">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Bókunarflokkar lánardrottna** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="560bb-125">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Vendor Posting Groups**, and then choose the related link.</span></span>  
4. <span data-ttu-id="560bb-126">Í reitunum **Debet gjaldm.jöfn.slétt.reikn** og **Kreditreikn. gjaldeyrisjöfn.** er fært inn viðkomandi fjárhagsreikningsnúmer til að bóka sléttunarmismun.</span><span class="sxs-lookup"><span data-stu-id="560bb-126">In the **Debit Curr. Appln. Rndg. Acc.** and **Credit Curr. Appln. Rndg. Acc.** fields, enter the relevant general ledger accounts to post rounding differences.</span></span>  

## <a name="see-also"></a><span data-ttu-id="560bb-127">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="560bb-127">See Also</span></span>
[<span data-ttu-id="560bb-128">Stjórna skuldum</span><span class="sxs-lookup"><span data-stu-id="560bb-128">Managing Payables</span></span>](payables-manage-payables.md)  
[<span data-ttu-id="560bb-129">Stjórnun skulda</span><span class="sxs-lookup"><span data-stu-id="560bb-129">Managing Receivables</span></span>](receivables-manage-receivables.md)  
<span data-ttu-id="560bb-130">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="560bb-130">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
