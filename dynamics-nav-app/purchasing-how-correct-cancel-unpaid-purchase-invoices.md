---
title: "Breyta eða hætta við ógreidda innkaupareikninga | Microsoft Docs"
description: "Útskýrir hvernig á að leiðrétta, hætta við, eða afturkalla bókaðan innkaupareikning og stofna sjálfvirkt innkaupakreditreikning."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: undo, credit memo, return
ms.date: 08/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 294094f8483f9b51d47ad614b8702b289b9d1862
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-correct-or-cancel-unpaid-purchase-invoices"></a>Leiðrétta eða afturkalla ógreidda innkaupareikninga
Hægt er að leiðrétta eða afturkalla bókaðan innkaupareikning. Þetta er gagnlegt þegar leiðrétta á innsláttarmistök eða breyta kaupunum snemma í pöntunarferlinu.

Ef þegar hefur verið greitt fyrir vörur á bókuðum innkaupareikningi er ekki hægt að leiðrétta eða hætta við úr bókaða innkaupareikningnum. Þess í stað verður þú að handvirkt skapa innkaupakreditreikning til að snúa við innkaup, valfrjálst stjórnað með vöruskilapöntun innkaupa. Nánari upplýsingar er að finna í [Hvernig á að: Vinna úr innkaupaskilum eða afturköllunum](purchasing-how-process-purchase-returns-cancellations.md).

Í glugganum **Bókaður innkaupareikningur** er hægt að velja hnappinn **Leiðrétting** eða hnappinn **Hætta við**. Þegar bókaður innkaupareikningur er leiðréttur eða afturkallaður, er bókaður innkaupakreditreikningur jafnaður við allar fjárhags- og raunbirgðafærslur sem búnar voru til við bókun hins upphaflega innkaupareiknings. Þetta bakfærir hinn bókaða innkaupareikning í fjárhagslegum færslum og lætur hina leiðréttu bókaða innkaupakreditreikninga í endurskoðunarrakninguna. Hér á eftir er notkun **Leiðrétting** og **Hætta við**lýst.

## <a name="to-correct-a-posted-purchase-invoice"></a>Til að leiðrétta bókaðan innkaupareikning.
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **bókaðir innkaupareikningar** og velja svo viðeigandi tengil.  
2. Veljið bókaða innkaupareikninginn sem á að leiðrétta.  

    > [!NOTE]  
   >   Ef gátreiturinn **Hætta við** er valinn, er ekki hægt að leiðrétta þennan bókaða sölureikning þar sem hann hefur þegar verið leiðréttur eða afturkallaður.
3. Í glugganum **Bókaður innkaupareikningur** skal velja **Rétt**.

    Nýr sölureikningur með sömu upplýsingum er stofnaður þar sem hægt er að gera leiðréttinguna. Nánari upplýsingar eru í [Hvernig á að: Skrá innkaup](purchasing-how-record-purchases.md). Reiturinn **Hætt við** á hinum upphaflega bókaða sölureikningi er breytt í **Já**.

    Leiðréttur sölukreditreikningur er búinn til sjálfkrafa og bókaður til að ógilda upphaflega bókaða sölureikninginn.
4. Veljið **Sýna leiðréttan kreditreikning** til að skoða bókaða sölukreditreikninginn sem ógildir upphaflega bókaða sölureikninginn.

## <a name="to-cancel-a-posted-purchase-invoice"></a>Til að afturkalla bókaðan innkaupareikning.
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **bókaðir innkaupareikningar** og velja svo viðeigandi tengil.  
2. Veljið bókaða innkaupareikninginn sem á að afturkalla.

    > [!NOTE]  
   >   Ef gátreiturinn **Afturkalla** er valinn, er ekki hægt að afturkalla þennan bókaða sölureikning þar sem hann hefur þegar verið leiðréttur eða afturkallaður.
3. Í glugganum **Bókaður innkaupareikningur** skal velja **Afturkalla**.

    Leiðréttur sölukreditreikningur er búinn til sjálfkrafa og bókaður til að ógilda upphaflega bókaða sölureikninginn. Reiturinn **Hætt við** á hinum upphaflega bókaða sölureikningi er breytt í **Já**.
4. Veljið **Sýna leiðréttan kreditreikning** til að skoða bókaða sölukreditreikninginn sem ógildir upphaflega bókaða sölureikninginn.

## <a name="see-also"></a>Sjá einnig
[Innkaup](purchasing-manage-purchasing.md)  
[Hvernig á að skrá kaup](purchasing-how-record-purchases.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

