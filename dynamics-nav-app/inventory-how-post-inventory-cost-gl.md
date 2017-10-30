---
title: "Hvernig á að bóka birgðakostnað í fjárhag"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 34eec596392e9316e807d3c073c3b8e59dbc12e9
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---

# <a name="how-to-post-inventory-costs-to-the-general-ledger"></a>Hvernig á að bóka birgðakostnað í fjárhag   
Þegar birgðafærslur (til dæmis söluafhending, innkaupareikningur eða birgðaleiðrétting) eru bókaðar skráir kerfið breytingar á magni og virði birgða í fjárhags- og virðisfærslur, hvort í sínu lagi. Til að endurspegla þessar breytingar á birgðavirði í ársreikningum, verður að bóka birgðakostnað á tengda birgðareikninga í fjárhag.

Hægt er að bóka birgðakostnað í fjárhag á tvo vegu:

- Sjálfvirkt, þannig að kerfið bókar birgðakostnaðinn í fjárhaginn í hvert skipti sem birgðafærsla er bókuð.
- Handvirkt, þannig að birgðakostnaður er aðeins bókaður í fjárhaginn þegar runuvinnsla er keyrð.


## <a name="to-post-inventory-costs-automatically"></a>Sjálfvirk bókun birgðakostnaðar
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Birgðagrunnur**, og velja síðan viðeigandi tengil.
2. Í glugganum **Birgðagrunnur** veljið gátreitinn **Sjálfvirk Kostnaðarbókun**.

Fyrir hverja birgðafærslu sem er bókuð er viðeigandi gildi bókað í birgðareikninginn, leiðréttingarreikninginn og KSV-reikninginn í fjárhagnum.

Þó að notuð sé sjálfvirk bókun kostnaðar er samt nauðsynlegt að keyra runuvinnsluna Leiðr. kostnað - Birgðafærslur með jöfnu millibili til að tryggja það að kostnaður vara sé áframsendur til viðeigandi færslna á útleið, eins og sölu eða millifærslna. Þetta skiptir sérstaklega miklu máli í aðstæðum þar sem vörur eru seldar áður en reikningur er færður inn fyrir kaupum á þessum vörum.

Ef villa kemur upp í víddaruppsetningunni á meðan það bókar birgðakostnaðinn í fjárhaginn endar bókunin á villu.

## <a name="to-post-inventory-costs-manually"></a>Handvirk bókun birgðakostnaðar
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **Bóka birgðakostnað í fjárhag**, og velja síðan viðeigandi tengil.
2. Birgðakostnaður er bókaður handvirkt í fjárhaginn með því að keyra runuvinnsluna. Þegar þessi keyrsla er keyrð eru fjárhagsfærslur stofnaðar á grundvelli virðisfærslna. Hægt er að bóka færslurnar þannig að þær eru teknar saman eftir bókunarhóp.

**Athugasemd**: Þegar þessi runuvinnsla er keyrð gæti kerfið rekist á villur sem hafa með uppsetningu sem vantar að gera eða ósamhæfa víddaruppsetningu. Ef keyrslan rekst á villur í víddaruppsetningunni hefur hún þessar villur að engu og notar víddir virðisfærslunnar. Í tilfelli annarra villna hoppar runuvinnslan yfir bókun virðisfærslnanna og telur þær upp við lok skýrslunnar í hluta sem heitir “Færslur sem hoppað var yfir.” Til að bóka þessar færslur þarf að laga villurnar.

Hægt er að sjá lista af villum áður en bókunarrunuvinnslan er keyrð með því að keyra skýrsluna **Bóka birgðabreytingar - Prófun**. Prófunarskýrslan telur upp allar þær villur sem finnast meðan á bókuninni stendur. Þá er hægt að laga villurnar og keyra bókunarkeyrslu birgðakostnaðar án þess að sleppa neinum færslum.

Til að fá yfirlit yfir það hvaða gildi var hægt að bóka í fjárhaginn án þess að framkvæma bókunina er hægt að keyra keyrsluna Bóka birgðabreytingar án þess að bóka gildin raunverulega í fjárhaginn. Hægt er að gera þetta með því að taka hakið úr reitnum Bóka á beiðnisíðunni. Á þennan hátt framleiðir kerfið bara skýrslu sem sýnir gildin sem eru tilbúin til bókunar í fjárhaginn þegar keyrslan er keyrð, en eru ekki bókuð.

## <a name="see-also"></a>Sjá einnig
[Stjórna birgðum](inventory-manage-inventory.md)    
[Hvernig á að: Leiðrétta birgðakostnað](inventory-how-adjust-item-costs.md)  
[Stjórna sölu](sales-manage-sales.md)  
[Stjórnun innkaupa](purchasing-manage-purchasing.md)

