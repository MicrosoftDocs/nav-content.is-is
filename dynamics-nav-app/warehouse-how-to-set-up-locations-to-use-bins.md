---
title: "Hvernig á að setja upp birgðageymslur til að þær noti hólf"
description: "Hólf tákna grunnvöruhúsauppbyggingu og eru notuð til að gera tillögur að staðsetningu vöru. Þegar hólfin hafa verið stofnuð er hægt að skilgreina nánar hvaða innihald á að setja í hvert hólf eða nota hólfið sem fljótandi hólf án tiltekins innihalds."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/23/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 95b36b6eed79da868c1e41905110788c90f24829
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-locations-to-use-bins"></a><span data-ttu-id="2ac08-104">Hvernig á að setja upp birgðageymslur til að þær noti hólf</span><span class="sxs-lookup"><span data-stu-id="2ac08-104">How to: Set Up Locations to Use Bins</span></span>
<span data-ttu-id="2ac08-105">Hólf tákna grunnvöruhúsauppbyggingu og eru notuð til að gera tillögur að staðsetningu vöru.</span><span class="sxs-lookup"><span data-stu-id="2ac08-105">Bins represent the basic warehouse structure and are used to make suggestions about the placement of items.</span></span> <span data-ttu-id="2ac08-106">Þegar hólfin hafa verið stofnuð er hægt að skilgreina nánar hvaða innihald á að setja í hvert hólf eða nota hólfið sem fljótandi hólf án tiltekins innihalds.</span><span class="sxs-lookup"><span data-stu-id="2ac08-106">When you have created your bins, you can define very specifically the contents that you want to place in each bin, or the bin can function as a floating bin without specified contents.</span></span>  

<span data-ttu-id="2ac08-107">Ef nota á hólf í birgðageymslu þarf fyrst að virkja aðgerðina á spjaldinu **birgðageymsla**</span><span class="sxs-lookup"><span data-stu-id="2ac08-107">To use the bin functionality at a location, you first activate the functionality on the **Location** card.</span></span> <span data-ttu-id="2ac08-108">Síðan er vöruflæðið í birgðageymslunni útbúið með því að tilgreina hólfakóða í uppsetningarreitum sem tákna ólík flæði.</span><span class="sxs-lookup"><span data-stu-id="2ac08-108">Then you design the item flow at the location by specifying bin codes in setup fields that represent the different flows.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="2ac08-109">Áður en hægt er að tilgreina hólfkóta í birgðageymsluspjaldinu þarf að stofna hólfkótana.</span><span class="sxs-lookup"><span data-stu-id="2ac08-109">Before you can specify bin codes on the location card, the bin codes must be created.</span></span> <span data-ttu-id="2ac08-110">Nánari upplýsingar eru í [Hvernig á að: Stofna hólf](warehouse-how-to-create-individual-bins.md).</span><span class="sxs-lookup"><span data-stu-id="2ac08-110">For more information, see [How to: Create Bins](warehouse-how-to-create-individual-bins.md).</span></span>  

## <a name="to-set-up-a-location-to-use-bins"></a><span data-ttu-id="2ac08-111">Til að setja upp birgðageymslur til að þær noti hólf</span><span class="sxs-lookup"><span data-stu-id="2ac08-111">To set up a location to use bins</span></span>  
1.  <span data-ttu-id="2ac08-112">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Staðsetningar** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="2ac08-112">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Locations**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="2ac08-113">Veljið birgðageymsluna þar sem á að nota hólf.</span><span class="sxs-lookup"><span data-stu-id="2ac08-113">Select the location where you want to use bins.</span></span>  
3.  <span data-ttu-id="2ac08-114">Veldu aðgerðina **Breyta**.</span><span class="sxs-lookup"><span data-stu-id="2ac08-114">Choose the **Edit** action.</span></span>  
4.  <span data-ttu-id="2ac08-115">Á flýtiflipanum **Vöruhús** er gátreiturinn **Hólf áskilin** valinn.</span><span class="sxs-lookup"><span data-stu-id="2ac08-115">On the **Warehouse** FastTab, select the **Bin Mandatory** check box.</span></span>  
5.  <span data-ttu-id="2ac08-116">Ef ekki er notaður beinn frágangur og tínsla er í reitnum **Sjálfgefið hólfaval** tilgreind aðferðin sem kerfið a´að nota þegar sjálfgefið hólf er tengt vöru.</span><span class="sxs-lookup"><span data-stu-id="2ac08-116">If you are not using directed put-away and pick for the location, fill in the **Default Bin Selection** field with the method the system should use when assigning a default bin to an item.</span></span>  
6.  <span data-ttu-id="2ac08-117">Opna spjaldið fyrir birgðageymsluna sem setja á upp hólf fyrir.</span><span class="sxs-lookup"><span data-stu-id="2ac08-117">Open the card for the location that you want to set up bins for.</span></span>
7.  <span data-ttu-id="2ac08-118">Á flýtiflipanum **Hólf** skal velja hólfin sem nota á sem sjálfgefin fyrir móttökur, afhendingar, á innleið, á útleið og opin vinnslusalarhólf.</span><span class="sxs-lookup"><span data-stu-id="2ac08-118">On the **Bins** FastTab, select the bins that you want to use as the default for receipts, shipments, inbound, outbound, and open shop floor bins.</span></span>  
8.  <span data-ttu-id="2ac08-119">Hólfakótarnir sem valdir eru hér munu birtast sjálfkrafa á hausum og línum vöruhúsaskjala.</span><span class="sxs-lookup"><span data-stu-id="2ac08-119">The bin codes you fill in here will appear automatically on the headers and on the lines of various warehouse documents.</span></span> <span data-ttu-id="2ac08-120">Sjálfgefnu hólfin skilgreina allar upphafs- og lokastaðsetningar vara í vöruhúsinu.</span><span class="sxs-lookup"><span data-stu-id="2ac08-120">The default bins define all starting or ending placements of items in the warehouse.</span></span>  
9.  <span data-ttu-id="2ac08-121">Ef notaður er beinn frágangur og tínsla skal velja hólf fyrir vöruhúsaleiðréttingar.</span><span class="sxs-lookup"><span data-stu-id="2ac08-121">If you are using directed put-away and pick, select a bin for your warehouse adjustments.</span></span> <span data-ttu-id="2ac08-122">Hólfakótinn í svæðinu **Kóti leiðréttingarhólfs** skilgreinir sýndarhólfið þar sem á að skrá misræmi í birgðum við skráningu annað hvort misræmis sem uppgötvast og skráð er í vöru í vöruhúsi færslubókar eða mismunar sem reiknaður er þegar raunbirgðir vöruhúss eru skráðar.</span><span class="sxs-lookup"><span data-stu-id="2ac08-122">The bin code in the **Adjustment Bin Code** field defines the virtual bin in which to record discrepancies in inventory when you register either observed differences registered in the warehouse item journal, or differences calculated when you register a warehouse physical inventory.</span></span>  
10. <span data-ttu-id="2ac08-123">Reitirnir á flýtiflipanum **Hólfareglur** eru fylltir út ef þeir eiga við í vöruhúsinu.</span><span class="sxs-lookup"><span data-stu-id="2ac08-123">Fill in the fields on the **Bin Policies** FastTab if they are relevant to your warehouse.</span></span> <span data-ttu-id="2ac08-124">Mikilvægustu reitirnir eru **Hólfageturegla**, **Leyfa einingaskipti** og **Kóti frágangssniðmáts**.</span><span class="sxs-lookup"><span data-stu-id="2ac08-124">The most important fields are **Bin Capacity Policy**, **Allow Breakbulk**, and **Put-away Template Code** fields.</span></span>  
11. <span data-ttu-id="2ac08-125">Á flýtiflipanum **Vöruhús** skal fylla út reitina **Afgr.tími vara á útl. úr vöruh.**, **Afgr.tími vara á innl. úr vöruh.** og **Kóti grunndagatals**.</span><span class="sxs-lookup"><span data-stu-id="2ac08-125">On the **Warehouse** FastTab, fill in the **Outbound Whse. Handling Time**, **Inbound Whse. Handling Time**, and the **Base Calendar Code** fields.</span></span> <span data-ttu-id="2ac08-126">Nánari upplýsingar er að finna í [Hvernig á að: setja upp grunndagatal](across-how-to-assign-base-calendars.md).</span><span class="sxs-lookup"><span data-stu-id="2ac08-126">For more information, see [How to: Set Up Base Calendars](across-how-to-assign-base-calendars.md).</span></span>

## <a name="filling-the-consumption-bin"></a><span data-ttu-id="2ac08-127">Fylla út notkunarhólfið</span><span class="sxs-lookup"><span data-stu-id="2ac08-127">Filling the Consumption Bin</span></span>
<span data-ttu-id="2ac08-128">Þetta flæðirit sýnir hvernig reiturinn **Hólfkóði** í framleiðslupöntunaríhlutalínum er útfylltur samkvæmt uppsetningu staðsetningar.</span><span class="sxs-lookup"><span data-stu-id="2ac08-128">This flow chart shows how the **Bin Code** field on production order component lines is filled according to your location setup.</span></span>

<span data-ttu-id="2ac08-129">![Flæðirit hólfa](media/binflow.png "Hólfaflæði")</span><span class="sxs-lookup"><span data-stu-id="2ac08-129">![Bin flow chart](media/binflow.png "BinFlow")</span></span>  

## <a name="see-also"></a><span data-ttu-id="2ac08-130">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="2ac08-130">See Also</span></span>
[<span data-ttu-id="2ac08-131">Vöruhúsastjórnun</span><span class="sxs-lookup"><span data-stu-id="2ac08-131">Warehouse Management</span></span>](warehouse-manage-warehouse.md)  
[<span data-ttu-id="2ac08-132">Birgðir</span><span class="sxs-lookup"><span data-stu-id="2ac08-132">Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="2ac08-133">[Vöruhúsastjórnun sett upp](warehouse-setup-warehouse.md)   </span><span class="sxs-lookup"><span data-stu-id="2ac08-133">[Setting Up Warehouse Management](warehouse-setup-warehouse.md)   </span></span>  
<span data-ttu-id="2ac08-134">[Samsetningardeild](assembly-assemble-items.md)  </span><span class="sxs-lookup"><span data-stu-id="2ac08-134">[Assembly Management](assembly-assemble-items.md)  </span></span>  
[<span data-ttu-id="2ac08-135">Hönnunarupplýsingar vöruhúsakerfi</span><span class="sxs-lookup"><span data-stu-id="2ac08-135">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)  
<span data-ttu-id="2ac08-136">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="2ac08-136">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
