---
title: "Hvernig á að: Vinna með vörueigindir"
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
ms.openlocfilehash: eaf539f1d4d00c2cd5679f39f29a3428e33ee1fd
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-work-with-item-attributes"></a>Hvernig á að: Vinna með vörueigindir
Þegar viðskiptamaður gerir fyrirspurn um vöru, annað hvort í beinum samskiptum eða í innbyggðri vefverslun getur hann spurt um vöruna eða leitað samkvæmt eiginleikum, t.d. hæð og árgerð. Til að veita þessa þjónustu við viðskiptamanninn er hægt að úthluta vörum mismunandi eigindargildum sem er svo hægt að nota við leit að vörum.

Einnig er hægt að úthluta vörueigindum á vöruflokka, sem síðan eiga við um vörur sem nota vöruflokka. Nánari upplýsingar eru í [Hvernig á að flokka vöru](inventory-how-categorize-items.md).

## <a name="to-create-item-attributes"></a>Að búa til vörueigind
1. Í efra hægra horni skal velja táknið **leita að síðu eða skýrslu** slá inn **Vörueigindir**, og velja síðan viðeigandi tengil.
2. Í glugganum **Vörueigindir** skal velja **Nýtt**.
3. Í glugganum **vörueigind** þarf að fylla reitina út eftir þörfum. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.

**Athugasemd**: Ef valið er **Kostur** á svæðinu **Tegund** er hægt að velja aðgerðina **Eigindargildi vöru** til að stofna gildi fyrir vörueigindina. Nánari upplýsingar eru í hlutanum "Stofna gildi fyrir vörueigindir af gerðinni valkostur".  

## <a name="to-create-values-for-item-attributes-of-type-option"></a>Stofna gildi fyrir vörueigindir af gerðinni valkostur.
1. Í efra hægra horni skal velja táknið **leita að síðu eða skýrslu** slá inn **Vörueigindir**, og velja síðan viðeigandi tengil.
2. Í glugganum **Vörueigindir** er valin vörueigind af gerðinni valkostur sem á að stofna gildi fyrir og veljið síðan aðgerðina **Eigindargildi vöru**.
3. Í glugganum **vörueigindagildi** þarf að fylla reitina út eftir þörfum. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.

## <a name="to-assign-item-attributes-to-items"></a>Að úthluta vörueigindum á vörur
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu** slá inn **Vörur**, og velja síðan viðeigandi tengil.
2. Í glugganum **Vörur** skal velja vöruna sem á að úthluta vörueigindum á og velja síðan aðgerðina **Eigindir**.
3. Í glugganum **vörueigindagildi** skal velja aðgerðina **Nýtt**.
4. Veldu hnappinn AssistEdit í reitnum **eigind** og veldu fyrirliggjandi vörueigind. Einnig má velja **Nýtt** aðgerðina til að stofna fyrst nýjan vörueigind eins og útskýrt er í "Stofna vörueigind" hlutanum.
5. Í reitnum **Gildi** er færð inn í vörueigindagildi, s.s. "2010" fyrir gildið árgerð.
6. Fyrir vörueigind af gerðinni valkostur, Veldu hnappinn AssistEdit í reitnum **gildi** og veldu fyrirliggjandi vörueigindargildi. Einnig má velja á **Nýtt** aðgerð til að stofna fyrst nýjan vörueigindargildi eins og útskýrt er í "Stofna gildi fyrir vörueigindir af gerðinni valkostur" hlutanum.
7. Liðir 4-6 eru endurteknir fyrir allar vörueigindir sem á að úthluta á vöru.

## <a name="to-assign-item-attributes-to-item-categories"></a>Að úthluta vörueigindum á vöruflokka
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu** slá inn **Vöruflokkar**, og velja síðan viðeigandi tengil.
2. Í glugganum **vöruflokkar** skal velja vöruflokk sem á að úthluta vörueigindum á og velja síðan aðgerðina **breyta**.
3. Í glugganum **vöruflokkaspjald** á flýtiflipanum **eigind** skal velja aðgerðina **Nýtt**.
4. Veldu hnappinn AssistEdit í reitnum **eigind** og veldu fyrirliggjandi vörueigind. Einnig má velja á **Nýtt** aðgerð til að stofna fyrst nýjan vörueigind eins og útskýrt er í "Stofna vörueigind" hlutanum.
5. Í reitnum **sjálfgefið gildi** skal velja hnappinn AssistEdit og velja vörueigindargildi.
6. Liðir 4-5 eru endurteknir fyrir allar vörueigindir sem á að úthluta á vöruflokk.

**Athugasemd**: vörueigindum fyrir vöruflokka yfirvöru verður afritaður á vöruflokka undireiningar. Þetta er tilgreint með reitnum **afritað Úr** í **Eigindum** Flýtiflipa. Nánari upplýsingar eru í [Hvernig á að flokka vöru](inventory-how-categorize-items.md).

## <a name="to-filter-by-item-attributes"></a>Afmarka eftir vörueigind
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu** slá inn **Vörur**, og velja síðan viðeigandi tengil.
2. Í glugganum **Vörur** skal velja aðgerðina **Afmarka eftir eigindum**.
3. Í glugganum **Afmarka vöru eftir eigind** skal velja AssistEdit-hnappinn á svæðinu **Eigind** og velja síðan vörueigind.
4. Í reitnum **Virði** skal velja hnappinn AssistEdit og velja eigindargildi sem á að afmarka vörur eftir.

    **Athugasemd**: Aðeins er hægt að velja gildi beint fyrir vörueigindir sem hafa föst gildi, til dæmis lit. Fyrir vörueigindir sem hafa breytileg gildi, til dæmis breidd, verður að tilgreina eigindargildi vöru eftir fyrsta val á skilyrði. Sjá skref 5.
5. Í reitnum **Virði** fyrir breytilega vörueigind skal velja hnappinn AssistEdit.
6. Í glugganum **Tilgreina afmörkunargildi** á svæðinu **Skilyrði** skal velja felliörina og velja skilyrði.
7. Í reitnum **Virði** skal færa eigindargildi til að afmarka vörur með.

    **Dæmi**: Til að afmarka vörur þar sem efnislýsing hefst með "blátt", skal fylla inn í reitina sem hér segir: Reiturinn **Eigind**: Efnislýsing, reiturinn **Skilyrði**: Hefst með, reiturinn **Virði**: Blátt.
8. Velja hnappinn **Í lagi**.   

Vörur í glugganum **Vörur** eru afmarkaðar eftir tilgreindum eigindagildum vörunnar.

## <a name="see-also"></a>Sjá einnig
[Hvernig á að: Flokka atriði](inventory-how-categorize-items.md)    
[Hvernig á að: Skrá nýjar vörur](inventory-how-register-new-products.md)  
[Stjórna birgðum](inventory-manage-inventory.md)  
[Unnið með Dynamics NAV](ui-work-product.md)

