---
title: "Hvernig á að stofna Vöruskilapantanir innkaupa Frágangur úr innanhússfrágangi"
description: "Þegar gengið hefur verið frá vörum og áður en þær eru tíndar til að fylla upp í framleiðslupöntun eða afhendingu eru þær geymdar í vöruhúsinu sem hluti af tiltækum birgðum."
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
ms.openlocfilehash: 970b9b9046018b0dcea5b9996d10e19e444a7639
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-pick-and-put-away-without-a-source-document"></a>Hvernig skal: tína og ganga frá án upprunaskjals
Þegar gengið hefur verið frá vörum og áður en þær eru tíndar til að fylla upp í framleiðslupöntun eða afhendingu eru þær geymdar í vöruhúsinu sem hluti af tiltækum birgðum.  

Þær aðstæður geta komið upp að taka þurfi vörur tímabundið úr tínsluhólfum vöruhússins, til dæmis til notkunar sem sýnishorn í sölukynningu. Þessar vörur eru enn í eigu fyrirtækisins og eru hluti af birgðum en eru ekki tiltæk í tínslu. Þær eru skráðar í sérstakt hólf sem stofnað er í þessum tilgangi; tæknilega eru vörurnar í vöruhúsinu en í raun gætu þær verið í fundarherbergi eða sýningarsal.  

Við aðrar aðstæður, gæti framleiðslueiningin óvænt þurft að fá nokkra hluti vegna vinnslu. Hægt er að tína vörur fyrir framleiðsluhólf með innanhússtínslunni. Þegar vinnslunni er lokið og úttak verður til er notkun vörunnar bókuð og framleiðsluhólfið tæmt sem síðan minnkar magn vörunnar í birgðageymslunni.  

Á sama hátt er hægt að skila vörum í vöruhúsið til frágangs. Varan gæti hafa verið tekin úr tiltækum birgðum og síðan aldrei notuð. Ganga verður frá þeim í hólfi til að þær verði tiltækar aftur í birgðum.  

**Innanhússfrágangar** gera þér kleift að framkvæma frágang án þess að vísa í ákveðið upprunaskjal. Auðvelt er að setja upp allar þær upplýsingar sem þarf til að stofna vöruhúsaleiðbeiningar um frágang.  

> [!NOTE]  
>  Ef ekki eru notaðar innanhússtínslur og innanhússfrágangar er hægt að gera þessar leiðréttingar með því að færa vörur úr hólfi í hólf eða að bóka magnleiðréttingar í hólfi.  
>   
>  þegar birgðageymslan notar beinan frágang og tínslu og því hólfategundir er ekki hægt að færa vörur handvirkt inn og út úr hólfi af tegundinni RECEIVE því vörur sem eru í hólfi af þeirri gerð verður að skrá sem frágengnar áður en þær verða hluti af tiltækum birgðum.  

## <a name="to-create-an-internal-pick"></a>Að búa til Innahússtínslur  
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Innanhússtínsla vöruhúss** og velja svo viðeigandi tengil.  
2.  Fylla þarf út reitinn **Nr.**. reitinn og **Kóði til-hólfs** reitinn á flýtiflipanum **Almennt**. Reiturinn **Kóti til-hólfs** tilgreinir hólfið sem vörurnar eru sóttar í. Við framleiðslu væri þetta hólf innhólf framleiðslu eða opið búðarhólf. Annars skal velja Kóta til-hólfs með hólfi af tegund sem ekki er notuð við tínslu, oftast nær undirbúnings- eða afhendingarhólf eða hólf fyrir sérstök tilefni.  
3.  Vara er valin í reitnum **Vörunr.** og magnið sem á að tína fært inn.  
4. Veldu aðgerðina **Stofna tínslu**. Vöruhúsatínsluleiðbeiningar eru nú tilbúnar fyrir starfsmann vöruhúss.  

## <a name="to-create-an-internal-put-away"></a>Stofna innanhússfrágang  
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Innanhússfrágangur vöruhúss** og velja svo viðeigandi tengil.  
2.  Fylla þarf út reitinn **Nr.**. og **Frá hólfakóða** reitina á flýtiflipanum **Almennt**. Reiturinn **Kóti frá-hólfs** tilgreinir hólfið þar sem vörurnar sem skila á í vöruhúsið, til dæmis úr framleiðslu, eru geymdar.  
3.  Vörunúmerin og magnið er fært inn í línurnar.  
4.  Veldu aðgerðina **Stofna frágang**. Leiðbeiningar um vöruhúsafrágang eru nú tilbúnar fyrir starfsmann vöruhúss.  

## <a name="see-also"></a>Sjá einnig  
[Vöruhúsastjórnun](warehouse-manage-warehouse.md)  
[Birgðir](inventory-manage-inventory.md)  
[Vöruhúsastjórnun sett upp](warehouse-setup-warehouse.md)     
[Samsetningardeild](assembly-assemble-items.md)    
[Hönnunarupplýsingar vöruhúsakerfi](design-details-warehouse-management.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

