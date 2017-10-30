---
title: "Hvernig á að: Virkja greiðslur viðskiptamanna gegnum PayPal"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 15f30a03c3e7ccc865ef527a707794c2c6428b2f
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---

# <a name="how-to-enable-customer-payments-through-paypal"></a>Hvernig á að: Virkja greiðslur viðskiptamanna gegnum PayPal#
Í stað þess að innheimta greiðslur með gíró eða kreditkort getur boðið að viðskiptamenn greiði gegnum PayPal reikning þeirra .

Þegar viðskiptamaður velur PayPal tengilinn á sölureikningi eða sölupöntunarskjali, birtist þjónustusíða fyrir PayPal reikning hans þar sem nákvæmar greiðsluupplýsingar fyrir söluna koma fram. Viðskiptamaður getur síðan greiða reikning og sem hverja aðra PayPal greiðslu.

Til að Virkja greiðslur viðskiptamanna gegnum PayPal verðurðu að gera eftirfarandi:

1. Setja upp PayPal Payments Standard sem greiðsluþjónustu í glugganum **GreiðslÞjónusta** .
2. Velja PayPal Payments Standard í á **Greiðsluþjónustu** reit á viðkomandi söluskjal.

PayPal-greiðslustaðalþjónusta er uppsett sem viðbót við Dynamics NAV og tilbúin til virkjunar. Frekari upplýsingar skoða [Sérstilla Dynamics NAV Nota viðbætur](ui-extensions.md).

## <a name="to-enable-the-paypal-payments-standard-service"></a>Virkja PayPal Payments Standard þjónustuna
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, **greiðsluþjónusta**, og velja síðan viðeigandi tengil.  
2. Í glugganum **Greiðsluþjónustur** skal velja aðgerðina **Nýtt**.
3. Veljið **PayPal Standard** og lokið svo glugganum.
4. Í glugganum **Greiðsluþjónustur** skal velja aðgerðina **uppsetning**.
5. Fyllið inn í svæðin eftir þörfum. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.

    **Bent er á**: Valið er **Alltaf Með skjölum** gátreitinn ef tenglum fyrir PayPal greiðsluþjónustu ætti alltaf að vera sýnilegt í söluskjölum þar sem greiðsla í gegnum PayPal er virkjuð.

6. Glugganum er lokað.

## <a name="to-select-paypal-payments-standard-on-a-sales-invoice"></a>Til að velja PayPal Payments Standard á sölureikning.
1. Í reitnum heimasíða velja **sölureikningar**.
2. Opnið sölureikningur sem á að virkja paypal greiðslur fyrir.
3. Í reitnum **GreiðsluÞjónustu** er valið er PayPal Payments Standard.

**Athuga skal að**: **GreiðsluÞjónustu** reiturinn birtist aðeins ef PayPal Payments Standard er virkjað.   

## <a name="see-also"></a>Sjá einnig  
[Uppsetning sölu](sales-setup-sales.md)  
[Stjórna sölu](sales-manage-sales.md)  
[Sérstilling Dynamics NAV með viðbótum](ui-extensions.md)

