---
title: "Hvernig á að: Vinna með Utanbirgðavörur"
author: SorenGP
ms.custom: na
ms.date: 09/29/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 6d99e06c167d3b86db97883c02c8bf5cd746ae10
ms.contentlocale: is-is
ms.lasthandoff: 07/19/2017

---

# Hvernig á að: Vinna með Utanbirgðavörur
Þú getur boðið viðskiptamaður þínum tilteknar vörur til þeim til hæginda, vörur sem þú vilt ekki geyma í birgðum fyrr en þú byrjar að selja þær. Þegar á að byrja að viðhalda slíkum vörum í birgðum, er hægt að breyta þeim í venjulegur birgðaspjöld á tvo vegu.

- Úr utanbirgðaspjaldi skal stofna nýtt birgðaspjald á grundvelli sniðmáts.
- Úr sölupöntunarlínu með tómum reit fyrir **Vöru** skal velja utanbirgðavara. Þegar sala er bókuð, er birgðaspjald sjálfkrafa stofnað fyrir þessa utanbirgðavöru.

**Athugasemd**: ekki hægt er Að velja utanbirgðavöru úr glugganum **Sölureikningur**. Hægt er að velja utanbirgðavöru á úr **Sölutilboð** glugganum, en utanbirgðavöru verður ekki umbreytt í venjulega vöru þegar þú notar **Búa til Pöntun** aðgerð.

Utanbirgðavara hefur yfirleitt vörunúmer þess lánardrottins sem sér um að veita hana. Til að virkja umbreytingu utanbirgðaspjalds í venjulegur birgðaspjald, þarf fyrst að setja upp hvernig númeraröð lánardrottins er breytt í eigin númeraröð vöru.   

## Stofna utanbirgðavöru
Utanbirgðavöruspjöld hafa mikið minni upplýsingar en venjulegur birgðaspjöldum þar sem þær eru aðeins boðnar gegn tilboðum og með öðrum hætti. Af þeirri ástæðu þær þarf að umbreyta þeim í venjulegur birgðaspjöldum áður en hægt bóka sölufærslur fyrir þá.

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu** slá inn **utanbirgðavara**, og velja síðan viðeigandi tengil.
2. Valið er **Nýtt** aðgerð.
2. Fyllið inn í svæðin eftir þörfum. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.

## Setja upp hvernig utanbirgðavörunúmerum er breytt í eigin númeraröð  
Til að virkja umbreytingu utanbirgðaspjalds í venjulegt birgðaspjald, þarf fyrst að setja upp hvernig númeraröð lánardrottins er breytt í eigin númeraraðasnið.

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu** slá inn **uppsetning utanbirgðavara**, og velja síðan viðeigandi tengil.
2. Fyllið inn í svæðin eftir þörfum.

## Breyta utanbirgðavara í venjulega vöru
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu** slá inn **utanbirgðavara**, og velja síðan viðeigandi tengil.
2. Opna spjald fyrir utanbirgðavara sem þú vilt umbreyta í venjulega vöru.
3. Í glugganum **utanbirgðavöruspjald** er valið **Stofna vara** aðgerð.

Stofnuð eru Nýtt birgðaspjald með sem er forútfyllt með upplýsingum úr utanbirgðavara og viðeigandi vörusniðmát. Hægt er síðan að fylla inn í eða breyta reitum á nýja birgðaspjaldinu eins og þörf krefur. Nánari upplýsingar eru í [Hvernig á að: Skrá nýjar vörur](inventory-how-register-new-products.md).

## Selja utanbirgðavara og breyta henni í venjulega vöru
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **sölupantanir**, og velja síðan viðeigandi tengil.
2. Valið er **Nýtt** aðgerð. reitirnir á flýtiflipanum **Almennt** eru eins og fyrir hverja aðra sölupöntun.
3. Á nýrri sölulínu, hafðu reitinn **Vara** auður, veldu **Línu**, **Aðgerðir**, og síðan valið **Utanbirgðavörur**.

    Utanbirgðavara er breytt í venjulega vöru Stofnuð eru Nýtt birgðaspjald með sem er forútfyllt með upplýsingum úr utanbirgðavara og viðeigandi vörusniðmát.
4. Í **utanbirgðavara** glugganum, veljið utanbirgðavöruna sem þú vilt selja og veljið svo hnappinn **Í lagi**.
5. Þegar sölupöntunarlínunum er lokið, skal velja **bóka** aðgerðina.

Hægt er síðan að fylla inn í eða breyta reitum á nýja birgðaspjaldinu eins og þörf krefur. Nánari upplýsingar eru í [Hvernig á að: Skrá nýjar vörur](inventory-how-register-new-products.md).

**Athugasemd**: millivísunarfærsla fyrir vöru er sjálfkrafa stofnuð fyrir lánardrottinn vörunnar á milli vörunúmers lánardrottins og nýja vörunúmersins þíns.

## Sjá einnig
[Hvernig á að: Skrá nýjar vörur](inventory-how-register-new-products.md)  
[Stjórna birgðum](inventory-manage-inventory.md)  
[Unnið með Dynamics NAV](ui-work-product.md)

