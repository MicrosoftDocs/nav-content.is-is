---
title: "Hvernig á að: Flytja út greiðslur í bankaskrá"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 09bdf56b3d5e76b12d868091e89232ce9c08e215
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-export-payments-to-a-bank-file"></a>Hvernig á að: Flytja út greiðslur í bankaskrá
Þegar hægt er að gera greiðslur á lánardrottna með glugganum **Greiðslubók** er hægt að flytja út skrá með greiðsluupplýsingum á færslubókarlínur. Þá er hægt að hlaða upp skránni í netbanka til að meðhöndla tengdan peningaflutning.

Í almennri útgáfu af Dynamics NAV, er altæk þjónustuveita til að umbreyta bankagögnum í annað skráarsnið sem bankinn krefst uppsett og tengt.

**Athugasemd**: Áður en þú getur flutt frá greiðslubók, verður þú að leyfa útflutning á tengdum bókarkeyrslum. Að auki verða bankareikningur þinn og bankareikningur lánardrottins að vera settir upp fyrir rafræna greiðslu. Nánari upplýsingar er að finna í [Hvernig á að: Setja upp umreikningsþjónustu fyrir bankagögn](bank-how-setup-bank-data-conversion-service.md).

Glugginn **Skráningar kreditmillifærslna** er notaður til að skoða greiðsluskrár sem hafa verið fluttar út úr greiðslubókinni. Í þessum glugga er einnig hægt að endurflytja út greiðsluskrár ef um er að ræða tæknilegar villur eða breytingar á skrá.

## <a name="to-export-payments-to-a-bank-file"></a>Til að flytja út greiðslur í bankaskrá
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Greiðslubækur**, og velja síðan viðeigandi tengil.
2. Fyllið út greiðslubókarlínur, t.d. með aðgerðinni **Greiðslutillögur til lánardrottna**. Nánari upplýsingar má sjá í [Hvernig á að: Leggja til greiðslutillögur til lánardrottna](payables-how-suggest-vendor-payments.md).  
3. Þegar öllum greiðslubókarlínunum er lokið skal velja **Flytja út greiðslu í skrá**.

    Öll villuboð birtast í **Villur í greiðsluskrá** upplýsingareitnum þar sem þú getur einnig valið villuboð til að sjá ítarlegar upplýsingar. Leysa þarf úr öllum villum áður en hægt er að flytja út greiðsluskrána.

    **Ábending**: Þegar þú notar umskráningarþjónustu fyrir bankagögn er algeng villa sú að bankareikningsnúmerið sé ekki með lengdina sem bankinn fer fram á. Til að koma í veg fyrir eða leysa villuna, þarf að fjarlægja gildið í svæðinu **IBAN** í glugganum **Bankareikningsspjald** og á svæðinu **Reikningur nr.** er fært inn númer bankareiknings með sniði sem bankinn fer fram á.
4. Í glugganum **Vista sem** skal tilgreina staðsetninguna þangað sem skráin er flutt út og velja svo **Vista**.

Bankagreiðsluskráin er flutt út á staðsetningu sem þú tilgreinir, og hægt er að meðhöndla hana til hlaða henni upp á rafrænn bankareikning og framkvæma greiðslurnar.

Þegar þú færð staðfestingu á að greiðslurnar hafi verið framkvæmdar af bankanum getur þú bókað útfluttu greiðslubókarlínurnar.

## <a name="to-plan-when-to-post-exported-payments"></a>Til að áætla hvenær á að bóka útfluttar greiðslur
Ef þú vilt ekki bóka greiðslubókarlínu fyrir útflutta greiðslu, t.d. vegna þess að þú ert að bíða eftir staðfestingu á því að færslan hafi verið meðhöndluð af bankanum geturðu einfaldlega eytt línunni. Þegar þú síðar stofnar greiðslubókarlínu til að greiða eftirstandandi upphæð á reikningnum sýnir reiturinn **Heildarupphæð flutt út** hversu mikið af greiðsluupphæðinni hefur þegar verið flutt út. Þú getur einnig fundið ítarlegar upplýsingar um heildarupphæðir sem hafa verið fluttar út með því að velja hnappinn **Skráningarfærslur kreditmillifærslna** til að sjá upplýsingar um útfluttar greiðsluskrár.

Ef fylgt er ferli þar sem ekki á að bóka greiðslur fyrr en staðfesting hefur fengist á því að þær hafa verið unnar í bankanum er hægt að stjórna því á tvo vegu.

* Í greiðslubók með tillögum að greiðslulínum geturðu flokkað með annað hvort dálkinum **Flutt út í greiðsluskrá** eða **Heildarupphæð flutt út** og svo eytt greiðslutillögum fyrir opna reikninga þar sem greiðslur hafa þegar átt sér stað og þú vilt ekki greiða.
* Í glugganum **Greiðslutillögur til lánardrottna** þar sem þú tilgreinir hvaða greiðslur eigi að setja í greiðslubókina, geturðu valið gátreitinn **Sleppa útfluttum greiðslum** ef þú vilt ekki setja inn færslubókarlínur fyrir greiðslur sem hafa þegar verið fluttar út.

Til að sjá upplýsingar um útfluttar greiðslur, veljið aðgerðina **Útflutningsferill greiðslna**.

## <a name="to-re-export-payments-to-a-bank-file"></a>Að endurútflytja greiðslur í bankaskrá
Hægt er að endurútflytja greiðsluskrár úr glugganum **Skráningar kreditmillifærslna**. Áður en greiðslubókarlínum er eytt eða þær bókaðar er einnig hægt að endurútflytja greiðsluskrána úr glugganum **Greiðslubók** með því að flytja hana einfaldlega út aftur.

Ef þú hefur eytt eða bókað greiðslubókarlínurnar eftir að þú hefur flutt þær út getur þú endurútflutt sömu greiðsluskrá úr glugganum **Skráningar kreditmillifærslna**. Veldu línuna fyrir runu kreditfærslanna sem þú vilt endurútflytja og notaðu svo aðgerðina **Endurútflytja greiðslur í bankaskrá**.

## <a name="see-also"></a>Sjá einnig
[Viðskiptaskuldir](payables-manage-payables.md)  
[Stjórnun innkaupa](purchasing-manage-purchasing.md)  
[Setja upp innkaup](purchasing-setup-purchasing.md)

