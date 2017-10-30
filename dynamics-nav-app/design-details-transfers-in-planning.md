---
title: "Hönnunarupplýsingar - Flutningur í áætlun"
description: "Þetta efnisatriði lýsir því hvernig á að nota flutningspantanir sem uppsprettu framboðs þegar verið er að áætla birgðastig."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: design, transfer, sku, locations, warehouse
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: b2c59ce5c37d5a99135b68ca63d0a2d06e871d7f
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-transfers-in-planning"></a><span data-ttu-id="c91d4-103">Hönnunarupplýsingar: Flutningur í áætlun</span><span class="sxs-lookup"><span data-stu-id="c91d4-103">Design Details: Transfers in Planning</span></span>
<span data-ttu-id="c91d4-104">Millifærslupantanir eru einnig uppspretta framboðs þegar unnið er á birgðahaldseiningarstigi.</span><span class="sxs-lookup"><span data-stu-id="c91d4-104">Transfer orders are also a source of supply when working at the SKU level.</span></span> <span data-ttu-id="c91d4-105">Þegar margar staðsetningar (vöruhús) eru notaðar er hægt að stilla áfyllingarkerfi birgðahaldseininga á Flutning og gefa þannig í skyn að staðsetningin verði áfyllt með því að flytja þangað varning af annarri staðsetningu.</span><span class="sxs-lookup"><span data-stu-id="c91d4-105">When using multiple locations (warehouses), the SKU replenishment system can be set to Transfer, implying that the location is replenished by transferring goods from another location.</span></span> <span data-ttu-id="c91d4-106">Í aðstæðum með fleiri vöruhús, fyrirtæki gætu haft keðju flutnings þar sem framboð til grænar staðsetningar er flutt frá gulum og framboð til gulra er flutt úr rauðum og svo framvegis.</span><span class="sxs-lookup"><span data-stu-id="c91d4-106">In a situation with more warehouses, companies might have a chain of transfers where supply to GREEN location is transferred from YELLOW, and supply to YELLOW is transferred from RED and so on.</span></span> <span data-ttu-id="c91d4-107">Í upphafi af keðjunni er áfyllingarkerfi Framl.pöntun eða innkaup.</span><span class="sxs-lookup"><span data-stu-id="c91d4-107">In the beginning of the chain, there is a replenishment system of Prod. Order or Purchase.</span></span>  
  
![](media/nav_app_supply_planning_7_transfers1.png "NAV_APP_supply_planning_7_transfers1")  
  
<span data-ttu-id="c91d4-108">Við samanburð á ástandinu þar sem birgðapöntun er beint á móti eftirspurnarpöntun við aðstæður þar sem sölupöntun er veitt í gegnum keðju af birgðahaldseiningum, er augljóst að áætlanagerð getur verið mjög flókin í sennna tilvikinu.</span><span class="sxs-lookup"><span data-stu-id="c91d4-108">When comparing the situation where a supply order is directly facing a demand order to a situation where the sales order is supplied through a chain of SKU transfers, it is obvious that the planning task in the latter situation can become very complex.</span></span> <span data-ttu-id="c91d4-109">Ef eftirspurn breytist gæti það valdið keðjuverkun gegnum keðjuna, vegna þess að vinna verður með allar millifærslupantanir auk innkaupa-/framleiðslupöntunarinnar á hinum enda keðjunnar til að koma aftur á jafnvægi milli eftirspurnar og framboðs.</span><span class="sxs-lookup"><span data-stu-id="c91d4-109">If demand changes, it might cause a ripple effect through the chain, because all transfer orders plus the purchase/production order in the opposite end of the chain will have to be manipulated to reestablish balance between demand and supply.</span></span>  
  
![](media/nav_app_supply_planning_7_transfers2.png "NAV_APP_supply_planning_7_transfers2")  
  
## <a name="why-is-transfer-a-special-case"></a><span data-ttu-id="c91d4-110">Hvers vegna er millifærsla sérstakt tilfelli?</span><span class="sxs-lookup"><span data-stu-id="c91d4-110">Why is Transfer a Special Case?</span></span>  
<span data-ttu-id="c91d4-111">Millifærslupöntun lítur svipað út eins aðrar pantanir í forritinu.</span><span class="sxs-lookup"><span data-stu-id="c91d4-111">A transfer order looks much like any other order in the program.</span></span> <span data-ttu-id="c91d4-112">Hins vegar er þetta mjög ólíkt á bak við tjöldin.</span><span class="sxs-lookup"><span data-stu-id="c91d4-112">However, behind the scene it is very different.</span></span>  
  
<span data-ttu-id="c91d4-113">Eitt grundvallaratriði sem greinir millifærslur í áætlun frá innkaupa- og framleiðslupöntununum er að millifærslulína stendur samtímis fyrir eftirspurn og framboð.</span><span class="sxs-lookup"><span data-stu-id="c91d4-113">One fundamental aspect that makes transfers in planning different from purchase and production orders is that a transfer line represents demand and supply at the same time.</span></span> <span data-ttu-id="c91d4-114">Sá hluti sem er á útleið, sem er fluttur af fyrri staðsetningunni, er eftirspurnin.</span><span class="sxs-lookup"><span data-stu-id="c91d4-114">The outbound part, which is shipped from the old location, is demand.</span></span> <span data-ttu-id="c91d4-115">Hlutinn á innleið, sem á að taka við á nýju staðsetningunni, er birgðir á þeirri staðsetningu.</span><span class="sxs-lookup"><span data-stu-id="c91d4-115">The inbound part, which is to be received at the new location, is supply at that location.</span></span>  
  
![](media/nav_app_supply_planning_7_transfers3.png "NAV_APP_supply_planning_7_transfers3")  
  
<span data-ttu-id="c91d4-116">Þetta þýðir að þegar kerfið vinnur á framboðshlið flutningsins, verður það að gera svipaða breytingu á eftirspurnarhlið.</span><span class="sxs-lookup"><span data-stu-id="c91d4-116">This means that when the system manipulates the supply side of the transfer, it must make a similar change on the demand side.</span></span>  
  
## <a name="transfers-are-dependent-demand"></a><span data-ttu-id="c91d4-117">Millifærslur eru háðar Eftirspurn</span><span class="sxs-lookup"><span data-stu-id="c91d4-117">Transfers are Dependent Demand</span></span>  
<span data-ttu-id="c91d4-118">Tengd eftirspurn og birgðir hafa einhver líkindi með íhlutum framleiðslupöntunarlínu en munurinn er sá að íhlutir verða á næsta áætlanastigi og tengjast annarri vöru en millifærsluhlutarnir tveir eru staðsettir á sama stigi og fyrir sömu vöru.</span><span class="sxs-lookup"><span data-stu-id="c91d4-118">The related demand and supply has some resemblance with components of a production order line, but the difference is that components will be on the next planning level and with a different item, whereas the two parts of the transfer is situated on the same level, for the same item.</span></span>  
  
<span data-ttu-id="c91d4-119">Mikilvæg líkindi eru að íhlutir eru bæði háðir eftirspurn og flutningseftirspurn.</span><span class="sxs-lookup"><span data-stu-id="c91d4-119">An important similarity is that just as components are dependent demand, so is the transfer demand.</span></span> <span data-ttu-id="c91d4-120">Eftirspurn frá millifærslulínu er ráðist af framboðshlið millifærslu í þeim skilningi að ef framboð er breytt, að eftirspurn er fyrir beinum áhrifum.</span><span class="sxs-lookup"><span data-stu-id="c91d4-120">The demand from a transfer line is dictated by the supply side of the transfer in the sense that if the supply is changed, the demand is directly affected.</span></span>  
  
<span data-ttu-id="c91d4-121">Nema sveigjanleiki áætlunar sé enginn, ætti millifærslulína aldrei að meðhöndla eins og sjálfstæða eftirspurn í áætlanagerð.</span><span class="sxs-lookup"><span data-stu-id="c91d4-121">Unless the planning flexibility is None, a transfer line should never be treated as independent demand in planning.</span></span>  
  
<span data-ttu-id="c91d4-122">Í áætlanaferli er flutningseftirspurn aðeins að taka tillit til þegar framboðshlið hefur verið unnin af áætlanakerfi.</span><span class="sxs-lookup"><span data-stu-id="c91d4-122">In the planning procedure, the transfer demand should only be taken into account after the supply side has been processed by the planning system.</span></span> <span data-ttu-id="c91d4-123">Áður en þetta, er raunveruleg eftirspurn ekki þekkt.</span><span class="sxs-lookup"><span data-stu-id="c91d4-123">Before this, the actual demand is not known.</span></span> <span data-ttu-id="c91d4-124">Röð breytinga er af þeim sökum mjög mikilvæg hvað varðar flutningspantanir.</span><span class="sxs-lookup"><span data-stu-id="c91d4-124">The sequence of the changes made is therefore very important when it comes to transfer orders.</span></span>  
  
## <a name="planning-sequence"></a><span data-ttu-id="c91d4-125">Áætlunarröð</span><span class="sxs-lookup"><span data-stu-id="c91d4-125">Planning Sequence</span></span>  
<span data-ttu-id="c91d4-126">Eftirfarandi mynd sýnir hvernig millifærslustrengur gæti litið út.</span><span class="sxs-lookup"><span data-stu-id="c91d4-126">The following illustration shows what a string of transfers could look like.</span></span>  
  
![](media/nav_app_supply_planning_7_transfers4.png "NAV_APP_supply_planning_7_transfers4")  
  
<span data-ttu-id="c91d4-127">Í þessu dæmi, viðskiptamaður pantar vöru á græna staðsetningu.</span><span class="sxs-lookup"><span data-stu-id="c91d4-127">In this example, a customer orders the item at location GREEN.</span></span> <span data-ttu-id="c91d4-128">Birgðageymslan GRÆNT fær tilföng með millifærslu frá miðlæga vöruhúsinu RAUTT.</span><span class="sxs-lookup"><span data-stu-id="c91d4-128">Location GREEN is supplied through transfer from the central warehouse RED.</span></span> <span data-ttu-id="c91d4-129">Aðalvöruhús RED fæst með millifærslu frá framleiðslu á staðsetningu blár.</span><span class="sxs-lookup"><span data-stu-id="c91d4-129">The central warehouse RED is supplied by transfer from production on location BLUE.</span></span>  
  
<span data-ttu-id="c91d4-130">Í þessu dæmi er áætlanakerfi mun byrja á viðskiptamannseftirspurn og vinna sig aftur í gegnum keðju.</span><span class="sxs-lookup"><span data-stu-id="c91d4-130">In this example, the planning system will start at the customer demand and work its way backwards through the chain.</span></span> <span data-ttu-id="c91d4-131">Kröfur og birgðir verða meðhöndlaðar á eina staðsetningu í einu.</span><span class="sxs-lookup"><span data-stu-id="c91d4-131">The demands and supplies will be processed one location at a time.</span></span>  
  
![](media/nav_app_supply_planning_7_transfers5.png "NAV_APP_supply_planning_7_transfers5")  
  
## <a name="transfer-level-code"></a><span data-ttu-id="c91d4-132">Flutningsstigskóði</span><span class="sxs-lookup"><span data-stu-id="c91d4-132">Transfer Level Code</span></span>  
<span data-ttu-id="c91d4-133">Röðin sem staðsetningar eru unnar í áætlanakerfinu er ákveðin af flutningsstigskóðanum í birgðahaldseiningunni.</span><span class="sxs-lookup"><span data-stu-id="c91d4-133">The sequence in which the locations are processed in the planning system is determined by the transfer level code of the SKU.</span></span>  
  
<span data-ttu-id="c91d4-134">Flutningsstigskóði er innri reitur sem er reiknaður sjálfkrafa og vistaður í birgðahaldseiningunni þegar hún er stofnuð eða henni breytt.</span><span class="sxs-lookup"><span data-stu-id="c91d4-134">The transfer level code is an internal field which is automatically calculated and stored on the SKU when SKU is created or modified.</span></span> <span data-ttu-id="c91d4-135">Útreikningur nær yfir allt BHE fyrir tiltekið samsetningu vöru/afbrigðis og notar staðsetningarkóðann og millifærslukóða til að ákvarða leiðina sem áætlun verður að nota í gegnum BHE til að tryggja að allar kröfur eru afgreidd.</span><span class="sxs-lookup"><span data-stu-id="c91d4-135">The calculation runs across all SKUs for a given combination of Item/Variant and uses the location code and the transfer-from code to determine the route the planning will have to use when traversing through the SKUs to ensure that all demands are processed.</span></span>  
  
<span data-ttu-id="c91d4-136">Flutningsstigskóði verður 0 fyrir birgðahaldseiningar með áfyllingarkerfi, Innkaupa- eða Framl.pöntun og verður -1 fyrir fyrsta flutningsstigið, -2 fyrir það næsta o.s.frv.</span><span class="sxs-lookup"><span data-stu-id="c91d4-136">The transfer level code will be 0 for SKUs with replenishment system Purchase or Prod. Order and will be -1 for the first transfer level, -2 for the second and so on.</span></span> <span data-ttu-id="c91d4-137">Í flutningskeðju sem lýst er hér að ofan, stigið væri því -1 fyrir rautt og -2 til Green, eins og sést á eftirfarandi mynd.</span><span class="sxs-lookup"><span data-stu-id="c91d4-137">In the transfer chain described above, the levels would therefore be -1 for RED and -2 for GREEN, as shown in the following illustration.</span></span>  
  
![](media/nav_app_supply_planning_7_transfers6.gif "NAV_APP_supply_planning_7_transfers6")  
  
<span data-ttu-id="c91d4-138">Þegar birgðahaldseining er endurnýjuð greinir áætlanakerfið hvort birgðahaldseiningar með uppsettu áfyllingarkerfi millifærsla eru settar upp með hringlaga tilvísunum.</span><span class="sxs-lookup"><span data-stu-id="c91d4-138">When updating a SKU, the planning system will detect if SKUs with replenishment system Transfer are set up with circular references.</span></span>  
  
## <a name="planning-transfers-without-sku"></a><span data-ttu-id="c91d4-139">Áætlun millifærslna án BHE</span><span class="sxs-lookup"><span data-stu-id="c91d4-139">Planning Transfers without SKU</span></span>  
  
<span data-ttu-id="c91d4-140">Jafnvel þótt birgðahaldseiningareiginleikinn sé ekki notaður er hægt að nota staðsetningar og gera handvirkan flutning milli staðsetninga.</span><span class="sxs-lookup"><span data-stu-id="c91d4-140">Even if the SKU feature is not used, it is possible to use locations and make manual transfers between locations.</span></span> <span data-ttu-id="c91d4-141">Fyriri fyrirtæki með einfaldari vöruhúsauppsetningu styður áætlunargerðarkerfið aðstæður þar sem fyrirliggjandi birgðir eru fluttar handvirkt á annan stað, til dæmis til að sinna sölupöntun á þeim stað.</span><span class="sxs-lookup"><span data-stu-id="c91d4-141">For companies with less advanced warehouse setup, the planning system supports scenarios where existing inventory is transferred manually to another location, for example to cover a sales order at that location.</span></span> <span data-ttu-id="c91d4-142">Á sama tíma, ætti áætlanakerfið að bregðast við breytingum í eftirspurn.</span><span class="sxs-lookup"><span data-stu-id="c91d4-142">At the same time, the planning system should react to changes in the demand.</span></span>  
  
<span data-ttu-id="c91d4-143">Til að styðja handvirka millifærslur greinir áætlunargerðin núverandi flutningspöntun og svo skipuleggur í hvaða röð á að vinna staðsetningar.</span><span class="sxs-lookup"><span data-stu-id="c91d4-143">To support manual transfers, the planning will analyze existing transfer orders and then plan the order in which the locations should be processed.</span></span> <span data-ttu-id="c91d4-144">Innbyrðis, mun áætlanakerfið stýra bráðabirgða birgðahaldseiningum sem innihalda flutningsstigskóða.</span><span class="sxs-lookup"><span data-stu-id="c91d4-144">Internally, the planning system will operate with temporary SKUs carrying transfer level codes.</span></span>  
  
![](media/nav_app_supply_planning_7_transfers7.png "NAV_APP_supply_planning_7_transfers7")  
  
<span data-ttu-id="c91d4-145">Ef fleiri millifærslur á tiltekinn stað eru til staðar skilgreinir fyrsta millifærslupöntunin áætlunarstefnuna.</span><span class="sxs-lookup"><span data-stu-id="c91d4-145">If more transfers to a given location exist, the first transfer order will define the planning direction.</span></span> <span data-ttu-id="c91d4-146">Millifærslur sem keyra í  í gagnstæða átt verður eytt.</span><span class="sxs-lookup"><span data-stu-id="c91d4-146">Transfers running in the opposite direction will be canceled.</span></span>  
  
## <a name="changing-quantity-with-reservations"></a><span data-ttu-id="c91d4-147">Breyting magni með frátekningum</span><span class="sxs-lookup"><span data-stu-id="c91d4-147">Changing Quantity with Reservations</span></span>  
<span data-ttu-id="c91d4-148">Þegar breyta á  magni af núverandi framboð,tekur  áætlanagerð tillit til frátekninga í þeim skilningi að fráteknið magn táknar neðri mörk fyrir hversu mikið framboð er hægt að minnka.</span><span class="sxs-lookup"><span data-stu-id="c91d4-148">When changing quantities on existing supply, the planning system takes reservations into account in the sense that the reserved quantity represents the lower limit for how much the supply can be reduced.</span></span>  
  
<span data-ttu-id="c91d4-149">Þegar breyta á magn á núverandi flutningspöntunarlína, hafa í huga að neðri mörk verður skilgreint sem hæsta frátekna magn á útleiðar og innleiðar flutningslínu</span><span class="sxs-lookup"><span data-stu-id="c91d4-149">When changing the quantity on an existing transfer order line, keep in mind that the lower limit will be defined as the highest reserved quantity of the outbound and inbound transfer line.</span></span>  
  
<span data-ttu-id="c91d4-150">Til dæmis ef flutningspöntunarlína 117 hluta er frátekin á sölulínu með 46 og innkaupalínu með 24 er ekki hægt að lækka flutningslínuna undir 46 hluti jafnvel þótt þetta gæti endurspeglað umframframboð á innleiðarhlið.</span><span class="sxs-lookup"><span data-stu-id="c91d4-150">For example, if a transfer order line of 117 pieces is reserved against a sales line of 46 and a purchase line of 24, it is not possible to reduce the transfer line below 46 pieces even though this might represent excess supply on the inbound side.</span></span>  
  
![](media/nav_app_supply_planning_7_transfers8.png "NAV_APP_supply_planning_7_transfers8")  
  
## <a name="changing-quantity-in-a-transfer-chain"></a><span data-ttu-id="c91d4-151">Breyting á magni í flutningskeðju</span><span class="sxs-lookup"><span data-stu-id="c91d4-151">Changing Quantity in a Transfer Chain</span></span>  
<span data-ttu-id="c91d4-152">Í eftirfarandi dæmi er upphafið er jöfnuð  staða með flutningskeðju sem býður sölupöntun með 27 á rauðri staðsetningu með samsvarandi innkaupapöntun á staðsetningunni Blá, flutt á staðsetninguna Bleikt.</span><span class="sxs-lookup"><span data-stu-id="c91d4-152">In the following example, the starting point is a balanced situation with a transfer chain supplying a sales order of 27 on location RED with a corresponding purchase order on location BLUE, transferred via location PINK.</span></span> <span data-ttu-id="c91d4-153">Því eru tvær flutningspantanir, fyrir utan sölu og kaup: BLÁTT-BLEIKT og BLEIKT-RAUTT.</span><span class="sxs-lookup"><span data-stu-id="c91d4-153">Therefore, apart from sales and purchase, there are two transfer orders: BLUE-PINK and PINK-RED.</span></span>  
  
![](media/nav_app_supply_planning_7_transfers9.png "NAV_APP_supply_planning_7_transfers9")  
  
<span data-ttu-id="c91d4-154">Nú velur áætlun í birgðageymslunni BLEIKT frátekt á móti innkaupum.</span><span class="sxs-lookup"><span data-stu-id="c91d4-154">Now the planner at PINK location chooses to reserve against the purchase.</span></span>  
  
![](media/nav_app_supply_planning_7_transfers10.png "NAV_APP_supply_planning_7_transfers10")  
  
<span data-ttu-id="c91d4-155">Þetta þýðir yfirleitt að áætlanakerfi mun hunsa innkaupapöntun og flytja eftirspurn.</span><span class="sxs-lookup"><span data-stu-id="c91d4-155">This usually means that the planning system will ignore the purchase order and the transfer demand.</span></span> <span data-ttu-id="c91d4-156">Svo lengi sem staða er fyrir hendi er ekkert vandamál.</span><span class="sxs-lookup"><span data-stu-id="c91d4-156">As long as there is balance, there is no problem.</span></span> <span data-ttu-id="c91d4-157">En hvað gerist þegar viðskiptavinur á RAUÐUM stað breytir pöntun sinni í 22?</span><span class="sxs-lookup"><span data-stu-id="c91d4-157">But what happens when the customer at RED location partly regrets his order and changes it to 22?</span></span>  
  
![](media/nav_app_supply_planning_7_transfers11.png "NAV_APP_supply_planning_7_transfers11")  
  
<span data-ttu-id="c91d4-158">Þegar áætlanakerfið er keyrt aftur ætti það að losa sig við umfram framboð.</span><span class="sxs-lookup"><span data-stu-id="c91d4-158">When the planning system runs again, it should get rid of excess supply.</span></span> <span data-ttu-id="c91d4-159">Hins vegar læsir frátekningin kaupunum og yfirfærir svo í magnið 27.</span><span class="sxs-lookup"><span data-stu-id="c91d4-159">However, the reservation will lock the purchase and the transfer to a quantity of 27.</span></span>  
  
![](media/nav_app_supply_planning_7_transfers12.png "NAV_APP_supply_planning_7_transfers12")  
  
<span data-ttu-id="c91d4-160">BLEIKTRAUTT pöntunin hefur verið minnkuð niður í 22.</span><span class="sxs-lookup"><span data-stu-id="c91d4-160">The PINK-RED transfer has been reduced to 22.</span></span> <span data-ttu-id="c91d4-161">Sá hluti af BLÁTTBLEIKT tilfærslunni sem er á innleið er ekki frátekinn en þar sem hlutinn á útleið er frátekinn er ekki hægt að minnka magnið niður fyrir 27.</span><span class="sxs-lookup"><span data-stu-id="c91d4-161">The inbound part of the BLUE-PINK transfer is not reserved, but because the outbound part is reserved it is not possible to reduce the quantity below 27.</span></span>  
  
## <a name="lead-time-calculation"></a><span data-ttu-id="c91d4-162">Útreikn. afhendingartíma</span><span class="sxs-lookup"><span data-stu-id="c91d4-162">Lead Time Calculation</span></span>  
<span data-ttu-id="c91d4-163">Við útreikning á skiladegi flutningspöntunar er tekið mið af mismunandi tegundir af afhendingartíma.</span><span class="sxs-lookup"><span data-stu-id="c91d4-163">When calculating the due date of a transfer order different kinds of lead time will be taken into account.</span></span>  
  
<span data-ttu-id="c91d4-164">Afhendingartímar sem eru virkir þegar millifærslupöntun er áætluð eru:</span><span class="sxs-lookup"><span data-stu-id="c91d4-164">The lead times that are active when planning a transfer order are:</span></span>  
  
* <span data-ttu-id="c91d4-165">Afgreiðslutími á vörum út úr vöruhúsi</span><span class="sxs-lookup"><span data-stu-id="c91d4-165">Outbound Warehouse Handling Time</span></span>  
* <span data-ttu-id="c91d4-166">Afhendingartími</span><span class="sxs-lookup"><span data-stu-id="c91d4-166">Shipping Time</span></span>  
* <span data-ttu-id="c91d4-167">Afgreiðslutími á vörum inn í vöruhús</span><span class="sxs-lookup"><span data-stu-id="c91d4-167">Inbound Warehouse Handling Time</span></span>  
* <span data-ttu-id="c91d4-168">Á áætlunarlínunni eru eftirfarandi reitir notaðir til að veita upplýsingar um útreikninginn.</span><span class="sxs-lookup"><span data-stu-id="c91d4-168">On the planning line, the following fields are used to provide information about the calculation.</span></span>  
* <span data-ttu-id="c91d4-169">Afh.dags. millifærslu</span><span class="sxs-lookup"><span data-stu-id="c91d4-169">Transfer Shipment Date</span></span>  
* <span data-ttu-id="c91d4-170">Upphafsdagsetning</span><span class="sxs-lookup"><span data-stu-id="c91d4-170">Starting Date</span></span>  
* <span data-ttu-id="c91d4-171">Lokadagsetning</span><span class="sxs-lookup"><span data-stu-id="c91d4-171">Ending Date</span></span>  
* <span data-ttu-id="c91d4-172">Skiladagur</span><span class="sxs-lookup"><span data-stu-id="c91d4-172">Due Date</span></span>  
  
<span data-ttu-id="c91d4-173">Afhendingardagur flutningslínunnar verður sýnd í reitnum Dagsetning flutningsafhendingar og móttökudagsetning flutningslínunnar er sýnd í reitnum Skiladagur.</span><span class="sxs-lookup"><span data-stu-id="c91d4-173">The shipment date of the transfer line will be shown in the Transfer Shipment Date field, and the receipt date of the transfer line will be shown in the Due Date field.</span></span>  
  
<span data-ttu-id="c91d4-174">Upphafs- og lokadagsetningar verða notaðar til að lýsa raunverulegu flutningstímabili.</span><span class="sxs-lookup"><span data-stu-id="c91d4-174">The starting and ending dates will be used to describe the actual transportation period.</span></span>  
  
<span data-ttu-id="c91d4-175">Eftirfarandi mynd sýnir túlkun á tíma upphafsdagsetningar og tíma lokadagsetningar á áætlanagerðarlínum sem tengjast millifærslupöntunum.</span><span class="sxs-lookup"><span data-stu-id="c91d4-175">The following illustration shows the interpretation of the starting date-time and ending date-time on planning lines related to transfer orders.</span></span>  
  
![](media/nav_app_supply_planning_7_transfers13.png "NAV_APP_supply_planning_7_transfers13")  
  
<span data-ttu-id="c91d4-176">Í þessu dæmi, þýðir það að:</span><span class="sxs-lookup"><span data-stu-id="c91d4-176">In this example, it means that:</span></span>  
  
* <span data-ttu-id="c91d4-177">Afhendingardagsetning + Afgreiðsla á útleið = Upphafsdagsetning</span><span class="sxs-lookup"><span data-stu-id="c91d4-177">Shipment date + Outbound handling = Starting Date</span></span>  
* <span data-ttu-id="c91d4-178">Upphafsdagsetning + Afhendingartími = Lokadagsetning</span><span class="sxs-lookup"><span data-stu-id="c91d4-178">Starting Date + Shipping time = Ending Date</span></span>  
* <span data-ttu-id="c91d4-179">Lokadagsetning + Afgreiðslutími inn í vöruhús = Móttökudagsetning</span><span class="sxs-lookup"><span data-stu-id="c91d4-179">Ending Date + Inbound Handling = Receipt Date</span></span>  
  
## <a name="safety-lead-time"></a><span data-ttu-id="c91d4-180">Öryggisforskot</span><span class="sxs-lookup"><span data-stu-id="c91d4-180">Safety Lead Time</span></span>  
<span data-ttu-id="c91d4-181">Reiturinn Sjálfgefið öryggisforskot í glugganum Uppsetning framleiðslu og tengdi reiturinn Öryggisforskot á vöruspjaldinu mun ekki taka tillit til við útreikning á að millifærslupöntun.</span><span class="sxs-lookup"><span data-stu-id="c91d4-181">The Default Safety Lead Time field in the Manufacturing Setup window and the related Safety Lead Time field on the item card will not be taken into account in the calculation of a transfer order.</span></span> <span data-ttu-id="c91d4-182">Hins vegar hefur öryggisafhendingartíminn áfram áhrif á heildaráætlunina eins og hann hefur áhrif á áfyllingarpöntunina (kaup eða framleiðslu) í upphafi flutningskeðjunnar þegar vörurnar eru settar á staðinn þaðan sem þær verða fluttar.</span><span class="sxs-lookup"><span data-stu-id="c91d4-182">However, the safety lead time will still influence the total plan like it will affect the replenishment order (purchase or production) in the beginning of the transfer chain when the items are put on the location from which they will be transferred.</span></span>  
  
![](media/nav_app_supply_planning_7_transfers14.png "NAV_APP_supply_planning_7_transfers14")  
  
<span data-ttu-id="c91d4-183">Í framleiðslupöntunarlínunni Lokadagsetning + Öryggisforskot + Afgreiðslutími vara á innleið í vöruhús = Gjalddagi.</span><span class="sxs-lookup"><span data-stu-id="c91d4-183">On the production order line, the Ending Date + Safety Lead Time + Inbound Warehouse Handling Time = Due Date.</span></span>  
  
<span data-ttu-id="c91d4-184">Í innkaupapöntunarlínunni Ráðgerð móttökudagsetning + Öryggisforskot + Afgreiðslutími vara á innleið í vöruhús Áætluð móttökudagsetning.</span><span class="sxs-lookup"><span data-stu-id="c91d4-184">On the purchase order line, the Planned Receipt Date + Safety Lead Time + Inbound Warehouse Handling Time = Expected Receipt Date.</span></span>  
  
## <a name="reschedule"></a><span data-ttu-id="c91d4-185">Endurtímasetja</span><span class="sxs-lookup"><span data-stu-id="c91d4-185">Reschedule</span></span>  
<span data-ttu-id="c91d4-186">Þegar fyrirliggjandi flutningslína er enduráætluð verður áætlanakerfi að fletta upp hlutanum á útleið og breyta dagsetningu og tíma hans.</span><span class="sxs-lookup"><span data-stu-id="c91d4-186">When rescheduling an existing transfer line, the planning system must look up the outbound part and change the date-time on this.</span></span> <span data-ttu-id="c91d4-187">Mikilvægt er að hafa í huga að ef afhendingartími hefur tilgreindur verður bil á milli afhendignar og móttöku.</span><span class="sxs-lookup"><span data-stu-id="c91d4-187">It is important to note that if lead time has been defined, there will be a gap between the shipment and the receipt.</span></span> <span data-ttu-id="c91d4-188">Eins og fyrr segir getur afhendingartími samanstaðið af fleiri einingum, eins og flutningstíma og meðhöndlunartíma í vöruhúsi.</span><span class="sxs-lookup"><span data-stu-id="c91d4-188">As mentioned, the lead time can consist of more elements, such as transportation time and warehouse handling time.</span></span> <span data-ttu-id="c91d4-189">Á tímalínu mun áætlanakerfið fara aftur í tímann á með það jafnar stöðu eininganna.</span><span class="sxs-lookup"><span data-stu-id="c91d4-189">On a time line, the planning system will move back in time while it balances the elements.</span></span>  
  
![](media/nav_app_supply_planning_7_transfers15.png "NAV_APP_supply_planning_7_transfers15")  
  
<span data-ttu-id="c91d4-190">Þegar gjalddaga er því breytt á flutningslínu þarf afhendingartími að vera reiknaður til að hægt sé að uppfæra þann hluta færslunnar sem er á útleið.</span><span class="sxs-lookup"><span data-stu-id="c91d4-190">Therefore, when changing the due date on a transfer line, the lead time must be calculated in order to update the outbound side of the transfer.</span></span>  
  
## <a name="seriallot-numbers-in-transfer-chains"></a><span data-ttu-id="c91d4-191">Rað-/Lotunúmer í millifærslukeðjum</span><span class="sxs-lookup"><span data-stu-id="c91d4-191">Serial/Lot Numbers in Transfer Chains</span></span>  
<span data-ttu-id="c91d4-192">Ef eftirspurn er með raðnúmer/lotunúmer og áætlunarvélin er keyrð leiðir það til þess að millifærslupantanir eru stofnaðar beint.</span><span class="sxs-lookup"><span data-stu-id="c91d4-192">If the demand carries serial/lot numbers, and the planning engine is run, it will give rise to some directly created transfer orders.</span></span> <span data-ttu-id="c91d4-193">Nánari upplýsingar um þetta hugtak eru í Eigindir vöru.</span><span class="sxs-lookup"><span data-stu-id="c91d4-193">For more information about this concept, see Item Attributes.</span></span> <span data-ttu-id="c91d4-194">Ef hins vegar raðnúmer / lotunúmeri eru fjarlægð úr eftirspurn, skapað flutningspantanir í keðjunni mun enn bera raðnúmer / lotunúmeri og mun því vera hunsuð af áætlanagerð (ekki eytt).</span><span class="sxs-lookup"><span data-stu-id="c91d4-194">If, however, serial/lot numbers are removed from the demand, the created transfer orders in the chain will still carry the serial/lot numbers and will therefore be ignored by planning (not deleted).</span></span>  
  
## <a name="order-to-order-links"></a><span data-ttu-id="c91d4-195">Tenglar á milli pantana</span><span class="sxs-lookup"><span data-stu-id="c91d4-195">Order-to-Order Links</span></span>  
<span data-ttu-id="c91d4-196">Í þessu dæmi, blá birgðahaldseining er sett upp við röð endurpöntunarstefnu, en bleikur og rauður nota Lotu -fyrir-Lotu.</span><span class="sxs-lookup"><span data-stu-id="c91d4-196">In this example, BLUE SKU is set up with the Order reordering policy, while PINK and RED use Lot-for-Lot.</span></span> <span data-ttu-id="c91d4-197">Þegar sölupöntun upp á 27 er búin til á rauðri staðsetningu mun það leiða til flutningskeðju með síðasta sameiginlega lið á blárri staðsetningu með frátekningu með bindingu.</span><span class="sxs-lookup"><span data-stu-id="c91d4-197">When a sales order of 27 is created on location RED, it will lead to a chain of transfers with the last joint at location BLUE being reserved with binding.</span></span> <span data-ttu-id="c91d4-198">Í þessu dæmi, eru frátekningar ekki harðar frátekningar búnar til af skipuleggjandi á bleikum stað, heldur bindingar búnar til af áætlanakerfinu.</span><span class="sxs-lookup"><span data-stu-id="c91d4-198">In this example, the reservations are not hard reservations created by the planner at PINK location, but bindings created by the planning system.</span></span> <span data-ttu-id="c91d4-199">Veigamesti munurinn er að áætlunarkerfið getur breytt því síðarnefnda.</span><span class="sxs-lookup"><span data-stu-id="c91d4-199">The important difference is that the planning system can change the latter.</span></span>  
  
![](media/nav_app_supply_planning_7_transfers16.png "NAV_APP_supply_planning_7_transfers16")  
  
<span data-ttu-id="c91d4-200">Ef eftirspurn er breytt úr 27 í 22 lækkar kerfið magnið niður í gegnum keðjuna, og bindandi frátekning er einnig minnkuð.</span><span class="sxs-lookup"><span data-stu-id="c91d4-200">If demand is changed from 27 to 22, the system will lower the quantity down through the chain, with the binding reservation also being reduced.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="c91d4-201">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="c91d4-201">See Also</span></span>  
<span data-ttu-id="c91d4-202">[Hönnunarupplýsingar: Áætlunarfæribreytur](design-details-planning-parameters.md) </span><span class="sxs-lookup"><span data-stu-id="c91d4-202">[Design Details: Planning Parameters](design-details-planning-parameters.md) </span></span>  
<span data-ttu-id="c91d4-203">[Hönnunarupplýsingar: áætlunartafla](design-details-planning-assignment-table.md) </span><span class="sxs-lookup"><span data-stu-id="c91d4-203">[Design Details: Planning Assignment Table](design-details-planning-assignment-table.md) </span></span>  
<span data-ttu-id="c91d4-204">[Hönnunarupplýsingar: Meðhöndlun endurpöntunarstefna](design-details-handling-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="c91d4-204">[Design Details: Handling Reordering Policies](design-details-handling-reordering-policies.md) </span></span>  
<span data-ttu-id="c91d4-205">[Hönnunarupplýsingar: Eftirspurn í birgðageymslunni TÓMT](design-details-demand-at-blank-location.md) </span><span class="sxs-lookup"><span data-stu-id="c91d4-205">[Design Details: Demand at Blank Location](design-details-demand-at-blank-location.md) </span></span>  
<span data-ttu-id="c91d4-206">[Hönnunarupplýsingar: Miðlægar hugmyndir áætlanakerfisins](design-details-central-concepts-of-the-planning-system.md) </span><span class="sxs-lookup"><span data-stu-id="c91d4-206">[Design Details: Central Concepts of the Planning System](design-details-central-concepts-of-the-planning-system.md) </span></span>  
<span data-ttu-id="c91d4-207">[Hönnunarupplýsingar: Jöfnun eftirspurnar og framboðs](design-details-balancing-demand-and-supply.md) </span><span class="sxs-lookup"><span data-stu-id="c91d4-207">[Design Details: Balancing Demand and Supply](design-details-balancing-demand-and-supply.md) </span></span>  
[<span data-ttu-id="c91d4-208">Hönnunarupplýsingar: framboðsáætlun</span><span class="sxs-lookup"><span data-stu-id="c91d4-208">Design Details: Supply Planning</span></span>](design-details-supply-planning.md)