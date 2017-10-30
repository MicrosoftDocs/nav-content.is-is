---
title: "Greina gögn eftir víddum"
description: "Lýsir því hvernig skal greina ýmis viðskiptagögn eftir víddum."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: bi, power BI, analysis, KPI
ms.date: 06/13/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 2ea54861f8203406cf6c9d110ad2317b8f883dde
ms.contentlocale: is-is
ms.lasthandoff: 10/23/2017

---
#  <a name="how-to-analyze-data-by-dimensions"></a><span data-ttu-id="c9946-103">Hvernig skal: Greina gögn eftir víddum</span><span class="sxs-lookup"><span data-stu-id="c9946-103">How to: Analyze Data by Dimensions</span></span>
<span data-ttu-id="c9946-104">Í fjárhagsgreiningu er vídd tiltekin gögn sem má bæta við færslu sem einskonar merki.</span><span class="sxs-lookup"><span data-stu-id="c9946-104">In financial analysis, a dimension is data that you can add to an entry as a kind of marker.</span></span> <span data-ttu-id="c9946-105">Þessi gögn eru notuð til að flokka saman færslur með svipuð einkenni, eins og viðskiptamenn, svæði, vörur og sölumenn og sækja þessa hópa á auðveldan hátt til greiningar.</span><span class="sxs-lookup"><span data-stu-id="c9946-105">This data is used to group entries with similar characteristics, such as customers, regions, products, and salesperson, and easily retrieve these groups for analysis.</span></span> <span data-ttu-id="c9946-106">Víddir má nota fyrir færslur í færslubókum, skjölum og fjárhagsáætlunum.</span><span class="sxs-lookup"><span data-stu-id="c9946-106">Dimensions can be used on entries in journals, documents, and budgets.</span></span> <span data-ttu-id="c9946-107">Heitið vídd lýsir því hvernig greiningin fer fram.</span><span class="sxs-lookup"><span data-stu-id="c9946-107">The term dimension describes how analysis occurs.</span></span> <span data-ttu-id="c9946-108">Tvívíð greining gæti til dæmis verið sala eftir svæðum.</span><span class="sxs-lookup"><span data-stu-id="c9946-108">A two-dimensional analysis, for example, would be sales per area.</span></span> <span data-ttu-id="c9946-109">Hins vegar er hægt að framkvæma flóknari greiningar með því að nota fleiri en tvær víddir þegar færsla er stofnuð, til dæmis sölu á hverja söluherferð, hvern viðskiptamann á hverju svæði.</span><span class="sxs-lookup"><span data-stu-id="c9946-109">However, by using more than two dimensions when creating an entry, you can carry out a more complex analysis, such as sales per sales campaign per customer group per area.</span></span> <span data-ttu-id="c9946-110">Frekari upplýsingar er að finna í [Unnið með víddir](finance-dimensions.md).</span><span class="sxs-lookup"><span data-stu-id="c9946-110">For more information, see [Working with Dimensions](finance-dimensions.md).</span></span>

<span data-ttu-id="c9946-111">Gagnagreining með víddum gefur meiri innsýn í viðskiptin fyrir mat á upplýsingum, t.d. hversu vel fyrirtækið starfar, hvar því gengur vel eða illa og hvar ætti að ráðstafa meiri forða.</span><span class="sxs-lookup"><span data-stu-id="c9946-111">Analyzing data by dimensions gives you greater insight into your business, so you can evaluate information, such as how well your business is operating, where it is thriving and where it is not, and where more resources should be allocated.</span></span>

> [!TIP]
> <span data-ttu-id="c9946-112">Hægt er að greina færslugögn út frá víddum á skjótan hátt með því að afmarka samtölur á bókhaldslyklum og færslum í öllum **Færslur** gluggum út frá víddum.</span><span class="sxs-lookup"><span data-stu-id="c9946-112">As a quick way to analyze transactional data by dimensions, you can filter totals in the chart of accounts and entries in all **Entries** windows by dimensions.</span></span> <span data-ttu-id="c9946-113">Leitaðu að aðgerðinni **Stilla víddarafmörkun**.</span><span class="sxs-lookup"><span data-stu-id="c9946-113">Look for the **Set Dimension Filter** action.</span></span>

## <a name="to-set-up-an-analysis-view"></a><span data-ttu-id="c9946-114">Að setja upp greiningaryfirlit</span><span class="sxs-lookup"><span data-stu-id="c9946-114">To set up an analysis view</span></span>  
<span data-ttu-id="c9946-115">Greining eftir víddum sýnir valda samsetningu vídda.</span><span class="sxs-lookup"><span data-stu-id="c9946-115">An analysis by dimensions displays a selected combination of dimensions.</span></span> <span data-ttu-id="c9946-116">Hægt er að geyma og sækja hverja greiningu sem sett hefur verið upp.</span><span class="sxs-lookup"><span data-stu-id="c9946-116">You can store and retrieve each analysis you have set up.</span></span> <span data-ttu-id="c9946-117">Upplýsingar um uppsetningu greiningar eru geymdar í **greiningaryfirlit** spjaldi til að einfalda greiningu seinna.</span><span class="sxs-lookup"><span data-stu-id="c9946-117">The information for setting up an analysis is stored on an **Analysis View** card to simplify future analysis.</span></span>  

1. <span data-ttu-id="c9946-118">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **greiningaryfirlit** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="c9946-118">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Analysis Views**, and then choose the related link.</span></span>  
2. <span data-ttu-id="c9946-119">Í glugganum **Listi yfir greiningaryfirlit** skal velja aðgerðina **Nýtt**.</span><span class="sxs-lookup"><span data-stu-id="c9946-119">In the **Analysis View List** window, choose the **New** action.</span></span>
3. <span data-ttu-id="c9946-120">Fyllið inn í reitina eftir þörfum.</span><span class="sxs-lookup"><span data-stu-id="c9946-120">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4. <span data-ttu-id="c9946-121">Til að bæta öðrum víddarkóðum við þá fjóra sem fyrir eru á flýtiflipanum **Víddir** er aðgerðin **Afmörkun** valin, reitirnir fylltir út og síðan er smellt á **Í lagi** hnappinn.</span><span class="sxs-lookup"><span data-stu-id="c9946-121">To add other dimension codes in addition to the four on the **Dimensions** FastTab, choose the **Filter** action, fill in the fields, and then choose the **OK** button.</span></span>  
5. <span data-ttu-id="c9946-122">Til að uppfæra yfirlitið er valin aðgerðin **Uppfæra**.</span><span class="sxs-lookup"><span data-stu-id="c9946-122">To update the view, choose the **Update** action.</span></span>

## <a name="to-analyze-by-dimensions"></a><span data-ttu-id="c9946-123">Að greina eftir víddum</span><span class="sxs-lookup"><span data-stu-id="c9946-123">To analyze by dimensions</span></span>
<span data-ttu-id="c9946-124">Hægt er að nota fylkið **Greining eftir víddum** til að skoða upphæðirnar í fjárhag með því að nota greiningaryfirlitin sem þegar eru uppsett.</span><span class="sxs-lookup"><span data-stu-id="c9946-124">You can use the **Analysis by Dimensions** matrix to view the amounts in your general ledger by using the analysis views that you have already set up.</span></span> <span data-ttu-id="c9946-125">Fyllt er í gluggann **Greining eftir víddum** til að skilgreina hvað fylkið sýnir og síðan er valin aðgerðin **Sýna fylki** til að skoða fylkið.</span><span class="sxs-lookup"><span data-stu-id="c9946-125">You fill in the **Analysis by Dimensions** window to define what will be shown in the matrix, and then you choose the **Show Matrix** action to view the matrix.</span></span>  

- <span data-ttu-id="c9946-126">Í dálkunum til vinstri eru upplýsingar byggðar á því sem valið er í reitnum **Sýna sem línur** í hausnum.</span><span class="sxs-lookup"><span data-stu-id="c9946-126">The leftmost columns contain information based on what you have selected in the **Show as Lines** field in the header.</span></span>  
- <span data-ttu-id="c9946-127">Í dálkunum lengst til hægri eru upplýsingar byggðar á því sem valið er í reitnum **Sýna sem dálka** í hausnum.</span><span class="sxs-lookup"><span data-stu-id="c9946-127">The rightmost columns contain information based on to what you have selected in the **Show as Columns** field in the header.</span></span>  

1. <span data-ttu-id="c9946-128">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Greining eftir víddum** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="c9946-128">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Analysis by Dimensions**, and then choose the related link.</span></span>  
2. <span data-ttu-id="c9946-129">Velja skal viðeigandi greiningaryfirlit og velja síðan aðgerðina **Breyta greiningaryfirliti**.</span><span class="sxs-lookup"><span data-stu-id="c9946-129">Select the relevant analysis view,  and then choose the **Edit Analysis View** action.</span></span>
3. <span data-ttu-id="c9946-130">Efst í glugganum **Greining eftir víddum** skal fylla inn í reitina til að skilgreina hvað birtist.</span><span class="sxs-lookup"><span data-stu-id="c9946-130">At the top of the **Analysis by Dimensions** window, fill in the fields to define what is shown.</span></span>
4. 5. <span data-ttu-id="c9946-131">Til að sjá lýsingu á upphæð sem er sýnd í fylkisglugganum er smellt á upphæðina .</span><span class="sxs-lookup"><span data-stu-id="c9946-131">To see a specification of an amount shown in the matrix window, choose the amount.</span></span>  

> [!IMPORTANT]  
>   <span data-ttu-id="c9946-132">Ekki er hægt að velja styttra tímabil en tímabil sem er skilgreint fyrir dagsetningarþjöppun á spjaldinu **Greiningaryfirlit**.</span><span class="sxs-lookup"><span data-stu-id="c9946-132">You cannot select a period length shorter than the period specified for the date compression on the **Analysis View** card.</span></span> <span data-ttu-id="c9946-133">Skipanirnar **Næsta safn** og **Fyrra safn** eru óvirkar ef valið var **Tímabil** , annaðhvort í reitnum **Sýna sem línur** eða **Sýna sem dálkar**.</span><span class="sxs-lookup"><span data-stu-id="c9946-133">The **Next Set** and **Previous Set** commands are inactive if you have selected **Period** in either the **Show as Lines** or the **Show as Columns** field.</span></span>  

> [!NOTE]  
>   <span data-ttu-id="c9946-134">Hægt er að nota skýrsluna **Víddir - Sundurliðun** til að sýna ítarlega flokkun á notkun vídda í færslum á tilteknu tímabili.</span><span class="sxs-lookup"><span data-stu-id="c9946-134">You can use the **Dimensions - Detail** report to display a detailed classification of how dimensions have been used on entries over a selected period.</span></span> <span data-ttu-id="c9946-135">Hægt er að nota skýrsluna **Víddir - Heild** til að sýna aðeins heildarupphæðirnar.</span><span class="sxs-lookup"><span data-stu-id="c9946-135">You can use the **Dimensions - Total** report to display only the total amounts.</span></span>  

> [!TIP]  
>   <span data-ttu-id="c9946-136">Einnig er hægt að breyta útlitinu með því að breyta innihaldi reitanna **Sýna sem línur** og **Sýna sem dálka** .</span><span class="sxs-lookup"><span data-stu-id="c9946-136">You can also change the view by changing the contents of the **Show as Lines** field and **Show as Columns** field.</span></span> <span data-ttu-id="c9946-137">Til að snúa við yfirlitsstillingu, skal velja aðgerðina **Snúa við línum og dálkum**.</span><span class="sxs-lookup"><span data-stu-id="c9946-137">To reverse a view setting, choose the **Reverse Lines and Columns** action.</span></span>

## <a name="to-update-an-analysis-view"></a><span data-ttu-id="c9946-138">Að uppfæra greiningaryfirlit</span><span class="sxs-lookup"><span data-stu-id="c9946-138">To update an analysis view</span></span>  
<span data-ttu-id="c9946-139">Upphæðirnar sem sýndar eru í glugganum **Greining eftir víddum** gefa mynd af stöðu fyrirtækisins við síðustu uppfærslu.</span><span class="sxs-lookup"><span data-stu-id="c9946-139">The amounts that are displayed in the **Analysis by Dimensions** window give you a picture of the company’s state at the time of the last update.</span></span> <span data-ttu-id="c9946-140">Til að sjá mynd af núverandi stöðu verður að uppfæra greiningaryfirlitið með því að keyra uppfærsluaðgerðina.</span><span class="sxs-lookup"><span data-stu-id="c9946-140">To get a picture of the current state, you must update the analysis view by running the update function.</span></span>

<span data-ttu-id="c9946-141">Eftirfarandi aðgerð er til að uppfæra greiningaryfirlit úr glugganum **Greining eftir víddum** .</span><span class="sxs-lookup"><span data-stu-id="c9946-141">The following procedure is for updating an analysis view from the **Analysis by Dimensions** window.</span></span> <span data-ttu-id="c9946-142">Skrefin eru svipuð og í gluggunum **Greiningaryfirlitsspjald** og **Greiningaryfirlitslisti**.</span><span class="sxs-lookup"><span data-stu-id="c9946-142">The steps are similar from the **Analysis View Card** and the **Analysis View List** windows.</span></span>  

1. <span data-ttu-id="c9946-143">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Greining eftir víddum** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="c9946-143">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Analysis by Dimensions**, and then choose the related link.</span></span>  
2. <span data-ttu-id="c9946-144">Í glugganum **Greining eftir víddum** skal velja reitinn **Kóði greiningaryfirlits**.</span><span class="sxs-lookup"><span data-stu-id="c9946-144">In the **Analysis by Dimensions** window, choose the **Analysis View Code** field.</span></span>  
3. <span data-ttu-id="c9946-145">Línan með viðeigandi greiningaryfirliti er valin.</span><span class="sxs-lookup"><span data-stu-id="c9946-145">Select the line with the relevant analysis view.</span></span>  
4. <span data-ttu-id="c9946-146">Velja skal aðgerðina **Uppfæra**.</span><span class="sxs-lookup"><span data-stu-id="c9946-146">Choose the **Update** action.</span></span>  

> [!TIP]  
>   <span data-ttu-id="c9946-147">Ef gátreiturinn **Uppfæra við bókun** er valinn á greiningaryfirlitsspjaldi, uppfærist yfirlitið sjálfkrafa þegar tengd færsla er bókuð.</span><span class="sxs-lookup"><span data-stu-id="c9946-147">If you select the **Update on Posting** check box on an analysis view card, the view is automatically updated when an involved transaction is posted.</span></span>

> [!NOTE]  
>   <span data-ttu-id="c9946-148">Til að uppfæra sum eða öll greiningaryfirlit á sama tíma, þarf að nota runuvinnsluna **Uppfæra greiningaryfirlit**.</span><span class="sxs-lookup"><span data-stu-id="c9946-148">To update some or all analysis views at the same time, you must use the **Update Analysis Views** batch job.</span></span>  

## <a name="see-also"></a><span data-ttu-id="c9946-149">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="c9946-149">See Also</span></span>
[<span data-ttu-id="c9946-150">Viðskiptaupplýsingar</span><span class="sxs-lookup"><span data-stu-id="c9946-150">Business Intelligence</span></span>](bi.md)  
[<span data-ttu-id="c9946-151">Fjármál</span><span class="sxs-lookup"><span data-stu-id="c9946-151">Finance</span></span>](finance.md)  
[<span data-ttu-id="c9946-152">Uppsetning Fjármála</span><span class="sxs-lookup"><span data-stu-id="c9946-152">Setting Up Finance</span></span>](finance-setup-finance.md)  
[<span data-ttu-id="c9946-153">Fjárhagur og bókhaldslyklar</span><span class="sxs-lookup"><span data-stu-id="c9946-153">The General Ledger and the Chart of Accounts</span></span>](finance-general-ledger.md)  
[<span data-ttu-id="c9946-154">Unnið með víddir</span><span class="sxs-lookup"><span data-stu-id="c9946-154">Working with Dimensions</span></span>](finance-dimensions.md)  
<span data-ttu-id="c9946-155">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="c9946-155">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  
