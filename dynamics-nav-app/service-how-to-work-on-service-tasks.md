---
title: "Hvernig á að vinna með þjónustuverkhluta"
description: "Þegar búið er að stofna þjónustupöntun eða þjónustutilboð, skrá þjónustuvörulínur og úthluta forða til þjónustuvöru í pöntuninni eða tilboðinu má byrja að gera við þjónustuvöru og halda henni við."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 3e8fd9d1e56de77c54f5190d97f95faa0702908e
ms.contentlocale: is-is
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-work-on-service-tasks"></a>Hvernig á að vinna með þjónustuverkhluta
Þegar búið er að stofna þjónustupöntun eða þjónustutilboð, skrá þjónustuvörulínur og úthluta forða til þjónustuvöru í pöntuninni eða tilboðinu má byrja að gera við þjónustuvöru og halda henni við.  

[!INCLUDE[d365fin](includes/d365fin_md.md)] er með gluggann **Þjónustuverkhlutar** sem veitir yfirlit yfir allar þjónustuvörur sem þarfnast athygli. Gluggann má hugsa sem þjónustumælaborð þar sem hægt er að sjá hvaða pantanir eru í bið, leita að og skrá varahluti, og sjá til þess að birgðir séu uppfærðar.  
  
Til að rekja breytingar og fá myndrænt yfirlit yfir þjónustufyrirtækið má nota upplýsingaverkfæri [!INCLUDE[d365fin](includes/d365fin_md.md)] til að búa til myndrit og greiningar hratt og sjálfkrafa.  
  
## <a name="to-work-on-a-service-task"></a>Unnið við þjónustuverkhluta:  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Þjónustuverkhlutar** og velja svo viðeigandi tengil. 
2. Ef fá á lista yfir verkhluta sem tilteknum forða eða forðaflokki er úthlutað til þarf að fylla út reitinn **Forðaafmörkun** eða **Forðaflokksafmörkun** og styðja á færslulykilinn.  
3. Ef fá á lista yfir þjónustuverkhluta með tiltekinni svardagsetningu eða svardagsetningum á tilteknu tímabili þarf að fylla út reitinn **Dags. afmörkun svars** og styðja á færslulykilinn.  
4. Ef fá á lista yfir verkhluta með tiltekna úthlutunarstöðu eða viðgerðarstöðu þarf að fylla út reitinn **Afm. úthlutunarstöðu** eða **Viðgerðarstöðukóti - afmörkun** og styðja á færslulykilinn.  
5. Veljið þjónustuverkið sem á að vinna með. Á flipanum **Færsluleit**, í flokknum **Þjónustuverkhlutar**, skal velja hnappinn **Þjónustuvörublað**. Glugginn **Þjónustuvörublað** opnast.  
6. Skrá staðlaður texti, varahlutir, forðastundir og kostnaður eins og við á með samsvarandi valkostum í  **Tegund**: <Blank> reitnum:  **Vara**, **Forði** og **Kostnaður**.  
7. Í reitnum **Viðgerðastaða** veljið viðeigandi stöðu.  
  
   > [!NOTE]  
   >  Fyllt er út í reitinn **Viðgerðarstaða** með stöðunni **Lokið** eða **Hluta þjónustu lokið** ef vinnu við þjónustuvöruna er lokið eða annar forði heldur áfram að veita þjónustu. Staðan **Lokið** eða **Þarf að endurúthluta** er sjálfkrafa valin fyrir úthlutunarfærsluna fyrir þjónustuvöruna.  

## <a name="to-register-service-operations"></a>Skráning þjónustuaðgerða  
Þegar þjónustupöntun er þjónustuð er hægt að skrá upplýsingar þar sem tilgreint er notaðar vörur, kostnaður sem stofnað hefur verið til og stundir sem búið er að eyða. Gögnin sem tilgreind eru eru geymd í glugganum **Þjónustuvörublað**. Hægt er að uppfæra gögnin eftir þörfum. 
   
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Þjónustupantanir** og velja svo viðeigandi tengil.  
2. Opna skal þjónustupöntunina til að skrá þjónustuna fyrir, og velja vörulínuna.  
3. Velja **Aðgerðir**, velja **Lína** og smella síðan á **Þjónustuvörublað**.  
4. Í línurnar skal tilgreina notaðar vörur, stofnaðan kostnað og stundir sem varið hefur verið í þjónustuna.  
  
   > [!NOTE]  
   >  Einnig er hægt að skrá þjónustuna beint í þjónustulínurnar sem tengdar eru við þjónustupöntunina.  
  
## <a name="to-register-spare-parts"></a>Varahlutir skráðir  
Þegar unnið er við þjónustuvöru í þjónustupöntunum kann að þurfa að nota varahluti til þjónustunnar. Eftirfarandi ferli sýnir hvernig á að skrá varahluti í glugganum **Þjónustuvörublað**.  
  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Þjónustuverkhlutar** og velja svo viðeigandi tengil. 
2. Valin er línan sem inniheldur viðeigandi þjónustuvöru og síðan skal velja **Vörublað** aðgerðin.  
3. Færð er inn ný þjónustulína.  
4. Í reiturinn **Tegund** skal velja **Vara**.  
5. Í reitnum **númer** veljið viðeigandi varahlut.  
6. Í reitinn **Magn** er fært magn vara sem á að nota.  
  
   Hægt er að nota svipaða aðferð til að skrá varahluti í síðuna **Þjónustulínur** sem hægt er að opna frá síðunni **Þjónustupöntun**.  
  
## <a name="to-register-spare-parts-from-a-service-order"></a>Til að skrá varahluti úr þjónustupöntun  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Þjónustupantanir** og velja svo viðeigandi tengil.  
2. Opna þjónustupöntunina sem skrá á varahlutina fyrir.  
3. Valin er línan sem inniheldur viðeigandi þjónustuvöru. Velja **Aðgerðir**, velja **Röð** og smella síðan á **Þjónustulínur**.  
4. færð er inn ný þjónustulína.  
  
## <a name="to-replace-a-service-item-or-a-service-item-component"></a>Skipta um þjónustuvöru eða þjónustuvöruíhlut  
Þegar veitt er þjónusta vegna þjónustuvöru sem er samsett úr íhlutum þarf kannski að skipta á gölluðum íhlut og nýjum. Í hvert sinn sem færður er inn varahlutur vegna þjónustuvöru úr íhlutum er hægt að velja um að skipta um íhlut eða stofna nýjan. Kerfið skráir ekki nýju vöruna sem íhlut þjónustuvörunnar fyrr en búið er að bóka þjónustulínuna eða þjónustupöntunina. 
    
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Þjónustuverkhlutar** og velja svo viðeigandi tengil. 
2. Valin er línan sem inniheldur þjónustuvöruna og síðan skal velja **Vörublað** aðgerðin.  
3. Færð er inn ný þjónustulína.  
4. Í reiturinn **Tegund** skal velja **Vara**.  
5. Í reitnum **númer** reitur, velja íhlutinn sem á að skipta út.  
6. Stutt er á **Færslulykilinn**. Þá birtist svarreitur með þremur valreitum: **Skipta um íhlut**, **Nýr íhlutur** og **Hunsa**. Eftirfarandi tafla lýsir valkostunum.  
  
    |Valkostur | Description|  
    |----------------------------------|---------------------------------------|  
    |**Skipta út íhlut**|Breytir stöðu íhlutarins sem verið er að skipta um í óvirka og hann birtist á lista yfir íhluti sem skipt hefur verið um vegna þjónustuvörunnar.|  
    |**Nýr Íhlutur**|Færir inn nýjan íhlut á íhlutalista þjónustuvörunnar.|  
    |**Hunsa**|Kerfið gerir ekkert við íhlutalista þjónustuvörunnar.|  
  
7. Velja **Skipta um íhlut**.  
8. Velja íhlutinn sem á að skipta út og síðan hnappinn **Í lagi**.  

## <a name="to-change-the-response-time-for-a-service-item-line"></a>Svartíma fyrir þjónustuvörulínu breytt:  
Þegar þú skráir þjónustuvörulínu í þjónustupöntun eða tilboði, háð því hvort þjónustuvaran er á þjónustusamningi er svartími í klst. sjálfkrafa færður inn og svardagsetning og tími reiknuð í samræmi við það. Hægt er að breyta svartíma í klst. og svardagsetningu og tíma ef þess er þörf.  

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Þjónustupöntun** eða **Þjónustutilboð** og velja svo viðeigandi tengil.  
2. Velja skal þjónustupöntunina eða tilboðið til að opna spjaldið.  
3. Á þjónustuvörulínunni sem viltu breyta svartímanum fyrir, annað hvort í reitnum **Svartími (klst.)** eða í reitunum **Svardagsetning** og **Svartími** er færð inn nýr svartími eða nýr svardagsetning og tími.  

## <a name="to-register-faultresolution-codes"></a>Skráning bilana- og úrlausnarkóta  
Þegar gert hefur verið við þjónustuvöru er hægt að skrá bæði bilanakótann og úrlausnarkótann fyrir vöruna með því að velja samsetningu í þeim tengslum bilana- og úrlausnarkóta sem til eru. Nú birtast valdir bilana- og úrlausnarkóðar í samsvarandi reitum í glugganum **Þjónustuvörublað**. Einnig má skrá kótana beint í þessum glugga.  
    
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Þjónustuverkhlutar** og velja svo viðeigandi tengil. 
2. Valin er línan sem inniheldur viðeigandi þjónustuvöru og síðan skal velja **Vörublað** aðgerðin.  
3. Á síðunni **Þjónustuvörublað** er valið **Tengsl úrlausnar-/bilanakóða**. Þá birtist glugginn **Tengsl bilunar/úrlausnarkóta**.  
  
   > [!Note]
   >  Afmarkanir eru settar á tengslin sem birtast í glugganum með því að afrita þjónustuvöruflokkinn og bilanakótana úr glugganum **Þjónustuvörublað**.  
  
4. Línan er fyllt út. Valin er samsetning bilana- og úrlausnarkóta og svo smellt á **Í lagi** til að afrita hana í þjónustuvöruna. Ef ekki finnst heppileg samsetning má búa til nýja í glugganum.  

## <a name="see-also"></a>Sjá einnig  
[Hvernig á að: setja upp bilanatilkynningar](service-how-setup-fault-reporting.md)
[Úthlutunarstaða og viðgerðastaða](service-allocation-status-and-repair-status.md)  
[Bókun þjónustu](service-service-posting.md)  


