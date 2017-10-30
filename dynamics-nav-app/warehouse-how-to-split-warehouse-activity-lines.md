---
title: "Hvernig á að skipta vöruhúsaaðgerðalínum"
description: "Í vöruhúsafrágöngum, hreyfingum eða tínslum og í birgðafrágöngum og birgðatínslum eru lögð til hólf fyrir frágang eða tínslu vara. Raunmagnið kann að vera ónægilegt eða ekki er nægilegt rými í hólfinu sem er lagt til til að ganga frá tilskyldu magni. Þá þarf að skipta línunni svo að vörur í einni línu séu teknar úr eða settar í fleiri en eitt hólf."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/16/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: d113b83d2c4d21463e1a015e7015bc1f566652f9
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-split-warehouse-activity-lines"></a><span data-ttu-id="a0d4a-105">Hvernig á að skipta vöruhúsaaðgerðalínum</span><span class="sxs-lookup"><span data-stu-id="a0d4a-105">How to: Split Warehouse Activity Lines</span></span>
<span data-ttu-id="a0d4a-106">Í vöruhúsafrágöngum, hreyfingum eða tínslum og í birgðafrágöngum og birgðatínslum eru lögð til hólf fyrir frágang eða tínslu vara.</span><span class="sxs-lookup"><span data-stu-id="a0d4a-106">In warehouse put-aways, movements, or picks, and in inventory put-aways and inventory picks, bins are suggested for the picking or putting away of items.</span></span> <span data-ttu-id="a0d4a-107">Raunmagnið kann að vera ónægilegt eða ekki er nægilegt rými í hólfinu sem er lagt til til að ganga frá tilskyldu magni.</span><span class="sxs-lookup"><span data-stu-id="a0d4a-107">The actual quantity in the bin suggested may not be sufficient, or there is not enough room in the suggested bin to put away the required quantity.</span></span> <span data-ttu-id="a0d4a-108">Þá þarf að skipta línunni svo að vörur í einni línu séu teknar úr eða settar í fleiri en eitt hólf.</span><span class="sxs-lookup"><span data-stu-id="a0d4a-108">In these cases, you need to split the line, so that the items for one line are either taken from or placed into more than one bin.</span></span>  

<span data-ttu-id="a0d4a-109">Eftirfarandi ferli á við öll vöruhúsaskjöl, s. s. frágangur í vöruhúsi, tilfærsla, og tínslulínur, eða frágangur birgða, tilfærsla og tínslulínur.</span><span class="sxs-lookup"><span data-stu-id="a0d4a-109">The following procedure applies to warehouse documents, such as warehouse put-away, movement, and pick lines, or inventory put-away, movement, and pick lines.</span></span>  

## <a name="to-split-warehouse-activity-lines"></a><span data-ttu-id="a0d4a-110">Til að skipta vöruhúsaaðgerðalínum</span><span class="sxs-lookup"><span data-stu-id="a0d4a-110">To split warehouse activity lines</span></span>  
1.  <span data-ttu-id="a0d4a-111">Opna vöruhúsaaðgerðalínu þar sem þú ert að reyna að meðhöndla ófullnægjandi magn.</span><span class="sxs-lookup"><span data-stu-id="a0d4a-111">Open a warehouse activity line where you are trying to handle an insufficient quantity.</span></span>  
2.  <span data-ttu-id="a0d4a-112">Í reitnum **Magn til afgreiðslu** er fært inn minnkað magn sem mögulegt er að meðhöndla.</span><span class="sxs-lookup"><span data-stu-id="a0d4a-112">In the **Qty. to Handle** field, enter the reduced quantity that you are able to handle.</span></span>  
3.  <span data-ttu-id="a0d4a-113">Á flýtiflipanum **Línur** skal velja aðgerðina **Aðgerðir**, velja aðgerðina **Aðgerðir** og loks velja aðgerðina **Skipta línu**.</span><span class="sxs-lookup"><span data-stu-id="a0d4a-113">On the **Lines** FastTab, choose the **Actions** action, choose the **Functions** action, and then choose the **Split Line** action.</span></span> <span data-ttu-id="a0d4a-114">Ný lína birtist, eins og sú upphaflega, nema að reiturinn **Magn til afgreiðslu** er með magninu sem var fjarlægt úr upphaflegu línunni.</span><span class="sxs-lookup"><span data-stu-id="a0d4a-114">A new line appears, which is a copy of the original line, except that the **Qty. to Handle** field contains the quantity that you removed from the original line.</span></span>  
4.  <span data-ttu-id="a0d4a-115">Réttu hólfi (og svæði ef notaður er beinn frágangur og tínsla) er úthlutað á þessa línu eða haldið áfram að skipta línunni eftir þörfum þar til fundist hafa rétt hólf fyrir allt magnið.</span><span class="sxs-lookup"><span data-stu-id="a0d4a-115">Assign an appropriate bin and, if you are using directed put-away and pick, a zone, to this new line, or continue splitting the line as necessary until you find appropriate bins for all of the quantity.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="a0d4a-116">Ef ef notaður er beinn frágangur og tínsla og línunum er skipt þarf notandinn að hafa þekkingu á vöruhúsinu og geta valið hólf sem hentar geymsluþörfum vörunnar og sem uppfyllir almennar kröfur í vöruhúsaskjalinu.</span><span class="sxs-lookup"><span data-stu-id="a0d4a-116">If the location uses directed put-away and pick and you split the lines, you must be familiar with the warehouse and be able to choose a bin that matches the storage requirements of the item and that fulfills the general requirements of the warehouse document.</span></span> <span data-ttu-id="a0d4a-117">Til dæmis ætti ekki að skipta upp línu á tínsluskjali og setja sumar vörur í magngeymslu.</span><span class="sxs-lookup"><span data-stu-id="a0d4a-117">For example, you would not split a line on a pick document and place some items in the bulk storage.</span></span>  

## <a name="see-also"></a><span data-ttu-id="a0d4a-118">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="a0d4a-118">See Also</span></span>  
[<span data-ttu-id="a0d4a-119">Vöruhúsastjórnun</span><span class="sxs-lookup"><span data-stu-id="a0d4a-119">Warehouse Management</span></span>](warehouse-manage-warehouse.md)  
[<span data-ttu-id="a0d4a-120">Birgðir</span><span class="sxs-lookup"><span data-stu-id="a0d4a-120">Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="a0d4a-121">[Vöruhúsastjórnun sett upp](warehouse-setup-warehouse.md)   </span><span class="sxs-lookup"><span data-stu-id="a0d4a-121">[Setting Up Warehouse Management](warehouse-setup-warehouse.md)   </span></span>  
<span data-ttu-id="a0d4a-122">[Samsetningardeild](assembly-assemble-items.md)  </span><span class="sxs-lookup"><span data-stu-id="a0d4a-122">[Assembly Management](assembly-assemble-items.md)  </span></span>  
[<span data-ttu-id="a0d4a-123">Hönnunarupplýsingar vöruhúsakerfi</span><span class="sxs-lookup"><span data-stu-id="a0d4a-123">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)  
<span data-ttu-id="a0d4a-124">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="a0d4a-124">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
