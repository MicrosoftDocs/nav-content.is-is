---
title: "Hvernig á að færa íhluti á aðgerðasvæði í einfaldri grunngerð vöruhúsa"
description: "Ef vöruvinnsla fer fram í vöruhúsi gæti þurft að færa vörur á milli innri hólfa í samræmi við innri upprunaskjöl, svo sem framleiðslu-, samsetningar- eða þjónustupantanir úr birgðageymslu."
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
ms.openlocfilehash: c1ee0394b835827eee3394a4bea3171d9294208c
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-move-components-to-an-operation-area-in-basic-warehouse-configurations"></a>Hvernig á að: færa íhluti á aðgerðasvæði í einfaldri grunngerð vöruhúsa
Ef vöruvinnsla fer fram í vöruhúsi gæti þurft að færa vörur á milli innri hólfa í samræmi við innri upprunaskjöl, svo sem framleiðslu-, samsetningar- eða þjónustupantanir úr birgðageymslu.  

> [!NOTE]  
>  Upplýsingar um hvernig færa á vörur á milli hólfa án upprunaskjala eru í Innri hreyfing.  

Í ítarlegri vöruhúsagrunnstillingu, þ.e. birgðageymslum sem nota uppsetningarreitinn **Beinn frágangur og tínsla**, er hægt að nota gluggann **Vinnublað hreyfingar** til að færa vörur milli hólfa. Nánari upplýsingar eru í [Hvernig á að færa vörur með ítarlegum vöruhúsaaðgerðum](warehouse-how-to-move-items-in-advanced-warehousing.md).  

Í einfaldri vöruhúsagrunnstillingu, þ.e. birgðageymslum sem nota uppsetningarreitina **Hólf áskilið** og **Krefjast tínslu** er hægt að skrá hreyfingar vara á svæði innri starfsemi samkvæmt innri upprunaskjölum á eftirfarandi hátt:  

-   Með glugganum **Birgðahreyfing**.  
-   Með glugganum **Birgðatínsla**.  

> [!NOTE]  
>  Birgðatínslur bóka einnig neikvæðar birgðafærslur sem notkun og eru aðeins studdar fyrir framleiðsluíhluti. Sjá Birgðatínsla fyrir frekari upplýsingar  

Til að fá nánari upplýsingar um birgðahreyfingar, sjá gluggann Birgðahreyfingar.  

Tvö mismunandi hlutverk geta stofnað upphafsbirgðahreyfinguna. Samsetningarstarfsmaður, til dæmis, getur stofnað hana úr útgefinni samsetningarpöntun þannig að hún birtist á lista starfsmanns í vöruhúsi yfir verk sem á eftir að gera. Ef búa á til birgðahreyfingu fyrir samsetningarpöntunarlínur sem eru tilbúnar til að láta flytja íhluti í tilgreind hólf sín notar samsetningarstarfsmaðurinn aðgerðina **Stofna birgðahreyfingu**.  

Að öðru kostir getur starfsmaður í vöruhúsi stofnað hana með því að benda á samsetningarpöntunina sem um ræðir. Þessu er lýst í eftirfarandi ferli.  

> [!NOTE]  
>  Ef hreyfing er til staðar fyrir samsetningarpöntun þegar vara er samsett úr sölupöntun er hægt að láta stofna birgðahreyfingaskjalið sjálfkrafa þegar birgðatínsluskjalið sem tekur við fullunnu samsetningarvörunni og bókar afhendingu er búið til. Til að setja þetta upp þarf að velja reitinn **Búa til hreyfingar sjálfvirkt** í **Uppsetning samsetningar** glugganum.  
>   
>  Nánari upplýsingar m samsetningapantanir og grunnskilgreiningar vöruhúsa eru í hlutanum „Meðhöndlun íhluta pantanasamsetninga við birgðatínslu” í [Hvernig skal: Taka til fyrir framleiðslu eða samsetningu](warehouse-how-to-pick-for-production.md).  

Þessi verklýsing sýnir hvernig á að búa til birgðahreyfingu úr glugganum **Birgðahreyfing** með því að vísa í útgefna samsetningarpöntun sem upprunaskjal. Ferlið er það sama þegar íhlutir eru færðir fyrir framleiðslupantanir og þjónustupantanir.  

## <a name="to-move-components-to-an-operation-area-in-basic-warehouse-configurations"></a>Til að færa íhluti á aðgerðasvæði í grunnskilgreiningu vöruhúss  
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Birgðahreyfingar** og velja svo viðeigandi tengil.  
2.  Á flýtiflipanum **Almennt** er reiturinn **Nr.** fylltur út . Hægt er að ýta á færslulykilinn til að velja úr númeraröð.  
3.  Í reitnum **Kóti birgðageymslu** er færð inn birgðageymslan þar sem hreyfingin á sér stað.  
4.  Valið er **Sækja upprunaskjöl** aðgerð. Að öðrum kosti er fyllt út í reitinn **Upprunaskjal** og valið svo hnappurinn **AssistEdit** í reitnum **Upprunanúmer**.  
5.  Í glugganum **Upprunaskjöl** er valin samsetningarpöntun sem á að færa íhluta í og veljið svo hnappinn **Í lagi**.  

    Fyrir hvern nauðsynlegan íhlut sem hægt er að flytja, eru ein Taka-lína og ein Setja-lína mynduð í glugganum **Birgðahreyfingar**. Allir reitir nema reiturinn **Magn til afgreiðslu** eru fylltir út fyrirfram samkvæmt upprunaskjalslínunum. Reiturinn **Magn til afgreiðslu** er stilltur á núll þar til magnið sem raunverulega hefur verið flutt er fært inn.  

    Hægt er að breyta hólfakóðanum á Taka-línunni, en aðeins í samræmi við ráðstöfunarmagn. Ef hnappurinn **AssistEdit** er valinn í reitnum **Hólfkóti** í Taka-línu mun glugginn **Innihald hólfs** opnast og aðeins sýna hólf þarf sem íhluturinn er tiltækur.  

    Ekki er hægt að breyta hólfkóta í línu. Aðeins hólfkóti sem er skilgreindur á íhlutalínu upprunaskjalsins er samþykktur. Þetta styður þá reglu að hlutverkið sem biður um íhlut, sem er samsetningarstarfsmaður í þessu ferli, eigi að vita hvar eigi að setja íhlutinn. Ef setja á íhluti í annað hólf þarf að fyrst að breyta hólfakótanum í íhlutalínunni og stofna birgðahreyfingalínurnar aftur.  
6.  Í reitnum **Magn til afgreiðslu** er fært inn að fullu eða að hluta til magnið sem raunverulega hefur verið flutt. Gildið á línum Taka og Setja verður að vera það sama. Annars er ekki hægt að skrá hreyfinguna.  

    > [!NOTE]  
    >  Eins og í öðrum vöruhúsaaðgerðum er hægt að skipta Setja-línu með því að velja **Aðgerðir** og svo **Skipta línu**. Í því tilviki verður samtala uppskiptu Setja-línanna tveggja að vera jöfn magninu í Taka-línunni.  

7.  Þegar allt er til reiðu til að skrá hreyfingar sem hafa verið framkvæmdar er aðgerðin **Skrá birgðahreyfingu** valin.  

    Vöruhúsafærslur eru stofnaðar til að spegla að íhlutirnir eru nú til í hólfunum sem tilgreind eru á samsetningarpöntunarlínunum.  

    > [!NOTE]  
    >  Ólíkt því þegar íhlutir eru færðir með birgðatínslu er notkun ekki bókuð þegar birgðahreyfing er skráð. Það skref verður að framkvæma sérstaklega með því að bóka samsetningu pöntunar, frálag og notkun. Frekari upplýsingar, sjá Samsetningarpöntun.  

## <a name="see-also"></a>Sjá einnig  
[Vöruhúsastjórnun](warehouse-manage-warehouse.md)  
[Birgðir](inventory-manage-inventory.md)  
[Vöruhúsastjórnun sett upp](warehouse-setup-warehouse.md)     
[Samsetningardeild](assembly-assemble-items.md)    
[Hönnunarupplýsingar vöruhúsakerfi](design-details-warehouse-management.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

