---
title: "Hvernig á að búa til tilboð með samsetningarpöntun"
description: "Hægt er að nota samsetningarstjórnun til að sérsníða samsetningaríhlut eftir beiðni viðskiptavinar á meðan söluferlinu stendur."
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
ms.openlocfilehash: 7ee62ddff43778bd81d4ed65c2dcdd466b79e422
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-quote-an-assemble-to-order-sale"></a><span data-ttu-id="c544a-103">Hvernig á að búa til tilboð með samsetningarpöntun</span><span class="sxs-lookup"><span data-stu-id="c544a-103">How to: Quote an Assemble-to-Order Sale</span></span>
<span data-ttu-id="c544a-104">Hægt er að nota samsetningarstjórnun til að sérsníða samsetningaríhlut eftir beiðni viðskiptavinar á meðan söluferlinu stendur.</span><span class="sxs-lookup"><span data-stu-id="c544a-104">You can use assembly management to customize an assembly item to a customer’s request during the sales process.</span></span> <span data-ttu-id="c544a-105">Frekari upplýsingar, sjá [Hvernig skal: Selja vörur sem eru settar saman í pöntun](assembly-how-to-sell-items-assembled-to-order.md).</span><span class="sxs-lookup"><span data-stu-id="c544a-105">For more information, see [How to: Sell Items Assembled to Order](assembly-how-to-sell-items-assembled-to-order.md).</span></span>  

<span data-ttu-id="c544a-106">Eins og þegar seld er hvers kyns önnur tegund af vöru, er einnig hægt að stofna sölutilboð fyrir sérsniðna samsetningarvöru áður en henni er umbreytt í sölupöntun.</span><span class="sxs-lookup"><span data-stu-id="c544a-106">As when you sell any other type of item, you can also create a sales quote for a customized assembly item before converting it to a sales order.</span></span> <span data-ttu-id="c544a-107">Þetta ferli felur í sér nokkur aukaskref í samanburði við stofnun venjulegs standandi sölutilboðs, og notar afbrigði tengdrar samsetningarpöntunar, sem er samsetningartilboð.</span><span class="sxs-lookup"><span data-stu-id="c544a-107">This process involves several extra steps when you compare it to creating a regular sales quote, and it uses a variation of a linked assembly order, which is an assembly quote.</span></span>

> [!NOTE]  
>  <span data-ttu-id="c544a-108">Eins og allar gerðir á tilboðum er magn samsetningartilboða ekki notað til ráðstöfunar, í áætlun eða frátekt.</span><span class="sxs-lookup"><span data-stu-id="c544a-108">Like all types of quotes, the quantities on assembly quotes are not used in availability, planning, or reservations.</span></span>  

## <a name="to-create-a-sales-quote-for-an-assemble-to-order-item"></a><span data-ttu-id="c544a-109">Til að stofna sölutilboð fyrir vöru sem setja skal saman í pöntun</span><span class="sxs-lookup"><span data-stu-id="c544a-109">To create a sales quote for an assemble-to-order item</span></span>  
1.  <span data-ttu-id="c544a-110">Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Sölutilboð** og velja svo viðeigandi tengil.</span><span class="sxs-lookup"><span data-stu-id="c544a-110">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales Quote**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="c544a-111">Stofna nýja sölupöntunarlínu með eina línu fyrir samsetningaríhlut.</span><span class="sxs-lookup"><span data-stu-id="c544a-111">Create a sales quote line with one line for an assembly item.</span></span> <span data-ttu-id="c544a-112">Nánari upplýsingar eru í [Hvernig á að gera tilboð](sales-how-make-offers.md).</span><span class="sxs-lookup"><span data-stu-id="c544a-112">For more information, see [How to: Make Offers](sales-how-make-offers.md).</span></span>  
3.  <span data-ttu-id="c544a-113">Í reitnum **Magn til samsetningar til pöntunar** skal færa inn fullt magn.</span><span class="sxs-lookup"><span data-stu-id="c544a-113">In the **Qty. to Assemble to Order** field, enter the full quantity.</span></span>

    > [!NOTE]  
    >  <span data-ttu-id="c544a-114">Ekki ætti að gera tilboð í hlutamagn.</span><span class="sxs-lookup"><span data-stu-id="c544a-114">You should not quote a partial quantity.</span></span> <span data-ttu-id="c544a-115">Því verður að færa inn sama magn og fært var inn í reitinn **Magn** í sölutilboðslínunni.</span><span class="sxs-lookup"><span data-stu-id="c544a-115">Therefore, you must enter the same quantity that you entered in the **Quantity** field on the sales quote line.</span></span>  

4.  <span data-ttu-id="c544a-116">Á flýtiflipanum skal velja **Línur**, velja **Lína**, velja **Samsetning til pöntunar** og síðan **Setja saman í pöntunarlínur**.</span><span class="sxs-lookup"><span data-stu-id="c544a-116">On the **Lines** FastTab, choose **Line**, choose **Assemble to Order**, and then choose **Assemble-to-Order Lines**.</span></span> <span data-ttu-id="c544a-117">Að öðrum kosti skal velja reitinn **Magn til samsetningar til pöntunar** í línunni.</span><span class="sxs-lookup"><span data-stu-id="c544a-117">Alternatively, choose the **Qty. to Assemble to Order** field on the line.</span></span>  
5.  <span data-ttu-id="c544a-118">Í glugganum **Setja saman í pöntunarlínu** endurskoðið og breytið samsetningu pöntunalína samkvæmt tilboði standandi pöntunar sem viðskiptamaðurinn hefur farið fram á.</span><span class="sxs-lookup"><span data-stu-id="c544a-118">In the **Assemble-to-Order Lines** window, review or modify the assembly order lines according to the quote that the customer is requesting.</span></span> <span data-ttu-id="c544a-119">Ef skoða á nánari upplýsingar skal velja aðgerðina **Sýna fylgiskjal** til að opna tilboð standandi pöntunarinnar.</span><span class="sxs-lookup"><span data-stu-id="c544a-119">If you want to view more information, choose the **Show Document** action to open the complete blanket quote order.</span></span> <span data-ttu-id="c544a-120">Ekki er hægt að breyta innihaldi i flestum reitum, og ekki er hægt að bóka.</span><span class="sxs-lookup"><span data-stu-id="c544a-120">You cannot change the contents of most fields, and you cannot post.</span></span>  
6.  <span data-ttu-id="c544a-121">Þegar búið er að leiðrétta samsetningarpöntunarlínur samkvæmt tilboðinu skal loka glugganum **Sameina-í-pöntun línur** til að fara aftur í gluggann **Sölutilboð** .</span><span class="sxs-lookup"><span data-stu-id="c544a-121">When you have adjusted the assembly order lines according to the quote, close the **Assemble-to-Order Lines** window to return to the **Sales Quote** window.</span></span>  
7.  <span data-ttu-id="c544a-122">Ef viðskiptamaðurinn samþykkir tilboðið skal stofna sölupöntun fyrir samsetningaríhlut tilboðsins.</span><span class="sxs-lookup"><span data-stu-id="c544a-122">If the customer accepts the quote, then create a sales order for the quoted assembly item.</span></span> <span data-ttu-id="c544a-123">Nánari upplýsingar eru í [Hvernig á að gera tilboð](sales-how-make-offers.md).</span><span class="sxs-lookup"><span data-stu-id="c544a-123">For more information, see [How to: Make Offers](sales-how-make-offers.md).</span></span> <span data-ttu-id="c544a-124">Tengt samsetningartilboð og allar sérstillingar tengjast við þessa nýju sölupöntun til undirbúnings á samsetningu vöru eða vörum sem á að selja.</span><span class="sxs-lookup"><span data-stu-id="c544a-124">The linked assembly quote and any customizations are linked to that new sales order to prepare for assembly of the item or items to be sold.</span></span>  

## <a name="see-also"></a><span data-ttu-id="c544a-125">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="c544a-125">See Also</span></span>  
[<span data-ttu-id="c544a-126">Samsetningardeild</span><span class="sxs-lookup"><span data-stu-id="c544a-126">Assembly Management</span></span>](assembly-assemble-items.md)  
[<span data-ttu-id="c544a-127">Hvernig á að: Vinna með uppskriftir</span><span class="sxs-lookup"><span data-stu-id="c544a-127">How to: Work with Bills of Material</span></span>](inventory-how-work-BOMs.md)  
[<span data-ttu-id="c544a-128">Birgðir</span><span class="sxs-lookup"><span data-stu-id="c544a-128">Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="c544a-129">Hönnunarupplýsingar vöruhúsakerfi</span><span class="sxs-lookup"><span data-stu-id="c544a-129">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)  
<span data-ttu-id="c544a-130">[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="c544a-130">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
