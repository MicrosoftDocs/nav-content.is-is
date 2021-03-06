---
title: "Flytja inn launafærslur"
description: "Þegar launum er stjórnað, eru fjárhagsfærslur fluttar inn og bókaðar frá launaveitu til fjárhags, með því að nota launaviðbætur eins og Ceridian eða Quickbooks."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: Ceridian, Quickbooks, salary
ms.date: 06/16/2017
ms.author: SorenGP
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 675a63c7862854ef3f8e2ca3d37dd3f2e290cf29
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-import-payroll-transactions"></a>Hvernig á að: Flytja inn launafærslur
Fyrir launagreiðslur og tengdar færslur verður að flytja inn og birta fjárhagslegar færslur úr launaveitu í fjárhag. Fyrir þetta þarf fyrst að flytja inn skrá úr launaveitu yfir í gluggann **Færslubók**. Síðan varparðu ytri reikningunum í skránni launagreiðslur á viðeigandi fjárhagsreikninga. Að lokum bókarðu launafærslur samkvæmt reikningsvörpuninni.

> [!NOTE]  
>   Til að nota þessa aðgerð þarf viðbót fyrir innflutning launa að vera uppsett og virkjuð. The Ceridian Payroll og Quickbooks Payroll File Import eftirnafn eru fyrirfram uppsett í [!INCLUDE[d365fin](includes/d365fin_md.md)]. Frekari upplýsingar skoða [Sérstilla [!INCLUDE[d365fin](includes/d365fin_md.md)] Nota viðbætur](ui-extensions.md).

## <a name="to-import-a-payroll-file"></a>Til að flytja inn launaskrá
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **færslubók** og velja svo viðeigandi tengil.
2. Í viðkomandi færslubókarkeyrslu skal velja **Flytja inn launafærslur**. Uppsetning með hjálp opnast.
3. Fylgdu skrefunum í glugganum **Flytja inn launafærslur**.

    > [!TIP]  
   >   Í liðnum þar sem ytri launaskrám er varpað í fjárhagsreikningana þína man kerfið þá vörpun næst þegar sömu skýrslur eru fluttar inn. Þetta sparar tíma því ekki þarf að fylla handvirkt inn svæðið **Reikningnúmer** í færslubókinni í hvert skipti sem þú hefur flutt inn ítrekaða launafærslu.   

    Þegar hnappurinn **Í lagi** er valinn í uppsetningu með leiðsögn er glugginn **Almenn færslubók** fullur af línum sem tákna færslurnar sem launaskráin innheldur og búið er að fylla út tilheyrandi lykla í reitunum **Fjárhagsreikningur** í samræmi við þá vörpun sem gerð var í leiðsögninni.
4. Breyta skal eða bóka færslubókarlínur líkt og fyrir allar aðrar færslur í fjárhag. Frekari upplýsingar, sjá [Hvernig skal: Bóka færslu beint yfir í Fjárhag](finance-how-post-transactions-directly.md)   

## <a name="see-also"></a>Sjá einnig
[Fjármál](finance.md)  
[Sérstilling [!INCLUDE[d365fin](includes/d365fin_md.md)] með viðbótum](ui-extensions.md)  
[Vinna í færslubókum](ui-work-general-journals.md)  

