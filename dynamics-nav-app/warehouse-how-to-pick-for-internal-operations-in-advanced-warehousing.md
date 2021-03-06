---
title: "Hvernig á að tína fyrir innri starfsemi með ítarlegum vöruhúsaskilgreiningum"
description: "Í ítarlegri vöruhúsagrunnstillingu þar sem birgðageymslan notar tínslu auk afhendingar eru íhlutir tíndir fyrir framleiðslu- og samsetningarverkþætti með glugganum **Vöruhúsatínsla**."
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
ms.openlocfilehash: 08b79f573a9fc013068f7e1f5dd593a596a579a3
ms.contentlocale: is-is
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-pick-for-assembly-or-production-in-advanced-warehouse-configurations"></a>Hvernig á að tína fyrir samsetningar- eða framleiðslu með ítarlegum vöruhúsaaðgerðum | Microsoft Docs
Í ítarlegri vöruhúsastillingu þar sem birgðageymslan notar tínslu auk afhendingar eru íhlutir tíndir fyrir framleiðslu- og samsetningarverkþætti með glugganum **Vöruhús - Tína**.  

Einnig er hægt að nota gluggann **Vinnublað hreyfingar** til að færa vörur milli hólfa á tilfallandi hátt, þ. e. a. án tilvísunar í upprunaskjal. Nánari upplýsingar má nálgast á [Hvernig á að færa vörur með ítarlegum vöruhúsaaðgerðum](warehouse-how-to-move-items-in-advanced-warehousing.md).  

Upplýsingar um tínslu atriða fyrir innri starfsemi í einföldum vöruhúsum sem hafa aðeins verið sett upp fyrir tínslu eru í [Hvernig á að: færa íhluti á aðgerðasvæði með einfaldri grunngerð vöruhúsa](warehouse-how-to-move-components-to-an-operation-area-in-basic-warehousing.md).  

Ekki er hægt að stofna vöruhúsatínsluskjal frá grunni þar sem í tínsluaðgerð er alltaf hluti af verkflæði, annað hvort sem dráttur eða ýting.  

Einnig er hægt að stofna vöruhúsatínsluskjöl eins og ýtingu í glugganum **Stofna vöruhússtínslu** á upprunaskjalinu, eins og útgefna samsetningarpöntun eða vöruhúsaafhendingu. Frekari upplýsingar, sjá [Hvernig á að: tína Vörur með vöruhúsatínslu](warehouse-how-to-pick-items-for-warehouse-shipment.md)  

Einnig er hægt að stofna vöruhúsatínsluskjal eins og drátt með því að nota gluggann **Vinnublað tínslu** til að finna tínslubeiðnir, bæði til afhendingar og innri aðgerða, og síðan stofna nauðsynleg vöruhúsatínsluskjöl.  

Eftirfarandi ferli skýrir dæmi þar sem valdir eru íhlutir fyrir afhenta framleiðslupöntun í gegnum gluggann **Vinnublað tínslu**. Ferlið á einnig við fyrir samsetningarpöntun.  

Til að stofna tínslubeiðnir, bæði fyrir tog- og ýtidæmi, þurfa viðkomandi upprunaskjöl að vera útgefin. Upprunaskjöl eru gefin út fyrir innri aðgerðir á eftirfarandi hátt.  

|Upprunaskjal|Losunaraðferð|  
|---------------------|--------------------|  
|Framleiðslupöntun|Breyta tegund pöntunar í útgefna framleiðslupöntun.|  
|Samsetningarpöntun|Breyta stöðu í Útgefið.|  

## <a name="to-pick-components-using-the-pick-worksheet"></a>Íhlutir tíndir úr tínsluvinnublöðunum:  
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Vinnublað tínslu** og velja svo viðeigandi tengil.  
2.  Velja skal **Sækja vöruhúsaskjöl** og síðan velja íhlutalínurnar í útgefnu framleiðslupöntuninni.  
3.  Línurnar eru skoðaðar, þeim raðað til að tryggja skilvirkni tínsluferðarinnar og þær sameinaðar öðrum vinnublaðslínum ef þarf, til að nýta tíma starfsmanna sem best.  
4.  Veldu aðgerðina **Stofna tínslu**.  
5.  Skilgreina hvernig eigi að stofna vöruhúsatínsluskjöl og hvernig á að raða tínslulínunum með því að fylla út reiti í gluggnum **Stofna tínslu**.  
6.  Velja hnappinn **Í lagi**. Vöruhúsatínsluskjöl eru búin til með tínslulínum fyrir hvern íhlut sem er krafist í innri aðgerð.  

Ef svæði innri starfsemi, s.s. framleiðsluvinnusalur, er sett upp með sjálfgefnu hólfi fyrir staðsetningu íhluta sem notaðir eru verður kóti þess hólfs settur inn í Setja-línur í tínsluskjali vöruhússins til að leiðbeina starfsmönnum í vöruhúsi um hvert setja eigi vörurnar. Nánari upplýsingar má nálgast á **Hólfkóði til framleiðslu** eða **Í samsetningu hólfakóð** reitina.

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

