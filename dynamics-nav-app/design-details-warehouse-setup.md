---
title: "Hönnunarupplýsingar - uppsetning vöruhúss"
description: "Vöruhúsavirkni í [!INCLUDE[d365fin](includes/d365fin_md.md)] inniheldur mismunandi flækjustig, eins og skilgreint með leyfisheimildum í eindum í boði. Flækjustig vöruhússlausnar er einkum skilgreint með hólfauppsetningu á staðsetningarspjöldum, sem aftur eru leyfisstýrð, svo að aðgangur að hólfauppsetningarreitum ræðst að leyfinu."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/29/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 16090e2f12d1b6052fc330b93e4c9466de8e8577
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-warehouse-setup"></a>Hönnunarupplýsingar uppsetningvöruhúss
Vöruhúsavirkni í [!INCLUDE[d365fin](includes/d365fin_md.md)] inniheldur mismunandi flækjustig, eins og skilgreint með leyfisheimildum í eindum í boði. Flækjustig vöruhússlausnar er einkum skilgreint með hólfauppsetningu á staðsetningarspjöldum, sem aftur eru leyfisstýrð, svo að aðgangur að hólfauppsetningarreitum ræðst að leyfinu. Að auki, forritshlutir í leyfinu stjórna hvaða notandaviðmótskjal til að nota fyrir studda vörugeymsla starfsemi.  

Eftirfarandi vöruhússtengdu eindir eru til:  

-   Grunnbirgðir (4010)  
-   Hólf (4170)  
-   Frágangur (4180)  
-   Vöruhúsamóttaka (4190)  
-   Taka til (4200)  
-   Vöruhúsaafhending (4210)  
-   Vöruhúsastjórnunarkerfi (4620)  
-   Innri tínslur og frágangur (4630)  
-   Sjálfvirkt gagnatökukerfi (4640)  
-   Uppsetning hólfs (4660)  

Nánari upplýsingar um hverja einingu eru á [[!INCLUDE[d365fin](includes/d365fin_md.md)] Verðblöð](http://go.microsoft.com/fwlink/?LinkId=238341) (ViðskiptafélagiUppruni Reikningur nauðsynlegur).  

Eftirfarandi tafla sýnir hvaða eininga er krafist til að skilgreina mismunandi vöruhúsaflækjustig, hvaða viðmótsskjöl styðja hvaða stig og hvaða staðsetningarkóðar endurspegla þessi stig í [!INCLUDE[d365fin](includes/d365fin_md.md)] sýnigagnagrunninum.  

|Flækjustig|Description|Notendaviðmótsskjal|CRONUS birgðageymsla|Lágmarksþörf einda|  
|----------------------|---------------------------------------|-----------------|---------------------------------|---------------------------------|  
|0|Engin sérstök vöruhúsaaðgerð.<br /><br /> Bókun móttöku/afhendingar úr pöntunum.|Röð|BLÁTT|Grunnbirgðir|  
|2|Engin sérstök vöruhúsaaðgerð.<br /><br /> Bókun móttöku/afhendingar úr pöntunum.<br /><br /> Hólfkóði er áskilið.|Pöntun, með hólfkóða|SILFRAÐ|Grunnbirgðir/hólf|  
|3 <br /><br /> **Athugið**: Jafnvel þótt stillingarnar séu kallaðar **Krefjast tínslu** og **Krefjast frágangs**, geturðu samt sem áður bókað móttöku og afhendingu beint frá uppruna viðskiptaskjala í birgðageymslum þar sem þú velur þessa gátreiti.|Grunnvöruhúsastarfsemi, pöntun fyrir pöntun.<br /><br /> Bókun móttöku/afhendingar úr birgðafrágangi/tínsluskjölum. <br /><br /> Hólfkóði er áskilið.|Birgðafrágangur(birgðahreyfing/birgðatínsla með hólfkóða|(Silfrað + Þarf að ganga frá eða tína)|Grunnbirgðir/hólf/Frágangur/Tiltekt|  
|4|Ítarlegar vöruhúsaaðgerðir, fyrir margar pantanir.<br /><br /> Samsett bókun taka við/senda byggð á skráningum í vöruhúsi frágangur/tiltekt.|Vöruhúsamóttaka/vöruhúsafrágangur/vöruhúsatiltekt/vöruhúsaafhending/tiltektarvinnublað|GRÆNT|Grunnbirgðir/vöruhúsamóttaka/Frágangur/Taka til/vöruhúsaafhending|  
|5|Ítarlegar vöruhúsaaðgerðir, fyrir margar pantanir.<br /><br /> Samsett bókun taka við/senda byggð á skráningum í vöruhúsi frágangur/tiltekt.<br /><br /> Hólfkóði er áskilið.|Vöruhúsamóttaka/vöruhúsafrágangur/vöruhúsatiltekt/vöruhúsaafhending/tiltektarvinnublað/frágangsvinnublað, með hólfkóða|(GRÆNT + Hólf áskilið)|Grunnbirgðir / Hólf / vöruhúsamóttaka / Frágangur / Tiltekt / vöruhúsaafhending|  
|6 <br /><br /> **Athugið**: Þetta stig er kallað „WMS“ þar sem það krefst ítarlegustu eindarinnar, Vöruhúsakerfisins.|Ítarlegar vöruhúsaaðgerðir, fyrir margar pantanir.<br /><br /> Samsett bókun taka við/senda byggð á skráningum í vöruhúsi frágangur/tiltekt.<br /><br /> Hólfkóði er áskilið.<br /><br /> Svæðis- eða flokkakóði er valfrjáls.<br /><br /> Starfsmenn í vöruhúsi stjórnað af verkflæði.<br /><br /> Áætlun áfyllingar hólfs<br /><br /> Hólfaflokkun<br /><br /> Uppsetning hólfs eftir getu.<br /><br /> Niðurröðun.<br /><br /> Samþætting við handtæki|Vöruhúsamóttaka/vöruhúsafrágangur/vöruhúsatiltekt/vöruhúsaafhending/vöruhúsahreyfing/tiltektarvinnublað/frágangsvinnublað/ vöruhúsatiltekt Innanhúss/vöruhúsafrágangur innanhúss, með hólfa/flokk/svæðiskóða<br /><br /> Ýmsar vinnublöð fyrir hólfastjórnun<br /><br /> ADCS-skjáir|HVÍTT|Grunnbirgðir / Hófl / Frágangur / vöruhúsamóttaka / Tiltekt / Vöruhúsasending / Vöruhúsastjórnkerfi / Innri tiltekt og frágangur /Hófaskipulag / Gagnatökukerfi sjálfvirkrar dagsetningar / Hólfauppsetning|  

Dæmi um hvernig notandaviðmótsskjölunum er beitt á vöruhúsaflækjustig eru í [Hönnunarupplýsingar: Vöruhúsaflæði á innleið](design-details-outbound-warehouse-flow.md).  

## <a name="bin-and-bin-content"></a>Hólf og Innihald hólfs  
Hólf er geymslutæki sem hannað fyrir geymslu tiltekinna hluta. Það er minnsta geymslueiningin í [!INCLUDE[d365fin](includes/d365fin_md.md)]. Vörumagn í hólfum er kallað innihald hólfs. Uppfletting í reitnum **Vara** eða reitnum **Hólfakóði** á vöruhúsatengdri skjalalínu sýnir reiknað framboð vöru í hólfi.  

Innhaldi hólfs er hægt að veita eiginleikann Fast, Sérstakt eða Sjálfgefið til að tilgreina hvernig innihald hólfsins verður notað. Vísað er í hólf með ekkert af þessu sem fljótandi hólf.  

Fast hólf inniheldur hluti sem er úthlutað á viðkomandi hólfkóða. Eiginleikinn Fast hólf tryggir að jafnvel þótt hólf sé tæmt um í augnablik hverfur innihaldið ekki og hólfið er því valið aftur um leið og það hefur verið endurnýjað.  

Sérstakt hólf innheldur innihald hólfs sem aðeins er hægt að tína fyrir tiltekinn forða, svo sem vélastöð, sem notar viðkomandi hólf. Annað efni sem ekki er tínt, svo sem magn á útleið í afhendingarbókun, er enn hægt að nota úr sérstöku hólfi. Aðeins innihald hólfs sem notað er í reiknireglunni **Stofna tínslu** er varið í sérstöku hólfi.  

Sjálfgefinn hólfaeiginleiki er notuð af kerfinu til að benda á hólf fyrir vöruhúsaaðgerðir. Á WMS-staðsetningum er sjálfgefið hólf ekki notuð. Í birgðageymslum þar sem hólfa er krafist er eigning notuð í innflæði til að tilgreina hvar á að setja vörur. Í flæði á útleið er eiginleikinn notaður til að tilgreina hvar á að taka vörur.  

> [!NOTE]  
>  Ef vörur á útleið eru settar í nokkur hólf eru vörurnar fyrst teknar úr hólfunum sem eru ekki sjálfgefin, til að tæma það innihald hólfa, og svo eru vörurnar sem eftir eru teknar úr sjálfgefna hólfinu.  

Aðeins er hægt að hafa eitt hólf fyrir hverja staðsetningu.  

## <a name="bin-type"></a>Tegund hólfs  
Í vöruhúsauppsetningum getur þú takmarka vöruhúsaaðgerðir sem eru leyfðar fyrir hólf með því að úthluta tegund hólfs á það. Eftirfarandi hólfagerðir eru til:  

|Tegund hólfs|Description|  
|------------------|---------------------------------------|  
|MÓTTAKA|Vörur sem skráðar eru sem mótteknar en sem ekki hefur verið gengið frá.|  
|AFH|Vörur sem tíndar hafa verið fyrir vöruhúsaafhendingarlínur en ekki verið bókaðar sem afhendar.|  
|PUT AWAY|Yfirleitt vörur sem geyma á í stórum einingum en sem kerfið á ekki að hafa aðgang að vegna tínslu. Þar sem hólfin eru ekki notuð til tínslu, hvort sem um er að ræða framleiðslupantanir eða afhendingar, getur notkun frágangshólfa verið takmörkuð en þau geta komið sér vel ef keypt hefur verið inn mikið af vörum. Hólf af þessari tegund ætti alltaf að flokka lágt þannig að þegar gengið er frá mótteknum vörum sé fyrst gengið frá öðrum hærra flokkuðum PUTPICK-hólfum sem fest eru við vöruna. Ef þessi tegund hólfs er notuð þarf að enduráfylla hólf reglulega svo að vörur sem þar eru geymdar séu einnig tiltækar í PUTPICK- og PICK-hólfum.|  
|PICK|Vörur sem aðeins eru notaðar í tínslu. Áfylling þessara hólfa getur aðeins farið fram með hreyfingu, ekki með frágangi.|  
|PUTPICK|Vörur í hólfum sem eru lagðar til fyrir bæði frágang og tínsluaðgerðir. Hólf af þessari tegund eru líklega með mismunandi hólfaflokkun. Hægt er að setja upp magngeymsluhólf með þessa hólfategund með lága hólfaflokkun samanborið við venjuleg tínsluhólf eða framtíðartínslusvæðishólf.|  
|QC|Þetta hólf er notað fyrir birgðaleiðréttingar ef þetta hólf er tilgreind á birgðageymsluspjaldinu í reitnum **Leiðréttingahólfskóði**. Einnig er hægt að setja upp hólf af þessari tegund fyrir gallaðar vörur og vörur sem teknar eru til skoðunar. Hægt er að flytja vörur í hólf af þessari tegund ef þær eiga ekki að vera tiltækar í venjulegu vöruflæði. **Athugið:** Ólíkt öllum öðrum gerðum hólfa hefur hólfategundin **GE** enga vörumeðhöndlunargátreiti valda að sjálfgefnu. Þetta tilgreinir að allt innihald sem sett er í QC-hólf er ekki haft með í vöruflæði.|  

Fyrir allar hólfagerðir nema PICK, PUTPICK og PUTAWAY er engin önnur aðgerð leyfileg fyrir hólfið en skilgreint er í hólfagerðinni. Til dæmis er aðeins hægt að nota hólf af gerðinni **Móttaka** til að taka á móti vörum í eða taka vörur úr.  

> [!NOTE]  
>  Aðeins er leyfð hreyfing í hólf af gerðinni MÓTTAKA og GÆÐAEFTIRLIT. Á sama hátt, er aðeins hægt að gera hreyfingar úr hólfum af gerðinni afhending og gæðaeftirlit.  

## <a name="bin-ranking"></a>Hólfaflokkun  
Í háþróaður vörugeymsla, getur þú sjálfvirkan og hagræða hvernig vörur eru innheimt í frágangs og tínsluvinnublöðum með því að raða hólfum svo vörur eru lagðar til sem teknar eða staðsettar samkvæmt röðunarskilyrðum til að nota vöruhúsaplássið sem best.  

Frágangsferlar eru fínstilltir samkvæmt hólfaflokkun með því að stinga upp á hærra skráðum hólfum á undan lægra skráðum. Á sama hátt eru tínsluferlar fínstilltir með því að stinga fyrst upp á vörum úr hólfum með háa hólfaflokkun. Enn fremur er stungið upp á hólfaáfyllingu frá lægri stigs hólfum til hærri stigs hólfa.  

Hólfaflokkun ásamt innihald hólfs eru grunneiginleikar sem leyfa notendum að taka frá atriði í vöruhúsi.  

## <a name="bin-setup"></a>Uppsetning hólfs  
Í vöruhúsauppsetningum geta hólf verið hægt að setja upp með afkastagetugildum svo sem magni, samtals rými og þyngd til að stjórna hvaða og hvernig vörur eru geymdar í hólfinu.  

Á hverju birgðaspjaldi er hægt að úthluta mælieiningu fyrir vöruna, svo sem stykkjum, vörubrettum, lítrum, grömmum eða kössum. Einnig er hægt að nota grunnmælieiningu fyrir vöru og tilgreina stærri grunnmælieiningu sem byggist á vörunni. Til dæmis er hægt að skilgreina bretti sem jafnt og 16 stykki, og hið síðarnefnda er þá grunnmælieining.  

Ef stilla á hámarksmagn af tiltekinni vöru sem á að geyma í sérstöku hólfi og varan er með fleiri en eina mælieiningu verður að stilla hámarksmagn fyrir hverja mælieiningu sem er á birgðaspjaldinu. Í samræmi, ef vara hefur verið sett upp fyrir meðhöndlun í stykkjum og á vörubrettum þarf reiturinn **Hámarks magn** í glugganum **Innihald hólfs** fyrir þá vöru einnig að vera í stykkjum og vörubrettum. Annars er leyft magn fyrir það hólf er ekki reiknað rétt.  

Áður en þú setur afkastahömlur á innihald hólfs í hólfi, verður þú fyrst að ganga úr skugga um að UOM og vídd hlutarins hafi verið sett upp á birgðaspjaldinu.  

> [!NOTE]  
>  Aðeins er hægt að vinna með margar mælieiningar í uppsetningum vöruhúsakerfa. Í öllum öðrum stillingum getur innihald hólfs aðeins verið í grunnmælieiningunni. Í öllum viðskiptum með mælieiningu hærri en grunnmælieiningu vörunnar, er magn er breytt í grunnmælieiningu.  

## <a name="zone"></a>Svæði  
Í ítarlegt vörugeymsla, hólf má flokka á svæðum til að stjórna hvernig verkflæði vörugeymsla starfsemi er beint.  

Svæðin gæti verið móttökusvæði eða lagersvæði og hvert svæði getur samanstaðið af einu eða fleiri hólfum.  

Flestum eiginleikum sem úthlutað er á svæði verður sjálfgefið úthlutað á hólfið sem er stofnað úr því svæði.  

## <a name="class"></a>Flokkur  
Í háþróaður vörugeymsla, þú geta framselja vöruhús flokki kóða á vörur, hólf, og svæði til að stjórna hvar  mismunandi vöruflokkar eru geymd, eins og frystivörum. Hægt er að deila svæði upp í nokkra vöruhúsaflokka. Til dæmis vörur á móttökusvæði er hægt að vista sem frosnar, hættulegar eða annað.  

Þegar þú vinnur með flokka vöruhúsa og sjálfgefið sendingar- og móttökuhólf verður þú að fylla handvirkt út viðeigandi hólf í vöruhússkvittunarlínum og afhendingarlínum.  

Í flæði á innleið er flokkakóði aðeins auðkenndur á innleiðarlínum þar sem vöruflokkakóðinn passar ekki við sjálfgefið móttökuhólf. Ef réttum sjálfgefnum hólfum er ekki úthlutað er ekki hægt að taka við magninu.  

## <a name="location"></a>Birgðageymsla  
Birgðageymsla er efnisleg bygging eða staður sem birgðir eru fluttar á, geymdar í og afhentar úr, mögulega skipulögð með hólfum. Birgðageymsla getur verið vöruhús, þjónustubifreið, sýningarsalur, verksmiðja eða svæði innan verksmiðju.  

## <a name="first-expired-first-out"></a>Fyrst útrunnið fyrst út  
Ef gátreiturinn **Tína eftir FEFO** er valinn á flýtiflipanum **Hólfareglur** á staðsetningarkortinu, þá eru vöruraktar vörur teknar til samkvæmt lokadegi þeirra. Vörurnar sem hafa elstu lokadagsetningarnar eru teknar til fyrst.  

Vöruhúsaaðgerðir í öllum tiltektar og hreyfingarskjölum eru flokkuð samkvæmt FEFO, nema vörurnar sem um ræðir hafa þegar raðnúmeri / lotunúmeri úthlutað. Ef aðeins hluti magnsins í línunni er þegar með úthlutuð lotu- eða raðnúmer notar kerfið FEFO til þess að raða því magni sem eftir stendur.  

Við tínslu FEFO er tiltækum vörum sem renna fyrst út safnað á tímabundinn vörurakningarlista eftir lokadegi. Ef tvær vörur með rað-/lotunúmeri hafa sömu fyrningadagsetningu velur kerfið vöruna með lægsta lotu- eða raðnúmerið. Ef rað- eða lotunúmerin eru þær sömu þá velur forritið þá vöru sem fyrst var skráð. Hefðbundin skilyrði fyrir vöruvali í tínsluhólfum, eins og Hólfaflokkun og Skipta einingum, eru notuð á þennan tímabundna FEFO-vörurakningarlista.  

## <a name="put-away-template"></a>Frágangssniðmát  
Frágangssniðmátinu má úthluta á vöru og á staðsetningu. Frágangssniðmátið tilgreinir bálk forgangsreglna sem verður að virða þegar frágangur er stofnaður. Til dæmis getur frágangssniðmát krafist þess að vara sé sett í hólf með hólfinnihaldi sem stemmir við mælieininguna og ef svipað hólf með nægu plássi finnst ekki verður að setja vöruna í tómt hólf.  

## <a name="see-also"></a>Sjá einnig  
[Hönnunarupplýsingar vöruhúsakerfi](design-details-warehouse-management.md)   
[Hönnunarupplýsingar: Framboð í vöruhúsi](design-details-availability-in-the-warehouse.md)

