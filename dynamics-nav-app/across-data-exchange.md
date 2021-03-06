---
title: "Rafræn skjöl í Dynamics NAV"
description: "Inngangur að sendingum og móttöku rafrænna skjala í [!INCLUDE[d365fin](includes/d365fin_md.md)]."
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/19/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 5459a76797a948555a6a20009d57de96fe9eec7f
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="exchanging-data-electronically"></a>Rafræn gagnaskipti
Hægt er að nota Gagnaskiptarammann til að skiptast á viðskiptaskjölum, bankaskrám, gengi gjaldmiðla og öllum öðrum gögnum á milli viðskiptafélaga.

## <a name="electronic-documents"></a>Rafræn skjöl
Annar valkostur við að senda skrár sem viðhengi í tölvupósti er að senda og taka á móti viðskiptaskjölum á rafrænan hátt. Með rafrænu skjali er átt við staðlaða og samþykkta skrá sem stendur fyrir viðskiptaskjal, s.s. reikning frá lánardrottni sem hægt er að taka á móti og umbreyta í innkaupareikning í [!INCLUDE[d365fin](includes/d365fin_md.md)]. Skipti rafrænna skjala á milli tveggja viðskiptafélaga er framkvæmd af ytri veitanda skjalaskiptaþjónustu. Almenn útgáfa [!INCLUDE[d365fin](includes/d365fin_md.md)] styður sendingu og móttöku rafrænna reikninga og kreditreikninga á PEPPOL-sniði, sem er stutt af stærstu skjalaskiptaþjónustukerfunum. Stór þjónustuveitandi skjalaskiptaþjónustu er forstilltur og tilbúinn til uppsetningar fyrir fyrirtækið. Til að veita stuðning fyrir aðrar rafrænar skjalasnið, þarf að stofna nýjar dagsetningar fyrir skiptiskilgreiningu í Data Exchange Framework.  

Úr PDF-skjölum eða myndaskrám sem standa fyrir skjöl á innleið er hægt að láta ytri OCR-þjónustu (sjónræn stafakennsl) stofna rafræn skjöl sem hægt er að umbreyta í skráarfærslur í [!INCLUDE[d365fin](includes/d365fin_md.md)], rétt eins og með rafræn PEPPOL-skjöl. Til dæmis Þegar reikningur berst frá lánardrottni á PDF-sniði er til dæmis hægt að senda hann til OCR-þjónustu úr glugganum **Skjöl á innleið**. Eftir nokkrar sekúndur berst skráin aftur sem rafrænn reikningur sem hægt er að breyta í innkaupareikning fyrir lánardrottin. Ef skráin er send í OCR-þjónustu með tölvupósti er ný færsla fyrir skjal á innleið sjálfkrafa stofnum þegar tekið er aftur á móti rafræna skjalinu.  

Til að senda, til dæmis, sölureikning sem rafrænt PEPPOL-skjal skal velja sem **Rafrænt skjal** valkostinn í á **Bóka og senda** svargluggi. Hér er hægt að einnig setja upp viðskiptamanns sjálfgefna skjalið sendingarsnið. Fyrst þarf að setja upp mismunandi aðalgögn, t.d. upplýsingar um fyrirtækið, viðskiptavini, atriði, og mælieiningar. Þau eru notuð til að bera kennsl á viðskiptafélaga og atriði þegar gögnum er umbreytt í reiti í [!INCLUDE[d365fin](includes/d365fin_md.md)] í einingar í skjalaskrá á útleið. Gagnaumreikningurinn og sending á PEPPOL-sölureikningum eru framkvæmdar af tilteknum kóðaeiningum og XMLports, táknað með **PEPPOL** rafræna skjalasniðinu.  

Til dæmis, til að taka á móti reikningur frá lánardrottinn sem rafrænu PEPPOL-skjali er skjalið unnið í glugganum **Skjöl á innleið** til að breyta því í innkaupareikningi í [!INCLUDE[d365fin](includes/d365fin_md.md)]. Það er annaðhvort hægt að setja upp verkraðareiginleika til að vinna reglulega úr slíkum skjölum eða hægt er að ræsa ferlið handvirkt. Fyrst þarf að setja upp mismunandi aðalgögn, t.d. upplýsingar um fyrirtækið, lánardrottna, atriði, og mælieiningar. Þau eru notuð til að bera kennsl á viðskiptafélaga og atriði þegar gögnum í einingum í skjalaskrá á innleið.er umbreytt í reiti í [!INCLUDE[d365fin](includes/d365fin_md.md)]. Móttaka og gagnaumbreyting PEPPOL-reikninga er framkvæmt af gagnaskiptaumgjörðinni sem stendur fyrir gagnaskiptaskilgreiningu **PEPPOL - Reikningur**.  

 Til að taka við, til dæmis, reikningi sem rafrænu OCR-skjali, er það meðhöndlað líkt og þegar rafrænt PEPPOL-skjal er móttekið. Móttaka og gagnaumbreyting rafrænna reikninga úr OCR er framkvæmt af gagnaskiptaumgjörðinni sem stendur fyrir gagnaskiptaskilgreiningu **PEPPOL - Reikningur**.  

## <a name="bank-files"></a>Bankaskrár  
 Skráasnið fyrir skipti bankagagna með ERP-kerfi er breytilegt eftir birgi skráarinnar og/eða landi/svæði. Almenn útgáfa [!INCLUDE[d365fin](includes/d365fin_md.md)] styður innflutning og útflutning á SEPA-bankaskrám (Single Euro Payments Area) og umskráningarþjónustu fyrir bankagögn af hálfu ytri veitanda, AMC Consult. Til að veita stuðning á öðrum rafrænu formi er notað Data Exchange Framework.  

Til að flytja út kreditfærslur SEPA skal velja hnappinn **Flytja greiðslur út í skrá** í glugganum **Greiðslubók** og hlaða svo upp skránni til að vinna úr greiðslunum í bankanum. Fyrst þarf að setja upp mismunandi aðalgögn, t.d. bankareikning, lánardrottna og greiðslumáta. Gagnaumreikningurinn og útflutningur á SEPA-bankagögnum eru framkvæmdar af þartilgerðum kóðaeiningum og XMLport, táknað með **SEPA-kreditfærsla** bankauppsetningu innflutningur/útflutningur. Að öðrum kosti er hægt að setja upp umreikningsþjónusta fyrir bankagögn og látið hana sjá um útflutninginn, táknað með **Umreikningsþjónusta bankagagna - Kreditfærslur** gagnaskiptaskilgreiningu.  

Til að flytja út leiðbeiningar fyrir SEPA-beingreiðslur skal velja hnappinn **Flytja út beingreiðsluskrá** í glugganum **Innheimta beingreiðslu** og senda hana svo í bankann til að innheimta sjálfkrafa umræddar greiðslur viðskiptamanns. Fyrst þarf að setja upp bankareikninga, lánardrottna, umboð fyrir beingreiðslu og greiðslumáta. Gagnaumreikningurinn og útflutningur á SEPA-bankagögnum eru framkvæmdar af þartilgerðum kóðaeiningum og XMLport, táknað með **SEPA-beingreiðsla** bankauppsetningu innflutningur/útflutningur.  

Til að flytja inn SEPA-bankayfirlit skal velja hnappinn Flytja inn bankayfirlit í gluggunum **Greiðsluafstemmingarbók** og **Bankareikn. Afstemming** og halda svo áfram og leggja fram hverja bankayfirlitsfærslu til greiðslu eða í fjárhagsfærslur, handvirkt eða sjálfkrafa. Fyrst þarf að setja upp bankareikninga. Innflutningur og gagnaumbreyting SEPA-bankagagna er framkvæmt af gagnaskiptaumgjörðinni sem stendur fyrir gagnaskiptaskilgreiningu **SEPA CAMT**. Að öðrum kosti er hægt að setja upp umreikningsþjónusta fyrir bankagögn og látið hana sjá um innflutninginn, táknað með **Umreikningsþjónusta bankagagna - Bankayfirlit** gagnaskiptaskilgreiningu.  

 Auk þess styðja staðbundnar útgáfur [!INCLUDE[d365fin](includes/d365fin_md.md)] ýmis önnur skráarsnið fyrir innflutning/útflutning á bankagögnum, launafærslum og öðrum gögnum. Nánari upplýsingar fást með því að skoða hjálparkaflann „Staðbundin virkni“ í útgáfu þíns lands af [!INCLUDE[d365fin](includes/d365fin_md.md)].  

## <a name="currency-exchange-rates"></a>Gengi gjaldmiðla  
Hægt er að setja upp ytri þjónusta til að gæta þess að gengi gjaldmiðils sé rétt. Þjónustan sem veitir uppfært gengi gjaldmiðils er virk af skilgreiningu gagnaskipta. Til samræmis er **Uppsetningarspjald fyrir uppfærslu gengis** glugginn samantekið yfirlit **Gagnaskiptaskilgreining** gluggans fyrir skilgreiningu gagnaskipta sem um ræðir.  

Fyrir öll gagnaskipti í XML-skrám er hægt að undirbúa gagnaskiptauppsetninguna með því að hlaða tengdum XML-skemaskrám í **XML-skemaskoðun** glugga. Hér eru fyrst valin gagnastökin sem á að skiptast á við [!INCLUDE[d365fin](includes/d365fin_md.md)] og svo skal annaðhvort hefja gagnaskiptiskilgreiningu eða mynda XMLport.  

Eftirfarandi tafla lýsir röð verkefna með tenglum í efnisatriði þar sem þeim er lýst.  

|Til|Sjá|  
|--------|---------|  
|Lesið um hvernig gagnaskiptaramminn virkar.|[Um gagnaskiptaramma](across-about-the-data-exchange-framework.md)|  
|Undirbúa gagnaskipti í skjali með því að endnýta XML-skema skrárinnar. Setja upp skilgreiningar gagnaskipta. Setja upp aðalgögn fyrir sendingu rafræns skjals. Setja upp mismunandi innflutnings/útflutningsreiti bakna.|[Setja upp gagnaskipti](across-set-up-data-exchange.md)|  
|Sendið PEPPOL-reikninga, takið við PEPPOL-reikningum, flytjið inn bankayfirlit og flytjið út bankagreiðsluskrár sem byggjast á gagnaskiptaskilgreiningum.|[Gagnaskipti](across-exchange-data.md)|  

## <a name="see-also"></a>Sjá einnig  
[Um gagnaskiptaramma](across-about-the-data-exchange-framework.md)  
[Hvernig á að. Nota XML-skema til að undirbúa skilgreiningar gagnaskipta](across-how-to-use-xml-schemas-to-prepare-data-exchange-definitions.md)  
[Setja upp gagnaskipti](across-set-up-data-exchange.md)  
[Gagnaskipti](across-exchange-data.md)  
[Skjöl á innleið](across-income-documents.md)  
[Almenn viðskiptavirkni](ui-across-business-areas.md)

