---
title: "Hvernig á að: Gera beinar afhendingar"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: f636de789dc6b006a449ec59c390fab85e62b443
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-make-drop-shipments"></a>Hvernig á að: Gera beinar afhendingar
Bein afhending er afhending frá einum af lánardrottnum fyrirtækisins beint til einhvers af viðskiptamönnum fyrirtækisins.

Þegar sölupöntun er merkt fyrir bein sending og þú býrð til innkaupapöntun sem tilgreinir viðskiptamaður í reitnum **Selt-til-Viðskm.nr.**  þá má tengja skjölin tvö og þannig segja lánardrottninum að senda beint til viðskiptamanns.

## <a name="to-create-a-sales-order-for-drop-shipment"></a>Sölupöntun fyrir beina afhendingu búin til
Til að Undirbúa bein afhending, er stofnuð sölupöntun fyrir vöru sem venjulega, nema þarf tilgreina í sölulínunni að salan krefst beinnar sendingar.

1. Stofnið sölupöntun fyrir vöru. Nánari upplýsingar eru í [Hvernig á að: selja vörur.](sales-how-sell-products.md)
2. Á sölupöntunarlínu fyrir vöru í beinni sendingu, er valinn **Bein sending** gátreitinn.

## <a name="to-create-the-purchase-order-for-drop-shipment"></a>Innkaupapöntunin stofnuð fyrir beina sendingu
Til að undirbúa beina sendingu fyrir vöru sem á að selja, stofnarðu innkaupapöntun sem venjulega, nema taka þarf fram í innkaupapöntun að senda verði til viðskiptamannsins, ekki til þíns sjálfs.

1. Stofna innkaupapöntun. Ekki fylla inn í neina reiti á línunum. Nánari upplýsingar eru í [Hvernig á að: Skrá innkaup](purchasing-how-record-purchases.md).
2. Í reitnum **Selt til Viðskm.nr.**. er valinn viðskiptamaður sem selt er til.
3. Veljið aðgerðina **beinar sendingar** og veljið síðan aðgerðina **sækja sölupöntun**.
4. Í **Sölulisti** glugganum er valin sölupöntun sem var útbúin í "stofna sölupöntun fyrir beina sendingu" hlutanum.
5. Velja hnappinn **Í lagi**.

Línuupplýsingar úr sölupöntun er sett í sölupöntunarlínu(r).

Nú er hægt að segja lánardrottninum aðsenda vörur til viðskiptamanns, til dæmis, með því að póstleggja innkaupapöntun sem er PDF.     

## <a name="to-view-the-linked-purchase-order-from-the-sales-order"></a>Til að skoða tengda innkaupapöntunina úr sölupöntuninni
1. Veldu Sölupöntunarlínu beinnar sendingar, veldu **Pöntun** aðgerð og veldu **Bein sending** aðgerð og síðan er valið aðgerðin **Innkaupapöntun**.

Tengd innkaupapöntun opnast.

## <a name="to-post-a-drop-shipment"></a>Til að bóka beina afhendingu
Þegar lánardrottinn hefur sent vörur, er hægt að bóka sölupöntunina sem senda. Einnig er hægt að bóka innkaupapöntun, en aðeins með **Móttöku** valkostinn fyrr en sölupöntunin hefur verið reikningsfært.
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **sölupantanir**, og velja síðan viðeigandi tengil.
2. Opnaðu sölupöntun sem þú stofnaðir í "stofna sölupöntun fyrir beina sendingu" hlutanum.
3. Í reitnum **magn til Afhendingar** er tilgreint hve mikið af pöntunarmagni skal senda, allt eða hluti pöntunarmagns.
3. Veljið aðgerðina **bóka** eða **Bóka og senda**.
4. Síðan er annað hvort valið **senda** valkosturinn til að reikningsfæra síðar eða valkostinn **senda og reikningsfæra** eigi að reikningsfæra strax.

## <a name="see-also"></a>Sjá einnig
[Hvernig á að: Selja vörur](sales-how-sell-products.md)    
[Hvernig á að skrá kaup](purchasing-how-record-purchases.md)  
[Stjórna sölu](sales-manage-sales.md)  
[Stjórna birgðum](inventory-manage-inventory.md)      
[Unnið með Dynamics NAV](ui-work-product.md)

