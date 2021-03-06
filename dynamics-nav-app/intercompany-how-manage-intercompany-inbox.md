---
title: "Vinna MF færslur á inn- og útleið"
description: "Færslur milli fyrirtækja sem berast þér rafrænt frá MF-félögum eru taldar upp í MF-innhólfinu, þar sem þú vinnur þær sjálfvirkt eða handvirkt."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: incoming document
ms.date: 07/07/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 869dacac09019fda487e8ac18a5c8ff5d0fd17ac
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-manage-the-intercompany-inbox-and-outbox"></a>Hvernig á að: Stjórna millifyrirtækja innhólfsfærslur og úthólfsfærslur
Allar færslur milli fyrirtækja sem berast þér rafrænt frá MF-félögum eru taldar upp í MF-innhólfinu.  

## <a name="organizing-the-inbox"></a>Innhólfinu raðað  
 Hægt er að nota afmörkunarreitina efst í innhólfsglugganum til að ákvarða hvaða færslur eru birtar í glugganum. Til dæmis, ef aðeins á skoða færslur sem tiltekinn félagi stofnaði er hægt að færa inn afmarkanir í afmörkununum **Uppruni færslu** og **MF-félagakóti**.  

### <a name="transaction-source"></a>Uppruni færslu  
Það sem hægt er að gera við færslu fer eftir því hvort hún var:  

- Stofnuð af Millifyrirtækjafélaga  
- Hafnað af MF-félaga og send til baka  

Hægt er að nota reitinn **Sýna uppruna færslu** til að afmarka gluggann **MF-innhólfsfærslur** þannig að í honum birtist aðeins önnur af þessum færslutegundum. (Einnig er hægt að afmarka eftir MF-félaga eða eftir efni reitarins **Línuaðgerð**.)  

#### <a name="created-by-intercompany-partner"></a>Stofnuð af Millifyrirtækjafélaga  
 Þegar ný færsla berst sem var stofnuð af félaga er hægt að velja að:

- Samþykkja færsluna  
- Hafna færslunni (endursenda til félaga)  
- Ógilda færsluna (eyða færslunni en senda hana ekki aftur til félaga)  

#### <a name="returned-from-intercompany-partner"></a>Skilað af Millifyrirtækjafélaga  
 Ef færslunni var hafnað af Millifyrirtækja-félaga er eina valið að ógilda færsluna í innhólfinu. Síðan þarf að stofna leiðréttingarlínur eða bakfæra færslubókina eða fylgiskjalið í fyrirtækinu.  

## <a name="re-creating-inbox-entries"></a>Innhólfsfærslur stofnaðar aftur  
 Ef færsla var samþykkt í innhólfinu en fylgiskjalinu eða færslubókinni var síðan eytt án þess að bóka hana er hægt að stofna innhólfsfærsluna aftur og samþykkja hana aftur.  

## <a name="getting-an-overview-of-intercompany-transactions-for-a-period"></a>Yfirlit yfir færslur milli fyrirtækja á tímabili  
 Hægt er að fá yfirlit yfir allar færslur milli fyrirtækja sem tekið var við og hafa verið sendar á tilteknu tímabili. Í skýrslunni **Millifyrirtækjafærslur** koma fram allar fjárhagsfærslur, viðskiptamannafærslur og lánardrottnafærslur milli fyrirtækja.

 > [!NOTE]  
 > Ef millifyrirtækjafélagar eru í sama gagnagrunni, eru færslur framkvæmdar án þess að nota þurfi skrá eða tölvupóst. Sjá **Færslugerð** reitinn í **Millifyrirtækjafélagi** glugganum. <br /><br />
Í því tilfelli, geturðu sett upp kerfi til að tengja fram hjá innhólfinu og úthólfinu með því að velja**Samþykkja færslur sjálfvirkt** gátreitinn í **Millifyrirtækjafélagi** glugganum og **Senda færslur sjálfvirkt** gátreitinn í **Uppsetning millifyrirtækis** glugganum.

## <a name="to-import-intercompany-transactions-from-a-file"></a>Færslur milli fyrirtækja fluttar inn úr skrá:  
Ef fyrirtækið er með milli-fyrirtækjafélaga sem er ekki í sama gagnagrunni og fyrirtækið er hægt að taka á móti færslum milli fyrirtækja frá félaganum í XML-skrá. Síðan þarf að flytja færslurnar inn í innhólfið.  

1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Fyrirtækjaupplýsingar** og velja svo viðeigandi tengil.
2. Skráin er vistuð á staðnum sem tilgreindur var í reitnum **MF innhólf upplýsingar** í glugganum **Fyrirtæki upplýsingar**.  
3. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Færslur í innboxi millifyrirtækis** og velja svo viðeigandi tengil.
4. Í glugganum **Færslur í innboxi millifyrirtækis** skal velja **Flytja inn færsluskrá** aðgerðina.  
5. Í glugganum sem birtist er XML-skráin með færslunum valin og síðan smellt á hnappinn **Opna**.  

Færslurnar eru fluttar inn í innhólfið og nú er hægt að vinna með þær.

## <a name="to-process-incoming-intercompany-transactions"></a>Vinna færslur milli fyrirtækja á innleið  
Þegar milli-fyrirtækjafélagar senda færslur milli fyrirtækja enda færslurnar í milli-fyrirtækjainnhólfinu. Meta þarf hverja færslu í innhólfinu og bregðast við henni.  

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Færslur í innboxi millifyrirtækis** og velja svo viðeigandi tengil.  
2. Í **Færslur í innhólfi millifyrirtækis** glugganum skal velja línu og og síðan aðgerð, eins og t.d. **Samþykkja** til að setja línuna í ferli.
3. Í glugganum **Lokið MF-innhólf aðgerð** skal fylla út reitina eins og þörf krefur. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4. Velja hnappinn **Í lagi**.  

Fyrir línur sem þú setur í ferli með **Samþykkja** aðgerðinni, verða fylgiskjöl eða færslubókarlínur síðan stofnaðar í fyrirtækinu. Opna skal hvert fylgiskjal eða færslubók, gera nauðsynlegar breytingar og bóka.  

Línur sem þú vannst með **Skila til félaga** aðgerðinni verða settar í úthólfið þaðan sem þú getur síðan sent þær til félaga þíns.

Fyrir línur sem þú vannst með aðgerðinni **Skilað af félaga** verður nú að bóka leiðréttingu á upphaflegu færslunni sem bókuð var í fyrirtækinu.

## <a name="to-process-outgoing-intercompany-transactions"></a>Vinna færslur milli fyrirtækja á útleið  
Þegar færslubók eða fylgiskjal milli fyrirtækja er bókað eða pantanastaðfesting milli fyrirtækja er send fara færslurnar í milli-fyrirtækja úthólfið. Til að þær verði sendar til milli-fyrirtækjafélaga þarf að opna úthólfið og vinna úr þeim.  

1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Færslur í úthólfi millifyrirtækis** og velja svo viðeigandi tengil.  
2. Í **Færslur í úthólfi millifyrirtækis** glugganum skal velja línu og og síðan aðgerð, eins og t.d. **Fara aftur í innhólf** til að setja línuna í ferli.

Línur sem þú vannst með aðgerðinni **Senda til millifyrirtækjafélaga** verða sendar í innhólf viðeigandi félaga.

Línur sem þú vannst með **Skila til félaga** aðgerðinni verða settar í innhólfið þar sem þú getur síðan samþykkt þær til að búa til skjöl eða færslubókarlínur í fyrirtækinu.  

Fyrir línur sem þú vannst með aðgerðinni **Hætta við** verður nú að bóka leiðréttingu á upphaflegu færslunni sem bókuð var í fyrirtækinu.  

## <a name="to-recreate-intercompany-inbox-transactions"></a>Innhólfsfærslur milli fyrirtækja endurstofnaðar  
Einstaka sinnum gæti verið ráðlegt að stofna aftur viðskipti í innhólfinu eða úthólfinu. Ef t.d. færsla var samþykkt í innhólfinu en fylgiskjalinu eða færslubókinni var síðan eytt án þess að bóka hana er hægt að stofna innhólfsfærsluna aftur og samþykkja hana aftur.  

Eftirfarandi ferli lýsir hvernig eigi að endurstofna innhólfsfærslur, en sömu skref eiga einnig við um úthólfið.

  1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Afgreiddar MF-innhólfsfærslur** og velja svo viðeigandi tengil.  

  2.  Í glugganum **Afgreiddar MF-innhólfsfærslur** veljið línuna með færslunni sem á að stofna aftur í innhólfinu, og veljið svo **Endurstofna innhólfsfærslu** aðgerðina.  

## <a name="see-also"></a>Sjá einnig
[Vinna með millifyrirtækjafærslur](intercompany-manage.md)  
[Fjármál](finance.md)  
[Uppsetning Fjármála](finance-setup-finance.md)  
[Vinna í færslubókum](ui-work-general-journals.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

