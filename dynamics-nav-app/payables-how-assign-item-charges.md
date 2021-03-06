---
title: "Úthlutun kostnaðarauka á sölu og innkaup"
description: "Ef þú vilt að birgðavörurnar beri aukinn kostnað, eind og t.d. farmur, efnisleg meðhöndlun, tryggingar og flutningar sem viðskipti þín með vörurnar hafa í för með sér, geturðu notað eiginleikann Kostnaðarauki."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: transportation, added cost
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: f5eebe7d1837657771d4f3004627be716d4d51bc
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-use-item-charges-to-account-for-additional-trade-costs"></a>Hvernig skal: Nota kostnaðarauka til að gera grein fyrir viðbótar viðskiptakostnaði
Til að tryggja rétt verðmat, verða birgðavörurnar þínar að bera allan auka kostnað, eind og t.d. farmur, efnisleg meðhöndlun, tryggingar og flutningar sem viðskipti þín með vörurnar hafa í för með sér. Í innkaupum, þá samanstendur raunkostnaður innkeyptrar vöru af innkaupaverði frá lánardrottni og öllu beinu viðbótarvörugjaldi sem hægt er að leggja á einstaka móttöku eða endursendar afhendingar. Það getur verið fyrirtækjum jafnmikilvægt að kunna skil á kostnaði við afhendingu seldrar vöru eins og að vita raunkostnað aðkeyptrar vöru.

Til viðbótar við skráningu aukakostnaðar á birgðavirði, geturðu notað eiginleikann Kostnaðarauki fyrir eftirfarandi:

- Til að ákvarða raunkostnað vöru og taka réttari ákvarðanir sem miða að því að bæta dreifikerfið.
- Til að sundurliða einingarkostnað og einingarverð vöru þegar framkvæmdar eru greiningar.
- til að hafa innkaupauppbætur með í einingarkostnaði og söluuppbætur í einingarverði.

Áður en þú getur úthlutað kostnaðarauka, þarf að setja upp kostnaðaraukanúmer fyrir ólíkar gerðir kostnaðarauka, og líka tiltaka á hvaða fjárhagsreikninga skal bóka kostnað sem hlýst af sölu, innkaupum og leiðréttingu birgða.  Kostnaðaraukanúmer inniheldur samsetningu almennra vörubókunarflokka, skattflokkskóða, VSK-vörubókunarflokka og kostnaðarauka. Þegar þetta kostnaðaraukanúmer er fært inn í innkaupa- eða söluskjal sækir kerfið fjárhagsreikning eftir uppsetningu kostnaðaraukanúmersins og upplýsingunum í viðkomandi skjali.

Hægt er að úthluta kostnaðarauka á bæði innkaupa- og söluskjöl á tvennan máta:
- Á skjalinu þar sem vörurnar sem kostnaðurinn tengist eru birtar. Þetta er vanalega gert við skjöl sem ekki eru enn fullbókuð.
- Á sérstakan reikning með því að tengja kostnaðaraukann við bókaða móttöku eða afhendingu, þar sem vörurnar sem kostnaðaraukinn tengist eru skráðar.

> [!NOTE]  
>   Hægt er að úthluta kostnaðarauka á pantanir, reikninga og kreditreikninga fyrir bæði sölu og innkaup. Eftirfarandi ferli lýsir því hvernig á að vinna með kostnaðarauka fyrir innkaupareikning. Skrefin eru svipuð fyrir öll önnur innkaupa- og söluskjöl.

## <a name="to-set-up-item-charge-numbers"></a>Uppsetning kostnaðaraukanúmera
Vörugjaldsnúmer eru notuð til að greina á milli mismunandi vörugjalda sem notuð eru fyrir innkaupaskjöl í fyrirtækinu.

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Kostnaðarauki** og velja svo viðeigandi tengil.
2. Í glugganum **Kostnaðarauki** skal velja aðgerðina **Nýtt** til að stofna nýja línu.
3. Fyllið inn í reitina eftir þörfum. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-assign-an-item-charge-directly-to-the-purchase-invoice-for-the-item"></a>Að úthluta kostnaðarauka beint til innkaupareiknings fyrir vöruna
Ef þú veist hver kostnaðaraukinn er þegar þú bókar innkaupareikning fyrir vöruna, skaltu fylgja þessu ferli.

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Innkaupareikningar** og velja svo viðeigandi tengil.
2. Stofnið nýja innkaupareikning. Nánari upplýsingar eru í [Hvernig á að: Skrá innkaup](purchasing-how-record-purchases.md).
3. Vertu viss um að innkaupareikningurinn hafi fleiri en eina línu af vörutegund.
4. Á nýja línu í reitnum **Tegund** er valinn **Kostnaðarauki Vöru**.
5. Í reitinn **Magn** er færður inn fjöldi eininga þess kostnaðarauka sem hefur verið reikningsfærður.
6. Í reitinn **Beinn einingakostnaður** er upphæð kostnaðaraukans færð inn.
7. Fyllið inn í eftirstandandi reiti eftir þörfum. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

    Í eftirfarandi skrefum, muntu framkvæma hina raunverulegu úthlutun. Þar til kostnaðarauka hefur verið úthlutað að fullu, er gildið í **Magn til úthlutunar** reitnum skrifað með rauðu letri.
8. Á flýtiflipanum **Línur** skal velja aðgerðina **Úthlutun kostnaðarauka**.

    Glugginn **Úthlutun kostnaðarauka** opnast og birtir eina línu fyrir hverja vörutegundarlínu á innkaupareikningnum. Til að úthluta kostnaðaraukanum á eina eða fleiri reikningslínur, er hægt að nota aðgerð sem úthlutar og dreifir honum fyrir þig, eða þú getur fyllt handvirkt út í reitinn **Magn til úthlutunar**. Eftirfarandi skref útskýra hvernig á að nota aðgerðina Leggja til úthlutun kostnaðarauka.

9. Í glugganum **Úthlutun kostnaðarauka** skal velja aðgerðina **Leggja til úthlutun kostnaðarauka**.
10. Ef það eru fleiri en ein vörutegundarlína í boði á reikningnum skal velja einn af fjórum dreifingarkostum.  

Ef kostnaðarauka hefur verið úthlutað að fullu, er gildið í **Magn til úthlutunar** reitnum á innkaupareikningnum núll.

Nú er kostnaðarauka úthlutað til innkaupareiknings. Þegar þú bókar innhreyfingu á innkaupareikning, er birgðavirði vörunnar uppfært með kostnaði kostnaðaraukans.  

## <a name="to-assign-an-item-charge-from-a-separate-invoice-to-the-purchase-invoice-for-the-item"></a>Að úthluta kostnaðarauka frá öðrum reikningi til innkaupareiknings fyrir vöruna
Ef þú færð sendan reikning fyrir kostnaðaraukann eftir að þú bókaðir upphaflegu innkaupamóttökuna, skaltu fylgja þessu ferli.
1. Endurtakið skref 1 til 8 í „Að úthluta kostnaðarauka beint til innkaupareiknings fyrir vöruna“ hlutanum.
2. Í glugganum **Úthlutun kostnaðarauka** skal velja aðgerðina **Sækja móttökulínur**.
3. Í glugganum **Innkaupamóttökulínur** skal velja bókaða innkaupamóttöku fyrir vöruna sem þú vilt úthluta kostnaðaraukanum á, og veljið því næst hnappinn **Í lagi**.
4. Veljið aðgerðina **Leggja til úthlutun kostnaðarauka**.

Kostnaðaraukinn á þessum aðgreinda innkaupareikningi er nú úthlutað til vörunnar á bókuðu innkaupamóttökunni, og þar með uppfærist birgðagildi vörunnar með kostnaði kostnaðaraukans.

## <a name="see-also"></a>Sjá einnig
[Stjórna skuldum](payables-manage-payables.md)  
[Hvernig á að skrá kaup](purchasing-how-record-purchases.md)  
[Hvernig er reikningsfært](sales-how-invoice-sales.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

