---
title: "Hvernig á að tína fyrir innri starfsemi með ítarlegum vöruhúsaskilgreiningum"
description: "Í ítarlegri vöruhúsagrunnstillingu þar sem birgðageymslan notar tínslu auk afhendingar eru íhlutir tíndir fyrir framleiðslu- og samsetningarverkþætti með glugganum **Vöruhúsatínsla**."
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
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 08b79f573a9fc013068f7e1f5dd593a596a579a3
ms.contentlocale: is-is
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-pick-for-assembly-or-production-in-advanced-warehouse-configurations"></a><span data-ttu-id="3ac38-103">Hvernig á að tína fyrir samsetningar- eða framleiðslu með ítarlegum vöruhúsaaðgerðum | Microsoft Docs</span><span class="sxs-lookup"><span data-stu-id="3ac38-103">How to: Pick for Assembly or Production in Advanced Warehouse Configurations</span></span>
<span data-ttu-id="3ac38-104">Í ítarlegri vöruhúsastillingu þar sem birgðageymslan notar tínslu auk afhendingar eru íhlutir tíndir fyrir framleiðslu- og samsetningarverkþætti með glugganum **Vöruhús - Tína**.</span><span class="sxs-lookup"><span data-stu-id="3ac38-104">In advanced warehouse configurations where the location is set up to use picking as well as shipping, you can pick components for production and assembly activities with the **Warehouse Pick** window.</span></span>  

<span data-ttu-id="3ac38-105">Einnig er hægt að nota gluggann **Vinnublað hreyfingar** til að færa vörur milli hólfa á tilfallandi hátt, þ. e. a. án tilvísunar í upprunaskjal.</span><span class="sxs-lookup"><span data-stu-id="3ac38-105">Alternatively, you can use the **Movement Worksheet** window to move items between bins ad hoc, meaning without reference to a source document.</span></span> <span data-ttu-id="3ac38-106">Nánari upplýsingar má nálgast á [Hvernig á að færa vörur með ítarlegum vöruhúsaaðgerðum](warehouse-how-to-move-items-in-advanced-warehousing.md).</span><span class="sxs-lookup"><span data-stu-id="3ac38-106">For more information, see [How to: Move Items in advanced warehouse configurations](warehouse-how-to-move-items-in-advanced-warehousing.md).</span></span>  

<span data-ttu-id="3ac38-107">Upplýsingar um tínslu atriða fyrir innri starfsemi í einföldum vöruhúsum sem hafa aðeins verið sett upp fyrir tínslu eru í [Hvernig á að: færa íhluti á aðgerðasvæði með einfaldri grunngerð vöruhúsa](warehouse-how-to-move-components-to-an-operation-area-in-basic-warehousing.md).</span><span class="sxs-lookup"><span data-stu-id="3ac38-107">For information about picking items for internal operations in basic warehouse locations that are set up for picking only, see [How to: Move Components to an Operation Area in Basic Warehouse Configurations](warehouse-how-to-move-components-to-an-operation-area-in-basic-warehousing.md).</span></span>  

<span data-ttu-id="3ac38-108">Ekki er hægt að stofna vöruhúsatínsluskjal frá grunni þar sem í tínsluaðgerð er alltaf hluti af verkflæði, annað hvort sem dráttur eða ýting.</span><span class="sxs-lookup"><span data-stu-id="3ac38-108">You cannot create a warehouse pick document from scratch because a pick activity is always part of a workflow, either in a pull or a push scenario.</span></span>  

<span data-ttu-id="3ac38-109">Einnig er hægt að stofna vöruhúsatínsluskjöl eins og ýtingu í glugganum **Stofna vöruhússtínslu** á upprunaskjalinu, eins og útgefna samsetningarpöntun eða vöruhúsaafhendingu.</span><span class="sxs-lookup"><span data-stu-id="3ac38-109">You can create the warehouse pick document in a push fashion by selecting **Create Whse. Pick** on the source document, such as a released assembly order or warehouse shipment.</span></span> <span data-ttu-id="3ac38-110">Frekari upplýsingar, sjá [Hvernig á að: tína Vörur með vöruhúsatínslu](warehouse-how-to-pick-items-for-warehouse-shipment.md)</span><span class="sxs-lookup"><span data-stu-id="3ac38-110">For more information, see [How to: Pick Items with Warehouse Picks](warehouse-how-to-pick-items-for-warehouse-shipment.md).</span></span>  

<span data-ttu-id="3ac38-111">Einnig er hægt að stofna vöruhúsatínsluskjal eins og drátt með því að nota gluggann **Vinnublað tínslu** til að finna tínslubeiðnir, bæði til afhendingar og innri aðgerða, og síðan stofna nauðsynleg vöruhúsatínsluskjöl.</span><span class="sxs-lookup"><span data-stu-id="3ac38-111">Alternatively, you can create the warehouse pick document in a pull fashion by using the **Pick Worksheet** window to detect pick requests, both for shipment and internal operations, and then create the required warehouse pick documents.</span></span>  

<span data-ttu-id="3ac38-112">Eftirfarandi ferli skýrir dæmi þar sem valdir eru íhlutir fyrir afhenta framleiðslupöntun í gegnum gluggann **Vinnublað tínslu**.</span><span class="sxs-lookup"><span data-stu-id="3ac38-112">The following procedure explains a pull scenario where you pick components for a released production order through the **Pick Worksheet** window.</span></span> <span data-ttu-id="3ac38-113">Ferlið á einnig við fyrir samsetningarpöntun.</span><span class="sxs-lookup"><span data-stu-id="3ac38-113">The procedure also applies for an assembly order.</span></span>  

<span data-ttu-id="3ac38-114">Til að stofna tínslubeiðnir, bæði fyrir tog- og ýtidæmi, þurfa viðkomandi upprunaskjöl að vera útgefin.</span><span class="sxs-lookup"><span data-stu-id="3ac38-114">To create pick requests, both for pull and for push scenarios, the source documents in question must be released.</span></span> <span data-ttu-id="3ac38-115">Upprunaskjöl eru gefin út fyrir innri aðgerðir á eftirfarandi hátt.</span><span class="sxs-lookup"><span data-stu-id="3ac38-115">Release source documents for internal operations in the following ways.</span></span>  

|<span data-ttu-id="3ac38-116">Upprunaskjal</span><span class="sxs-lookup"><span data-stu-id="3ac38-116">Source Document</span></span>|<span data-ttu-id="3ac38-117">Losunaraðferð</span><span class="sxs-lookup"><span data-stu-id="3ac38-117">Release Method</span></span>|  
|---------------------|--------------------|  
|<span data-ttu-id="3ac38-118">Framleiðslupöntun</span><span class="sxs-lookup"><span data-stu-id="3ac38-118">Production Order</span></span>|<span data-ttu-id="3ac38-119">Breyta tegund pöntunar í útgefna framleiðslupöntun.</span><span class="sxs-lookup"><span data-stu-id="3ac38-119">Change order type to released production order.</span></span>|  
|<span data-ttu-id="3ac38-120">Samsetningarpöntun</span><span class="sxs-lookup"><span data-stu-id="3ac38-120">Assembly Order</span></span>|<span data-ttu-id="3ac38-121">Breyta stöðu í Útgefið.</span><span class="sxs-lookup"><span data-stu-id="3ac38-121">Change status to Released.</span></span>|  

## <a name="to-pick-components-using-the-pick-worksheet"></a><span data-ttu-id="3ac38-122">Íhlutir tíndir úr tínsluvinnublöðunum:</span><span class="sxs-lookup"><span data-stu-id="3ac38-122">To pick components using the pick worksheet</span></span>  
1.  <span data-ttu-id="3ac38-123">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Vinnublað tínslu** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="3ac38-123">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Pick Worksheet**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="3ac38-124">Velja skal **Sækja vöruhúsaskjöl** og síðan velja íhlutalínurnar í útgefnu framleiðslupöntuninni.</span><span class="sxs-lookup"><span data-stu-id="3ac38-124">Choose the **Get Warehouse Documents** action, and then select the component lines from the released production order.</span></span>  
3.  <span data-ttu-id="3ac38-125">Línurnar eru skoðaðar, þeim raðað til að tryggja skilvirkni tínsluferðarinnar og þær sameinaðar öðrum vinnublaðslínum ef þarf, til að nýta tíma starfsmanna sem best.</span><span class="sxs-lookup"><span data-stu-id="3ac38-125">Inspect the lines, sort them to ensure an efficient picking round, and combine them with other worksheet lines if necessary to make best use of employee time.</span></span>  
4.  <span data-ttu-id="3ac38-126">Veldu aðgerðina **Stofna tínslu**.</span><span class="sxs-lookup"><span data-stu-id="3ac38-126">Choose the **Create Pick** action.</span></span>  
5.  <span data-ttu-id="3ac38-127">Skilgreina hvernig eigi að stofna vöruhúsatínsluskjöl og hvernig á að raða tínslulínunum með því að fylla út reiti í gluggnum **Stofna tínslu**.</span><span class="sxs-lookup"><span data-stu-id="3ac38-127">Define how to create the warehouse pick documents and how to sort pick lines by filling fields in the **Create Pick** window.</span></span>  
6.  <span data-ttu-id="3ac38-128">Velja hnappinn **Í lagi**.</span><span class="sxs-lookup"><span data-stu-id="3ac38-128">Choose the **OK** button.</span></span> <span data-ttu-id="3ac38-129">Vöruhúsatínsluskjöl eru búin til með tínslulínum fyrir hvern íhlut sem er krafist í innri aðgerð.</span><span class="sxs-lookup"><span data-stu-id="3ac38-129">Warehouse pick documents are created with pick lines for each component that is required in the internal operation.</span></span>  

<span data-ttu-id="3ac38-130">Ef svæði innri starfsemi, s.s. framleiðsluvinnusalur, er sett upp með sjálfgefnu hólfi fyrir staðsetningu íhluta sem notaðir eru verður kóti þess hólfs settur inn í Setja-línur í tínsluskjali vöruhússins til að leiðbeina starfsmönnum í vöruhúsi um hvert setja eigi vörurnar.</span><span class="sxs-lookup"><span data-stu-id="3ac38-130">If the internal operation area, such as a production shop floor, is set up with a default bin for placement of components to be used in the operation, then that bin code is inserted in the Place lines on the warehouse pick document to instruct warehouse workers where to place the items.</span></span> <span data-ttu-id="3ac38-131">Nánari upplýsingar má nálgast á **Hólfkóði til framleiðslu** eða **Í samsetningu hólfakóð** reitina.</span><span class="sxs-lookup"><span data-stu-id="3ac38-131">For more information, see the **To-Production Bin Code** or the **To-Assembly Bin Code** field.</span></span>

## <a name="filling-the-consumption-bin"></a><span data-ttu-id="3ac38-132">Fylla út notkunarhólfið</span><span class="sxs-lookup"><span data-stu-id="3ac38-132">Filling the Consumption Bin</span></span>
<span data-ttu-id="3ac38-133">Þetta flæðirit sýnir hvernig reiturinn **Hólfkóði** í framleiðslupöntunaríhlutalínum er útfylltur samkvæmt uppsetningu staðsetningar.</span><span class="sxs-lookup"><span data-stu-id="3ac38-133">This flow chart shows how the **Bin Code** field on production order component lines is filled according to your location setup.</span></span>

<span data-ttu-id="3ac38-134">![Flæðirit hólfa](media/binflow.png "Hólfaflæði")</span><span class="sxs-lookup"><span data-stu-id="3ac38-134">![Bin flow chart](media/binflow.png "BinFlow")</span></span>  

## <a name="see-also"></a><span data-ttu-id="3ac38-135">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="3ac38-135">See Also</span></span>
[<span data-ttu-id="3ac38-136">Vöruhúsastjórnun</span><span class="sxs-lookup"><span data-stu-id="3ac38-136">Warehouse Management</span></span>](warehouse-manage-warehouse.md)  
[<span data-ttu-id="3ac38-137">Birgðir</span><span class="sxs-lookup"><span data-stu-id="3ac38-137">Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="3ac38-138">[Vöruhúsastjórnun sett upp](warehouse-setup-warehouse.md)   </span><span class="sxs-lookup"><span data-stu-id="3ac38-138">[Setting Up Warehouse Management](warehouse-setup-warehouse.md)   </span></span>  
<span data-ttu-id="3ac38-139">[Samsetningardeild](assembly-assemble-items.md)  </span><span class="sxs-lookup"><span data-stu-id="3ac38-139">[Assembly Management](assembly-assemble-items.md)  </span></span>  
[<span data-ttu-id="3ac38-140">Hönnunarupplýsingar vöruhúsakerfi</span><span class="sxs-lookup"><span data-stu-id="3ac38-140">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)  
<span data-ttu-id="3ac38-141">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="3ac38-141">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
