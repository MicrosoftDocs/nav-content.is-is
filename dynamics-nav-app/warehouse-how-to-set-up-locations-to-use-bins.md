---
title: "Hvernig á að setja upp birgðageymslur til að þær noti hólf"
description: "Hólf tákna grunnvöruhúsauppbyggingu og eru notuð til að gera tillögur að staðsetningu vöru. Þegar hólfin hafa verið stofnuð er hægt að skilgreina nánar hvaða innihald á að setja í hvert hólf eða nota hólfið sem fljótandi hólf án tiltekins innihalds."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/23/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 95b36b6eed79da868c1e41905110788c90f24829
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-locations-to-use-bins"></a>Hvernig á að setja upp birgðageymslur til að þær noti hólf
Hólf tákna grunnvöruhúsauppbyggingu og eru notuð til að gera tillögur að staðsetningu vöru. Þegar hólfin hafa verið stofnuð er hægt að skilgreina nánar hvaða innihald á að setja í hvert hólf eða nota hólfið sem fljótandi hólf án tiltekins innihalds.  

Ef nota á hólf í birgðageymslu þarf fyrst að virkja aðgerðina á spjaldinu **birgðageymsla** Síðan er vöruflæðið í birgðageymslunni útbúið með því að tilgreina hólfakóða í uppsetningarreitum sem tákna ólík flæði.  

> [!NOTE]  
>  Áður en hægt er að tilgreina hólfkóta í birgðageymsluspjaldinu þarf að stofna hólfkótana. Nánari upplýsingar eru í [Hvernig á að: Stofna hólf](warehouse-how-to-create-individual-bins.md).  

## <a name="to-set-up-a-location-to-use-bins"></a>Til að setja upp birgðageymslur til að þær noti hólf  
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Staðsetningar** og velja svo viðeigandi tengil.  
2.  Veljið birgðageymsluna þar sem á að nota hólf.  
3.  Veldu aðgerðina **Breyta**.  
4.  Á flýtiflipanum **Vöruhús** er gátreiturinn **Hólf áskilin** valinn.  
5.  Ef ekki er notaður beinn frágangur og tínsla er í reitnum **Sjálfgefið hólfaval** tilgreind aðferðin sem kerfið a´að nota þegar sjálfgefið hólf er tengt vöru.  
6.  Opna spjaldið fyrir birgðageymsluna sem setja á upp hólf fyrir.
7.  Á flýtiflipanum **Hólf** skal velja hólfin sem nota á sem sjálfgefin fyrir móttökur, afhendingar, á innleið, á útleið og opin vinnslusalarhólf.  
8.  Hólfakótarnir sem valdir eru hér munu birtast sjálfkrafa á hausum og línum vöruhúsaskjala. Sjálfgefnu hólfin skilgreina allar upphafs- og lokastaðsetningar vara í vöruhúsinu.  
9.  Ef notaður er beinn frágangur og tínsla skal velja hólf fyrir vöruhúsaleiðréttingar. Hólfakótinn í svæðinu **Kóti leiðréttingarhólfs** skilgreinir sýndarhólfið þar sem á að skrá misræmi í birgðum við skráningu annað hvort misræmis sem uppgötvast og skráð er í vöru í vöruhúsi færslubókar eða mismunar sem reiknaður er þegar raunbirgðir vöruhúss eru skráðar.  
10. Reitirnir á flýtiflipanum **Hólfareglur** eru fylltir út ef þeir eiga við í vöruhúsinu. Mikilvægustu reitirnir eru **Hólfageturegla**, **Leyfa einingaskipti** og **Kóti frágangssniðmáts**.  
11. Á flýtiflipanum **Vöruhús** skal fylla út reitina **Afgr.tími vara á útl. úr vöruh.**, **Afgr.tími vara á innl. úr vöruh.** og **Kóti grunndagatals**. Nánari upplýsingar er að finna í [Hvernig á að: setja upp grunndagatal](across-how-to-assign-base-calendars.md).

## <a name="filling-the-consumption-bin"></a>Fylla út notkunarhólfið
Þetta flæðirit sýnir hvernig reiturinn **Hólfkóði** í framleiðslupöntunaríhlutalínum er útfylltur samkvæmt uppsetningu staðsetningar.

![Flæðirit hólfa](media/binflow.png "Hólfaflæði")  

## <a name="see-also"></a>Sjá einnig
[Vöruhúsastjórnun](warehouse-manage-warehouse.md)  
[Birgðir](inventory-manage-inventory.md)  
[Vöruhúsastjórnun sett upp](warehouse-setup-warehouse.md)     
[Samsetningardeild](assembly-assemble-items.md)    
[Hönnunarupplýsingar vöruhúsakerfi](design-details-warehouse-management.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

