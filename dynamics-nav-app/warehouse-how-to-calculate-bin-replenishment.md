---
title: "Hvernig á að reikna út áfyllingu hólfs"
description: "Þegar birgðageymslan er sett upp þannig að hún noti beinan frágang og tínslu er forgangsröðun frágangssniðmátsins tekið með í reikninginn þegar verið er að ganga frá móttökum."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/23/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 3a6ff833aad54cf98720857a8ae67492abe9af4f
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-calculate-bin-replenishment"></a>Hvernig á að Reikna út áfyllingu hólfs
Þegar birgðageymslan er sett upp þannig að hún noti beinan frágang og tínslu er forgangsröðun frágangssniðmátsins tekið með í reikninginn þegar verið er að ganga frá móttökum. Á meðal forgangsatriða eru fast lágmarks- og hámarksmagn tiltekins hólfs og hólfaflokkanir. Því fyllist á mest notuðu hólfin eftir því sem þau tæmast ef vörur berast jafnt og þétt.  

En birgðir berast ekki alltaf í jöfnum skömmtum. Stundum eru vörur keyptar í miklu magni til að fá afslátt eða þá að framleitt er mikið í einu til að lækka einingarkostnað. Þá berast vörurnar ekki aftur í vöruhúsið í nokkurn tíma og færa þarf vörur með reglulegu millibili í tínsluhólf úr geymslusvæðum.  

Einnig getur verið að von sé á nýjum birgðum og tæma eigi geymslusvæðið áður en nýju vörurnar koma.  

Að lokum, hafi geymsluhólfin aðeins verið skilgreind fyrir **frágang** þ.e. tegund hólfanna er ekki með valda aðgerðina **Tína** þarf alltaf að hafa tínsluhólfin full þar sem ekki er ráðlagt að vörur séu tíndar úr hólfum sem eru bara fyrir frágang.  

## <a name="to-replenish-pick-bins"></a>Fyllt á tínsluhólf  
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Hreyfingarvinnublað** og velja svo viðeigandi tengil.  
2.  Velja skal aðgerðina **Reikna áfyllingu hólfs** til að opna síður skýrslubeiðna.  
3.  Beiðnigluggi keyrslunnar er fylltur út til að takmarka umfang áfyllingartillagna sem verða reiknaðar. Til dæmis gæti átt að leggja áherslu á tilteknar vörur, svæði eða hólf.  
4.  Velja hnappinn **Í lagi**. Línur eru stofnaðar fyrir áfyllingarhreyfingar sem þarf að framkvæma reglum sem settar hafa verið upp fyrir hólfin og innihald hólfa, þ.e. vörur í hólfum.  
5.  Eigi að framkvæma allar áfyllingar sem lagðar eru til skal velja aðgerðina **Stofna hreyfingu**. Starfsmenn geta nú fundið leiðbeiningar í valmyndaratriðinu **Hreyfingar**, fylgt þeim og skráð þær.  
6.  Eigi aðeins að framkvæma sumar af tillögunum skal eyða línunum sem skipta minna máli og stofna síðan hreyfingu.  

Næst þegar áfylling hólfa er reiknuð verða tillögurnar sem eytt er stofnaðar aftur ef þær eiga enn við á þeim tíma.  

> [!NOTE]
>  Ef eftirfarandi skilyrðum er fullnægt vegna vöru:  
> 
> - Varan er fyrningadagsett, og  
>   -   Reiturinn **Tína eftir FEFO** í birgðageymsluspjaldinu er valinn og  
>   -   Aðgerðin **Reikna út áfyllingu hólfs** er notuð  
> 
>   þá verða **Frá-svæði** og **Frá-hólf** reitirnir auðir vegna þess að reiknisögnin sem notuð er til að reikna hvaðan á að færa vörurnar er aðeins virkjuð þegar aðgerðin **Stofna hreyfingu** er ræst.  

## <a name="see-also"></a>Sjá einnig  
[Vöruhúsastjórnun](warehouse-manage-warehouse.md)  
[Tínsla eftir FEFO](warehouse-picking-by-fefo.md)  
[Birgðir](inventory-manage-inventory.md)  
[Vöruhúsastjórnun sett upp](warehouse-setup-warehouse.md)     
[Samsetningardeild](assembly-assemble-items.md)    
[Hönnunarupplýsingar vöruhúsakerfi](design-details-warehouse-management.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

