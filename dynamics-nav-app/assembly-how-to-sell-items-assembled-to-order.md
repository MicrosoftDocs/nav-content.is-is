---
title: "Hvernig á að selja hluti sem eru settir saman í pöntun"
description: "Ef varan er settu upp til samsetningar til pöntunar er ekki gert ráð fyrir því að varan sé í birgðum og þá þarf að setja hana saman fyrir þessa sölupöntun. Þegar varan er sett inn í sölupöntunarlínu er samsetningarpöntun síðan búin til sjálfkrafa og tengd við sölupöntunina."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/15/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: fc140a0fa7d58c38234f67471323241ac94ca489
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-sell-items-assembled-to-order"></a>Hvernig á að selja sem eru settar saman í pöntun
Ef reiturinn **Samsetningarstefna** á birgðaspjaldi samsetningarvörunnar er **Samsetning til pöntunar** er ekki gert ráð fyrir því að varan sé í birgðum og þá þarf að setja hana saman fyrir þessa sölupöntun. Þegar varan er sett inn í sölupöntunarlínu er samsetningarpöntun síðan búin til sjálfkrafa og tengd við sölupöntunina.  

> [!NOTE]  
>  Ef einhverjar samsetningarpöntunarvörur eru þegar í birgðum er hægt að draga það magn frá samsetningarpöntuninni og taka það frá í birgðum. Frekari upplýsingar, sjá [Hvernig á að selja birgðavörur með flæði samsetningarpantana](assembly-how-to-sell-assemble-to-order-items-and-inventory-items-together.md).  

Í þessu ferli er sala vöru sem verður sett saman samkvæmt óskum viðskiptamannsins meðhöndluð. Skrefin eru meðal annars að hefja sölupöntunarlínuna, sérsníða samsetningarvöruna með því að breyta íhlutum hennar og forða, athuga hvað er til ráðstöfunar til að ákveða skiladag og gefa út sölupöntun sem setja má saman og afhenda tafarlaust.  

> [!NOTE]  
>  Eftirfarandi ferli inniheldur ekki stöðluðu sölupöntunarskrefin fyrir skrefið þegar birgðir sem settar eru saman í pöntun eru færðar inn í sölupöntunarlínu.  

## <a name="to-sell-an-item-that-is-assembled-to-order"></a>Til að selja vöru sem er sett saman í pöntun  
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Sölupantanir** og velja svo viðeigandi tengil.  
2.  Stofnið sölupöntun. Nánari upplýsingar eru í [Hvernig á að: selja vörur.](sales-how-sell-products.md)  
3.  Í reitnum **númer** færið inn vöru sem stillt eru til að setja saman í pöntun.  
4.  Í reitnum **Kóti birgðageymslu** er tilgreind sú birgðageymsla sem varan mun verða seld frá. Samsetningarferlið fer fram í þeirri birgðageymslu.  
5.  Í reitnum **Magn** er fært inn hversu margar einingar á að selja.  

    > [!NOTE]  
    >  Ef einn eða fleiri íhlutir umbeðins magns samsetningarvöru eru ekki tiltækir birtist nákvæmur ráðstöfunarviðvörunargluggi. Nánari upplýsingar, sjá samsetning í boði.  

    Samsetningarpöntun er nú stofnuð sjálfkrafa og tengd við sölupöntunarlínuna. Gjalddagi þessarar samsetningarpöntunar er samstilltur við afhendingardagsetningu sölupöntunarlínunnar.  

    Magnið sem á að selja er afritað í reitinn **Magn Til að setja saman í pöntun**, sem þýðir að uppsetning vörunnar býst við að allt magn í sölulínunni sé sett saman í pöntunina. Hægt er að minnka magnið til að setja saman í pöntun, t. d. ef vitað er að sumar vörur eru þegar til staðar. Frekari upplýsingar, sjá [Hvernig á að selja birgðavörur með flæði samsetningarpantana](assembly-how-to-sell-inventory-items-in-assemble-to-order-flows.md).  

6.  Til að gefa til kynna að viðskiptavinur vill aukavöru í setti er farið í flýtiflipann **Línur** , aðgerðin **Lína** valin, síðan **Sameina í pöntun** aðgerðin og svo **Sameina-í-pöntun línur** aðgerðin til að skoða og breyta stöðluðum samsetningaríhlutum. Að öðrum kosti skal velja reitinn **Magn til samsetningar til pöntunar**.  
7.  Í glugganum **Setja saman í pöntunarlínur** stofnið nýja tegund línu **Atriði** vegna viðbótarinnihalds setts sem beðið var um. Línan stendur fyrir annan samsetningaríhlut.  

    Einnig er hægt að sérsníða pöntun með því að auka magni einnar af staðalvöru í setti. Hægt er að gera þetta með því að auka gildið í reitnum **Magn á** á viðkomandi samsetningarpöntunarlínu.  

    > [!NOTE]  
    >  Glugginn **Setja-saman-í-pöntun línur** hefur aðeins að geyma grunnsvæði sem vænst er að sölufulltrúi noti til að sérsníða íhlutalistann, bæta við vörurakningarnúmeri eða leysa vandamál með framboð íhluta. Til að sjá frekari upplýsingar um samsetningarpöntun, til dæmis upphafsdagsetningu samsetningarpöntunarinnar, er farið í flipann **Heim**, flokkinn **Vinna** og **Sýna skjöl** valið. Þá opnast fullt yfirlit yfir samsetningarpöntunina sem er tengd við sölupöntunarlínuna. Ekki er hægt að breyta innihaldi flestra reita í haus samsetningarpöntunar, og ekki er hægt að bóka frálag samsetningar þar sem nota þarf afhendingarbókun sölupöntunarlínunnar.  
    >   
    >  Í haus tengdra samsetningarpantana, getur aðeins reitnum **Upphafsdagsetning** verið breytt til að virkja samsetningarstarfsmenn til að tilgreina dagsetningu sem er á undan gjalddaga um hvenær þeir munu hefja ferlið. Öllum reitum í línunum á tengdu samsetningarpöntuninni er hægt að breyta svo að vöruhússstarfsmenn geti fært inn notkunartölur við vinnsluna.  

8.  Fara skal yfir eða bregðast við vandamálum með ráðstöfun íhluta. Veljið til dæmis tiltæka staðgengdarvöru eða komið á nýjum gjalddaga.  
9. Loka glugganum **Setja saman í pöntunarlínur**. Tengda samsetningarpöntunin er nú tilbúin til að hefja samsetningu sérsniðnu vörunnar eftir gjalddaganum.  
10. Á sölupöntuninni skal velja **Losa** aðgerðina til að tilkynna samsetningardeildinni að sem samsetningarferlið geti hafist.  
11. Í samsetningardeildinni, framkvæmið aðgerðir samsetningu varanna sem seldar eru í þessu ferli. Frekari upplýsingar, sjá [Hvernig skal: Setja saman vörur](assembly-how-to-assemble-items.md).  

## <a name="see-also"></a>Sjá einnig  
[Samsetningardeild](assembly-assemble-items.md)  
[Hvernig á að: Vinna með uppskriftir](inventory-how-work-BOMs.md)  
[Birgðir](inventory-manage-inventory.md)  
[Hönnunarupplýsingar vöruhúsakerfi](design-details-warehouse-management.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

