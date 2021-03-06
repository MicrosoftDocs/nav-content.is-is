---
title: "Uppsetning á óinnleystum virðisaukaskatti"
description: "Ef þú ert að nota bókhaldsreikning getur þú tilgreint hvernig á að meðhöndla óinnleyst virðisaukaskatt vegna sölu og kaupa."
documentationcenter: 
author: bholtorf
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: cash, VAT, unrealized, cash-based
ms.date: 09/08/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: f5786a79e8f12bd86b3d6f7ce53e0c698b19cef4
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---

# <a name="how-to-set-up-unrealized-vat-for-cash-based-accounting"></a>Hvernig á að: Setja upp áætlaður VSK fyrir reikningsskilaaðferðir í reiðufé
Ef þú ert að nota reikningsskilaaðferðir í reiðufé, getur þú sett upp [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)] til að takast á við óinnleystan virðisaukaskatt.

## <a name="to-use-general-ledger-accounts-for-unrealized-vat"></a>Nota fjárhagsreikninga fyrir óinnleystan virðisaukaskatt
Hægt er að velja að VSK-upphæðir verði reiknaðar og bókaðar á bráðabirgðafjárhagsreikning þegar reikningur er bókaður, og síðan bókaður á rétta fjárhagsreikninginn og settur í VSK-yfirlitin þegar endanlega greiðsluupphæð reikningsins er bókuð. Áður en þetta er hægt þarf að ljúka við VSK-bókunargrunninn.

Til að nota reikninga fyrir óinnleyst virðisaukaskatt skaltu fylgja þessum skrefum:
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Uppsetning fjárhags** og velja svo viðeigandi tengil. 
2. Á **Uppsetning fjárhags** síðunni á flýtiflipanum **Almennt** velurðu **Sýna meira** og svo **Óinnleystur VSK** gátreitinn.
3. Lokaðu síðunni.
4. velja **Leita að síðu eða skýrslu** táknið ![Leita að síðu eða skýrslu](media/ui-search/search_small.png "Leita að síðu eða skýrslu táknið"), færa inn **VSK-bókunargrunnur**. 
5. Á **VSK-bókunargrunnur** velurðu VSK-bókunarflokk og síðan **Breyta**. 
6. Í reitnum **Tegund áætlaðs VSK**, veldu valkost til að tilgreina hvernig á að úthluta greiðslum til reikningsupphæð (án virðisaukaskatts) og virðisaukaskatts sjálfs og hvernig á að flytja virðisfjárhæðir úr óreynduðu virðisaukaskatti á reikninginn. Eftirfarandi tafla lýsir valkostunum.

| Valkostur | Lýsing |
| --- | --- |
| Autt | Veldu þennan valkost ef þú vilt ekki nota óinnleystur virðisaukaskatt. |
| prósentu | Greiðslur nær bæði virðisaukaskatti og reikningsupphæðinni í hlutfalli við hlutfall greiðslunnar af því sem eftir er af reikningnum. Greiddur virðisaukaskattur er fluttur frá óinnleyst VSK reikningi til áttaðs VSK reikning. |
| Fyrsta | Greiðslur ná fyrst yfir virðisaukaskatt og síðan reikningsupphæðir. Þegar svo vill til verður upphæð sem flutt er af reikningi áætlaðs VSK á VSK-reikning jöfn upphæð greiðslu uns VSK er greiddur að fullu. |
| Síðasta | Greiðslur taka fyrst til reikningsupphæðar og síðan VSK. Í þessu tilviki verður engin upphæð flutt úr óreiknuðu virðisaukaskatti til VSK reiknings þar til heildarfjárhæð reikningsins, án virðisaukaskatts, hefur verið greiddur. |
| Fyrst (fullgreitt) | Greiðslur munu ná til virðisaukaskatts fyrstu (eins og valkosturinn _Fyrst_) en engin upphæð verður flutt á VSK reikning fyrr en heildarupphæð virðisaukaskatts hefur verið greidd. |
| Síðast (fullgreitt) | Greiðslur verða fyrst og fremst gjaldfærð (eins og valkosturinn _Síðasti_) en engin upphæð verður flutt á VSK reikning fyrr en heildarupphæð virðisaukaskatts hefur verið greidd. |

6. Í **Reikn. áætlaðs útskatts**, veldu reikning fyrir óinnleyst söluskatt.

    > [!NOTE]  
   >   VSK upphæðin verður bókuð á þennan reikning, og verður þar til greiðslu viðskiptavinarins er bókuð. Fjárhæðin er síðan flutt á reikninginn vegna söluverðs.
7. Í **Reikn. áætlaðs innskatts** sláðu inn aðalbókaratölu fyrir óinnleyst kaupverð.

    > [!NOTE]  
   >   VSK upphæðin verður bókuð á þennan reikning, og verður þar til greiðslu viðskiptavinarins er bókuð. Fjárhæðin er síðan flutt á reikninginn vegna söluverðs.

## <a name="see-also"></a>Sjá einnig
[Uppsetning á virðisaukaskatti](finance-setup-vat.md)
