---
title: "Stjórnun skýrsluútlita"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 57cd575c1f72841dae162b077d1f676720ee24e7
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---
    
# <a name="manage-report-layouts"></a>Stjórnun skýrsluútlita
Útlit skýrslu stjórnar efni og sniði skýrslunnar, þ.m.t. hvaða gagnareitir gagnasafn skýrslu birtast í henni, stöðu þeirra, textastíl, myndir og meira. Í biðlurum Dynamics NAV er hægt að breyta því hvaða útlit er notað í skýrslu, búa til nýtt útlit eða breyta fyrirliggjandi útliti. 

Skýrsluútlit setur einkum eftirfarandi upp:

- Merkið og gagnareitir sem taka á með úr gagnamengi tiltekinnar Dynamics NAV skýrslu.
- Textasniðið, eins og leturgerð, stærð og litur.
- Fyrirtækjamerki og staðsetning þess.
- Almennar síðustillingar, eins og spássíur og bakgrunnsmyndir. 

Dynamics NAV getur verið uppsett með mismunandi útliti sem hægt er að skipta á milli. Hægt er að nota eitt af innbyggðum skýrsluútlitum eða stofna sérsniðið skýrsluútlit og úthluta þeim á skýrslur eftir þörfum.

Það eru tvær gerðir skýrsluútlita sem hægt er að nota á skýrslur, Word og RDLC.

## <a name="word-report-layout-overview"></a>Yfirlit Word skýrsluútlits
Word-skýrsluútlit byggir á Word-skjali (.docx-skráargerð). Word-skýrsluútlit gerir þér kleift að hanna skýrsluútlit með Microsoft Word 2013 eða síðar. Word skýrsluútlit ákvarðar innihald skýrslunnar og stjórnar því hvernig þeir efnisþættir raðast og hvernig þeir líta út. Word skýrsluútlitsskjal notar vanalega töflur til að raða efni, þar sem hólf geta innihaldið gögn, reiti, texta eða myndir.

## <a name="rdlc-layout-overview"></a>Yfirlit RDLC-útlits
RDLC-útlit eru byggð á skýrsluskilgreiningarútliti biðlara (.rdlc- eða .rdl-skráargerðir). Þessi útlit eru búin til og þeim breytt með SQL Server Report Builder. Hönnun RDLC-útlits er svipað og Word útlits, þar sem útlitið tilgreinir almennt snið skýrslunnar og ákvarðar reitina sem á að taka með úr gagnamenginu. Hönnun RDLC-útlits er ítarlegra en Word-útlits.

## <a name="built-in-and-custom-report-layouts"></a>Innbyggt og sérsniðið skýrsluútlit
 Dynamics NAV inniheldur nokkur innbyggð útlit. Innbyggt útlit er skilgreint útlit hönnuð fyrir tilteknar skýrslur. Skýrslur Dynamics NAV eru með innbyggt útlit sem RDLC-skýrsluútlit, Word-skýrsluútlit eða, í sumum tilfellum, bæði. Ekki er hægt að breyta innbyggðu útliti úr Dynamics NAV, en þau eru notuð sem upphafspunktur til að búa til eigin sérsniðin skýrsluútlit. 

Sérstillt útlit er skýrsluútlit sem þú hannar til að breyta útliti skýrslu. Þú býrð vanalega til sérsniðið útlit byggt á innbyggðu útliti, en þú getur búið þau til frá grunni eða úr afriti fyrirliggjandi sérsniðins útlits. Sérstillt útlit gera þér kleift að hafa mörg útlit fyrir sömu skýrsluna, sem hægt er að skipta á milli eftir þörfum. Til dæmis er hægt að hafa mismunandi útlit fyrir hvert Dynamics NAV-fyrirtæki, eða hægt er að hafa mismunandi útlit fyrir sama fyrirtækið við tiltekin tilefni eða aðstæður, eins og sérstaka herferð eða hátíðir.

## <a name="deciding-whether-to-use-a-word-or-rdlc-report-layout"></a>Ákvörðun um hvort Word eða RDLC-skýrsluútlit er notað 
Skýrsluútlit getur verið byggt á Word-skjali eða RDLC-skrá. Þegar ákvörðun er tekin um hvort nota eigi Word-skýrsluútlit eða RDLC-skýrsluútlit fer það eftir því hvernig skýrslan sem mynduð er á að líta út og þekkingu notanda á Word og SQL Server Report Builder. 

Almenna hönnunin fyrir Word og RDLC-útlit eru mjög svipaðar. Hins vegar er hver gerð með tiltekin hönnunareinkenni sem hafa áhrif á það hvernig skýrslan sem mynduð er birtist í Dynamics NAV. Þetta þýðir að sama skýrsla gæti litið mismunandi út eftir því hvort Word-skýrsluútlitið eða RDLC-skýrsluútlitið er notað.

Ferlið til að setja upp Word-skýrsluútlit og RDLC-skýrsluútlit á skýrslum er það sama. Helsti munurinn liggur í því hvernig útlitinu er breytt. Yfirleitt er auðveldara að búa til og breyta Word-skýrsluútliti en RDLC-útliti þar sem hægt er að nota Word. RDLC-skýrsluútlitum er breytt með SQL Server Report Builder sem ætlað er reyndari notendum.

Fyrir upplýsingar um hvernig eigi að breyta útliti, sjá [Hvernig á að breyta því hvaða útlit er notað á skýrslum](ui-how-change-layout-currently-used-report.md)

## <a name="see-also"></a>Sjá einnig
[Unnið með Dynamics NAV](ui-work-product.md)  
[Hvernig á að búa til sérsniðið útlit](ui-how-create-custom-report-layout.md)  
[Hvernig á að: Senda skjöl í tölvupósti](ui-how-send-documents-email.md)

