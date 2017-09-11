---
title: "Hvernig á að: Vinna með verkefnisbirgðir"
author: SorenGP
ms.custom: na
ms.date: 11/01/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 00b9ed8480f6b5ab9265beb0fe2dc0060b1c3192
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-manage-job-supplies"></a><span data-ttu-id="6aced-102">Hvernig á að: Vinna með verkbirgðir</span><span class="sxs-lookup"><span data-stu-id="6aced-102">How to: Manage Job Supplies</span></span>
<span data-ttu-id="6aced-103">Það er mikilvægur og óaðskiljanlegur hluti af framkvæmd allra verka að hafa umsjón með framboði á vöru, þjónustu og útgjöldum.</span><span class="sxs-lookup"><span data-stu-id="6aced-103">Managing project supplies of items, services, and expenses is an integral and critical aspect of the execution of all jobs.</span></span> <span data-ttu-id="6aced-104">Nota má birgðamagn eða gera verktengd innkaup með innkaupapöntunum og/eða innkaupareikningum.</span><span class="sxs-lookup"><span data-stu-id="6aced-104">You can use inventory quantities or make job-specific purchases using purchase orders or purchase invoices.</span></span> <span data-ttu-id="6aced-105">Sem dæmi má nefna þjónustuverk á tölvu sem krefst þess að nýr diskur sé keyptur.</span><span class="sxs-lookup"><span data-stu-id="6aced-105">For example, a service job on a computer requires a new disk.</span></span> <span data-ttu-id="6aced-106">Þá er búinn til innkaupareikningur til kaupa á nýjum diski og verkið, sem nota á diskinn í, er skráð.</span><span class="sxs-lookup"><span data-stu-id="6aced-106">You create a purchase invoice to buy a new disk and record the job that it will be used on.</span></span>

<span data-ttu-id="6aced-107">Ef innkaupavinnslan krefst þess ekki að efnislegu viðskiptin séu skráð sérstaklega er hægt að vinna innkaup í glugganum **Fjárhagsbók verks**.</span><span class="sxs-lookup"><span data-stu-id="6aced-107">If the purchase process does not require that the physical transaction be recorded separately, then a purchase may be processed in the **Job G/L Journal** window.</span></span> <span data-ttu-id="6aced-108">Nánari upplýsingar eru í [Hvernig á að: Skrá notkun vegna verka](projects-how-record-job-usage.md).</span><span class="sxs-lookup"><span data-stu-id="6aced-108">For more information, see [How to: Record Usage for Jobs](projects-how-record-job-usage.md).</span></span>

## <a name="to-purchase-items-or-services-for-a-job"></a><span data-ttu-id="6aced-109">Að kaupa vörur eða þjónustu fyrir verk</span><span class="sxs-lookup"><span data-stu-id="6aced-109">To purchase items or services for a job</span></span>
<span data-ttu-id="6aced-110">Eftirfarandi ferli sýnir hvernig á að nota innkaupareikning til að kaupa vörur fyrir verk.</span><span class="sxs-lookup"><span data-stu-id="6aced-110">The following procedure shows how to use a purchase invoice to purchase products for a job.</span></span> <span data-ttu-id="6aced-111">Sömu skref eiga við þegar innkaupapöntun er notuð.</span><span class="sxs-lookup"><span data-stu-id="6aced-111">The same steps apply when using a purchase order.</span></span>  

1. <span data-ttu-id="6aced-112">Í efra hægri horni skal velja táknið **Leita að síðu eða skýrslu** ,slá inn **Innkaupareikningar**, og velja síðan viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="6aced-112">In the top right corner, choose the **Search for Page or Report** icon, enter **Purchase Invoices**, and then choose the related link.</span></span>  
2. <span data-ttu-id="6aced-113">Veljið aðgerðina **Nýtt** og fyllið svo út reitina eins og þörf krefur.</span><span class="sxs-lookup"><span data-stu-id="6aced-113">Choose the **New** action and fill in the fields as necessary.</span></span> <span data-ttu-id="6aced-114">Nánari upplýsingar eru í [Hvernig á að: Skrá innkaup](purchasing-how-record-purchases.md).</span><span class="sxs-lookup"><span data-stu-id="6aced-114">For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).</span></span>
3. <span data-ttu-id="6aced-115">Í reitina **Verknr.**</span><span class="sxs-lookup"><span data-stu-id="6aced-115">In the **Job No.**</span></span> <span data-ttu-id="6aced-116">og **Verkhlutanr.**</span><span class="sxs-lookup"><span data-stu-id="6aced-116">and **Job Task No.**</span></span> <span data-ttu-id="6aced-117">skal velja þær upplýsingar um verkið sem kaupa skal vörur eða þjónustu vegna.</span><span class="sxs-lookup"><span data-stu-id="6aced-117">fields, select the information of the job that you want to purchase items or services for.</span></span>  

    <span data-ttu-id="6aced-118">Gildið sem valið er í reitnum **Verklínutegund** skilgreinir hvort búin sé til áætlunarlína þegar notkun vörunnar er bókuð.</span><span class="sxs-lookup"><span data-stu-id="6aced-118">The value that you select in the **Job Line Type** field defines whether a planning line is created when you post the usage of the item.</span></span> <span data-ttu-id="6aced-119">Ef reiturinn inniheldur **Reikningshæft** eru stofnaðar áætlunarlínur sem eru tilbúnar til að vera reikningsfærðar til viðskiptavinar.</span><span class="sxs-lookup"><span data-stu-id="6aced-119">If the field contains **Billable**, then job planning lines that are ready to be invoiced to the customer are created.</span></span> <span data-ttu-id="6aced-120">Nánari upplýsingar eru í [Hvernig á að: Reikningsfæra verk](projects-how-invoice-jobs.md).</span><span class="sxs-lookup"><span data-stu-id="6aced-120">For more information, see [How to: Invoice Jobs](projects-how-invoice-jobs.md).</span></span>

4. <span data-ttu-id="6aced-121">Valið er **bóka** aðgerð.</span><span class="sxs-lookup"><span data-stu-id="6aced-121">Choose the **Post** action.</span></span>

## <a name="to-view-the-value-of-purchases-for-a-job"></a><span data-ttu-id="6aced-122">Til að skoða virði innkaupa fyrir verk</span><span class="sxs-lookup"><span data-stu-id="6aced-122">To view the value of purchases for a job</span></span>  

1. <span data-ttu-id="6aced-123">Uppi í hægra horninu skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Verk** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="6aced-123">In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link.</span></span>
2. <span data-ttu-id="6aced-124">Opnið viðeigandi verkspjald.</span><span class="sxs-lookup"><span data-stu-id="6aced-124">Open a relevant job card.</span></span>

    <span data-ttu-id="6aced-125">Á flýtiflipanum **Verkhlutar** sýnir reiturinn **Óafgreiddar pantanir** útistandandi upphæð í staðbundnum gjaldmiðli fyrir vörur í birgðaskrá og þjónustu á innkaupaskjöl fyrir verkhlutalínuna.</span><span class="sxs-lookup"><span data-stu-id="6aced-125">On the **Tasks** FastTab, the **Outstanding Orders** field shows the total outstanding amount, in local currency, of inventory items and services on purchase documents for the job task line.</span></span>  

    <span data-ttu-id="6aced-126">Reiturinn **Afh. upph. óreikn.færð** sýnir virði vara sem afhentra vara í innkaupaskjölum sem ekki hafa verið reikningsfærðar enn.</span><span class="sxs-lookup"><span data-stu-id="6aced-126">The **Amt. Rec. Not Invoiced** field shows the value of items delivered on purchase documents, but not yet invoiced.</span></span>  

3. <span data-ttu-id="6aced-127">Veljið annan hvorn reitinn til að opna í glugganum **Innkaupalínur** þar sem hægt er að fara yfir upplýsingar um línur í tengdum innkaupaskjölum, þ.m.t. hvaða vörum eða þjónustu hefur verið tekið við.</span><span class="sxs-lookup"><span data-stu-id="6aced-127">Choose either of the fields to open the **Purchase Lines** window where you can review information about the related purchase document lines, including which items or services have been received.</span></span>

## <a name="to-post-a-job-related-expense"></a><span data-ttu-id="6aced-128">Til að bóka verktengdan kostnað</span><span class="sxs-lookup"><span data-stu-id="6aced-128">To post a job-related expense</span></span>  
<span data-ttu-id="6aced-129">Ef um óeðlileg útgjöld eða einstök útgjöld er að ræða vegna verks er hægt að nota gluggann **Fjárhagsbók verks** til að bóka slíkt beint á reikning viðeigandi verks.</span><span class="sxs-lookup"><span data-stu-id="6aced-129">If you incur extraordinary or one-time job expenses, you can use the **Job G/L Journal** window to post them directly to the relevant job account.</span></span>

1. <span data-ttu-id="6aced-130">Uppi í hægra horninu skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Fjárhagsbækur verks** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="6aced-130">In the top right corner, choose the **Search for Page or Report** icon, enter **Job G/L Journals**, and then choose the related link.</span></span>  
2. <span data-ttu-id="6aced-131">Búa skal til nýja línu og slá inn upplýsingar um útgjöldin, þ.m.t. upplýsingar í reitina **Verknr.**</span><span class="sxs-lookup"><span data-stu-id="6aced-131">Create a new line and enter information about the expense, including information in the **Job No.**</span></span> <span data-ttu-id="6aced-132">og **Verkhlutanr.**</span><span class="sxs-lookup"><span data-stu-id="6aced-132">and **Job Task No** fields.</span></span>  
3. <span data-ttu-id="6aced-133">Þegar færslubókin er tilbúin skal velja aðgerðina **Bóka**.</span><span class="sxs-lookup"><span data-stu-id="6aced-133">When the journal is complete, choose the **Post** action.</span></span>


## <a name="see-also"></a><span data-ttu-id="6aced-134">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="6aced-134">See Also</span></span>
[<span data-ttu-id="6aced-135">Unnið með verkefni</span><span class="sxs-lookup"><span data-stu-id="6aced-135">Manage Projects</span></span>](projects-manage-projects.md)  
[<span data-ttu-id="6aced-136">Fjármál</span><span class="sxs-lookup"><span data-stu-id="6aced-136">Finance</span></span>](finance-setup.md)  
<span data-ttu-id="6aced-137">[Stjórnun innkaupa](purchasing-manage-purchasing.md)       </span><span class="sxs-lookup"><span data-stu-id="6aced-137">[Manage Purchasing](purchasing-manage-purchasing.md)       </span></span>  
<span data-ttu-id="6aced-138">[Stjórna sölu](sales-manage-sales.md)    </span><span class="sxs-lookup"><span data-stu-id="6aced-138">[Manage Sales](sales-manage-sales.md)    </span></span>  
[<span data-ttu-id="6aced-139">Unnið með Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="6aced-139">Work With Dynamics NAV</span></span>](ui-work-product.md)  

