---
title: "Hvernig á að Úthluta forða"
description: "Hægt er að breyta árlegri upphæð þjónustusamnings eða samningstilboðs til að leiðrétta upphæðina sem verður reikningsfærð árlega."
author: bholtorf
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/08/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 7882727735c38a11281ef22ac94b82f543b712b7
ms.contentlocale: is-is
ms.lasthandoff: 10/23/2017

---

# <a name="how-to-allocate-resources"></a>Hvernig á að: Úthluta forða
Lykilþáttur þjónustukerfis er fólkið sem veitir þjónustuna. Hægt að setja upp [!INCLUDE[d365fin](includes/d365fin_md.md)] til að úthluta réttu fólki í viðeigandi verk. Úthlutun verka er hægt að byggja á þjónustusvæðinu sem starfsfólk er á eða því hvar þjónustan á sér stað. Auk þess er hægt að flokka forða saman þegar þjónustubeiðnum er svarað. Nánari upplýsingar er að finna í [Hvernig á að: setja upp forðaúthlutun](service-how-setup-resource-allocation.md).

Þú getur úthlutað forða, til dæmis, tæknimönnum, með því að nota **Afgreiðslustöð**, eða frá þjónustupöntun. Þú getur notað forða til ráðstöfunar til að úthluta forða til að framkvæma þjónustuverkhlutana í pöntununum eða tilboðunum.

Úthluta sama forða, t.d. tæknimanni, eða forðaflokki á allar þjónustuvörur í þjónustupöntun. Úthlutunarfærslur eru stofnaðar fyrir aðra þjónustuvöru í pöntuninni með sama forðanúmeri og úthlutunardagsetningu og línan sem úthlutað var. Úthlutaðar stundir eru þær sem úthlutað var deilt með fjölda þjónustuvöru í pöntuninni. Reiturinn **Staða** er sjálfkrafa stilltur á **Virkt** fyrir allar færslur sem voru stofnaðar.

## <a name="to-see-an-overview-of-service-orders-and-service-quotes"></a>Yfirlit þjónustupantana/þjónustutilboða skoðað  
Oft gæti þurft að skoða lista yfir þjónustupantanir eða þjónustutilboð sem uppfylla ákveðnar kröfur til að geta unnið tilteknar aðgerðir með þeim hverja á eftir annarri. Til dæmis gæti þurft að úthluta forða til þjónustupantana sem tilheyra tilteknum viðskiptamanni.  

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Afgreiðslustöð** og velja svo viðeigandi tengil.  
2. Í reitnum **Fylgiskjalsafmörkun** er valin tegund fylgiskjala sem á að skoða.
3. Ef fá á lista yfir fylgiskjöl sem innihalda verkhluta sem er úthlutað tilteknum forða eða forðaflokki þarf að fylla út reitina **Forðaafmörkun** og **Forðaflokksafmörkun** og styðja á færslulykilinn.  
4. Ef fá á lista yfir fylgiskjöl með tiltekinni svardagsetningu eða svardagsetningum á tilteknu dagabili þarf að fylla út reitinn **Dags. afmörkun svars** og velja **Færslulykil**.  
5. Ef fá á lista yfir fylgiskjöl með tiltekna úthlutunarstöðu eða fylgiskjalsstöðu þarf að fylla út reitinn **Úthlutunarafmörkun/Stöðuafmörkun** og styðja á **færslu** lykilinn.  
6. Ef fá á lista yfir fylgiskjöl sem tilheyra ákveðnum samningi, viðskiptamanni, svæði er reiturinn **Samningsafmörkun/Viðskiptamannaafmörkun/Svæðisafmörkun** fylltur út og stutt á **færslu** lykilinn.  
7. Velja skal línu sem samsvarar viðkomandi þjónustupöntun eða þjónustutilboði og velja síðan **Sýna skjal** aðgerðina.  

    Gluggarnir **Þjónustupöntun** eða **Þjónustutilboð** opnast og hægt er að vinna í skjalinu. Til að fara aftur á síðuna **Afgreiðslustöð** skal velja **Í lagi**.

## <a name="to-allocate-a-resource-using-resource-or-resource-group-availability"></a>Forða úthlutað út frá forða eða forðaflokki til ráðstöfunar    
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Afgreiðslustöð** og velja svo viðeigandi tengil.  
2. Veljið þjónustupöntunina og velja svo aðgerðina **Forðaúthlutun**.  
3. Velja skal færslu með þjónustuverkinu sem úthluta á forða til.  
4. Veldu annað hvort **Forði til ráðstöfunar** eða **Forðaflokkur til ráðstöfunar** aðgerðina.  
5. Í glugganum **Forði til ráðstöfunar (þjónusta)** veljið **Sýna fylki**.  
6. Veljið forða til að úthluta. Hægt er að byggja valið á því hvort forðinn sé hæfur í verkhlutann, hvort hann sé staðsettur á svæði viðskiptamanns og/eða hvort viðskiptamaðurinn vill hann helst.  
7. Valin er dagsetning þegar forðinn er með nægar vinnustundir til ráðstöfunar til verksins og sem er nálægt svardegi þjónustupöntunar.  
8. Í reitinn **Magn til úthlutunar** er færður inn stundafjöldinn sem á að úthluta forðanum til þjónustuverksins.  
9. Í flipanum **Aðgerðir** í flokknum **Eiginleikar** veljið **Úthlutun** til að úthluta völdum forða á valinni dagsetningu.  

     Reiturinn **Staða** er sjálfkrafa stillt á **Virkt**.  

   Skrefin eru endurtekin fyrir hverja dagsetningu sem á að úthluta forða til þjónustuverks.  

> [!NOTE]  
>  Virkar þjónustupöntunarúthlutunarfærslur geta aðeins verið með úthlutunina **Virkt** með einum forða eða forðaflokki í einu fyrir þjónustuvöru í þjónustupöntun.  

## <a name="to-allocate-a-resource-using-a-service-order"></a>Forða úthlutað út frá þjónustupöntun:  
Þegar þjónustupöntun eða þjónustutilboð hefur verið stofnað og fyllt út er hægt að úthluta forða, til dæmis tæknimönnum, til að framkvæma þjónustuverkhluta sem eru skráðir sem þjónustuvörulínur í skjalinu.  

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Þjónustupantanir** og velja svo viðeigandi tengil.  
2. Veljið þjónustupöntunina og velja svo **Breyta**.  
3. Smellt er á þjónustuvörulínuna sem samsvarar þjónustuverkhlutanum sem á að úthluta forða.  
4. Velja **Úthlutun forða**.
5. Í glugganum **Úthlutun forða** er valin óvirk úthlutunarfærsla með þjónustuverkhlutanum sem úthluta á forðanum til. Ef óvirka færslan er ekki til er hægt að stofna nýja með því að velja **Ný**.  
7. Tilgreinið þjónustuverkhluta með því að fylla út **Nr. þjónustuvöru** í sömu línu.  
8. Í reitnum **Forðanr.** er forði valinn. Ef forðinn er hluti af forðaflokki er númer forðaflokksins fært sjálfkrafa inn í reitinn **Forðaflokkur nr.** reitinn .  
9. Reitirnir **Úthlutunardags.** og **Úthlutaðar stundir** eru fylltir út. Reiturinn **Staða** er stilltur á **Virk**. Það þýðir að forðanum hefur verið úthlutað til þjónustuverkhlutans.  
10. Hægt er að úthluta forða til allra vara, með því að velja **Úthluta til allra þjónustuvara**.

> [!NOTE]  
>  Virkar úthlutunarfærslur geta aðeins verið með úthlutunina Virkt með einum forða eða forðaflokki í einu fyrir þjónustuvöru í þjónustupöntun.

## <a name="to-reallocate-resources-on-a-service-order"></a>Forða endurúthlutað á þjónustupöntun  
Hægt er að endurúthluta forða beint úr þjónustupöntun eða þjónustutilboði á meðan unnið er. Eldri færslan er enn til en staðan er uppfærð á eftirfarandi hátt:  

* Hafi þjónustan hafist þegar úthlutun var **Virk** hafi viðgerðarstaða þjónustuvörunnar í færslunni breyst í **Í vinnslu** breytist úthlutunarstaðan úr **Þarf að endurúthluta** í **Lokið**.  
* Hafi þjónusta ekki hafist á meðan úthlutun var **Virk** breytist úthlutunarstaða úr **Þarf að endurúthluta** í **Hætt við**.  
* Ef endurúthlutað er þjónustupöntun sem breytt var úr tilboði breytir kerfið alltaf stöðu úthlutunarfærslnanna sem skráðar eru fyrir tilboðið í **Lokið** þegar þjónustuvörunum í þjónustupöntuninni er endurúthlutað.  

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Þjónustupantanir** og velja svo viðeigandi tengil.  
2. Opna skal viðeigandi þjónustupöntun.  
3. Smellt er á þjónustuvörulínuna sem samsvarar þjónustuverkhlutanum sem á að úthluta forða.  Velja **Aðgerðir**, velja **Lína** og smella síðan á **Úthlutun forða**.  
4. Í glugganum **Úthlutun forða** er valin úthlutunarfærslan með þjónustuverkhlutanum sem endurúthluta á forðanum til. Í reitnum **Forðanr.** er viðeigandi forði valinn. Hann kemur í staðinn fyrir forðanúmerið sem þegar er í reitnum.  
5. Ýtið á færslulykilinn. Þá opnast svargluggi og spurt er hvort endurúthluta eigi færslunni. Fyllið út reitinn **Ástæðukóti** ef það á við og veljið hnappinn **Í lagi** til að staðfesta endurúthlutun.  
6. Reitirnir **Úthlutunardags.** og **Úthlutaðar stundir** eru fylltir út. Nú sýnir færslan nýjan forða og staðan er **Virk**.

## <a name="to-reallocate-a-resource-using-the-dispatch-board"></a>Forða endurúthlutað út frá afgreiðslustöð  
Ef forðinn sem þjónustuverkhluta er úthlutað getur ekki lokið við verkið verður að endurúthluta þjónustuverkhlutanum forða. Yfirleitt er forða endurúthlutað til þjónustuverkhluta með **Afgreiðslustöð**.  

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Afgreiðslustöð** og velja svo viðeigandi tengil.  
2. Í reitnum **Úthlutunarafmörkun** skal velja **Þarf að endurúthluta**. Nú sýnir glugginn **Afgreiðslustöð** lista yfir þjónustupantanir sem fela í sér þjónustuverkhluta þar sem þarf að endurúthluta.  
3. Velja skal viðeigandi þjónustupöntun. Á flipanum **Færsluleit**, í flokknum **Áætlun**, skal velja **Úthlutun forða**. Glugginn **Úthlutun forða** opnast.  
4. Valin er úthlutunarfærslu þess þjónustuverkhluta sem á að endurúthluta forða.  
5. Í reitnum **Forðanr.** er viðeigandi forði valinn. Hann kemur í staðinn fyrir forðanúmerið sem þegar er í reitnum.  
6. Ýtt er á færsluhnappinn. Svarglugginn **Ástæður endurúthlutunarfærslu** opnast og spyr hvort endurúthluta eigi þessari færslu. Fyllið út reitinn **Ástæðukóti** ef það á við og veljið hnappinn **Í lagi** til að staðfesta endurúthlutun.  
7. Reitirnir **Úthlutunardags.** og **Úthlutaðar stundir** eru fylltir út. Nú sýnir færslan nýjan forða og staðan er **Virk**.  

   > [!NOTE]
   >  Eldri færslan er enn til en kerfið uppfærir stöðuna með eftirfarandi hætti:  
   > 
   > * Hafi þjónustan hafist þegar úthlutun var **Virk** hafi viðgerðarstaða þjónustuvörunnar í færslunni breyst í **Í vinnslu** breytist úthlutunarstaðan úr **Þarf að endurúthluta** í **Lokið**.  
   >   * Hafi þjónusta ekki hafist á meðan úthlutun var **Virk** breytist úthlutunarstaðan úr **Þarf að endurúthluta** í **Hætt við**.  
   >   * Ef endurúthlutað er þjónustupöntun sem breytt var úr tilboði breytir kerfið alltaf stöðu úthlutunarfærslnanna sem skráðar eru fyrir tilboðið í **Lokið** þegar þjónustuvörunum í þjónustupöntuninni er endurúthlutað.  

## <a name="to-register-resource-hours"></a>Forðastundir skráðar  
Þegar unnið er við þjónustuvöru í þjónustupöntunum þarf að skrá forðastundir sem notaðar eru til þjónustunnar. Eftirfarandi ferli sýnir hvernig á að skrá forðastundir í glugganum **Þjónustuvörublað**.  

Hægt er að nota sömu aðferð við að skrá stundirnar í glugganum **Þjónustulínur**, sem hægt er að opna úr glugganum Þjónustupöntun. Opna viðeigandi þjónustuspjald og velja síðan **Aðgerðir**, velja **Pöntun** og velja síðan **Þjónustulínur**.  

Ef sami forði nýtist til allrar þjónustuvöru í þjónustupöntun má aðeins skrá heildarfjölda forðastunda fyrir eina vöru og síðan er forðalínunni skipt upp til að úthluta annarri þjónustuvöru forðastundum.

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Þjónustuverkhlutar** og velja svo viðeigandi tengil.
2. Valin er línan sem inniheldur viðeigandi þjónustuvöru og síðan skal velja **Þjón.vörublað** aðgerðin.  
3. Fyllið inn í reitina eftir þörfum. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-assign-a-resource-to-all-service-items-in-an-order"></a>Úthlutun forða til allrar þjónustuvöru í pöntun
Ef sami forði, til dæmis tæknimaður, nýtist til allrar þjónustuvöru í þjónustupöntun má aðeins skrá heildarfjölda forðastunda fyrir eina vöru og síðan er forðalínunni skipt upp til að deila forðastundum í forðalínur fyrir hinar þjónustuvörurnar.  

Eftirfarandi aðferð sýnir hvernig forðalínum er skipt upp í glugganum **Þjónustureikningslínur**.  

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Þjónustupantanir** og velja svo viðeigandi tengil.  
2. Opna skal viðeigandi þjónustupöntun.  
3. Á flýtiflipanum **Línur** skal velja **Aðgerðir**, velja **Röð** og velja síðan **Þjónustulínur**. Glugginn **Þjónustulínur** opnast.  
4. Smellt er á forðalínuna sem á að skipta. Efni reitsins **Magn** er deilt milli allrar þjónustuvöru í pöntuninni.  
5. Í flipanum **Aðgerðir** veljið **Skipta forðalínu** aðgerðina. Veljið **Já** til staðfestingar.  

    Forðafærslur eru stofnaðar fyrir aðra þjónustuvöru í pöntuninni með sama forðanúmeri og línan sem skipt var upp. Magn er magnið fyrir línuna sem skipt var upp deilt með fjölda þjónustuvöru í pöntuninni.  

## <a name="to-cancel-an-allocation"></a>Hætt við úthlutanir:  
Þú getur hætt við forðaúthlutanir fyrir þjónustuverkhluta án þess að endurúthluta verkhlutunum.  

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Afgreiðslustöð** og velja svo viðeigandi tengil.  
2. Veljið þjónustupöntunina og velja svo aðgerðina **Forðaúthlutun**.  
3. Valin er úthlutunarfærslan með þjónustuverkhlutanum sem hætta á við úthlutun fyrir.  
4. Valið er **Hætta við úthlutun** aðgerð.  
5. Í reitnum **Ástæðukóti** veljið viðeigandi ástæðukóta.  
6. Velja **Já** til að staðfesta afturköllun.  

   > [!NOTE]  
    > Í reitnum **Staða** er valkosturinn **Þarf að endurúthluta** sjálfkrafa valinn. Ef viðgerðarstaða þjónustuvörunnar er **Upphaflegt** er viðgerðarstöðu breytt í **Verki vísað** (engin þjónusta hefur verið veitt). Ef viðgerðarstaðan er **Í vinnslu**er viðgerðarstöðunni breytt í **Hluta þjónustu lokið** (hluti vinnunnar búinn).

## <a name="see-also"></a>Sjá einnig
[Hvernig á að: Setja upp forðaúthlutun](service-how-setup-resource-allocation.md)  
[Úthlutunarstaða og viðgerðarstaða](service-allocation-status-and-repair-status.md)  

