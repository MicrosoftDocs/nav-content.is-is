---
title: "Afmörkun skjalanna"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 8eab393a0a77f9f1595ca1247c7549e68b491cb2
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="entering-criteria-in-filters"></a>Afmörkun skjalanna
Til að leita að gögnum, svo sem heiti viðskiptamanna, aðsetrum eða vöruhópum er hægt að setja inn skilyrði. Í leitarskilyrðum er hægt að nota alla sömu tölustafi og bókstafi sem venjulega eru notaðir í reitnum. Ennfremur er hægt að nota sértákn til að afmarka niðurstöðurnar frekar.

## <a name="searching-using-the-quick-filter"></a>Leita með því að nota flýtiafmörkun
Hægt er að bæta afmörkunum við allar síður með því að nota flýtiafmörkun. Flýtiafmörkun er virkjuð með því að velja stækkunarglerstáknið í efra hægra horni síðu. Þessi síugerð er notuð fyrir flýtiinnfærslu viðmiða.

**Mikilvægt**: Flýtiafmörkun veitir auðveldan aðgang að afmörkunargögnum með því að færa inn texta án sniðtákna en veitir einnig margs konar valkosti fyrir leitarskilyrði. Það fer eftir því hvort þú slærð texta eða texta með táknum, flýtiafmörkun hagar sér öðruvísi.  
- Ef ósniðinn texti er sleginn inn í leitarskilyrðum eru leitarskilyrðin túlkuð sem leit óháð há- og lágstöfum sem inniheldur ákveðinn texta.  
- Ef texti með táknum er sleginn inn í leitarskilyrðum eru leitarskilyrðin túlkuð nákvæmlega eins og þau voru slegin inn og leitin er háð há- og lágstöfum.

### <a name="quick-filter-criteria"></a>Skilyrði flýtiafmörkunar
<!-- html syntax because symbols conflict with MarkDown syntax -->
<TABLE>
  <TR>
    <TH>Leitarskilyrði</TH>
    <TH>Túlkað sem...</TH>
    <TH>Vöruskil...</TH>
  </TR>
  <TR>
    <TD>>man</TD>
    <TD>@*karlmaður*</TD>
    <TD>Allar færslur þurfa að innihalda textann man og rétta há- og lágstafi.</TD>
  </TR>
  <TR>
    <TD>>se</TD>
    <TD>@*se*</TD>
    <TD>Allar færslur þurfa að innihalda textann se og rétta há- og lágstafi.</TD>
  </TR>
  <TR>
    <TD>>Karl*</TD>
    <TD>Hefst á Man og greinarmunur á litlum og stórum stöfum.</TD>
    <TD>Allar færslur sem byrja á textanum Man</TD>
  </TR>
  <TR>
    <TD>‚man‘</TD>
    <TD>Nákvæmur texti og greinarmunur á litlum og stórum stöfum.</TD>
    <TD>Allar færslur sem samsvara man nákvæmlega.</TD>
  </TR>
  <TR>
    <TD>@*man</TD>
    <TD>Lýkur á og enginn greinarmunur á litlum og stórum stöfum.</TD>
    <TD>Allar færslur sem enda á man.</TD>
  </TR>
  <TR>
    <TD>@man*</TD>
    <TD>Hefst á og enginn greinarmunur á litlum og stórum stöfum.</TD>
    <TD>Allar færslur sem byrja á man.</TD>
  </TR>
</TABLE>

**Athugasemd**: Ekki er hægt að nota algildisstafi þegar afmarkanir eru á tölusettum reitum, til dæmis reiturinn **Staða** á sölupöntunum. Til að færa inn afmörkun fyrir þessa gerð reits, er hægt að færa inn númeragildið sem afmörkunarbreytu. Til dæmis í reitnum **Sala** á sölupöntun sem hafa gildin **Opin**, **Útgefið**, **Samþykkt í bið** og **Fyrirframgreiðsla í bið** skal nota gildin **0**, **1**, **2** og **3** til þess að afmarka þessa valmöguleika.  

## <a name="see-also"></a>Sjá einnig
[Unnið með Dynamics NAV](ui-work-product.md)

