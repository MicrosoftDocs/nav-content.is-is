---
title: "Setja upp og skrá Intrastat"
description: "Lærið hvernig skal setja upp skráningareiginleika Intrastat og hvernig skal skrá viðskipti við fyrirtæki í öðrum ESB löndum."
documentationcenter: 
author: bholtorf
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: electronic document, Intrastat, trade, EU, European Union
ms.date: 08/15/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 1eb3a9a17f07806546022d941f923bc195c7c7fc
ms.contentlocale: is-is
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-set-up-and-report-intrastat"></a>Hvernig skal: Setja upp og skrá Intrastat
Öll fyrirtæki í löndum innan Evrópusambandsins þurfa að gefa öðrum löndum/svæðum innan sambandsins skýrslur um viðskipti sín. Einnig þarf að gefa hagstofu viðkomandi lands/svæðis mánaðarlega skýrslu um hreyfingu vöru og skýrsluna þarf að afhenda skattayfirvöldum. Í kerfinu er þetta kallað Intrastat-skýrslur. **Intrastatbók** er notuð til að vinna reglulegar Intrastat-skýrslur.  
  
## <a name="required-and-optional-setups"></a>Áskilin og valfrjáls uppsetning
Áður en þú getur notað Intrastat bókina til að gefa skýrslur í formi Intrastat upplýsinga, eru nokkrir hlutir sem þarf að setja upp.  
  
* **Sniðmát Instrastatbókar**: Nauðsynlegt er að setja upp sniðmát og keyrslur Intrastatbókarinnar sem notaðar verða. Þar sem Intrastat-skýrslugerð er framkvæmd mánaðarlega verður að stofna 12 intrastatbókarkeyrslur sem miðast við sama sniðmát.  
* **Vörukóði**: Tolla- og skattyfirvöld hafa sett fram númerakóða sem flokka vörur og þjónustu. Þú tiltekur þessa kóða á vörum.
* **Eðliskóðar færslu**: Lönd og svæði hafa ólíka kóða fyrir tegundir Instrastat viðskipti, eins og venjuleg innkaup og sala, skipti á skilavörum, og skipti á vörum sem ekki hefur verið skilað. Setja upp alla kóða sem eiga við í þínu landi/svæði. Þú notar þessa kóða í sölu- og innkaupaskjölum, og þegar þú vinnur vöruskil.  
* **Flutningsmáti**: Það eru sjö einstölu kóðar fyrir Intrastat flutningsmáta. **1** fyrir sjóleið, **2** fyrir lest, **3** fyrir akstur, **4** fyrir flug, **5** fyrir póstsendingar, **6** fyrir fastar uppsetningar, og **9** fyrir eigin knúningsafl (til dæmis, flytja bíl með því að aka honum). Dynamics NAV fer ekki fram á þessa kóða, en við mælum engu að síður með því að lýsingarnar beri með sér svipaða merkingu.  

Einnig er hægt að setja upp:

* **Viðskiptalýsingar**: Nota þær til að drýgja lýsingarnar af gerð viðskiptanna.  
* **Svæði**: Nota þau til að drýgja lýsingarnar um lönd og svæði.  
* **Komu/brottfarastaðir**: Nota þá til að tiltaka staðsetningar þar sem vöruafhending og móttaka fara fram í viðskiptum við önnur lönd. Heathrow flugstöðin er dæmi um komu-brottfararstað. Komu/brottfararstaði er hægt að færa inn í sölu- og innkaupskjöl á flýtiflipanum **Erlend viðskipti**. Þessar upplýsingar verða einnig afritaðar úr birgðafærslum þegar Intrastatbók er stofnuð.  

### <a name="to-set-up-intrastat-templates-and-batches"></a>Uppsetning Intrastat-sniðmáts og keyrslna.
Intrastat keyrslurnar ná aðeins yfir birgðafærslur, en ekki fjárhagsfærslur. Ef birgðafærslur eru til staðar sem eru gjaldgengar fyrir Intrastat-skýrslu, verður að færa þær inn handvirkt. Ef fyrirtækið kaupir t.d. tölvu frá öðru landsvæði innan ESB, er tölvan ekki sett í birgðir heldur bókuð í fjárhagsreikning. Slíka færslu verður að færa handvirkt inn í Intrastat-færslubókina.  
  
Hægt er að flytja færsluna út í skrá sem þú getur sent til Instrat yfirvalda. Einnig er hægt að prenta skýrslu, færa upplýsingarnar handvirkt inn í formið frá yfirvöldum, og svo senda upplýsingarnar inn.

> [!Note]
> Mælt er með því að keyrsla Intrastatbóka sé stofnuð fyrir hvern mánuð.  
  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Sniðmát Intrastat bóka** og velja svo viðeigandi tengil.  
2. Fyllið inn í reitina eftir þörfum. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]. Stofna sniðmát fyrir hvert Instrastat form sem er notað.  
3. Til að stofna keyrslu, skal velja **Færsluleit** og svo **Keyrslur**.  
4. Fyllið inn í reitina eftir þörfum. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]. Stofna sniðmát fyrir hvert Instrastat form sem er notað.  

> [!Note]
> Í reitinn **Upplýsingatímabil** er upplýsingatímabilið fært inn sem fjögurra stafa númer og tákna fyrstu tveir tölustafirnir árið og þeir sem á eftir koma mánuðinn. Til dæmis er 1706 fært inn fyrir júní 2017.

### <a name="to-set-up-commodity-codes"></a>Uppsetning vörukóða
Allar vörur sem eru keyptar eða selda verða að hafa vörukóða.  
  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Vörukóðar** og velja svo viðeigandi tengil.  
2. Fyllið inn í reitina eftir þörfum. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  
3. Til að úthluta vörukóða til vöru, skal fara í **Birgðaspjald** síðuna, útvíkka **Kostnaður & Bókanir** flýtiflipann og síðan færa inn kóðann í **Vörukóði** reitinn.   

### <a name="to-set-up-transaction-nature-codes"></a>Uppsetning eðliskóða viðskipta
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Eðliskóðar viðskipta** og velja svo viðeigandi tengil.  
2. Fyllið inn í reitina eftir þörfum. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

> [!Tip]
> Ef sérstakur eðliskóði viðskipta er notaður oft, geturðu gert hann sjálfgefinn. Til að gera það, skal fara á **Uppsetning Intrastat** síðuna, og velja kóðann. 

### <a name="to-set-up-transport-methods"></a>Uppsetning Flutningsmátar
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Flutningsmátar** og velja svo viðeigandi tengil.  
2. Fyllið inn í reitina eftir þörfum. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

## <a name="to-report-intrastat"></a>Setja fram Intrastat skýrslu
Þegar Intrastatbók er útfyllt er hægt að prenta skýrsluna **Gátlisti** til að tryggja að allar upplýsingar í bókinni séu réttar. Eftir það er hægt að intrastat-skýrsla prentuð á eyðublað eða stofnuð sem skrá og því næst send til skattayfirvalda viðkomandi landssvæðis.  

### <a name="to-fill-in-intrastat-journals"></a>Fært inn í Intrastatbækur:  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Intrastatbók** og velja svo viðeigandi tengil.  
2. Á **Intrastatbók** síðunni, í reitnum **Heiti keyrslu** skal velja viðeigandi færslubókarkeyrslu og velja því næst hnappinn **Í lagi**.  
3. Veljið aðgerðina **Leggja til línur**. Reitirnir **Upphafsdags.** og **Lokadagsetning** eru þegar komnir með dagsetningarnar sem tilgreindar eru fyrir upplýsingatímabilið í bókarkeyrslunni.  
4. Hægt er að færa prósentu í reitinn **Kostnaðarregla %** (til að ná yfir flutning og tryggingar). Ef færð er inn prósenta verður efni reitsins **Upplýsingagildi** í færslubókinni hlutfallslega hærra.  
5. Smellt er á **Í lagi** til að hefja keyrsluna.  
  
Keyrslan sækir allar birgðafærslur á upplýsingatímabilinu og setur þær inn í Intrastatbókina sem línur. Hægt er að breyta línunum ef þörf er á.  
  
> [!IMPORTANT]  
>  Keyrslan sækir aðeins þær færslur sem eru með lands-/svæðiskóða og fengið hafa Intrastatkóða á síðunni **Lönd/svæði**. Þess vegna er brýnt að færa inn Intrastatkóta fyrir lands-/svæðiskótana sem keyrslan er fyrir.  

### <a name="how-to-report-intrastat-on-a-form-or-a-file"></a>Hvernig á að senda Intrastat-skýrslu á eyðublaði eða sem skrá.
Prenta þarf skýrsluna **Intrastat – Eyðublað** til að fá upplýsingarnar sem þarf fyrir INTRASTAT-eyðublaðið frá hagstofu. Áður en hægt er að gera þetta þarf að undirbúa Intrastatbókina og fylla hana út. Ef bæði er um sölu- og innkaupafærslur að ræða þarf að fylla út sérstakt eyðublað fyrir hvora tegundina fyrir sig svo að þörf er á að prenta skýrsluna tvisvar.  
  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Intrastatbækur** og velja svo viðeigandi tengil.  
2. Á **Intrastat bók** síðunni, í reitnum **Heiti keyrslu** skal velja viðeigandi færslubókarkeyrslu.  
3. Fylla skal handvirkt út í færslubókina, ef það hefur ekki verið gert nú þegar, eða velja **Leggja til línur**.  
4. Veljið aðgerðina **Prentar Intrastatbók**.  
5. Á flýtiflipanum **Intrastatbókalína** er bætt við afmörkuninni **Tegund** til að velja einn af eftirfarandi valkostum: **Móttaka** eða **Afhending**.  
6. Til að prenta skýrsluna skal velja **Senda til**.  

### <a name="how-to-report-intrastat-in-a-file"></a>Hvernig á að senda Intrastat-skýrslu sem skrá.
Hægt er að senda Intrastat-skýrsluna sem skrá. Áður en skráin er búin til er hægt að prenta gátlista með upplýsingunum sem verða í skránni.  
  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Intrastatbók** og velja svo viðeigandi tengil.  
2. Í glugganum **Intrastatbók** er viðkomandi færslubókarkeyrsla valin í reitnum **Heiti keyrslu**.  
3. Fylla skal handvirkt út í færslubókina, ef það hefur ekki verið gert nú þegar, eða velja **Leggja til línur**.  
4. Aðgerðin **Stofna Skrá** er valin.  
5. Í runuvinnslunni veljið hnappinn **Í lagi**.  
6. Velja **Vista**.  
7. Flett er að möppunni þar sem vista á skrána og skráarheiti fært inn og síðan valið **Vista**. 

## <a name="how-to-reorganize-intrastat-journals"></a>Hvernig á að Endurskipuleggja Intrastatbækur
Þar sem Intrastat-skýrslu þarf að senda inn mánaðarlega og búa til nýja færslubókarkeyrslu fyrir hverja þeirra, muntu að lokum hafa margar bókarkeyrslur. Færslubókarlínurnar eyðast ekki sjálfkrafa. Ef til vill á að endurraða heitum færslubókarkeyrslnanna eftir tímabilum. Það er gert með því að eyða færslubókarkeyrslunum sem ekki er lengur þörf fyrir. Færslubókarlínunum í þessum keyrslum er einnig eytt.  
  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Intrastatbækur** og velja svo viðeigandi tengil.  
2. Í glugganum  er reiturinn **Heiti keyrslu** valinn til að sjá valkosti.  
3. Veldu bókarkeyrslurnar sem á að eyða og svo **Eyða**.  

## <a name="see-also"></a>Sjá einnig
[Fjármálastjórnun](finance.md)

## 
