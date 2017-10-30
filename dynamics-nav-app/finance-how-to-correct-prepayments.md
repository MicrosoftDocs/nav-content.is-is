---
title: "Hvernig á að leiðrétta fyrirframgreiðslu"
description: "Hægt er að gera leiðréttingu á pöntun eftir að búið er að bóka fyrirframgreiðslureikning fyrir pöntunina. Hægt er að bæta nýjum línum við pöntun eftir að búið er að senda fyrirframgreiðslu og bóka síðan annan fyrirframgreiddan reikning en ekki er unnt að eyða línu í pöntun eftir fyrirframgreiðsla hefur verið reikningsfærð fyrir línu."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/04/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: c39223940880514f9a59eae96e88182e19db2b5e
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-correct-prepayments"></a><span data-ttu-id="a6c2d-104">Hvernig á að leiðrétta fyrirframgreiðslu</span><span class="sxs-lookup"><span data-stu-id="a6c2d-104">How to: Correct Prepayments</span></span>
<span data-ttu-id="a6c2d-105">Hægt er að gera leiðréttingu á pöntun eftir að búið er að bóka fyrirframgreiðslureikning fyrir pöntunina.</span><span class="sxs-lookup"><span data-stu-id="a6c2d-105">You can make a correction to an order after you have posted a prepayment invoice for the order.</span></span> <span data-ttu-id="a6c2d-106">Hægt er að bæta nýjum línum við pöntun eftir að búið er að senda fyrirframgreiðslu og bóka síðan annan fyrirframgreiddan reikning en ekki er unnt að eyða línu í pöntun eftir fyrirframgreiðsla hefur verið reikningsfærð fyrir línu.</span><span class="sxs-lookup"><span data-stu-id="a6c2d-106">You can add new lines to an order after issuing a prepayment, and then you can post another prepayment invoice, but you cannot delete a line from an order after a prepayment has been invoiced for the line.</span></span>  

## <a name="to-correct-a-prepayment"></a><span data-ttu-id="a6c2d-107">Til að leiðrétta fyrirframgreiðslu:</span><span class="sxs-lookup"><span data-stu-id="a6c2d-107">To correct a prepayment</span></span>
<span data-ttu-id="a6c2d-108">Eftirfarandi ferli sýnir hvernig gefa skal út kreditreikning fyrirframgreiðslu til að afturkalla allar reikningsfærðar fyrirframgreiðslur fyrir sölupöntun.</span><span class="sxs-lookup"><span data-stu-id="a6c2d-108">The following procedure shows how to issue a prepayment credit memo to cancel all invoiced prepayments for a sales order.</span></span>  
1. <span data-ttu-id="a6c2d-109">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Sölupantanir** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="a6c2d-109">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales Orders**, and then choose the related link.</span></span>  
2. <span data-ttu-id="a6c2d-110">Viðeigandi sölupöntun er opnuð.</span><span class="sxs-lookup"><span data-stu-id="a6c2d-110">Open the relevant sales order.</span></span>
3. <span data-ttu-id="a6c2d-111">Veljið aðgerðina **Fyrirframgreiðsla** og síðan aðgerðina **Bóka kreditreikning fyrirframgreiðslu** eða **Bóka og prenta kr.reikn. fyrirframgr.** aðgerðina.</span><span class="sxs-lookup"><span data-stu-id="a6c2d-111">Choose the **Prepayment** action, and then choose the **Post Prepayment Credit Memo** action or the **Post and Print Prepmt. Cr. Memo** action.</span></span>  
4. <span data-ttu-id="a6c2d-112">Í glugganum **Kreditreikningur sölu** skal farið í leiðréttingu viðeigandi færslna, sem og alla kreditreikninga sölu.</span><span class="sxs-lookup"><span data-stu-id="a6c2d-112">In the **Sales Credit Memo** window, proceed to correct the relevant entries, as for any sales credit memo.</span></span> <span data-ttu-id="a6c2d-113">Fyrir frekar upplýsingar, sjá [hvernig á að: Meðhöndlun söluvöruskila eða afturkallana](sales-how-process-sales-returns-cancellations.md)</span><span class="sxs-lookup"><span data-stu-id="a6c2d-113">For more information, see [How to: Process Sales Returns or Cancellations](sales-how-process-sales-returns-cancellations.md).</span></span>     

    > [!NOTE]  
    > <span data-ttu-id="a6c2d-114">Til að lækka upphæðina í reitnum **Upphæð línu**, verður fyrst að auka fyrirframgreiðsluprósentuna í línunni svo gildið í reitnum **fyrirfrgr. línuupphæð** sé ekki lækkuð niður fyrir gildið í reitnum **fyrirfrg. reikningsupphæð**.</span><span class="sxs-lookup"><span data-stu-id="a6c2d-114">To Reduce the amount in the **Line Amount** field, you must first increase the prepayment percentage on the line so that the value in the **Prepmt. Line Amount** field is not decreased below the value in the **Prepmt. Amt. Inv.** field.</span></span>

5. <span data-ttu-id="a6c2d-115">Til að gera fyrirframgreiðslureikning fyrir nýjar línur í sölukreditreikningi, veljið aðgerðina **Fyrirframgreiðsla** og síðan aðgerðina **Bóka reikning fyrirframgreiðslu** eða **Bóka og prenta reikn. fyrirframgr.** aðgerðina.</span><span class="sxs-lookup"><span data-stu-id="a6c2d-115">To make a prepayment invoice for any new lines in the sales credit memo, choose the **Prepayment** action, and then choose the **Post Prepayment Invoice** action or the **Post and Print Prepmt. Invoice** action.</span></span>  
6. <span data-ttu-id="a6c2d-116">Til að gefa út auka fyrirframgreiðslureikning, skal hækka upphæð fyrirframgreiðslu í einni eða fleiri línum og bóka fyrirframgreiðslureikninginn.</span><span class="sxs-lookup"><span data-stu-id="a6c2d-116">To issue an additional prepayment invoice, increase the prepayment amount on one or more lines and post the prepayment invoice.</span></span> <span data-ttu-id="a6c2d-117">Nýr reikningur er stofnaður fyrir mismuninn á milli reikningsfærðra upphæða fyrirframgreiðslu og nýju fyrirframgreiðsluupphæðanna.</span><span class="sxs-lookup"><span data-stu-id="a6c2d-117">A new invoice will be created for the difference between the prepayment amounts invoiced and the new prepayment amounts.</span></span>  

## <a name="see-also"></a><span data-ttu-id="a6c2d-118">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="a6c2d-118">See Also</span></span>  
[<span data-ttu-id="a6c2d-119">Reikningsfærsla fyrirframgreiðslna</span><span class="sxs-lookup"><span data-stu-id="a6c2d-119">Invoicing Prepayments</span></span>](finance-invoice-prepayments.md)  
[<span data-ttu-id="a6c2d-120">Kynning: Uppsetning og reikningsfærsla fyrirframgreiðslna fyrir sölu</span><span class="sxs-lookup"><span data-stu-id="a6c2d-120">Walkthrough: Setting Up and Invoicing Sales Prepayments</span></span>](walkthrough-setting-up-and-invoicing-sales-prepayments.md)  
[<span data-ttu-id="a6c2d-121">Fjármál</span><span class="sxs-lookup"><span data-stu-id="a6c2d-121">Finance</span></span>](finance.md)  
<span data-ttu-id="a6c2d-122">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="a6c2d-122">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
