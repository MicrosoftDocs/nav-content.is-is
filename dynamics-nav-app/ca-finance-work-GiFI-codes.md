---
title: "Hvernig á að: Vinna með GIFI kóða í Kanada"
author: SorenGP
ms.custom: na
ms.date: 09/21/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 695bca0a6836c47610210b759ae48af27484761f
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

#<a name="how-to-work-with-gifi-codes-in-canada"></a>Hvernig á að: Vinna með GIFI kóða í Kanada
Fjárhagsupplýsingar geta innihaldið fjárhagsreikninga, skýrslur, rekstrarreikninga, efnahagsreikninga og yfirlit yfir óráðstafað eigið fé. Fjárhagsupplýsingar eru flokkaðar með kóðum. Notkun kóða hjálpar hinu opinbera að vinna upplýsingar, undirbúa rafræn skattskil og staðfesta upplýsingar um skatta rafrænt. Notkun kóða auðveldar einnig hagstofum og slíkum stofnunum vinnuna, þar sem fjárhagsupplýsingar eru aðgengilegri. Nánari upplýsingar eru á vefsíðu [Tekjuskrifstofu Kanada](http://www.cra-arc.gc.ca/).

Tekjuskrifstofa Kanada notar kóða úr Almennri atriðaskrá um fjárhagsupplýsingar (General Index of Financial Information, GIFI) til að safna saman, sannprófa, og vinna ársreikninga og vsk-upplýsingar rafrænt. Það er best að úthluta GIFI kóðum aðeins á bókunarreikninga, til þess að allar samtölur séu gerðar af hugbúnaðinum sem notaður er fyrir undirbúning vsk-skatts.

Þegar reikningur er tengdur GIFI kóða er hann skráður í tekjuskrifstofunni undir þeim kóða. Margir sameinaðir reikningar geta haft sama GIFI kóða, en hver reikningur getur aðeins haft einn GIFI kóða.

Hægt er að flytja út upplýsingar um stöðu eftir GIFI kóða og vista útfluttu skrána í Excel, sem er gagnlegt við að flytja upplýsingar til hugbúnaðarins sem notaður er fyrir undirbúning vsk-skatts.

## <a name="to-set-up-gifi-codes"></a>Uppsetning GIFI kóða
Í Dynamics NAV þarf að setja upp GIFI kóða fyrir fjárhagsreikninga, skýrslur, efnahagsreikninga, tekjureikninga og yfirlit yfir óráðstafað eigið fé.

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **GIFI kóða**, og velja síðan viðeigandi tengil.
2. Í glugganum **GIFI kóðar** skal velja aðgerðina **Nýtt**.
3. Setjið upp GIFI kóða með því að fylla í reitina. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.

## <a name="to-associate-gifi-codes-with-gl-accounts"></a>Til að tengja GIFI kóða við fjárhagsreikninga
Til að tilkynna fjárhagslegar upplýsingar eftir GIFI kóða þarf hver GIFI kóði að vera tengdur við viðeigandi reikninga í bókhaldslyklinum.

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **bókhaldslykill**, og velja síðan viðeigandi tengil.
2. Veljið viðeigandi fjárhagsreikning og veljið svo aðgerðina **Breyta**.
3. Í flýtiflipanum **Kostnaðarbókhald** í svæðinu **GIFI kóði** er viðeigandi GIFI kóði valinn.

## <a name="to-view-account-balances-using-the-gifi-code-report"></a>Til að skoða reikningsstöður með GIFI kóða skýrslunni.
Hægt er að skoða stöðu reikninga eftir GIFI kóða með því að nota skýrsluna **Staða reikninga eftir GIFI kóða**.

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Staða reikninga eftir GIFI kóða**, og velja síðan viðeigandi tengil.
2. Tilgreina þarf hvað eigi að taka með í skýrslunni með því að fylla í reitina. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.
3. Veljið hnappinn **Prenta** eða **Forskoðun**.

## <a name="to-export-balance-information-using-gifi-codes"></a>Til að flytja út reikningsupplýsingar með því að nota GIFI kóða
Hægt er að flytja út reikningsupplýsingar með því að nota GIFI kóða og vista útfluttu skrána í Excel. Hægt er að breyta, vista eða eyða skrám. Skrána má nota til að flytja upplýsingar til hugbúnaðarins sem notaður er fyrir undirbúning vsk-skatts.

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Flytja GIFI upplýsingar í Excel**, og velja síðan viðeigandi tengil.
2. Skilgreina þarf hvað eigi að flytja út í Excel með því að fylla í reitina. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.
3. Velja hnappinn **Í lagi**.

**Athugasemd:** Excel-skráin hefur eftirfarandi einkenni:

* Staðan er sléttuð í næstu prósentu en gildi reitsins viðheldur sömu prósentu og í fjárhag.

* Neikvæð númer eru sýnd sem jákvæð númer í svigum. Í samræmi við það er talan -123 sýnd sem (123).

## <a name="see-also"></a>Sjá einnig
[Fjármál](finance-setup.md)   
[Setja upp kjarnafjárhagsferli](finance-setup-setup-finance-setup.md)

