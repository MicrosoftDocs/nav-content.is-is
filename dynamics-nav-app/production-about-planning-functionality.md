---
title: "Um áætlunaraðgerðir"
description: "Áætlunarkerfið tekur öll gögn um eftirspurn og framboð með í reikninginn, reiknar út niðurstöðurnar og kemur með tillögur að því að jafna framboðið og eftirspurnina."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 6d62c2e2fb3d5803df51a4e697a986f059def18d
ms.contentlocale: is-is
ms.lasthandoff: 10/23/2017

---
# <a name="about-planning-functionality"></a>Um áætlunaraðgerðir
Áætlunarkerfið tekur öll gögn um eftirspurn og framboð með í reikninginn, reiknar út niðurstöðurnar og kemur með tillögur að því að jafna framboðið og eftirspurnina.  

Frekari og nákvæmari upplýsingar, sjá [Hönnunarupplýsingar: Framboðsáætlun](design-details-supply-planning.md)  

> [!NOTE]  
> Fyrir öll þau svið sem minnst er á í þessu efnisatriði, lesa ábendingarnar til að skilja virkni þeirra. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="demand-and-supply"></a>Eftirspurn og Framboð  
Áætlanagerð hefur tvo hluta: eftirspurn og framboð. Halda þarf þeim í jafnvægi til að tryggja það að eftirspurninni sé annað á tímanlegan og hagkvæman hátt.  

- Eftirspurn er notað sem almennt heiti yfir hvers konar brúttóþörf eins og sölupöntun, þjónustupöntun, íhlutaþörf frá samsetningu eða framleiðslupantanir, millifærslur á útleið, standandi pöntun eða spá. Þar að auki býður kerfið upp á nokkrar aðrar tæknilegar tegundir eftirspurnar - eins og neikvæða framleiðslu- eða innkaupapöntun, neikvætt birgðamat og innkaupaskil.  
- Framboð er það orð sem er mest notað fyrir hvaða tegund af áfyllingu sem er, eins og birgðir, innkaupapöntun, samsetningarpöntun, framleiðslupöntun eða millifærslu á innleið. Á sama hátt getur verið til neikvæð sölu- eða þjónustupöntun, neikvæð íhlutaþörf eða innkaupaskil – sem er allt á einhvern hátt dæmi um framboð.  

Annað markmið áætlunarkerfisins er að tryggja það að birgðamagnið hækki ekki að óþörfu. Í tilfelli minnkandi eftirspurnar mun áætlunarkerfið leggja til að annað hvort verði þeim áfyllingarpöntunum sem eru fyrir hendi frestað, þær minnkaðar eða afpantaðar.  

## <a name="planning-calculation"></a>Áætlunarútreikningur  
Áætlunarkerfið er knúið áfram af viðbúinni og raunverulegri eftirspurn viðskiptavina auk endurpöntunarfæribreytum birgða. Ef áætlunarútreikningurinn er keyrður mun það leiða til þess að kerfið leggi til sérstakar aðgerðir (Aðgerðarboð) til að framkvæma varðandi mögulega áfyllingu frá lánardrottnum, millifærslur á milli vöruhúsa eða framleiðslu. Ef áfyllingarpantanir eru þegar til gætu tillögurnar verið þess efnis að auka við pantanirnar eða flýta þeim til að koma til móts við eftirspurnarbreytingarnar.  

Grundvöllur áætlunarrútínunnar er í útreikningunum frá hagnaði til taps. Nettóþarfir knýja áætlaða útgáfu pantana sem eru tímasettar eftir leiðarupplýsingum (framleiddar vörur) eða afhendingartíma birgðaspjaldsins (keyptar vörur). Magn áætlaðrar útgáfu pöntunar er byggt á áætlunarútreikningunum og verður fyrir áhrifum af þeim færibreytum sem eru stilltar fyrir hvert stakt birgðaspjald.  

## <a name="planning-with-manual-transfer-orders"></a>Áætlað með handvirkum millifærslupöntunum
Eins og sjá má í reitnum **Áfyllingarkerfið** á birgðahaldseiningarspjaldi er hægt að setja áætlunarkerfið upp til að stofna millifærslupantanir til að jafna framboð og eftirspurn á milli birgðageymslna.  

Til viðbótar slíkum sjálfvirkum millifærslupöntunum getur stundum þurft að framkvæma almennan flutning á birgðum í aðra birgðageymslu, óháð eftirspurn. Til þess er millifærslupöntun stofnuð handvirkt fyrir magnið sem á að flytja. Til að tryggja að áætlunarkerfið breyti ekki þessari handvirku millifærslupöntun þarf að stilla reitinn **Sveigjanleiki áætlunar** í millifærslulínunum á Enginn.  

Hins vegar, ef áætlunarkerfið á að leiðrétta magn og dagsetningar í millifærslupöntunum samkvæmt eftirspurn þarf að stilla reitinn **Sveigjanleiki áætlunar** á sjálfgildið, Ótakmarkað.

## <a name="planning-parameters"></a>Áætlunarfæribreytur  
Áætlunarfæribreyturnar stýra því hvenær, hversu mikið og hvernig er fyllt á eftir mismunandi stillingunum á birgðaspjaldinu (eða birgðaeiningu - SKU) og framleiðsluuppsetningunni.  

Eftirtaldar áætlunarfæribreytur eru til á vöru eða birgðahaldseiningarspjaldi:  

-   Hömlutímabil  
-   Hömlu magn  
-   Endurpöntunarstefna  
-   Endurpöntunarmark
-   Hámarksbirgðir  
-   Yfirflæðisstig  
-   Tímarammi  
-   Lotusöfnunartímabil  
-   Enduráætlunartímabil  
-   Pöntunarmagn  
-   Öryggisforskot  
-   Magn í öryggisbirgðum  
-   Samsetningarstefna  
-   Framleiðslustefna  

Eftirfarandi pöntunarbreytur eru til á vöru eða birgðahaldseiningarspjaldi:  

-   Lágmarksmagn pöntunar  
-   Hámarksmagn pöntunar  
-   Fjöldapanta  

Á meðal uppsetningarreita altækar áætlunar í glugganum **Framleiðslugrunnur** eru:  

-   Sveigjanlegur lágstigskóti  
-   Gildandi framleiðsluspá  
-   Nota spá með staðsetningu  
-   Sjálfgefið öryggisforskot  
-   Autt yfirflæðisstig  
-   Sameinaður MPS/MRP útreikn.   
-   Íhlutir á staðnum  
-   Sjálfgefið hömlunartímabil  
-   Sjálfgefið hömlu magn  

Nánari upplýsingar eru í [Upplýsingar um hönnun: Áætlunarfæribreytur](design-details-planning-parameters.md)  

## <a name="other-important-planning-fields"></a>Önnur mikilvæg áætlunarsvið
### <a name="planning-flexibility"></a>Sveigjanleiki áætlunar
Á flestum birgðapöntunum, eins og t.d. framleiðslupöntunum, getur valið **Ótakmarkaður** eða **Enginn** í **Sveigjanleiki áætlunar** reitnum.

Tilgreinir hvort birgðir sem framleiðslupöntunarlína sýnir eru teknar með í áætlunarkerfinu þegar aðgerðarboð eru reiknuð.
Ef reiturinn inniheldur **Ótakmarkað** tekur áætlunarkerfið línuna með í reikninginn þegar aðgerðarboð eru reiknuð. Ef reiturinn inniheldur **Enginn** er línan föst og óbreytanleg og áætlunarkerfið tekur hana ekki með í reikninginn þegar aðgerðarboð eru reiknuð.

### <a name="warning"></a>Viðvörun
Upplýsingareiturinn **Viðvörun** í **Áætlunarvinnublað** glugganum lætur þig vita um allar áætlunarlínur sem gerðar eru vegna óvenjulegra með texta, sem notandinn getur smellt á til að lesa viðbótarupplýsingar. Eftirfarandi tegundir viðvarana eru til:

- Neyð
- Frávik
- Athugið
- Neyð

Neyðarviðvörun birtist í tveimur aðstæðum:

- Birgðir eru neikvæðar á upphafsdagsetningu áætlunar.
- Framboðs- eða eftirspurnaratvik eru til aftur í tíma.

Ef birgðir eru neikvæðar á upphafsdegi áætlunarinnar stingur kerfið upp á neyðarpöntun með neikvæða magninu fyrir upphafsdagsetninguna. Upphafsdagsetningin og magn neyðarpöntunarinnar eru tiltekin í viðvörunartextanum.

Allar skjalalínur með skiladagsetningar á undan upphafsdagsetningu áætlunarinnar eru settar í eina neyðarpöntun til að varan berist á áætlaðri upphafsdagsetningu.

### <a name="exception"></a>Frávik
Viðvörun um frávik birtist ef áætlaðar birgðir eru undir öryggismarki birgða.

Áætlunarkerfið stingur upp á framboðspöntun til að uppfylla eftirspurnina á lokadagsetningunni. Viðvörunartextinn segir til um magn í öryggisbirgðum fyrir vöruna og dagsetninguna sem það magn varð of lítið.

Þegar farið er undir öryggismagn í birgðum er það talið frávik þar sem það ætti ekki að gerast ef endurpöntunarmark hefur verið stillt rétt.

> [!NOTE]
> Framboði fyrir áætlunarlínur með viðvörunum um frávik er yfirleitt ekki breytt samkvæmt áætlunarfæribreytum. Þess í stað stingur áætlunarkerfið einungis upp á framboði til að anna nákvæmu eftirspurnarmagni. Hins vegar er hægt að stilla áætlunarkeyrsluna þannig að hún virði tilteknar áætlunarfæribreytur fyrir áætlunarlínur með viðvörunum. Nánari upplýsingar er að finna í „Virða áætlunarfæribreytur fyrir viðvaranir um frávik“ í Reikna áætlun - áætlun. Wksh.

### <a name="attention"></a>Athugið
Viðvörunin Til athugunar birtist í tveimur aðstæðum:

- Upphafsdagsetning áætlunarinnar er á undan kerfisdagsetningunni.
- Áætlunarlínan stingur upp á því að útgefinni innkaupa- eða framleiðslupöntun verði breytt.

> [!NOTE]
> Í áætlunarlínum með viðvaranir er reiturinn **Samþykkja aðgerðarboð** ekki valinn þar sem sá sem gerir áætlunina á að kanna þessar línur nánar áður en lokið er við áætlunina. 

## <a name="see-also"></a>Sjá einnig  
[Hönnunarupplýsingar: framboðsáætlun](design-details-supply-planning.md)  
[Áætlun](production-planning.md)   
[Uppsetning framleiðslu](production-configure-production-processes.md)  
[Framleiðsla](production-manage-manufacturing.md)    
[Birgðir](inventory-manage-inventory.md)  
[Innkaup](purchasing-manage-purchasing.md)  
[Uppsetning bestu venjur: Framboðsáætlun](setup-best-practices-supply-planning.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

