---
title: "Nota innkaupakreditreikninga til að vinna skil eða afturkallanir"
description: "Útskýrir hvernig á að stofna og bóka innkaupakreditreikning þegar þú vilt skila vörum til lánardrottins eða afturkalla keypta þjónustu."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: cancel, undo, correct
ms.date: 08/03/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 3f0c187e2cd2520854fe69f3896f6d7311cdc2da
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-process-purchase-returns-or-cancellations"></a>Meðhöndlun innkaupaskila eða afturkallana
Ef skila á vörum til lánardrottins eða afturkalla þjónustu sem hefur verið keypt, er hægt að búa til og bóka kreditreikning sem tilgreinir breytingarnar sem óskað er eftir vegna hins upphaflega innkaupareiknings. Til að taka réttar innkaupareikningsupplýsingar með, er hægt að stofna innkaupakreditreikning beint úr bókaða innkaupareikningnum eða þú getur stofnað nýja innkaupakreditreikning með afrituðum reikningsupplýsingum.

Ef þú þarft meiri stjórn á innkaupaskilaferlinu, eins og t.d. vöruhúsaskjöl fyrir vöruafgreiðsluna eða betra yfirlit yfir móttöku vöruskila frá mörgum innkaupaskjölum með einum vöruskilum, geturðu stofnað vöruskilapöntun innkaupa. Vöruskilapöntun innkaupa gefur sjálfkrafa út tengda innkaupakreditreikninginn. Frekari upplýsingar, sjá hlutann „Stofna vöruskilapöntun innkaupa byggða á einu eða fleiri bókuðu innkaupaskjali“.

> [!NOTE]  
>   Ef bókaður innkaupareikningur hefur ekki verið greiddur er hægt að nota aðgerðirnar **Leiðrétta** eða **Afturkalla** á bókuðu innkaupareikningnum til að afturkalla umræddar færslur. Þessir eiginleikar virka aðeins fyrir ógreidda reikninga og styðja ekki vöruskil að hluta eða afturkallanir. Nánari upplýsingar er að finna [hvernig á að: ógreiddir innkaupareikningar leiðréttir eða afturkallaðir](purchasing-how-correct-cancel-unpaid-purchase-invoices.md)

Venjulega, getur þú búið til innkaupakreditreikning eða vöruskilapöntun innkaupa sem svar við kreditreikningur sem lánardrottinn sendir þér. Innkaupakreditreikningurinn eða vöruskilapöntun innkaupa virkar eins og innra fylgiskjal fyrir bókahaldið um kreditreikningsferlið eða til að stjórna afhendingu varanna sem um ræðir.

Breytingin gæti tengst öllum vörunum á hinum upphaflega innkaupareikningi eða aðeins sumum varanna. Hægt er að skila mótteknum vörum að hluta, eða fara fram á endurgreiðslu að hluta af móttekinni þjónustu. Í því tilfelli, er nauðsynlegt að breyta upplýsingunum um innkaupakreditreikninginn eða vöruskilapöntun innkaupa.

Auk upprunalega bókaðan innkaupareikning, er hægt að jafna innkaupakreditreikning eða vöruskilapöntun innkaupa við öðrum innkaupaskjölum, t.d. aðra bókaður innkaupareikningur, Því þú ert einnig að skila vörum sem voru afhentar með viðkomandi reikningur.

Bókun innkaupareiknings mun einnig snúa við öllum kostnaðarauka sem var úthlutað á bókaða skjalið, þannig að vöruvirðisfærslurnar eru þær sömu og áður en kostnaðaraukanum var úthlutað.

## <a name="inventory-costing"></a>Birgðakostnaður
Til að varðveita rétt birgðaverðmat, eru vanalega teknar til skilavörur frá birgðum á því kostnaðarverði sem þær voru keyptar á, en ekki núgildandi kostnaðarverði. Þetta er kallað nákvæm bakfærsla kostnaðar.

Til er tvenns konar virkni, til að úthluta bakfærslu nákvæms kostnaðar sjálfvirkt:  

|Virkni|Description|  
|------------------|---------------------------------------|  
|**Sækja bókaðar fylgiskjalalínur til að bakfæra** aðgerð í **vöruskilapöntun innkaupa** glugganum.|Afritar línur úr einu eða fleiri bókuðum fylgiskjölum sem á að bakfæra til vöruskilapöntun innkaupa. Frekari upplýsingar, sjá hlutann „Stofna vöruskilapöntun innkaupa og tengdan sölukreditreikning, fyrir einn eða fleiri bókuðu innkaupareikningi“.|  
|**Afrita skjal** aðgerð í **Innkaupakreditreikningur** og **Vöruskilapöntun innkaupa** glugganum.|Afritar bæði haus og línur af einu bókuðu fylgiskjali sem á að bakfæra.<br /><br /> Krefst þess að **Nákvæm bakfærsla kostnaðar** gátreitur sé valinn í glugganum **Uppsetning fyrir Innkaup & Viðskiptaskuldir**.|

Til að úthluta nákvæmri bakfærslu kostnaðar, skal velja reitinn **Jafna frá birgðafærslu** á einhverja gerð skilaskjalslínu, og velja síðan númer upphaflega innkaupafærslunnar. Það tengir innkaupakreditreikning eða vöruskilapöntun innkaupa við upphaflega innkaupafærslu og tryggir að varan sé metin út frá upphaflegu einingarverði.

Nánari upplýsingar, sjá [Upplýsingar um hönnun: Birgðakostnaður](design-details-inventory-costing.md)

## <a name="to-create-a-purchase-credit-memo-from-a-posted-purchase-invoice"></a>Stofna nýjan innkaupakreditreikning úr bókaðan innkaupareikningur.
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **bókaðir innkaupareikningar** og velja svo viðeigandi tengil.  
2. Í gluggann **Bókaðir innkaupareikningar** og veldu bókaða innkaupareikninginn sem á að bakfæra og veldu svo stofna aðgerðina **stofna leiðréttandi kkreditreikning**

    Flestir reitir á innkaupakreditreikningshausnum eru nú fylltir út með upplýsingum úr bókaður innkaupareikningur Hægt er að breyta allir reitir, til dæmis með nýjar upplýsingar sem endurspegla endursenda samkomulagið.
3. Breyta upplýsingum í línunum í samræmi við samninginn, eins og fjöldi þeirra vara sem skilað er eða upphæð sem á að endurgreiða.
4. Valið er **Jafna Færslur** aðgerð.
5. Í **Jafna Lánardr.færslur** glugganum, velja línan með bókaða innkaupaskjalið sem á að jafna við innkaup sölukreditreikning innkaupakreditreikning á og velja síðan aðgerðina **Jöfnunarkenni**. Númer innkaupakreditreikningsins er sett í reitinn **jöfnunarkenni**
6. Í reitnum  **Upphæð til jöfnunar** er rituð upphæðin sem á að jafna ef hún er lægri en upprunalega upphæðin.

    Neðst á **Jafna Lánardr.færslur** glugganum, er hægt að skoða heildarupphæðin sem á að nota til að bakfæra allar viðkomandi færslur, nefnilega þegar gildið í **Stöðu** reitnum er núll.
7. Velja hnappinn **Í lagi**. Þegar innkaupakreditreikningurinn er bókaður, verður hann jafnaður við tilgreinda bókaða innkaupaskjölin

    Þegar stofnaðar eða breyttar hafa verið línur fyrir innkaupakreditreikninga og ein eða fleiri jöfnun hefur verið tilgreind, er hægt að fara í að bóka innkaupakreditreikninginn.
8. Valið er **bóka** aðgerð.

Bókuðu innkaupareikningarnir sem jafnaðir eru við kreditreikninginn eru nú bakfærðir. Ef þegar upprunalegi reikningurinn hefur þegar verið greiddur ætti lánardrottinn nú að endurgreiða greiðsluna. Ef kreditreikningurinn er aðeins fyrir hluta afurðarinnar á upprunalega reikningnum geturðu aðeins greitt eftirstandandi upphæð á upprunalega innkaupareikningnum til að loka honum.

Innkaupakreditreikningurinn er fjarlægður og skipt út fyrir nýtt fylgiskjal á lista bókaðra innkaupakreditreikninga.

## <a name="to-create-a-purchase-credit-memo-by-copying-a-posted-purchase-invoice"></a>Til að stofna nýjan innkaupakreditreikning með því að afrita bókaðan innkaupareikningur.
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Innkaupakreditreikningar** og velja svo viðeigandi tengil.
2. Valið er **Nýtt** aðgerð til að opna ný auður innkaupakreditreikningur.
3. Í reitnum **lánardrottins** er fært inn nafn núverandi lánardrottins.
4. Valið er **Afrita fylgiskjal** aðgerð.
5. Í glugganum **afrita innkaupaskjal** í **Gerð fylgiskjals** velurðu **Bókaður reikningur**.
6. Velja reitinn **Númer fylgiskjals** til að opna gluggann **Bókaðir innkaupareikningar** og velja síðan bókaða innkaupareikninginn sem inniheldur línur sem á að bakfæra.
7. Veljið gátreitinn **Endurreikna línur**, ef bókaða innkaupakreditreikningslínan sem var afrituð á að uppfærast með breytingum á vöruverði og kostnaðarverði síðan reikningurinn var bókaður.
8. Velja hnappinn **Í lagi**. Afrituðu reikningslínurnar eru settar inn í innkaupakreditreikninginn.
9. Ljúktu Innkaupakreditreikningur eins og útskýrt er í reitnum "Stofna nýjan innkaupakreditreikning úr bókaðan innkaupareikningur" hlutanum í þessu efnisatriði.

## <a name="to-create-a-purchase-return-order-based-on-one-or-more-a-posted-purchase-documents"></a>Til að stofna vöruskilapöntun innkaupa byggða á einu eða fleiri bókuðu innkaupaskjali.
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Vöruskilapöntun innkaupa** og velja svo viðeigandi tengil.  
2. Valið er **Nýtt** aðgerð.  
3. Fyllt er út í reitina á flýtiflipanum **Almennt** eftir þörfum.
4. Á flýtiflipanum **Línur** skal fylla þessar línur út handvirkt, eða afrita upplýsingar úr öðrum fylgiskjölum til að fylla út línurnar sjálfvirkt:

    - Hægt er að nota aðgerðina **Sækja bókaðar fylgiskjalalínur til að bakfæra** til að afrita eina eða fleiri bókaðar fylgiskjalalínur frá einu eða fleiri bókuðum fylgiskjölum. Þessi aðgerð bakfærir alltaf nákvæmlega kostnaðinn úr bókuðu fylgiskjalslínunni. Þessu aðgerð er lýst í eftirfarandi skrefum.    
    - Nota aðgerðina **Afrita skjal** til að afrita fyrirliggjandi fylgiskjal í vöruskilapöntun. Þessi aðgerð er notuð til að afrita allt fylgiskjalið. Það er annað hvort bókað fylgiskjal eða fylgiskjal sem hefur ekki enn verið bókað. Þessi aðgerð gerir aðeins kleift að bakfæra kostnað á nákvæman hátt þegar **Nákvæm bakfærsla kostnaða áskilin** gátreiturinn er valinn í glugganum **Uppsetning fyrir Sölu & Útistandandi**.  

4. Velja aðgerðina **Sækja bókaðar fylgiskjalalínur til að bakfæra**.
5. Efst í glugganum **Bókaðar línur innkaupaskjals** er valið gátmerki **Sýna eingöngu bakfæranlegar línur** ef eingöngu á að birta línur sem eru með magn sem enn hefur ekki verið skilað. Til dæmis ef bókað magn innkaupareiknings hefur verið skilað kann ekki að vera æskilegt að skila magninu í nýtt fylgiskjal vöruskila innkaupa.

    > [!NOTE]  
    >  Þessi reitur virkar eingöngu fyrir bókaðar móttökur og bókaðar reikningslínur, ekki fyrir bókuð vöruskil eða bókaðar kreditreikningslínur.  

    Vinstra megin í glugganum er ólík tegund fylgiskjals og númerið í sviga sýnir númer skjalsins af tiltekinni tegund sem er til taks.

6. Í reitnum **Afmörkun fylgiskjalsgerðar** skal velja tegund bókaðra lína fylgiskjals sem nota skal.  
7. Velja skal línurnar sem á að afrita í nýja fylgiskjalið.  

    > [!NOTE]  
    >  Ef Ctrl+A er notað til að velja allar línur eru allar línur afritaðar innan afmörkunarinnar sem er virk en hundsar afmörkunina **Sýna eingöngu bakfært magn**. Til dæmis er búið að afmarka línurnar við tiltekið fylgiskjalsnúmer með tveimur línu, og búið er að skila annarri. Jafnvel þótt gátreiturinn **Sýna eingöngu bakfært magn** sé valinn afritar forritið eingöngu tvær línur þegar ýtt er á Ctrl+A til að afrita báðar línur, í stað þess að afrita eingöngu þá línu sem ekki hefur verið bakfærð.  

8. Veldu hnappinn **Í lagi** ef afrita á línurnar í nýja skjalið.  

    Eftirfarandi ferli fara fram:  

    -   Fyrir bókaðar fylgiskjalslínur af tegundinni **Vara** er ný fylgiskjalslína stofnuð sem er afrit af bókuðu fylgiskjalslínunni með magni sem ekki hefur verið bakfært. Fyllt er inn í **jafna við birgðafærslu** svæðið, fyrir innkaupaskjöl, eins og við á, með færslunúmeri birgðahöfuðbókar bókaðrar skjalslínu.  

    -   Fyrir bókaðar fylgiskjalslínur sem eru ekki af tegundinni **Vara** t.d. kostnaðarauki er ný fylgiskjalslína stofnuð sem er afrit af upphaflegu bókuðu fylgiskjalslínunni.  

    -   Reiknar reitinn **Kostn.verð (SGM)** í nýju línunni úr kostnaði í samsvarandi birgðafærslu.  

    -   Ef afritaða fylgiskjalið er bókuð afhending, bókuð móttaka, bókuð vöruskilamóttaka eða bókuð vöruskilaafhending er kostnaðarverðið úr birgðaspjaldinu reiknað sjálfkrafa.  

    -   Ef bókaða fylgiskjalið er bókaður reikningur eða kreditreikningur er kostnaðarverðið, reikningsafsláttur og línuafsláttur afritað úr bókuðu fylgiskjalslínunni.  

    -   Ef bókaða fylgiskjalslínan inniheldur vörurakningarlínu er reiturinn **Jafna við birgðafærslu** í vörurakningarlínunni fylltur með viðeigandi birgðafærslunúmerum úr bókuðu vörurakningarlínunum.  

     Þegar bókaður reikningur eða bókaður kreditreikningur er afritaður afritar kerfið viðeigandi reikningsafslætti og línuafslætti sem gilda við bókun fylgiskjalsins úr bókuðu fylgiskjalslínunni í nýju fylgiskjalslínunni. Hins vegar þarf að hafa í huga að ef valkosturinn **Reikna reikn.afsl.** er ræstur í **Uppsetning Innkaup & viðskiptaskuldir** glugganum, er reikningsafslátturinn nýreiknaður þegar nýja fylgiskjalslínan er bókuð. Þess vegna getur verið að línuupphæðin fyrir nýju línuna sé önnur en línuupphæðin fyrir bókuðu fylgiskjalslínuna, allt eftir nýja útreikningnum á reikningsafslættinum.  

    > [!NOTE]  
    >  Ef hluti magns bókuðu fylgiskjalslínunnar hefur þegar verið bakfært eða selt eða notað, er eingöngu stofnuð lína fyrir magnið sem eftir er í birgðum eða sem ekki hefur verið skilað. Ef búið er að bakfæra allt magn í bókaðri fylgiskjalslínu er ný fylgiskjalslína ekki stofnuð.  
    >   
    >  Ef flæði vara í bókuðu fylgiskjali er það sama og flæði vara í nýja fylgiskjalinu er einfaldlega stofnað afrit af upphaflegu bókuðu fylgiskjalslínunni í nýja fylgiskjalinu. Ekki er fyllt út í reitinn **Jafna frá birgðafærslu** vegna þess að bakfærsla nákvæms kostnaðar er ekki möguleg í þessu tilviki. Ef aðgerðin **Sækja bókaðar fylgiskjalalínur til að bakfæra** er t.d. notuð til að sækja bókaða innkaupakreditreikningalínu fyrir nýjan innkaupakreditreikning er eingöngu upphaflega bókaða kreditreikningslínan afrituð í nýja kreditreikninginn.  

8. Í glugganum **Vöruskilapöntun innkaupa** í reitnum **Ástæðukóði skila** á hverri línu, skal velja ástæðu skilanna.
9. Valið er **Bóka** aðgerðin.

## <a name="to-create-a-replacement-purchase-order-from-a-purchase-return-order"></a>Innkaupapöntun fyrir skiptivöru stofnuð úr vöruskilapöntun innkaupa.
Samkomulag kann að takast við lánardrottininn um bætur vegna keyptrar vöru með því að skipta henni. Um sömu vöru getur verið að ræða, eða eitthvað annað. Þessi staða getur komið upp ef lánardrottinn hefur sent ranga vöru.  
1.  Í glugganum **Vöruskilapöntun innkaupa** fyrir virkt skilaferli, er í auðri línu búin til neikvæð færsla vegna skiptivörunnar með því að færa inn neikvætt magn í reitinn **Magn**.  
2. Velja aðgerðina **Flytja neikvæðar línur**.  
3. Í glugganum **Flutningur Neikvætt sölulínur** skal fylla út reitina eins og þörf krefur.
4. Velja hnappinn **Í lagi**. Neikvæðri línu eytt úr vöruskilapöntun innkaupa og ný innkaupapöntun stofnuð. Nánari upplýsingar eru í [Hvernig á að: Skrá innkaup](purchasing-how-record-purchases.md).  

## <a name="to-create-a-purchase-allowance"></a>Innkaupaheimild stofnuð:  
Ef rangar vörur berast frá lánardrottni t.d. ef þær eru eitthvað skemmdar, í röngum lit eða af rangri stærð er hugsanlegt að lánardrottininn bjóði innkaupauppbót.  

Hægt er að bóka þetta lægra innkaupaverð sem kostnaðarauka á kreditreikningi eða vöruskilapöntun og tengja það bókuðu móttökunni. Eftirfarandi lýsir því fyrir vöruskilapöntun innkaupa, en sömu skref eiga við um innkaupakreditreikning.

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Innkaupakreditreikningar** og velja svo viðeigandi tengil.
2. Valið er **Nýtt** aðgerð til að opna ný auður innkaupakreditreikningur.  
3.  Upplýsingar um lánardrottininn sem sendi innkaupauppbótina eru færðar í kreditreikningshausinn.  
4. Á flýtiflipanum **Línur** í reitnum **Tegund** er valin **Gjald (vara)**.  
5.  Í reitnum **númer** er valið viðeigandi vörugjaldsnúmer.  

    Gott gæti verið að stofna sérstakt vörugjaldsnúmer fyrir innkaupauppbætur.  
6.  Fært er inn **1** í reitinn **Magn**.  
7.  Í reitinn **Innk.verð** er upphæð innkaupauppbótarinnar færð inn.  
8.  Innkaupauppbótinni er  úthlutað sem vörugjaldi á vörurnar í bókuðu móttökunni. Frekari upplýsingar, sjá [Hvernig skal: Nota kostnaðarauka til að gera grein fyrir viðbótar viðskiptakostnaði](payables-how-assign-item-charges.md). Þegar uppbótinni hefur verið úthlutað er snúið aftur í gluggann **innkaupakreditreikningur**.

Þegar vöruskilapöntun innkaupa er bókuð er söluafslætti bætt við viðkomandi upphæð innkaupafærslu. Þannig er hægt að vinna með nákvæmt birgðaverðmat.  

## <a name="to-combine-return-shipments"></a>Sameining endursendra afhendinga:  
Ef skila á vörum sem eru í mismunandi innkaupapöntunum til eins lánardrottins er hægt að nota aðgerðina **Sameina skilaafhendingar**.  

Þegar vörurnar eru sendar þarf að bóka tengdar innkaupaskilapantanir sem sendar, og þannig stofna bókaðar innkaupaskilapantanir.  

Þegar kemur að því að reikningsfæra vörurnar er hægt að stofna innkaupakreditreikning og afrita sjálfkrafa bókaðar innkaupaskilasendingarlínur í skjalið, í stað þess að reikningsfæra hverja innkaupaskilapöntun sérstaklega. Þá má bóka innkaupakreditreikning og reikningsfæra allar opnar vöruskilapantanir innkaupa á sama tíma.  

Þegar vöruskilaafhendingar eru sameinaðar á kreditreikningi og bókfærðar stofnast Bókaður innkaupakreditreikn. fyrir reikningsfærðu línurnar. Reiturinn **Reikningsfært magn** á upprunalegri vöruskilapöntun innkaupa er uppfærður á grundvelli reikningsfærða magnsins. Hins vegar er upprunalegri vöruskilapöntun innkaupa ekki eytt jafnvel þó hún hafi verið móttekin og reikningsfærð að fullu og því verður að eyða þeirri vöruskilapöntun innkaupa handvirkt.

> [!NOTE]  
> Þessi aðferð gerir ráð fyrir því að til séu margar innkaupaskilapantanir fyrir lánardrottinn og að þær séu bókaðar sem sendar.     

1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Innkaupakreditreikningar** og velja svo viðeigandi tengil.  
2.  Valið er **Nýtt** aðgerð.  
3. Fyllt er út í reiti eftir því sem er nauðsynlegt í flýtiflipanum **Almennt**.  
4. Velja aðgerðina **Sækja vöruskilaafhendingarlínur**.  
5.  Nokkrar skilaafhendingarlínur eru valdar sem eiga að vera á reikningnum:  

    Ef röng vöruskilaafhendingarlína er valin eða ef byrja á upp á nýtt má einfaldlega eyða línunum á innkaupakreditreikningnum og síðan nota aftur aðgerðina **Sækja skilaafhend.línur**.  
6.  Valið er **Bóka** aðgerðin.  

### <a name="to-remove-open-purchase-return-orders-after-combined-return-shipment-posting"></a>Til að fjarlægja opnar vöruskilapantanir innkaupa eftir bókun sameinaðrar afhendingar  

1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Eyða reikningsfærðum vöruskilapöntun innkaupa** og velja svo viðeigandi tengil.  
2.  Fyllið út aðra reitina að þörfum og smellið veljið síðan hnappinn **Í lagi**.  
3.  Að öðrum kosti skal eyða einstökum vöruskilapöntunum innkaupa handvirkt.

## <a name="see-also"></a>Sjá einnig
[Innkaup](purchasing-manage-purchasing.md)  
[Hvernig á að skrá kaup](purchasing-how-record-purchases.md)  
[Hvernig á að: Hvernig á að: Leiðrétta eða afturkalla ógreidda innkaupareikninga](purchasing-how-correct-cancel-unpaid-purchase-invoices.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

