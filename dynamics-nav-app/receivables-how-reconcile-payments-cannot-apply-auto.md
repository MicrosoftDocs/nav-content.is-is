---
title: "hvernig á að: afstemma greiðslur sem ekki er hægt að afstemma sjálfkrafa."
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
ms.openlocfilehash: f9fd7c2958aaa359d2f6af5dde2e8be81349e900
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-reconcile-payments-that-cannot-be-applied-automatically"></a>hvernig á að: afstemma greiðslur sem ekki er hægt að afstemma sjálfkrafa.
Stundum gætirðu þurft að meðhöndla greiðslur inna á bankareikninginn þinn sem ekki er hægt að jafna við tengdan opinn viðskiptavin, lánardrottin, eða bankareikningsfærslu. Ástæðurnar geta verið að ekkert skjal er til í Dynamics NAV sem greiðslan getur verið jöfnuð við, eða tengd skjal í Dynamics NAV hefur aðra upphæð en færsluupphæð, til dæmis, vegna gengi gjaldmiðils. Í **greiðslubók Afstemming** glugga, allar færsluupphæðir fyrir greiðslur sem ekki eru jafnaðar enn birtast í **mismunur** reit, þar með talið upphæðir sem ekki er hægt að jafna vegna ástæða eins og þeirrar sem nefd var að ofan.

Greiðslur sem ekki er hægt að jafna geta birst á greiðsluafstemmingarbókarlínum á eftirfarandi mismunandi hætti:

- Gildið í **Mismunur** reit er jafnt og gildið í **færsluupphæð** reitnum sem gefur til kynna að enginn hluti greiðslunnar getur verið jafnaður við tengda opna viðskiptavina-, lánardrottna- eða bankareikningsfærslu.

- Gildið í **Mismunur** reit er lægri en gildið í **færsluupphæð** reitnum sem gefur til kynna að hluti greiðslunnar getur verið jafnaður við tengda opna viðskiptavina-, lánardrottna- eða bankareikningsfærslu. Eftirstandandi hluti greiðslunnar er ekki hægt að jafna og verður að vera afstemmdur handvirkt eða með því að bóka hann beint á reikninginn.

Að afstemma slíka greiðslu, þú getur valið flutnings hnappinn Flytja mismun á reikning og tilgreina síðan hvaða reikning upphæðin í reitnum mismunur verður bókuð á þegar þú bókar greiðsluafstemmingarbók.

**Athuga skal að**: Svipuð virkni er til til að setja upp sjálfvirka afsettmingu á endurteknum greiðslum sem er ekki hægt að jafna við tengda opna viðskiptavina-, lánardrottna- eða bankareikningsfærslur. [Fyrir frekar upplýsingar, sjá Hvernig á að varpa texta á endurteknar greiðslur á reikninga fyrir sjálfvirka afstemmingu](receivables-how-map-text-recurring-payments-accounts-auto-reconcilliation.md)

## <a name="to-reconcile-payments-that-cannot-be-applied"></a>Að afstemma greiðslur sem ekki er hægt að jafna
1. Í efra hægra horni, veldu **leita að síðu eða skýrslu**, færðu inn **Greiðsluafstemmingarbækur** og velja síðan viðkomandi tengil.
2. Opna skal greiðsluafstemmingarbók. Frekari upplýsingar eru í [hvernig á að afstemma greiðslur með því að nota sjálfvirka jöfnun](receivables-how-reconcile-payments-auto-application.md)
3. Veldu **Flytja mismun á reikning** **Flytja mismun á reikning** 3 Glugginn  opnast.
4. Í reitnum **Tegund reiknings** tilgreindu tegund reiknings sem greiðsluupphæðin verður bókuð á.
5. Í svæðinu **Bankareikningsnúmer**,  reit, tilgreindu reiknings sem greiðsluupphæð verður bókuð á.
6. Í reitnum **Lýsing** tilgreindu texta sem lýsir þessum beinu greiðslubókun. Sjálfgefið er að textinn í reitnum **Færslutexti** sé færður inn.
7. Velja hnappinn **Í lagi**.

Ef gildið í í **Mismunur** reit var jafnt og gildið í reitnum á **færsluupphæð** reit þegar þú bókar greiðsluafstemmingarbók, verður öll greiðslan á færslubókarlínu bókuð beint á tilgreindan mótreikning.

Ef gildið í í **Mismunur** reit var lægra en gildið í **færsluupphæð** þá verður aukaleg færslubókarlína stofnuð með sama texta og dagsetningu með mismuninum innsettum í reitinn **færsluupphæð** Á upphaflegu færslubókarlínu er mismunurinn dreginn frá gildinu í **færsluupphæð** reitnum, og greiðslan verður áfram jöfnuð við tengdan viðskiptavinar-, lánardrottins eða bankareikningsfærslu. Þegar þú bókar greiðsluafstemmingarbók, verður einn hluti greiðslunnar bókuð sem jöfnuð greiðsla. Aðra hluti greiðslu bókast beint á tilgreinda reikninga.

## <a name="see-also"></a>Sjá einnig
[Umsjón viðskiptakrafna](receivables-manage-receivables.md)  
[Stjórna sölu](sales-manage-sales.md)

