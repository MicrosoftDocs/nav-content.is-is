---
title: "Hvernig á að reikna dagsetningu pöntunarloforðs"
description: "Pöntunarloforðsaðgerðin nýtist til að reikna fyrstu hugsanlegu dagsetningu fyrir sendingu eða afhendingu á vöru. Einnig eru búnar til innkaupatillögulínur fyrir dagsetningarnar sem eru samþykktar."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/10/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 5c2167397d95d04c937ddf1820e6e9edff906b2f
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-calculate-order-promising-dates"></a>Hvernig á að reikna Dagsetningu pöntunarloforðs
Fyrirtæki verður að geta upplýst viðskiptamenn sína um afhendingardagsetningar pöntunar. Glugginn **Línur pöntunarloforðs** gerir kleift að framkvæma þetta í sölupöntunarlínu.  

Grundvallaður á þekktum og áætluðum ráðstöfunardagsetningum vöru, [!INCLUDE[d365fin](includes/d365fin_md.md)] reiknar strax sendingar- og afhendingardagsetningar, sem er svo hægt að lofa viðskiptamanninum.  

Ef tilgreindur er afgreiðsludagsetning á sölupöntunarlínunni notar forritið þessa dagsetningu sem upphafspunkt fyrir eftirfarandi útreikninga  

- Umbeðin afgreiðsludagsetning – Flutningstími = Áætluð afhendingardagsetning  
- sfhendingardagsetning + afgr.tími vara á útl. úr vöruh. = afh.dags.  

Ef varan er tiltæk til tínslu á afhendingardagsetningu þá getur söluferlið haldið áfram. Ef varan er ekki tiltæk til tínslu á afhendingardegi þá birtist viðvörun um að varan sé uppseld.  

Ef ekki er tilgreind umbeðin afgreiðsludagsetning á sölupöntunarlínunni, eða ef ekki er hægt að verða við umbeðinni afgreiðsludagsetningu, er reiknuð fyrsta dagsetningin sem vörurnar eru tiltækar. Sú dagsetning er færð inn í reitinn **Afhendingardagsetning** á línuna og eftirtaldar reiknireglur eru síðan notaðar til að reikna út hvenær áætlað er að senda vörurnar ásamt því á hvaða degi viðskiptamaðurinn fær þær afhentar.  

- Afhendingardagsetning + afgr.tími vara á útl. úr vöruh. = Áætluð afhendingardagsetning  
- áætluð afhendingardagsetning + flutningstími = áætluð afgreiðsludagsetning  

## <a name="about-order-promising"></a>Um pöntun lofað
Aðgerðin Pöntunarloforð gerir kleift að lofa því að pöntun verði send eða afhent á tilteknum degi. Kerfið reiknar út hvenær vara er tiltæk eða hægt að lofa henni og það býr til pöntunarlínur fyrir þær dagsetningar sem samþykktar eru. Pöntunarloforðsaðgerðin reiknar fyrstu hugsanlegu dagsetningu fyrir sendingu eða afhendingu á vöru. Einnig eru búnar til innkaupabeiðnilínur, ef fyrst skyldi þurfa að kaupa inn vörurnar, fyrir dagsetningarnar sem eru samþykktar.

[!INCLUDE[d365fin](includes/d365fin_md.md)] notar tvö grundvallarhugtök:  

- Tiltækt að lofa (ATP)  
- Hægt að lofa (CTP)  

### <a name="available-to-promise"></a>Tiltækt að lofa  
Tiltæk til að lofa (ATP) reiknar út dagsetningar á grundvelli frátekningarkerfisins. Hún gerir ráðstöfunarathugun á ófráteknu magni í birgðum með tilliti til áætlaðrar framleiðslu, innkaupa, flutninga og söluskila. Á grundvelli þessarar upplýsinga, reiknar [!INCLUDE[d365fin](includes/d365fin_md.md)] afhendingardagsetningu fyrir pöntun viðskiptamanns þar sem vörurnar eru tiltækar, annaðhvort í birgðum eða í áætluðum móttökum.  

### <a name="capable-to-promise"></a>Hægt að lofa  
Hægt að lofa (CTP) tekur á sig mynd „hvað ef“ dæmis, þar sem varan er ekki til í birgðum og engum pöntunum eru raðað. Samkvæmt þessu dæmi, reiknar [!INCLUDE[d365fin](includes/d365fin_md.md)] út fyrstu dagsetningu þegar varan er til ef á að framleiða hana, kaupa eða flytja.  


### <a name="calculations"></a>Útreikningar  
Þegar [!INCLUDE[d365fin](includes/d365fin_md.md)] reiknar afhendingardagsetningu viðskiptamanns framkvæmir það tvo verkhluta:  

- Reiknar elstu dagsetninguna þegar viðskiptamaður hefur ekki beðið um sérstaka afgreiðsludagsetningu.  
- Vottar hvort afhendingardagsetningin sem viðskiptavinurinn biður um eða er lofað er raunsæ.  

Ef viðskiptamaðurinn biður ekki um sérstaka afgreiðsludagsetningu verður afhendingardagsetningin stillt á vinnudagsetninguna og ráðstöfunin verður byggð á þeirri dagsetningu. Ef varan er í birgðum reiknar [!INCLUDE[d365fin](includes/d365fin_md.md)] fram í tíma til að ákvarða hvenær afhenda megi pöntunina. Þetta næst með eftirfarandi formúlum:  

- Afh.dags + út úr vöruhúsi + áætluð afhending + Afgreiðslutími = Dagsetning  
- Áætluð afhendingardagsetning + Flutningstími = Áætluð afgreiðsludagsetning  

[!INCLUDE[d365fin](includes/d365fin_md.md)] síðan er sannreynt hvort útreiknuð afhendingardagsetning er raunhæf með því að reikna aftur í tímann til að ákvarða hvenær varan verður að vera tiltæk til að standast setta dagsetningu. Þetta næst með eftirfarandi formúlum:  

- Áætluð afhendingardagsetning – Flutningstími = Áætluð afgreiðsludagsetning  
- Áætluð afhendingardagsetning - Afgreiðslutími út úr vöruhúsi + Afh.dags.  

Afhendingardagsetning er notuð til að gera til ráðstöfunarathugunina. Ef varan er tiltæk á þeim degi staðfestir [!INCLUDE[d365fin](includes/d365fin_md.md)] að umbeðin/lofuð afhending standist með því að stilla áætlaða afhendingardagsetningu á umbeðna/lofaða afhendingardagsetningu. Ef varan er ekki tiltæk er auðri dagsetningu skilað og þá getur pöntunarvinnslan notað CTP-virkni.  

Byggt á nýjum dagsetningum og tímum, allar tengdar dagsetningar eru reiknaðar samkvæmt reiknireglum sem lýst var fyrr í þessum kafla. CTP-útreikningurinn tekur lengri tíma en gefur nákvæmari dagsetningu þess hvenær viðskiptavinurinn gefur vænst þess að fá vöruna afhenta. Dagsetningarnar sem eru reiknaðar með CTP eru sýndar í **Áætluð afhendingardagsetning** og **Fyrsti mögulegi afhendingardagur** svæðunum í **Pöntun lofað línur** glugganum.  

Pantanavinnsla lýkur CTP-ferlinu með því að samþykkja dagsetningarnar. Þetta þýðir að áætlunarlína og frátekningarfærslan hafa verið stofnaðar fyrir vöruna fyrir reiknaðar dagsetningar til að tryggja að pöntunin sé uppfyllt.  

Auk ytri pantanaloforða í glugganum sem hægt er að framkævma í glugganum **Pöntun lofað línur** er einnig hægt að lofa innri eða ytri afhendingardagsetningu fyrir uppskriftavörur. Frekari upplýsingar, sjá [Hvernig skal: Skoða tiltækileika vöru](inventory-how-availability-overview.md).

## <a name="to-set-up-order-promising"></a>Uppsetning pöntunarloforðs  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Pöntun lofað uppsetning** og velja svo viðeigandi tengil.  
2. Númer og tímaeiningarkóti er fært inn í reitinn **Mótfært (Tími)**. Einn af eftirfarandi kótum er valinn:  

    |Kóti|Lýsing|  
    |----------|-----------------|  
    |**d**|Almanaksdagur|  
    |**v**|Vika|  
    |**m**|Mánuður|  
    |**f**|Fjórðungur|  
    |**á**|Ár|  

    Til dæmis merkir “3v” að mótfærður tími eða frestur er þriggja vikna. Til að gefa til kynna gildandi tímabil, setjið forlið fyrir alla þessa kóta með bókstafnum “ c “. Eigi til dæmis mótfærður tími að vera yfirstandandi mánuður er fært inn **cm**.  
3. Númeraröð er færð inn í reitinn **Pöntunarloforð nr.** með því að velja línu af listanum í glugganum **Nr. röð**.  
4. Sniðmát pöntunarloforða er fært inn í reitinn **Sniðmát pöntunarloforða** með því að velja línu af listanum í glugganum **Listi yfir innkaupatillögusniðmát** .  
5. Innkaupatillögusniðmát er fært inn í reitinn **Pöntunarloforð Innkaupatillaga** með því að velja línu af listanum í glugganum **Listi yfir innkaupatillögusniðmát** .

### <a name="to-enter-inbound-warehouse-handling-time-in-the-inventory-setup-window"></a>Fært inn á birgðageymsluspjöld afgreiðslutíma á vörum í birgðagrunna.  
Ef afgreiðslutími á vörum inn í vöruhús á að vera tekinn með þegar reiknað er út hvenær pöntun er lofað í sölulínu er hægt að setja þetta upp sem sjálfgefið fyrir birgðirnar og birgðageymsluna sem um ræðir.    
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Uppsetning birgða** og velja svo viðeigandi tengil.  
2. Á flýtiflipanum **Almennt** í reitnum **Afgr.tími vara á innl. í vöruh.** er færður inn sá dagafjöldi sem á taka með í útreikningi á því hvenær pöntunum er lofað.  

> [!NOTE]  
>  Ef fyllt hefur verið út í reitinn **Afgr.t. vara á innl. í vöruh.** á **Birgðageymsluspjald** fyrir birgðageymsluna er það sem er í þeim reit notað sem sjálfgefinn afgreiðslutíma á vörum inn í vöruhús.  

### <a name="to-enter-inbound-warehouse-handling-time-on-location-cards"></a>Til að færa inn á birgðageymsluspjöld afgreiðslutíma á vörum inn í vöruhús:  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Birgðageymsla** og velja svo viðeigandi tengil.  
2.  Opna skal viðeigandi birgðageymsluspjald.  
3.  Á flýtiflipanum **Vöruhús** skal færa inn þann dagafjölda sem nota skal við útreikning á hvenær pöntunum er lofað inn í reitinn **Afgr.t. vara á innl. í vöruh.**.  

> [!NOTE]  
>  Ef reiturinn **Afgr.t. vara á innl. í vöruh.** er skilinn eftir auður verður gildið úr glugganum **Birgðagrunnur** notað við útreikninginn.

### <a name="to-enter-outbound-warehouse-handling-time-in-the-inventory-setup-window"></a>Fært inn á birgðageymsluspjöld afgreiðslutíma á vörum í birgðagrunna.  
Ef afgreiðslutími á vörum út úr vöruhúsi á að vera tekinn með þegar reiknað er út hvenær pöntun er lofað í sölulínu er hægt að setja þetta upp sem sjálfgefið fyrir birgðirnar.

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Uppsetning birgða** og velja svo viðeigandi tengil.  
2. Á flýtiflipanum **Almennt** í reitnum **Afgr.tími vara á útl. úr vöruh.** er færður inn sá dagafjöldi sem á taka með í útreikningi á því hvenær pöntunum er lofað.  

> [!NOTE]  
>  Ef fyllt hefur verið út í reitinn **Afgr.tími vara á útl. úr vöruh.** á Birgðageymsluspjald fyrir birgðageymsluna er það sem er í þeim reit notað sem sjálfgefinn afgreiðslutíma á vörum út úr vöruhúsi.  

### <a name="to-enter-outbound-warehouse-handling-time-on-location-cards"></a>Til að færa inn á birgðageymsluspjöld afgreiðslutíma á vörum út úr vöruhúsi:  
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Staðsetningar** og velja svo viðeigandi tengil.  
2.  Opna skal viðeigandi birgðageymsluspjald.  
3.  Á flýtiflipanum **Vöruhús** skal færa inn þann dagafjölda sem nota skal við útreikning á hvenær pöntunum er lofað inn í reitinn **Afgr.t. vara á útl. úr vöruh.**.  

> [!NOTE]  
>  Ef reiturinn **Afgr.tími vara á útl.úr vöruh.** er skilinn eftir auður verður gildið úr glugganum **Birgðagrunnur** notað við útreikninginn.

## <a name="to-make-an-item-critical"></a>Varan bundin:  
Áður en vara er sett inn í útreikning pöntun lofað, verður að merkja hana sem mikilvægt. Þessi uppsetning tryggir að ó-mikilvægar vörur trufli ekki útreikning pöntunarloforða.   
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Vörur** og velja svo viðeigandi tengil.  
2.  Viðeigandi birgðaspjald er opnað.  
3.  Á flýtiflipanum **Áætlun** skal velja svæðið **Bundið**.  

## <a name="to-calculate-an-order-promising-date"></a>Dagsetning pöntunarloforðs reiknuð:  
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Sölupöntun** og velja svo viðeigandi tengil.  
2.  Glugginn sölupöntun er opnaður og sölupöntunarlínurnar sem kerfið á að reikna valdar.  
3.  Veldu aðgerðina **Pöntun lofað** og veldu svo aðgerðina **Pöntun lofað línur**.  
4.  Veldu línu og síðan einn af eftirfarandi valmöguleikum:  

    - Velja skal  **Tiltæki** ef kerfið á að reikna út hvaða dag varan verður fyrst tiltæk að teknu tilliti til birgða, áætlaðrar móttöku og brúttóþarfa.  
    - Velja skal  **Óhætt að lofa** ef vitað er að varan er ekki til í birgðahaldi og ef kerfið á að reikna út hvenær varan verður fyrst tiltæki með því að gefa út tillögur um endurnýjun.  
5.  Velja hnappinn **Samþykkja** til að samþykkja fyrstu tiltæku sendingardagsetningu.  

## <a name="see-also"></a>Sjá einnig  
[Sala](sales-manage-sales.md)  
[Dagsetning útreiknings fyrir kaup.](purchasing-date-calculation-for-purchases.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

