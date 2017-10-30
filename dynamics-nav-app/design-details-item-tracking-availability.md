---
title: "Hönnunarupplýsingar - vörurakning framboð"
description: "**Vörurakningarlínurnar** Og **Samantekt vörurakningar** gluggar afla kvikar framboðsupplýsingar fyrir raðnúmer eða lotunúmeri. Tilgangurinn með þessu er að auka gagnsæi fyrir notendur á fylgiskjölum á útleið, svo sem sölupöntunum, með því að sýna þeim hvaða raðnúmerum eða hve mörgum einingum lotunúmers er sem stendur úthlutað á önnur opin fylgiskjöl. Þetta minnkar óvissu sem stafar af tvöfaldri úthlutun og framkallar traust í pantanavinnslum að vörurakningarnúmerin og dagsetningar sem þeir eru að lofa á óbókuðum sölupöntunum sé hægt að uppfylla."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/26/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 4d106a10ab0f6a6c0e0eb63c6e6641f9ff358e9e
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-item-tracking-availability"></a><span data-ttu-id="a54f7-105">Hönnunarupplýsingar: vörurakning framboð</span><span class="sxs-lookup"><span data-stu-id="a54f7-105">Design Details: Item Tracking Availability</span></span>
<span data-ttu-id="a54f7-106">**Vörurakningarlínur** Og **Samantekt vörurakningar** gluggar afla kvikar framboðsupplýsingar fyrir raðnúmer eða lotunúmeri.</span><span class="sxs-lookup"><span data-stu-id="a54f7-106">The **Item Tracking Lines** and **Item Tracking Summary** windows provide dynamic availability information for serial or lot numbers.</span></span> <span data-ttu-id="a54f7-107">Tilgangurinn með þessu er að auka gagnsæi fyrir notendur á fylgiskjölum á útleið, svo sem sölupöntunum, með því að sýna þeim hvaða raðnúmerum eða hve mörgum einingum lotunúmers er sem stendur úthlutað á önnur opin fylgiskjöl.</span><span class="sxs-lookup"><span data-stu-id="a54f7-107">The purpose of this is to increase transparency for users on outbound documents, such as sales orders, by showing them which serial numbers or how many units of a lot number are currently assigned on other open documents.</span></span> <span data-ttu-id="a54f7-108">Þetta minnkar óvissu sem stafar af tvöfaldri úthlutun og framkallar traust í pantanavinnslum að vörurakningarnúmerin og dagsetningar sem þeir eru að lofa á óbókuðum sölupöntunum sé hægt að uppfylla.</span><span class="sxs-lookup"><span data-stu-id="a54f7-108">This reduces uncertainty that is caused by double allocation and instills confidence in order processors that the item tracking numbers and dates that they are promising on unposted sales orders can be fulfilled.</span></span> <span data-ttu-id="a54f7-109">Nánari upplýsingar eru í [Upplýsingar um hönnun: Vörurakningarlínur gluggi](design-details-item-tracking-lines-window.md).</span><span class="sxs-lookup"><span data-stu-id="a54f7-109">For more information, see [Design Details: Item Tracking Lines Window](design-details-item-tracking-lines-window.md).</span></span>  

 <span data-ttu-id="a54f7-110">Þegar þú opnar gluggann **Vörurakningarlínu** eru aðgengisgögn sótt úr töflunni **birgðafærsla** og töflunni **Frátekningarfærsla** án nokkurrar gagnaafmörkunar.</span><span class="sxs-lookup"><span data-stu-id="a54f7-110">When you open the **Item Tracking Lines** window, availability data is retrieved from the **Item Ledger Entry** table and the **Reservation Entry** table, with no date filter.</span></span> <span data-ttu-id="a54f7-111">Þegar þú velur reitinn **Raðnr.** eða **Lotunr.** opnast glugginn **Samantekt vörurakningar** og birtir samantekt á vörurakningarupplýsingum í töflunni **Frátekningarfærsla**.</span><span class="sxs-lookup"><span data-stu-id="a54f7-111">When you choose the **Serial No.** field or the **Lot No.** field, the **Item Tracking Summary** window opens and shows a summary of the item tracking information in the **Reservation Entry** table.</span></span> <span data-ttu-id="a54f7-112">Þessi samantekt inniheldur eftirfarandi upplýsingar um hvert rað- eða lotunúmer í vörurakningarlínunni:</span><span class="sxs-lookup"><span data-stu-id="a54f7-112">The summary contains the following information about each serial or lot number on the item tracking line:</span></span>  

|<span data-ttu-id="a54f7-113">Svæði</span><span class="sxs-lookup"><span data-stu-id="a54f7-113">Field</span></span>|<span data-ttu-id="a54f7-114">Description</span><span class="sxs-lookup"><span data-stu-id="a54f7-114">Description</span></span>|  
|---------------------------------|---------------------------------------|  
|<span data-ttu-id="a54f7-115">**Heildarmagn**</span><span class="sxs-lookup"><span data-stu-id="a54f7-115">**Total Quantity**</span></span>|<span data-ttu-id="a54f7-116">Heildarmagn rað- eða lotunúmers sem er í birgðum.</span><span class="sxs-lookup"><span data-stu-id="a54f7-116">The total quantity of the serial or lot number that is currently in inventory.</span></span>|  
|<span data-ttu-id="a54f7-117">**Umbeðið magn samtals**</span><span class="sxs-lookup"><span data-stu-id="a54f7-117">**Total Requested Quantity**</span></span>|<span data-ttu-id="a54f7-118">Heildarmagn lotu- eða raðnúmers sem þegar er í beiðni í öllum skjölum.</span><span class="sxs-lookup"><span data-stu-id="a54f7-118">The total quantity of the serial or lot number that is currently requested in all documents.</span></span>|  
|<span data-ttu-id="a54f7-119">**Magn í undirbúningi**</span><span class="sxs-lookup"><span data-stu-id="a54f7-119">**Current Pending Quantity**</span></span>|<span data-ttu-id="a54f7-120">Magnið sem er fært inn í núverandi tilvik í glugganum **Vörurakningarlínur** en hefur enn ekki verið skuldbundið í gagnagrunninum.</span><span class="sxs-lookup"><span data-stu-id="a54f7-120">The quantity that is entered in the current instance of the **Item Tracking Lines** window but is not yet committed to the database.</span></span>|  
|<span data-ttu-id="a54f7-121">**Heildarmagn tiltækt**</span><span class="sxs-lookup"><span data-stu-id="a54f7-121">**Total Available Quantity**</span></span>|<span data-ttu-id="a54f7-122">Tilgreinir tiltækt magn sem notandinn getur tekið frá í þeim gerðum af færslum sem eru í línunni.</span><span class="sxs-lookup"><span data-stu-id="a54f7-122">The quantity of the serial or lot number that is available for the user to request.</span></span><br /><br /> <span data-ttu-id="a54f7-123">Þetta magn er reiknað út frá öðrum reitum í gluggann sem hér segir:</span><span class="sxs-lookup"><span data-stu-id="a54f7-123">This quantity is calculated from other fields in the window as follows:</span></span><br /><br /> <span data-ttu-id="a54f7-124">heildarmagn – (umbeðið heildarmagn + núgildandi magn í bið).</span><span class="sxs-lookup"><span data-stu-id="a54f7-124">total quantity – (total requested quantity + current pending quantity).</span></span>|  

> [!NOTE]  
>  <span data-ttu-id="a54f7-125">Einnig er hægt að sjá upplýsingar í töflunni á undan með því að nota aðgerðina **Velja færslur** í glugganum**Vörurakningarlínur**.</span><span class="sxs-lookup"><span data-stu-id="a54f7-125">You can also see the information in the preceding table by using the **Select Entries** function in the **Item Tracking Lines** window.</span></span>  

 <span data-ttu-id="a54f7-126">Til að varðveita gagnasafn frammistöðu, gögn um magn til ráðstöfunar er aðeins sótt einu sinni úr gagnagrunninum þegar þú opnar **Vörurakningarlínur** glugga og þegar þú notar **Endurnýja Til ráðstöfunar** eiginleikann í glugganum.</span><span class="sxs-lookup"><span data-stu-id="a54f7-126">To preserve database performance, availability data is only retrieved once from the database when you open the **Item Tracking Lines** window and when you use the **Refresh Availability** function in the window.</span></span>  

## <a name="calculation-formula"></a><span data-ttu-id="a54f7-127">Tegund útreiknings</span><span class="sxs-lookup"><span data-stu-id="a54f7-127">Calculation Formula</span></span>  
 <span data-ttu-id="a54f7-128">Eins og lýst er í undanfarandi töflu er framboð á tilteknu raðnúmeri eða lotunúmeri reiknað á eftirfarandi hátt.</span><span class="sxs-lookup"><span data-stu-id="a54f7-128">As described in the preceding table, the availability of a given serial or lot number is calculated as follows.</span></span>  

 <span data-ttu-id="a54f7-129">Allt Laust Magn = magn birgða - (öll eftirspurn + magn ekki enn úthlutað á gagnagrunninum</span><span class="sxs-lookup"><span data-stu-id="a54f7-129">total available quantity = quantity in inventory – (all demands + quantity not yet committed to the database)</span></span>  

> [!IMPORTANT]  
>  <span data-ttu-id="a54f7-130">Þessi formúla gefur til kynna að rað- eða lotunúmer framboðsútreiknings taki aðeins til birgða og hundsi áætlaðar innhreyfingar.</span><span class="sxs-lookup"><span data-stu-id="a54f7-130">This formula implies that the serial or lot number availability calculation considers only inventory and ignores projected receipts.</span></span> <span data-ttu-id="a54f7-131">Í samræmi hefur framboð sem ekki hefur verið bókað í birgðir ekki áhrif á framboð vörurakningar öfugt við eðlilegt vöruframboð þar sem áætlaðar móttökur eru teknar með.</span><span class="sxs-lookup"><span data-stu-id="a54f7-131">Accordingly, supply that is not yet posted to inventory does not affect item tracking availability, as opposed to regular item availability where projected receipts are included.</span></span>  

## <a name="see-also"></a><span data-ttu-id="a54f7-132">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="a54f7-132">See Also</span></span>  
 [<span data-ttu-id="a54f7-133">Hönnunarupplýsingar: vörurakning</span><span class="sxs-lookup"><span data-stu-id="a54f7-133">Design Details: Item Tracking</span></span>](design-details-item-tracking.md)
