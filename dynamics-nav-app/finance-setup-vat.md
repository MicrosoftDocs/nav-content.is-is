---
title: "Að setja upp virðisaukaskatt"
description: "Ganga úr skugga um að rétt reikna, bóka, og tilkynna á VSK vegna sölu eða innkaup."
documentationcenter: 
author: bholtorf
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: VAT, posting, tax, value-added tax
ms.date: 04/20/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: 97a346156b16784fb9ef5a382a7c1407685f7606
ms.contentlocale: is-is
ms.lasthandoff: 10/26/2017

---

# <a name="setting-up-to-calculations-and-posting-methods-for-value-added-tax"></a>Uppsetning fyrir útreikning og bókunaraðferðir virðisaukaskatts
Neytendur og fyrirtæki greiða virðisaukaskatt (VSK) þegar þau kaupa vörur eða þjónustu. Upphæð VSK til greiðslu getur verið mismunandi, það fer eftir nokkrum þáttum. Í [!INCLUDE[d365fin](includes/d365fin_md.md)], setur þú upp VSK til að tilgreina taxtana til að nota til að reikna skattaupphæðir, byggt á eftirfarandi: 

* Hverjum selt er  
* Hverjum keypt er af  
* Það sem er selt  
* Hvað keypt er  
  
Hægt er að setja upp VSK-útreikning handvirkt, en það getur verið bæði snúið og tímafrekt. Til að auðvelda, útveguðum við uppsetningarleiðsögn með hjálp sem nefnist **VSK Uppsetning** sem hjálpar til við verkstig. Mælt er með að nota uppsetningarleiðsögn til að setja upp VSK.

> [!NOTE]  
>   Hægt er að nota leiðbeiningarnar, aðeins ef þú hefur stofnað Mitt fyrirtæki, og hefur ekki bókað færslur sem innihalda VSK. Annars er mjög auðvelt að nota mismunandi VSK taxta af misgáning og gera VSK-skýrslum ónákvæmt.  
  
Ef þú vilt setja upp VSK-útreikning sjálfur eða vilt aðeins fá upplýsingar um hvert skref, er í þessu efnisatriði lýsingar á öll þrep.

## <a name="to-use-the-vat-setup-assisted-setup-guide-to-set-up-vat-recommended"></a>Nota VSK-uppsetningarleiðsögnina með hjálp til að setja upp VSK (ráðlagt)
Mælt er með að nota VSK-uppsetningarleiðsögn með hjálp til að setja upp VSK í [!INCLUDE[d365fin](includes/d365fin_md.md)]. 

Til að ræsa uppsetningleiðbeiningar með hjálp, fylgið þessum skrefum:
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Uppsetning með aðstoð**.  
2. Velja **VSK Uppsetning**.

## <a name="to-set-up-vat-business-posting-groups"></a>Uppsetning VSK-viðskiptabókunarflokka
VSK-viðskiptabókunarflokkar á að tákna markaðina þar sem þú stundar viðskiptum við viðskiptamenn og lánardrottna, og tilgreina hvernig á að reikna og bóka VSK á sérhverjum markaði. Dæmi um VSK viðskiptabókunarflokka eru **Innanlands** og **Evrópusambandið (ESB)**.  

Nota skal kóða sem auðvelt er að muna og er auðkennandi fyrir viðskiptaflokkinn, til dæmis **ESB**, **Ekki-ESB**, eða **Innlent**. Kótinn þarf að vera einstakur. Þú getur sett upp eins marga kóða og þörf krefur, en ekki er hægt að nota sama kóðann oftar en einu sinn í einni töflu.
  
Til að setja upp VSK-viðskiptabókunarflokk er þessu skrefum fylgt:

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **VSK-viðskiptabókunarflokkur** og velja svo viðeigandi tengil.  
2. Fyllið inn í svæðin eftir þörfum.

Sjálfgefnir VSK-viðskiptabókunarflokkar eru settir upp með því að tengja þá við almenna viðskiptabókunarflokka. [!INCLUDE[d365fin](includes/d365fin_md.md)] úthlutar sjálfkrafa VSK-viðskiptabókunarflokkinum þegar þú úthlutar viðskiptabókunarflokki til viðskiptamanns, lánardrottins eða fjárhagsreiknings. 

## <a name="to-set-up-vat-product-posting-groups"></a>Uppsetning VSK-vörubókunarflokka
VSK-vörubókunarflokkar tákna þær vörur og tilföng sem þú kaupir eða selur, og ákvarða hvernig skal reikna út og bóka VSK eftir tegund vöru eða tilfangs sem eru keypt eða seld.  
Góð regla er að nota kóða sem auðvelt er að muna og lýsa taxtanum, eins og **ÁN-VSK** eða **Núll**, **VSK10** eða **Skertur** fyrir 10% VSK, og **VSK25** eða **Staðlað** fyrir 25%.

Til að setja upp VSK-viðskiptabókunarflokk er þessu skrefum fylgt:

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **VSK-vörubókunarflokkar** og velja svo viðeigandi tengil.  
2. Fyllið inn í reitina eftir þörfum.

## <a name="to-combine-vat-posting-groups-in-vat-posting-setups"></a>Sameina VSK-bókunarflokka og VSK-bókunaruppsetningar
[!INCLUDE[d365fin](includes/d365fin_md.md)] reiknar VSK-upphæðir í sölu og innkaup á grundvelli VSK-bókunaruppsetninga, sem eru samsetningar VSK-viðskipta- og vörubókunarflokka. Fyrir hverja samsetningu geturðu valið VSK-prósenta, VSK-útreikningstegund, og fjárhagsreikninga fyrir bókun VSK sem tengist sölu, innkaupum, og bakfærðum gjöldum. Einnig er hægt að tilgreina hvort endurreikna skal VSK þegar greiðsluafsláttur er veittur eða fenginn.  

Hægt er að setja upp ótakmarkaðan fjölda samsetninga. Ef flokka á saman samsetningar VSK-bókunaruppsetninga með svipaða eiginleika, er hægt að tilgreina **Kennimerki VSK** fyrir hvern flokk og úthluta kenninu til flokksmeðlimanna.

Til að sameina VSK-bókunaruppsetningar skal fylgja eftirfarandi skrefum:

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **VSK-bókunargrunnur** og velja svo viðeigandi tengil.
2. Fyllið inn í reitina eftir þörfum.

## <a name="to-assign-vat-posting-groups-by-default-to-multiple-entities"></a>Úthluta VSK-bókunarflokkum sjálfvirkt til fjölda eininga
Eigi að beita sömu VSK-bókunarflokkum á fjölda eininga, er hægt að setja upp [!INCLUDE[d365fin](includes/d365fin_md.md)] sem gerir það sjálfvirkt. Hægt er að gera þetta á tvennan hátt:

* Hægt er að úthluta VSK-viðskiptabókunarflokkum til almennra viðskiptabókunarflokka eða sniðmáts viðskiptamanns eða lánardrottins 
* Hægt er að úthluta VSK-vörubókunarflokkum til almennum vörubókunarflokkum  

VSK-viðskipta- eða vörubókunarflokki er úthlutað þegar valið er viðskipta- eða vörubókunarflokki fyrir viðskiptamann, lánardrottinn, vöru eða tilföng.

## <a name="to-assign-vat-posting-groups-to-individual-accounts-customers-vendors-items-and-resources"></a>Úthluta VSK-bókunarflokka á einstaka reikninga, viðskiptamenn, lánardrottnar, vörur og tilföng
Eftirfarandi hlutar útskýra hvernig á að úthluta VSK-bókunarflokkum til einstakra einingar.

### <a name="to-assign-vat-posting-groups-to-individual-general-ledger-accounts"></a>Hvernig á að úthluta VSK-bókunarflokkum til einstakra fjárhagsreikninga 
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **bókhaldslykill** og velja svo viðeigandi tengil.  
2. Opna **Fjárhagsreikningur** spjaldið fyrir reikninginn.  
3. Á **Bókun** Flýtiflipanum, í **Alm. bókunartegund** reitnum, er valið annaðhvort **Sölu** eða **Innkaupa**.  
5. Velja skal VSK-bókunarflokkana til að nota fyrir sölureikninginn eða kaupreikninginn.  

### <a name="to-assign-vat-business-posting-groups-to-customers-and-vendors"></a>Að úthluta VSK-viðskiptabókunarflokkum til viðskiptamenn og lánardrottna.  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Viðskiptamaður** eða **Lánardrottinn** og velja svo viðeigandi tengil.  
2. Á **Viðskiptamaður** eða **Lánardrottinn** spjaldinu, víkið flýtiflipann **Reikningar**.  
3. Veljið VSK-viðskiptabókunarflokkana.  

### <a name="to-assign-vat-product-posting-groups-to-individual-items-and-resources"></a>Til að úthluta VSK-vörubókunarflokkar til einstakra vörur og tilföng.  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Vara** eða **Tilföng** og velja svo viðeigandi tengil.  
2. Gert er eitt af eftirfarandi:  

* Á **Vöru** spjaldinu, stækkið **Verð & Bókun** Flýtiflipann, og velja síðan **Sýna fleiri** til að birta **VAT Vörubókunarflokkur** reitinn.  
* Á **Tilfang** spjaldinu, stækkið **Reikningagerð** flipann.  
* Veljið VSK-vörubókunarflokk.  

## <a name="to-set-up-clauses-to-explain-the-use-of-non-standard-vat-rates"></a>Setja upp ákvæði til að útskýra notkun óstaðlaðra VSK taxta
VSK-klausa er sett upp til að lýsa upplýsingum um hvaða tegund VSK er notuð. Reglur stjórnvalda gætu krafist þessara upplýsinga. Þegar búið er að setja upp VSK-ákvæði og tengja það við VSK-bókunaruppsetningu, birtist VSK-ákvæðið á öllum prentuðum söluskjölum sem nota VSK-bókunaruppsetningarflokkinn. 

Ef með þarf er einnig hægt að tilgreina hvernig skal þýða VSK ákvæði yfir á öðrum tungumálum. Þegar söluskjal sem inniheldur VSK-kenni er stofnað og prentað, mun skjalið innihalda VSK-ákvæðið sem var þýtt. Tilgreindur tungumálakóðinn á viðskiptamannaspjaldinu ákvarðar tungumálið.

Hægt er að breyta eða eyða VSK-klausu og þá birtast breytingarnar í myndaðri skýrslu. [!INCLUDE[d365fin](includes/d365fin_md.md)] geymir hins vegar breytingasöguna. Í skýrslunni eru VSK-klausulýsingar prentaðar og birtar fyrir allar línur í skýrslunni ásamt VSK-upphæðinni og upphæð VSK-stofnsins. Ef VSK-klausa hefur ekki verið skilgreind fyrir neinar línur í söluskjalinu er öllum hlutanum sleppt þegar skýrslan er prentuð.
  
### <a name="to-set-up-vat-clauses"></a>Að setja upp VSK-ákvæði
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **VSK-ákvæði** og velja svo viðeigandi tengil.  
2. Á **VSK ákvæði** síðunni, skal búa til nýja línu.  
3. Í reitnum **Kóði** er auðkenni ákvæðisins slegið inn. Þessi kóði er notuð til að úthluta ákvæðinu á VSK-bókunarflokka.  
4. Í reitnum **Lýsing** er færður inn textinn sem þú vilt að birtast á fylgiskjala sem geta innihaldið VSK. Í reitnum **Lýsing 2** er færður inn viðbótartexti ef þörf krefur. Textinn birtist á nýjum línum.  
5. Valfrjálst: Til að úthluta VSK-ákvæði til VSK-bókunaruppsetningar strax, veljið **Uppsetning**, og velja síðan ákvæðið. Ef þú vilt bíða, er hægt að úthluta ákvæðinu síðar á VSK-Bókunaruppsetning síðunni.  
6. Valfrjálst: Til að tilgreina hvernig skal þýða VSK-ákvæðið er **Þýðingar** aðgerðin valin.

### <a name="to-assign-a-vat-clause-to-a-vat-posting-setup"></a>Til að úthluta VSK-ákvæði til VSK-bókunaruppsetningar
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **VSK-bókunargrunnur** og velja svo viðeigandi tengil.  
2. Í dálkinum **VSK-Ákvæði** skal velja ákvæðið sem nota á fyrir hvert VSK-bókunaruppsetningu sem það á við um.  

### <a name="to-specify-translations-for-vat-clauses"></a>Að tilgreina þýðingar fyrir VSK-ákvæði
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **VSK-ákvæði** og velja svo viðeigandi tengil.  
2. Veljið aðgerðina **Þýðingar**.  
3. Í reitnum **Tungumálakóði** skal velja tungumál sem þýtt er yfir á.  
4. Í reitunum **Lýsing** og **Lýsing 2** eru færðar inn þýðingar á lýsingunum. Þessi texti er birtur í þýddum VSK-skýrsluskjölum.  
  
## <a name="to-create-a-vat-posting-setup-to-handle-import-vat"></a>Stofna VSK-bókunaruppsetningu til að sjá um VSK vegna Innflutnings
Aðgerðin VSK vegna innflutnings er notuð þegar á að bóka fylgiskjal þar sem öll upphæðin er VSK. Þetta þarf að gera ef reikningur kemur frá skattyfirvöldum fyrir VSK á innfluttar vörur.  
  
Til að setja upp kóða fyrir VSK vegna innflutnings, skal fylgja þessum skrefum:  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **VSK-vörubókunarflokkar** og velja svo viðeigandi tengil.  
2. Á síðunni VSK-vörubókunarflokkar, skal setja upp nýja VSK-vörubókunarflokkur fyrir VSK vegna innflutnings.  
3. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **VSK-bókunargrunnur** og velja svo viðeigandi tengil.  
4. Á síðunni VSK-bókunaruppsetning skal stofna nýja lína, eða nota VSK-viðskiptabókunarflokk sem fyrir er í samsetningu með nýja VSK-vörubókunarflokknum fyrir VSK vegna innflutnings.  
5. Í reitnum **SK-Útreikningstegund** skal velja **Fullur VSK**.  
6. Í **VSK-sölureikningur** reitinn skal færa inn fjárhagsreikningurinn sem á að nota til að bóka VSK vegna innflutnings. Allir aðrir reikninga eru valfrjáls.  
  
## <a name="to-verify-vat-registration-numbers"></a>Staðfesta VSK-skráningarnúmer
Mikilvægt er að þau VSK-númer sem þú hefur fyrir viðskiptamenn, lánardrottna og tengiliði séu gild. Fyrirtæki breyta til dæmis stundum stöðu skattaskuldar hjá sér, og í sumum lönd gætu skattayfirvöld farið fram á að fá skýrslur, til dæmis skýrsluyfirlit um sölu innan Evrópubandalagsins, sem inniheldur VSK-númerin sem þú ert að nota við í viðskiptum. 
  
Framkvæmdarstjórn Evrópusambandsins býður á vefsíðu sinni þjónustu VIES varðandi VSK Númerastaðfestingu, sem býðst öllum og er án endurgjalds. [!INCLUDE[d365fin](includes/d365fin_md.md)] getur sparað þér það skref og leyft þér að nota þjónustu VIES til að staðfesta og rekja VSK-númer viðskiptamanna, lánardrottna og tengiliði beint úr spjöldum viðskiptamaður, lánardrottinn og tengiliða. Þjónustan í [!INCLUDE[d365fin](includes/d365fin_md.md)] kallast **ESB VSK Skrá. Nr. Staðfestingarþjónusta**. Þjónustan er tiltæk í **Þjónustutengingar** síðunni og þú getur hafið notkun strax. Þjónustan er án endurgjalds og skráningar er ekki krafist.

> [!Note]
> Til að virkja VSK-skráningarnúmer innan ESB staðfestingarþjónustuna verður þú að hafa kerfisstjóraheimildir.

Þegar þjónustu okkar er notuð, skráum við ferill VSK-númera og VSK-staðfestinga fyrir hvern viðskiptamann, lánadrottinn eða tengiliðar, í reitnum **VSK Skráning Skrá**, þannig að þú getur auðveldlega rekja þá. Skráin á sérstaklega við hvern viðskiptamann. Til dæmis kemur skráin að gagni við að sanna það að þú hafir staðfest að gildandi VSK-númer séu réttar. Þegar VSK-númer er staðfest, mun **Biðja um kennimerki** dálkurinn í skránni endurspegla að þú hafir framkvæmt hlutinn. 

Hægt er að skoða VSK-skráning skránna á spjöldunum fyrir viðskiptamann, lánardrottin eða tengilið, á **Reikningsfæra** Flýtiflipanum með því að velja hnappinn uppfletting á **VSK-númer**  

Okkar þjónustu getur einnig sparað þér tíma þegar verið er að stofna viðskiptamann eða lánardrottin. Ef þú veist VSK-númer viðskiptamanns, geturðu fært það inn í reitinn **VSK-númer** á spjöldum viðskiptamanns eða lánardrottins, og við fyllum út nafn viðskiptamanns fyrir þig. Sumar lönd bjóða einnig upp á aðsetur fyrirtækis á skipulögðu sniði. Í þeim löndum, munum við fylla út aðsetur líka.  

> [!NOTE]  
> Það eru nokkur atriði sem vert er að athuga varðandi þjónustu VIES á VSK-númerastaðfestingu:

* Þjónustan notar http-reglur, sem táknar að gagnaflutningur um þjónustuna er ekki dulkóðaður.  
* Þú getur upplifað óvirkan tíma í þessari þjónustu sem Microsoft er ekki ábyrgt fyrir. Þjónustan er hluti af víðfemu ESB skráningarkerfi VSK-númera.

## <a name="using-reverse-charge-vat-for-trade-between-eu-countries-or-regions"></a>Nota bakfærðan VSK fyrir viðskipti milli ESB-landa eða svæða
Sum fyrirtæki verða að nota bakfærðan VSK þegar þau eiga viðskipti við önnur fyrirtæki. Reglan gildir til dæmis fyrir innkaup frá ESB-löndum/svæðum og sölu til ESB-landa/svæða.  
  
> [!NOTE]  
> Þessi regla á við þegar skipt er við fyrirtæki sem eru skráð VSK-skyld í öðrum ESB-löndum/svæðum. Ef skipt er beint við viðskiptamenn í öðrum ESB-löndum/svæðum ætti að hafa samband við skattayfirvöld til að fá upplýsingar um viðeigandi VSK-reglur.  
  
> [!TIP]  
> Þú getur staðfest að fyrirtæki sé skráð VSK-skylt í öðru ESB-landi með því að nota ESB staðfestingarþjónustu VSK-númera. Þjónustan er tiltæk án endurgjalds í [!INCLUDE[d365fin](includes/d365fin_md.md)]. Frekari upplýsingar má finna í hlutanum sem nefndur er _Staðfesting VSK-númera_ í þessu efnisatriði.

### <a name="sales-to-eu-countries-or-regions"></a>Sala til ESB-landa eða svæða
VSK er ekki reiknaður á sölu til VSK-skyldra fyrirtækja í öðrum ESB-löndum/svæðum. Tilkynna þarf virði sölu til ESB-landa/svæða sérstaklega á VSK-yfirlitinu.  

Til að reikna VSK rétt fyrir sölu til ESB-landa/ svæða ætti að:  
  
* Setja upp línu fyrir sölu með sömu upplýsingum fyrir innkaup. Ef línur eru þegar uppsettar í glugganum VSK-bókunargrunnur fyrir innkaup frá ESB-löndum/-svæðum er einnig hægt að nota línurnar fyrir sölu.  
* Úthluta VSK-viðskiptabókunarflokkunum í reitnum **VSK viðsk.bókunarflokkur** á flýtiflipanum **Reikningar** í viðskiptamannaspjöldum ESB-viðskiptamanna. Einnig ætti að færa inn VSK-númer viðskiptamannsins í reitnum **VSK-númer** á flýtiflipanum **Erlent**.  

Þegar sala til viðskiptamanns í öðru ESB-landi/svæði er bókuð er VSK-upphæðin reiknuð og VSK-færsla með upplýsingum um bakfærðan VSK og VSK-stofn (upphæðina sem notuð er til að reikna VSK-upphæðina) stofnuð. Engar færslur eru bókaðar í VSK-reikningana í fjárhagnum.

## <a name="understanding-vat-rounding-for-documents"></a>Að skilja VSK-sléttun fyrir fylgiskjöl
Upphæðir í fylgiskjölum sem ekki hafa verið bókaðar eru sléttaðar og birtar á þann hátt sem samsvarar lokasléttun upphæða sem búið er að bóka. VSK er reiknaður fyrir heilt skjal, sem þýðir að VSK sem er reiknaður í fylgiskjali er byggður á summu allra lína með sama VSK-kenni í skjalinu.

## <a name="understanding-the-vat-rate-conversion-process"></a>Að skilja umbreytingarferli VSK-hlutfalls.  
VSK-hlutfall breytingarverkfærið umreiknar VSK-hlutfall fyrir aðalgögn, færslubækur og pantanir á mismunandi hátt. Valin aðalgögn og færslubækur verða uppfærð af nýja almenna vörubókunarflokknum eða VSK-vörubókunarflokki. Ef pöntun hefur verið afhent að fullu eða að hluta munu afhentar vörur halda almenna vörubókunarflokknum eða VSK-vörubókunarflokknum. Ný pöntunarlína verður stofnuð fyrir óafhentar vörur og uppfærð til að samræma núverandi og nýtt VSK eða almenna vörubókunarflokka. Úthlutanir kostnaðarauka, frátekningar og vörurakningarupplýsingar uppfærast einnig í samræmi við það.  
  
Það eru hins vegar nokkrir hlutir sem verkfærið getur ekki umbreytt:

* Sölu-eða innkaupapöntunum og reikningum þar sem sendingar hafa verið bókaðar. Þessi skjöl eru bókuð með gildandi VSK-hlutfalli.  
* Skjölum sem hafa bókaða fyrirframgreiðslureikninga. Til dæmis gæti notandi hafa greitt eða móttekið fyrirframgreiðslur á reikningum sem eru ekki loknir áður en breytingaverkfærið VSK-hlutfall er notað. Í þessu tilviki verður mismunur á vsk sem er á gjalddaga og vsk sem hefur verið borgaður í fyrirframgreiðslum þegar reikningnum er lokið. Breytingarverkfæri VSK-hlutfalls sleppir þessum skjölum og það þarf að uppfæra þau handvirkt.  
* Beinum afhendingum eða sérpöntunum.  
* Sölu- eða innkaupapöntunum með samhæfingu vöruhúsa ef þær eru að hluta sendar eða mótteknar.  
* Þjónustusamninga.  

### <a name="to-prepare-vat-rate-change-conversions"></a>Til að undirbúa umreikning VSK-hlutfalls  
Áður en breytingaverkfæri VSK-hlutfalls er sett upp þarf að velja úr eftirfarandi.

* Ef mismunandi hlutföll eru notuð í færslum þarf að búa til nýjar fjárhagsreikninga fyrir hvert hlutfall eða nota gagnaafmarkanir til að flokka færslur eftir hlutfalli.  
* Ef stofnaðir eru nýir fjárhagsreikningar þarf að stofna nýja almenna bókunarflokka.  
* Til að fækka fylgiskjölum sem er breytt skal bóka eins mörg fylgiskjöl og mögulegt er og halda óbókuðum skjölum í lágmarki.  
* Taka öryggisafrit af gögnum.

### <a name="to-set-up-the-vat-rate-change-tool"></a>Til að setja upp breytingaverkfæri VSK-hlutfalls  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Uppsetning VSK hlutfall breytingar** og velja svo viðeigandi tengil.  
2. Á flýtiflipunum **Aðalgögn**, **Færslubækur** og **Skjöl** skal velja gildi bókunarflokks af valkostalistanum fyrir nauðsynlega reiti.  
  
### <a name="to-set-up-product-posting-group-conversion"></a>Til að setja upp vörubókunarflokksumbreytingar  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Uppsetning VSK hlutfall breytingar** og velja svo viðeigandi tengil.  
2. Á síðunni **VSK hlutfall breyta uppsetning** á flipanum **Heim** í flokknum **Í vinnslu** veljið annað hvort **Umreikna VSK framl. Bókunarflokkur** eða **Umreikna Alm framl. Bókunarflokkur**.  
3. Í reitnum **Frá kóða** er færður inn núverandi bókunarflokkur.  
4. Í reitnum **Til kóða** er færður inn nýr bókunarflokkur.  

### <a name="to-perform-vat-rate-change-conversion"></a>Til að umreikna VSK-hlutfall  
Breytingarverkfæri VSK-hlutfalls er notað til að stjórna breytinum á stöðluðu VSK-hlutfalli. VSK og útreikningar almenns vörubókunarflokks eru notaðir til að breyta VSK-hlutfalli og viðhalda nákvæmum VSK-skýrslum. Eftirfarandi breytingar eru gerðar, allt eftir uppsetningu:  
  
* VSK og almennum bókunarflokkum er umbreytt.  
* Breytingar eru innleiddar í fjárhagsreikninga, viðskiptamenn, lánardrottna, opin skjöl, bókarlínum, o.s.frv.  
  
> [!IMPORTANT]  
>  Áður en þú umreiknar VSK-hlutfallsbreytingu, er hægt að prófa umreikninginn. Til að gera það, skal fylgja eftirfarandi skrefum, en vertu viss um að hafa auða gátreitina **Framkvæma umreikning** og **VSK hlutfall breytingarverkfæri lokið**. Við prófun á umreikningi er reiturinn **Umbreytt** í töflu **Breyting á VSK gengi í skráningarfærslu** hreinsað og reiturinn **Umbreytt dagsetning** í töflunni **Breyting á VSK gengi í skráningarfærslu** auður. Þegar umreikningnum er lokið, skal velja **Breytingaskrárfærslur fyrir VSK-hlutfall** til að skoða niðurstöður af prufuumreikningnum. Staðfesta hverja færslu áður en umreikningur er framkvæmdur. Sérstaklega skal staðfesta færslur sem nota eldra VSK-hlutfall.     

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **VSK hlutfall breyta** og velja svo tengilinn **Uppsetning VSK hlutfall breyta**.  
2. Staðfesta að VSK-vörubókunarflokksumbreytingar eða almennar vörubókunarflokksumbreytingar hafi þegar verið settar upp.  
3. Velja skal gátreitinn **Framkvæma umreikning**.  
  
> [!IMPORTANT]
>  Hreinsa gátreitinn **breytingaverkfæri fyrir VSK gengi lokið**. Gátreiturinn er valinn sjálfvirkt þegar umreikningi vsk-stigs er lokið.  
  
4. Velja skal **Umreikna** aðgerðina.  
5. Þegar umreikningnum er lokið, á flipanum **Heim**, í flokknum **Vinna**, skal velja **Breytingaskrárfærslur fyrir VSK-hlutfall** til að skoða niðurstöður af umreikningnum.  
  
> [!IMPORTANT]  
>  Eftir prófun á umreikningi er reiturinn **Umbreytt** í töflu **Breyting á VSK gengi í skráningarfærslu** valinn og reiturinn **Umbreytt dagsetning** í töflunni **Breyting á VSK gengi í skráningarfærslu** sýnir umreiknuðu dagsetninguna.  
  
## <a name="see-also"></a>Sjá einnig  
[Uppsetning á óinnleystum virðisaukaskatti](finance-setup-unrealized-vat.md)  
[Hvernig á að: Senda VSK skýrslu inn til skattayfirvalda](finance-how-report-vat.md)  
[Hvernig á að: vinna með VSK í sölu og innkaupum](finance-work-with-vat.md)  
