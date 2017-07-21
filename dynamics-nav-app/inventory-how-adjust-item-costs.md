---
title: "Hvernig á að: Leiðrétta birgðakostnað"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 59db38c159dd2810656edc668ee431c6414b9d90
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-adjust-item-costs"></a>Hvernig á að: Leiðrétta birgðakostnað   
Kostnaðarverð vöru (birgðavirði) sem er keypt og seld síðar getur breyst á líftímanum, til dæmis vegna þess að kostnað við frakt er bætt við innkaupakostnaðinn þegar varan hefur verið seld. Til þess að vita alltaf rétt birgðavirði verður því að leiðrétta kostnaðarverð vöru reglubundið.
Þetta tryggir að sölu- og hagnaðartölur séu réttar og afkastavísar (KPI) fjárhags séu réttir.

**Til athugunar**: Vörukostnaður er aðeins leiðréttur með FIFO-aðferðinni. Þetta þýðir að kostnaðarverð vöru er raunvirði sérhverrar innhreyfingar vörunnar og við verðmat birgða er gert ráð fyrir því að fyrstu vörurnar í birgðunum séu seldar fyrst.

Kostnaðarleiðréttingin vinnur aðeins virðisfærslur sem hafa ekki verið lagfærðar. Ef keyrslan þarf að flytja kostnaðarbreytingar á innleið í tengdar færslur á útleið gerir hún það með því að stofna nýjar virðisleiðréttingarfærslur sem byggja á upplýsingum um upphaflegar virðisfærslur en innihalda leiðréttingarupphæðina. Kostnaðarleiðréttingin notar dagsetningu bókunar upphaflegu virðisfærslunnar í leiðréttingarfærslunni nema hún sé í lokuðu birgðatímabili. Í því tilfelli notar kerfið upphafsdagsetningu næsta birgðatímabils. Ef birgðatímabil eru ekki notuð munu gögnin í reitnum **Bókun leyfð frá** í glugganum **Fjárhagsgrunnur** skilgreina hvenær leiðréttingarfærslan er bókuð.

**Athugasemd**: Þegar kostnaður vöru hefur verið leiðréttur þarf að bóka birgðakostnað á fjárhag, annaðhvort sjálfvirkt eða handvirkt. Nánari upplýsingar má sjá í [Hvernig á að: Bóka Birgðakostnað í fjárhag](inventory-how-post-inventory-cost-gl.md).

Hægt er að leiðrétta kostnað vöru á tvo vegu:
 - Setja kerfið þannig upp að leiðrétt sé sjálfvirkt vegna allra kostnaðarbreytinga í hvert sinn sem birgðafærslur eru bókaðar.
 - Handvirkt með því að keyra runuvinnsluna **Leiðr. Kostnað - Birgðafærslur** fyrir eina eða fleiri vörur þegar vitað er að kostnaður vegna þeirra hefur breyst.  

## <a name="to-adjust-item-costs-automatically"></a>Til að uppfæra kostnað vörusjálfvirkt
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn**Birgðagrunnur**, og velja síðan viðeigandi tengil.
2. Í glugganum **Birgðagrunnur** í svæðinu **Sjálfvirk Kostnaðarleiðrétting** er valið eitt af eftirfarandi gildum.

|Valkostur |Virkni |
|-------|---------|
|Aldrei|Kostnaður er ekki leiðréttur við bókun|
|Dagur|Kostnaður er leiðréttur ef bókun á sér stað innan eins dags frá vinnudagsetningunni.|
|Vika|Kostnaður er leiðréttur ef bókun á sér stað innan einnar viku frá vinnudagsetningunni.|
|Mánuður|Kostnaður er leiðréttur ef bókun á sér stað innan eins mánaðar frá vinnudagsetningunni.|
|Fjórðungur|Kostnaður er leiðréttur ef bókun á sér stað innan eins ársfjórðungs frá vinnudagsetningunni.|
|Ár|Kostnaður er leiðréttur ef bókun á sér stað innan eins árs frá vinnudagsetningunni.|
|Alltaf|Kostnaður er alltaf leiðréttur við bókun óháð bókunardagsetningunni.|

## <a name="to-adjust-item-costs-manually"></a>Til að uppfæra birgðakostnað verks handvirkt
1. Í efra hægri horni skal velja táknið **Leita að síðu eða skýrslu** slá inn **Leiðr. Kostnað - Birgðafærslur**, og velja síðan viðeigandi tengil.
2. Í glugganum **Leiðr. Kostnað - Birgðafærslur** skal tilgreina hvaða vörur á að leiðrétta kostnað fyrir og hvort leiðréttur kostnaður verður bókaður í fjárhag á sama tíma.

## <a name="see-also"></a>Sjá einnig
[Stjórna birgðum](inventory-manage-inventory.md)  
[Hvernig á að bóka birgðakostnað í fjárhag](inventory-how-post-inventory-cost-gl.md)  
[Stjórna sölu](sales-manage-sales.md)  
[Stjórnun innkaupa](purchasing-manage-purchasing.md)

