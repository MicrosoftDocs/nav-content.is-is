---
title: "Hvernig á að: Stofna verk"
author: SorenGP
ms.custom: na
ms.date: 11/01/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: df34c435d07e9526cb4d93e2bfc30162258ba957
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-create-jobs"></a>Hvernig á að: Stofna verk
Þegar nýtt verk er stofnað verður að stofna verkspjald með samþættum verkhlutum og áætlunarlínum, sem skipt er upp í tvö lög.  

Fyrsta lagið samanstendur af verkhlutum. Það verður að stofna að minnsta kosti einn verkhluta fyrir hvert verk vegna þess að allar bókanir vísa til verkhluta. Ef a.m.k. einn verkhluti er í verkinu er hægt að setja upp áætlunarlínur og bóka notkun fyrir verkið.

Hitt lagið samanstendur af áætlunarlínum sem tilgreina ítarlega notkun forða, vara og ýmis fjárhagsleg útgjöld.

Lagskiptingin gerir kleift að skipta verkinu í smærri verk og notast við ítarlegri upplýsingar við fjárhagsáætlun, tilboð og skráningu. Auk þess veitir það innsýn í framvindu verksins. Til dæmis er hægt að rekja hvort notandinn nái tilskildum áföngum, eða hvort hann sé á réttri leið til að ná væntingum áætlunar.

**Til athugunar**: Aðgerðin **Nýtt Verk** í hlutverkinu **Verkefnastjóri** setur af stað uppsetningarleiðsögn sem leiðir notandann í gegnum skrefin við að stofna verk með samþættum verkhlutum og áætlunarlínum. Eftirfarandi ferli sýnir hvernig á að framkvæma skrefin handvirkt.

## <a name="to-create-a-job-card"></a>Til að stofna verkspjald
Stofnað er verkspjald og svo eru stofnaðar verkhlutalínur og áætlunarlínur fyrir það.

1. Uppi í hægra horninu skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Verk** og velja svo viðeigandi tengil.  
2. Veljið aðgerðina **Nýtt** og fyllið svo út reitina eins og þörf krefur. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.
3. Til að tilgreina verkið með upplýsingum um önnur verk skal velja aðgerðina **Afrita verk** og fylla svo út reitina eins og þörf krefur og velja hnappinn **Í lagi**.

**ATHUGIÐ**: Ef vinnuskýrslur eru notaðar í verkinu þarf einnig að tilnefna ábyrgan aðila. Einstaklingurinn getur samþykkt vinnuskýrslur fyrir starfsmannaverkefni sem tengjast verkinu. Frekari upplýsingar eru í [Hvernig á að: Setja upp vinnuskýrslur](projects-how-setup-time-sheets.md).

## <a name="to-create-tasks-for-a-job"></a>Til að búa til verkhluta fyrir verk  
Lykilatriði í stofnun verka er að tilgreina þá verkhluta sem verkið felur í sér. Þetta er gert með því að bæta við nýjum línum á flýtiflipanum **Verkhlutar** í glugganum **Verkspjald**, eitt verk í hverri línu. Hvert verk verður að hafa að minnsta kosti einn verkhluta.

1. Uppi í hægra horninu skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Verk** og velja svo viðeigandi tengil.
2. Opnið verkspjaldið fyrir viðeigandi verk.
3. Á flýtiflipanum **Verkhlutar** skal fylla út reitina eins og þörf krefur í nýrri línu.
4. Til að draga inn verkhluta og búa til stigveldi skal velja aðgerðina **Verkhlutar** og svo aðgerðina **Draga inn verkhluta**.
5. Endurtakið skref 3 og 4 fyrir alla verkhluta sem þarf fyrir verkið.
6. Til að tilgreina verkhluta með upplýsingum um aðra verkhluta skal velja aðgerðina **Afrita verkhluta frá** og fylla svo út reitina eins og þörf krefur og velja hnappinn **Í lagi**.

## <a name="to-create-planning-lines-for-a-job"></a>Til að stofna verkáætlunarlínu fyrir verk  
Hægt er að fínstilla nýja verkhluta á áætlunarlínum verksins. Áætlunarlínu er hægt að nota til að halda utan um hvers kyns upplýsingar sem rekja þarf í verki. Nota má áætlunarlínur til að bæta við upplýsingum líkt og hvaða forði þurfi að vera til staðar og til að gera grein fyrir hvaða vörur séu nauðsynlegar til að inna verkið af hendi. Ef verkhluti felst til dæmis í því að fá samþykki viðskiptamanns fyrir verki er hægt að tengja verkið við áætlunarlínur fyrir atriði eins og fundi með viðskiptamanninum og úthlutun forða.  

Áætlunarlína getur verið ein af eftirfarandi tegundum.  

|Gerð|Lýsing|
|----|-----------|
|**Fjárhagsáætlun**|Sýnir áætlaða notkun og kostnað við verkið, yfirleitt í verkefni af tíma- og efnisgerð. Áætlunarlínur af þessari gerð er ekki hægt að reikningsfæra.|
|**Reikningshæft**|Sýnir áætlaða reikningsfærslu til viðskiptamanns, yfirleitt í verkefni með fast verð.|
|**Bæði fjárhagsáætlun og reikningshæft**|Sýnir áætlaða notkun sem jafngildir því sem á að reikningsfæra.|  

**Athugasemd** Þegar upplýsingar um verkáætlunarlínur eru færðar inn eru kostnaðarupplýsingar fylltar út sjálfkrafa. Sem dæmi má taka að kostnaður, verð og afsláttur forða og vara byggist í upphafi á upplýsingum sem eru tilgreindar á forðaspjaldi og birgðaspjaldi.

1. Uppi í hægra horninu skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Verk** og velja svo viðeigandi tengil.
2. Opnið viðeigandi verkspjald.
3. Valinn er verkhluti þar sem reiturinn **Verkhlutagerð** inniheldur **Bókuð** og svo er aðgerðin **Verkhlutalínur** valin.  
4. Í glugganum **Verkáætlunarlínur** skal fylla út reitina eins og þörf krefur í nýrri línu.
5. Endurtakið skref 3 og 4 fyrir allar verkhlutalínur sem þarf fyrir verkhlutann.

## <a name="see-also"></a>Sjá einnig
[Unnið með verkefni](projects-manage-projects.md)  
[Fjármál](finance-setup.md)  
[Stjórnun innkaupa](purchasing-manage-purchasing.md)         
[Stjórna sölu](sales-manage-sales.md)      
[Unnið með Dynamics NAV](ui-work-product.md)  

