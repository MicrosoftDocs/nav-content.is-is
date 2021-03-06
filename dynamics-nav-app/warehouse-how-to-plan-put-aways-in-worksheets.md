---
title: "Hvernig á að áætla frágang á vinnublöðum"
description: "Ef birgðageymslan krefst bæði frágangs- og móttökuvinnslu og áætla á frágangsleiðbeiningar fyrir margar móttökur, í stað þess að fara eftir leiðbeiningum sem stofnaðar eru fyrir einstakar bókaðar móttökur, er hægt að nota frágangsvinnublaðið."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/16/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: a868a1cb2e03d736aa6edb6ab9cb145efce79c11
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-plan-put-aways-in-worksheets"></a>Hvernig á að áætla frágang á vinnublöðum
Ef birgðageymslan krefst bæði frágangs- og móttökuvinnslu og áætla á frágangsleiðbeiningar fyrir margar móttökur, í stað þess að fara eftir leiðbeiningum sem stofnaðar eru fyrir einstakar bókaðar móttökur, er hægt að nota frágangsvinnublaðið.  

Eigi að setja vöruhúsið þannig upp að móttökulínur séu tiltækar á frágangsvinnublaðinu um leið og þær hafa verið bókaðar þarf að setja gátmerki í reitinn **Nota vinnublað frágangs** á flýtiflipanum **Vöruhús** á birgðageymsluspjaldinu. Nánari upplýsingar er að finna í [Uppsetning vöruhúsastjórnunar](warehouse-setup-warehouse.md).  

Ef gátmerki er ekki sett í þennan reit eru frágangsleiðbeiningar stofnaðar sjálfkrafa fyrir móttökur þegar þær eru bókaðar.  

> [!NOTE]  
>  Óháð stöðu reitarins **Nota vinnublað frágangs** á birgðageymsluspjaldinu er alltaf hægt að sækja frágangsleiðbeiningalínur (bókaðar móttökulínur) í frágangsvinnublaðið með því að gera eftirfarandi:  
>   
>  1.  Í glugganum **Vöruhús – frágangur** er ýtt á Ctrl+D til að eyða öllum frágangsleiðbeiningunum eða línurnar sem á að vinna með á vinnublaðinu valdar og þeim eytt.  
> 2.  Þessu er haldið áfram þar til línunum sem vinna á með á vinnublaðinu hefur verið eytt. Veljið nú **Vinnublöð frágangs** og haldið áfram að áætla.  

## <a name="to-plan-instructions-in-the-put-away-worksheet"></a>Leiðbeiningar áætlaðar á vinnublaði frágangs:  
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Frágangsvinnublað** og velja svo viðeigandi tengil.  
2.  Valið er **Sækja vöruhúsaskjöl** aðgerð. Glugginn **Frágangsval** opnast.  

    Hægt er að sjá allar bókaðar móttökur og skráðan innanhússfrágang sem send hafa verið í frágangsaðgerðina, þar á meðal þá sem frágangsleiðbeiningar hafa þegar verið stofnaðar fyrir. Skjöl með frágangslínur sem gengið hefur verið frá að fullu og skráðar birtast ekki á þessum lista.  

3. Skjölin sem vinna á með á vinnublaðinu eru valin. Hægt er að vinna með línur úr nokkrum skjölum í einu.  

    > [!NOTE]  
    >  Ef reynt er að velja móttöku eða innanhússfrágang sem leiðbeiningar hafa þegar verið stofnaðar fyrir allar línur í, birtist tilkynning um það að ekkert sé til meðhöndlunar.  

4. Reiturinn **Röðunaraðferð** er fylltur út til að raða línunum eins og óskað er eftir.  

    > [!NOTE]  
    >  Röðun lína á vinnublaðinu flyst ekki sjálfkrafa í frágangsleiðbeiningar en sömu röðunaraðferðir eru fyrir hendi ásamt hólfaflokkun. Þannig er auðvelt að endurgera línuröðunina á vinnublaðinu þegar frágangsleiðbeiningarnar eru stofnaðar eða með því að raða í frágangsleiðbeiningunum.  

5.  Fylla inn í reitinn **Magn til afgreiðslu**. Velja aðgerðina **Færa sjálfkr. magn til afgr.** eða fyllið út reitina handvirkt.  
6.  Ef þess þarf er línunum breytt handvirkt. Hægt er að eyða línum, til dæmis ef setja þarf sumar vörur í hólf sem er langt frá hólfunum fyrir hinar vörurnar.  

    > [!NOTE]  
    >  Línum er aðeins eytt af þessu vinnublaði, ekki frágangsvallistanum.  

7.  Veldu aðgerðina **Stofna frágang**. Glugginn **Stofna fylgiskjal** opnast, þar sem hægt er að bæta við upplýsingum í fráganginn sem verið er að stofna, á eftirfarandi hátt:  

    -   Hægt er að úthluta fráganginum á tiltekinn starfsmann.  
    -   Hægt er að raða frágangsleiðbeiningalínum eins og gert var á vinnublaðinu eða eftir flokkun hólfa. Þegar raðað er eftir flokkun hólfa birtast Taka-línurnar fyrst þar sem flestar móttökulínurnar hafa hólfaflokkunina 0 og Setja línurnar birtast síðast í hækkandi röð eftir hólfaflokkun. Hafi vöruhúsið verið skipulagt þannig að hólf með svipaða flokkun séu næst hvert öðru, sparar röðun með þessum hætti starfsmönnunum sporin.  
    -   Hægt er að fela millilínurnar sem stofnaðar eru þegar kerfið skiptir stórri mælieiningu í smærri mælieiningar með því að velja reitinn **Setja einingaskiptaafmörkun**. Frekari upplýsingar, sjá [Hvernig skal: Virkja sjálfvirk einingaskipti með beinum frágangi og tínslu] (warehouse-enable-automatic-breaking-bulk-with-directed-put-away-and-pick.md).  
    -   Hægt er að velja að ekki sé sjálfkrafa fyllt út í reitinn **Magn til afgreiðslu** í frágangsleiðbeiningunum.  
    -   Hægt er að prenta skjalið strax.  

8.  Veldu hnappinn **Í lagi** og þá stofnar kerfið fráganginn samkvæmt óskum notandans.  

## <a name="see-also"></a>Sjá einnig  
[Vöruhúsastjórnun](warehouse-manage-warehouse.md)  
[Birgðir](inventory-manage-inventory.md)  
[Vöruhúsastjórnun sett upp](warehouse-setup-warehouse.md)     
[Samsetningardeild](assembly-assemble-items.md)    
[Hönnunarupplýsingar vöruhúsakerfi](design-details-warehouse-management.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

