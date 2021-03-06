---
title: "Hvernig á að sameina vörur"
description: "Ef reiturinn **Áfyllingarkerfi** á birgðaspjaldinu inniheldur **Samsetning** er sjálfgefin afhendingaraðferð vörunnar að setja hana saman úr skilgreindum íhlutum og mögulega með skilgreindum forða."
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
ms.openlocfilehash: b7f371c48aa70d2b99ce7b7333b92a63d7764f28
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-assemble-items"></a>Hvernig á að sameina vörur
Ef reiturinn **Áfyllingarkerfi** á birgðaspjaldinu inniheldur **Samsetning** er sjálfgefin afhendingaraðferð vörunnar að setja hana saman úr skilgreindum íhlutum og mögulega með skilgreindum forða.  

Íhluti og forð sem fara í þess háttar samsetningarvörur verður að skilgreina í samsetningaruppskrift. Nánari upplýsingar er að finna í [Hvernig á að: Vinna með uppskrift.](inventory-how-work-BOMs.md)  

Samsetningarvörur er hægt að setja upp fyrir tvo mismunandi samsetningarferla:  

-   Setja saman í birgðir.  
-   Setja saman í pöntun.  

Yfirleitt er **Setja saman í birgðir** notað fyrir vörur sem á að setja saman á undan sölu, s.s. þegar söluherferð fyrir sett er undirbúin og þau geymd í birgðum áður en þær eru pantaðar. Þessar vörur eru yfirleitt staðlaðar vörur eins og innpökkuð sett sem þú býður ekki upp á að séu sérsniðin eftir beiðni viðskiptavina.  

Yfirleitt er **Setja saman í pöntun** notað fyrir vörur sem ekki á að setja í birgðir þar sem búist er við að þær verði sérsniðnar að þörfum viðskiptavinar eða vegna þess að lágmarka á birgðakostnað sem því að veita þær rétt í tíma. Frekari upplýsingar, sjá [Hvernig skal: Selja vörur sem eru settar saman í pöntun](assembly-how-to-sell-items-assembled-to-order.md).  

Frekari upplýsingar um hvernig samsetningaríhlutur er settur upp eru í [Skilja hvernig skal setja saman í pöntun eða setja saman í birgðir](assembly-assemble-to-order-or-assemble-to-stock.md).  

Þessir uppsetningarvalkostir eru sjálfgefnar stillingar sem stjórna hvernig sölu- og samsetningarpöntunarlínurnar eru upphaflega unnar. Hægt er að fara úr þessum sjálfgildum og afhenda samsetningaríhlut á sem hagkvæmastan hátt þegar sala er í vinnslu. Frekari upplýsingar, sjá [Hvernig skal: Selja birgðavörur sem eru settar saman í pöntun flæði](assembly-how-to-sell-assemble-to-order-items-and-inventory-items-together.md).og [Hvernig skal: selja saman vörur og birgðavörur sem eru settar saman í pöntun](assembly-how-to-sell-assemble-to-order-items-and-inventory-items-together.md).

> [!NOTE]  
> Samsetningaríhlutir eru meðhöndlaðir á sérstakan hátt í grunnskilgreiningum vöruhúss. Nánari upplýsingar eru í hlutanum „Meðhöndlun íhluta pantanasamsetninga við birgðatínslu” í [Hvernig skal: Tína vörur með Birgðatínsla](warehouse-how-to-pick-items-with-inventory-picks.md).   

Í þessu ferli er stofnuð og unnið úr samsetningarpöntun fyrir vörur sem eru settar saman í birgðir, sem þýðir án. tengdrar sölupöntunar. Skrefin eru meðal annars að hefja framleiðslupöntunina, meðhöndla möguleg ráðstöfunarvandamál íhluta og bóka samsetningarvörufrálag að hluta.

## <a name="to-assemble-an-item"></a>Til að setja vöru saman  
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Samsetningarpöntun** og velja svo viðeigandi tengil.  
2.  Valið er **Nýtt** aðgerð. Glugginn **Ný samsetningarpöntun** opnast.  
3.  Fyllið inn í reitina eftir þörfum. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4.  Í reitnum **Vöru Nr.** veljið samsetningarvöruna sem á að vinna með. Reiturinn er síaður til að hann sýni aðeins vörur sem eru settar upp fyrir samsetningu, sem þýðir að þær hafa úthlutaða samsetningaruppskrift.  
5.  Í reitnum **Magn** er fært inn hversu margar einingar vörunnar setja á saman.  

    > [!NOTE]  
    >  Ef einn eða fleiri íhlutir geta ekki uppfyllt skráð magn samsetningarvöru fyrir tilgreindan skiladag mun glugginn **Samsetning tiltæk** opnast sjálfkrafa og veita nákvæmar upplýsingar um hversu margar samsetningarvörur er hægt að setja saman miðað við íhluti til ráðstöfunar. Frekari upplýsingar, sjá [Hvernig skal: Skoða tiltækileika vöru](inventory-how-availability-overview.md).  Þegar glugganum er lokað, er samsetningarpöntun stofnuð ráðstöfunarviðvaranir í íhlutalínum sem fyrir áhrifum verða.  

    Samsetningarpöntunarlínurnar eru sjálfkrafa fylltar út með innihaldi samsetningaruppskriftar og með línumagni samkvæmt haus samsetningarpöntunarinnar.  

    > [!NOTE]  
    >  Ef glugginn **Samsetning tiltæk** opnaðist þegar fyllt var út í haus samsetningarpöntunarinnar inniheldur hver lína samsetningarpöntunar sem það hefur áhrif á **Já** í reitnum **Tilt. aðvörun** með tengli á ítarlegar upplýsingar um ráðstöfun. Frekari upplýsingar eru í Athuga framboð. Hægt er að leysa úr vandamáli við framboði íhlutar með því að fresta upphafdagsetningu, skipta út íhlut fyrir aðra vöru eða velja tiltækan varahlut ef slíkur er tilgreindur.  

6.  Í reitnum **Magn til samsetningar** er fært inn hversu margar einingar af samsetningarvöru eigi að bóka næst þegar samsetningarpöntun er bókuð. Þetta magn getur verið lægra en gildið í svæðinu **Magn** til að spegla hlutafrálagsbókun.  

    > [!NOTE]  
    >  Til að tryggja að bókun íhlutanotkunar passi við frálagsbókun samsetningarvörunnar eru magnreitirnir í samsetningarpöntunarlínunum sjálfkrafa lagaðir að gildinu sem fært er inn í reitinn **Magn til að setja saman**.  
7.  Á samsetningarpöntunarlínum af gerðinni **Vara** eða **Forði**, í reitnum **Magn til notkunar**, tilgreinið hversu margar einingar á að bóka sem notað, næst þegar samsetningarpöntun er bókuð. Sjálfgefið er að væntanlegt magn til notkunar í samræmi við samsetningaruppskriftina og magn samsetningarpöntunarhauss sé fært inn, en hægt er að hækka eða lækka það, til dæmis til að endurspegla á yfirnotkun íhluta eða viðbótarforðar voru notaðir.  
8.  Þegar komið er að því að bóka að hluta eða í heild er valin aðgerðin **Bóka**.  

    > [!NOTE]  
    >  Ef viðvaranir eru enn til staðar í einhverjum af samsetningarpöntunarlínum er lokað á bókunina. Skilaboð birtast um það hvaða íhlutur eða íhlutir eru ekki til í birgðum.  

Eftir að bókun tekst, er samsetningarvaran bókuð sem frálag birgðageymslukótans og hugsanlegs hólfakóta sem eru skilgreindir í samsetningarpöntuninni. Fyrir samsetningarpantanir sem voru stofnaðar handvirkt er hægt að afrita staðsetninguna úr uppsetningarreitnum **Sjálfgefin staðsetning fyrir pantanir**. Fyrir sameiningarpöntunarflæði, er hægt að afrita kóta birgðageymslu úr sölupöntunarlínunni.  

## <a name="see-also"></a>Sjá einnig
[Samsetningardeild](assembly-assemble-items.md)  
[Hvernig á að: Vinna með uppskriftir](inventory-how-work-BOMs.md)  
[Birgðir](inventory-manage-inventory.md)  
[Hönnunarupplýsingar vöruhúsakerfi](design-details-warehouse-management.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

