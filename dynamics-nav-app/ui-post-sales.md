---
title: "Sölubókun"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: e87dd5faf7713aecfbe7209d00bb8076fcae9d25
ms.contentlocale: is-is
ms.lasthandoff: 07/19/2017

---

# <a name="posting-sales"></a><span data-ttu-id="aa445-102">Sölubókun</span><span class="sxs-lookup"><span data-stu-id="aa445-102">Posting Sales</span></span>
<span data-ttu-id="aa445-103">Í **bókunarflokki** á söluskjali er hægt að velja milli eftirfarandi bókunaraðgerða:</span><span class="sxs-lookup"><span data-stu-id="aa445-103">In the **Posting group** on a sales document, you can choose between the following posting functions:</span></span>

- <span data-ttu-id="aa445-104">**Færsla**</span><span class="sxs-lookup"><span data-stu-id="aa445-104">**Post**</span></span>
- <span data-ttu-id="aa445-105">**Prófunarskýrsla**</span><span class="sxs-lookup"><span data-stu-id="aa445-105">**Test Report**</span></span>
- <span data-ttu-id="aa445-106">**Bóka og senda**</span><span class="sxs-lookup"><span data-stu-id="aa445-106">**Post and Send**</span></span>
- <span data-ttu-id="aa445-107">**Bóka og prenta**</span><span class="sxs-lookup"><span data-stu-id="aa445-107">**Post and Print**</span></span>
- <span data-ttu-id="aa445-108">**Bóka og senda í tölvupósti**</span><span class="sxs-lookup"><span data-stu-id="aa445-108">**Post and Email**</span></span>
- <span data-ttu-id="aa445-109">**Bóka runu**</span><span class="sxs-lookup"><span data-stu-id="aa445-109">**Post Batch**</span></span>
- <span data-ttu-id="aa445-110">**Forskoðun bókunar**</span><span class="sxs-lookup"><span data-stu-id="aa445-110">**Preview Posting**</span></span>

<span data-ttu-id="aa445-111">Þegar lokið hefur verið við allar línurnar og allar upplýsingar færðar á sölupöntunina er hægt að bóka hana.</span><span class="sxs-lookup"><span data-stu-id="aa445-111">When you have completed all the lines and entered all the information on the sales order, you can post it.</span></span> <span data-ttu-id="aa445-112">Þetta stofnar afhendingu og reikning.</span><span class="sxs-lookup"><span data-stu-id="aa445-112">This creates a shipment and an invoice.</span></span>

<span data-ttu-id="aa445-113">Þegar sölupöntun er bókuð, eru reikningur viðskiptavinar, fjárhagurinn og birgðahöfuðbókarfærslur uppfærðar.</span><span class="sxs-lookup"><span data-stu-id="aa445-113">When a sales order is posted, the customer's account, the general ledger, and the item ledger entries are updated.</span></span>

<span data-ttu-id="aa445-114">Sölufærsla er stofnuð í töflunni G/L Entry **fjárhagsfærsla** fyrir hverja sölupöntun.</span><span class="sxs-lookup"><span data-stu-id="aa445-114">For each sales order, a sales entry is created in the **G/L Entry** table.</span></span> <span data-ttu-id="aa445-115">Færsla er einnig stofnuð í reikningi viðskiptamanns í töflunni **sérsniðin fjárhagsfærsla** og fjárhagsfærsla er stofnuð í viðeigandi safnreikningi viðskiptamanns.</span><span class="sxs-lookup"><span data-stu-id="aa445-115">An entry is also created in the customer's account in the **Cust. Ledger Entry** table and a general ledger entry is created in the relevant receivables account.</span></span> <span data-ttu-id="aa445-116">Auk þess getur bókun pöntunarinnar leitt til VSK-færslu og fjárhagsfærslu vegna afsláttar.</span><span class="sxs-lookup"><span data-stu-id="aa445-116">In addition, posting the order may result in a VAT entry and a general ledger entry for the discount amount.</span></span> <span data-ttu-id="aa445-117">Hvort færsla vegna afsláttar er bókuð fer eftir því sem er í glugganum **Afsláttarbókun** í töflunni **Sölugrunnur**.</span><span class="sxs-lookup"><span data-stu-id="aa445-117">Whether an entry for the discount is posted depends on the contents of the **Discount Posting** field in the **Sales & Receivables Setup** window.</span></span>

<span data-ttu-id="aa445-118">Birgðafærsla er stofnuð í töflunni **birgðafærsla** fyrir hverja sölupöntunarlínu (ef línurnar eru með vörunúmerum) eða þá að fjárhagsfærsla er stofnuð í töflunni **Fjárhagsfærsla** (ef fjárhagsreikningur er í sölulínunum).</span><span class="sxs-lookup"><span data-stu-id="aa445-118">For each sales order line, an item ledger entry will be created in the **Item Ledger Entry** table (if the sales lines contain item numbers) or a general ledger entry will be created in the **G/L Entry** table (if the sales lines contain a general ledger account).</span></span> <span data-ttu-id="aa445-119">Auk þess eru sölupantanir alltaf skráðar í töflunum **Söluafhendingarhaus** og **Sölureikningshaus**.</span><span class="sxs-lookup"><span data-stu-id="aa445-119">In addition to this, sales orders are always recorded in the **Sales Shipment Header** and **Sales Invoice Header** tables.</span></span>

<span data-ttu-id="aa445-120">**Mikilvægt** Þegar pöntun er bókuð er hægt að búa til bæði afhendingu og reikning.</span><span class="sxs-lookup"><span data-stu-id="aa445-120">**Important**: When you post an order, you can create both a shipment and an invoice.</span></span> <span data-ttu-id="aa445-121">Það er hægt að gera á sama tíma eða hvort í sínu lagi.</span><span class="sxs-lookup"><span data-stu-id="aa445-121">These can be done at the same time or independently.</span></span> <span data-ttu-id="aa445-122">Einnig er hægt að mynda hlutaafhendingu og gera hlutareikning með því að fylla út reitina **magn til að flytja** og/eða **magn til að reikningsfæra** í einstökum sölupöntunarlínum áður en bókað er.</span><span class="sxs-lookup"><span data-stu-id="aa445-122">You can also create a partial shipment and a partial invoice by completing the **Qty. to Ship** and **Qty. to Invoice** fields on the individual sales order lines before you post.</span></span> <span data-ttu-id="aa445-123">Bent er á að ekki er hægt að búa til reikning fyrir eitthvað sem ekki er afhent.</span><span class="sxs-lookup"><span data-stu-id="aa445-123">Note that you cannot create an invoice for something that is not shipped.</span></span> <span data-ttu-id="aa445-124">Það er að segja, áður en hægt er að gera reikning verður afhending að vera skráð, nema afhending sé skráð um leið og reikningur er gerður.</span><span class="sxs-lookup"><span data-stu-id="aa445-124">That is, before you can invoice, you must have recorded a shipment, or you must choose to ship and invoice at the same time.</span></span> 

<span data-ttu-id="aa445-125">Þegar bókun er lokið hverfa bókuðu sölulínurnar úr pöntuninni.</span><span class="sxs-lookup"><span data-stu-id="aa445-125">When the posting is completed, the posted sales lines are removed from the order.</span></span> <span data-ttu-id="aa445-126">Skilaboð segja til um hvenær bókun er lokið.</span><span class="sxs-lookup"><span data-stu-id="aa445-126">A message tells you when the posting is completed.</span></span> <span data-ttu-id="aa445-127">Að þessu loknu verður hægt að sjá bókuðu færslurnar í ýmsum af þeim gluggum sem innihalda bókaðar færslur, eins og **Viðskiptamannafærslur**, **Fjárhagsfærslur**, **Birgðafærslur,**, **Bókuð söluafhending** og **Bók. sölureikningur**.</span><span class="sxs-lookup"><span data-stu-id="aa445-127">After this, you will be able to see the posted entries in the various windows that contain posted entries, such as the **Cust. Ledger Entries**, **G/L Entries**, **Item Ledger Entries**, **Posted Sales Shipments**, and **Posted Sales Invoices** windows.</span></span>

## <a name="see-also"></a><span data-ttu-id="aa445-128">Sjá einnig</span><span class="sxs-lookup"><span data-stu-id="aa445-128">See Also</span></span>
[<span data-ttu-id="aa445-129">Hvernig á að: Senda skjöl í tölvupósti</span><span class="sxs-lookup"><span data-stu-id="aa445-129">How to: Send Documents by Email</span></span>](ui-how-send-documents-email.md)

