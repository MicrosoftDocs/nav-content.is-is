---
title: "Vinna með viðskiptamenn með því nota Dynamics 365 for Sales"
description: "Hægt er að nota Dynamics 365 for Sales innan Dynamics NAV til að varpa gögnum og hafa óaðfinnanlegur samþætting og samstillingu í heildarferlinu."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: integration, synchronize, map
ms.date: 06/06/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: 3f26a80427a2a1c38949ca94848751527383d7f9
ms.contentlocale: is-is
ms.lasthandoff: 10/26/2017

---
# <a name="managing-customers-and-sales-created-in-dynamics-365-for-sales"></a>Umsjón með viðskiptamönnum og sölum sem stofnuð eru í Dynamics 365 for Sales
Ef þú notar Dynamics 365 for Sales til að taka þátt í viðskiptum, getur þú notað [!INCLUDE[d365fin](includes/d365fin_md.md)] til þess að panta vinnslu og fjármál og hafa óaðfinnanlegur samþættingu í framhaldi af peningum.

Þegar umsóknin þín er sett upp til að samþætta við Dynamics 365 for Sales, hefur þú aðgang að söluupplýsingum frá [!INCLUDE[d365fin](includes/d365fin_md.md)] og öfugt í sumum tilfellum. Þessi samþætting gerir þér kleift að vinna með og samstilla gagnategundir sem eru algengar fyrir bæði þjónustu, svo sem viðskiptavini, tengiliði og söluupplýsingar og halda gögnunum uppfærðar á báðum stöðum.  

Til dæmis getur sölumaðurinn í Dynamics 365 for Sales notað verðlista frá [!INCLUDE[d365fin](includes/d365fin_md.md)] þegar þeir búa til sölufyrirmæli. Þegar þeir bæta hlutnum við sölulínuna í Dynamics 365 for Sales, geta þeir einnig séð birgðahæð (framboð) hlutarins frá [!INCLUDE[d365fin](includes/d365fin_md.md)].

Á móti kemur að pantanavinnslur í [!INCLUDE[d365fin](includes/d365fin_md.md)] geta afgreitt sérkenni sölupantana sem eru fluttar sjálfkrafa eða handvirkt úr Dynamics 365 for Sales, eins og að stofna og bóka sjálfkrafa gildar sölupantanalínur fyrir vörur eða forða sem var fært inn í Sölu sem innskriftarvörur. Frekari upplýsingar er að finna í hlutanum „Afgreiðsla sérstakra sölupöntunargagna“.  

> [!NOTE]
> Áður en þú getur samþætt við Dynamics 365 for Sales verður þú að sinna ýmsum tæknilegum undirbúningi. Nánari upplýsingar er að finna í [Hvernig á að: setja upp Dynamics CRM tengingu](https://msdn.microsoft.com/en-us/dynamics-nav/how-to-set-up-a-dynamics-crm-connection) og [Hvernig á að: undirbúa Dynamics CRM fyrir samþættingu](https://msdn.microsoft.com/en-us/dynamics-nav/how-to-prepare-dynamics-crm-for-integration) í MSDN.

## <a name="setting-up-the-connection"></a>Uppsetning tengingarinnar
Á upphafssíðunni geturðu nálgast leiðbeiningar um uppsetningu með hjálp fyrir **uppsetningu tengingar Dynamics 365 for Sales** sem hjálpar þér að setja tenginguna upp. Þegar það er gert verður þú að hafa óaðfinnanlega tengingu við Dynamics 365 for Sales færslur með [!INCLUDE[d365fin](includes/d365fin_md.md)] skrám.  

> [!NOTE]  
> Eftirfarandi útskýrir uppsetningu með aðstoð, en þú getur framkvæmt sömu verkhluta handvirkt í glugganum **Uppsetning tengingar Dynamics 365 for Sales**.

Í aðstoðarsamskipunarleiðbeiningunni geturðu valið hvaða gögn eru samstillt á milli tveggja þjónustunnar. Þú getur einnig tilgreint að þú viljir flytja inn núverandi Dynamics 365 for Sales lausnina þína. Í því tilviki verður þú að tilgreina stjórnsýslu notendareikning.

### <a name="setting-up-the-user-account-for-importing-the-solution"></a>Setja upp notandareikninginn til að flytja inn lausnina
Til að flytja inn núverandi Dynamics 365 for Sales lausn, notar uppsetningarleiðarvísir stjórnunarreikning. Þessi reikningur verður að vera gilt notandi í Dynamics 365 for Sales með eftirfarandi öryggishlutverki:

* Kerfisstjóri  
* Lausnastilling  

Frekari upplýsingar er að finna í [Búa til notendur og úthluta Microsoft Dynamics NAV (á netinu) öryggishlutverkum ](https://technet.microsoft.com/library/jj191623.aspx) á techNet og [Hvernig á að: Stjórna notendum og heimildum](ui-how-users-permissions.md).  

Þessi reikningur er aðeins notaður meðan á uppsetningu stendur. Þegar lausnin er flutt inn í [!INCLUDE[d365fin](includes/d365fin_md.md)] er reikningurinn ekki lengur þörf.

### <a name="setting-up-the-user-account-for-synchronization"></a>Setja upp notandareikning fyrir samstillingu
Samþættingin byggist á sameiginlegum notendareikningi. Svo í Office 365 áskriftinni þinni verður þú að búa til hollur notandi sem verður notaður til samstillingar á milli tveggja þjónustunnar. Þessi reikningur verður þegar að vera giltur notandi í Dynamics 365 for Sales, en þú þarft ekki að úthluta öryggishlutverkum til reikningsins vegna þess að uppsetningarleiðarvísirinn muni gera það fyrir þig. Þú verður að tilgreina þennan notandareikning einn eða fleiri sinnum í uppsetningarhandbókinni, háð því hversu mikið samstilling þú vilt virkja. Nánari upplýsingar er að finna í [Búa til notendur og úthluta öryggishlutverkum Microsoft Dynamics NAV (online)](https://technet.microsoft.com/library/jj191623.aspx) á techNet.

Ef þú velur að virkja *hlutafyrirkomulag*, verður aðgangur að notendareikningurinn að vera með aðgangstakkann fyrir vefþjónustu. Þetta er tvíþætt hlutur á [!INCLUDE[d365fin](includes/d365fin_md.md)] síðunni fyrir þennan notandareikning. Þú verður að velja **Breyta aðgangslykill vefþjónustu** Og í uppsetningarleiðbeiningar Dynamics 365-tengingarinnar verður þú að tilgreina þann notanda sem notanda OData vefþjónustunnar.

Ef þú velur að gera kleift að virkja *sölupöntunarsamþætting*, verður þú að tilgreina notanda sem getur séð þessa samstillingu - samþætting notandans eða annan notandareikning.

### <a name="coupling-records"></a>Tengja skrár
Í aðstoðarsamskipunarleiðbeiningunni geturðu valið að samstilla á milli tveggja þjónustunnar. En síðar getur þú einnig sett upp samstillingu tiltekinna gerða gagna. Þetta er kallað *tenging* og í þessum kafla er að finna tillögur um það sem þú verður að taka tillit til.

Til dæmis, ef þú vilt sjá Dynamics 365 for Sales reikninga sem viðskiptavini í [!INCLUDE[d365fin](includes/d365fin_md.md)], verður þú að tengja tvær tegundir af skrám. Það er ekki mjög flókið - þú opnar lista **Viðskiptavinalista** í [!INCLUDE[d365fin](includes/d365fin_md.md)], og það er aðgerð í borði til að tengja þessar upplýsingar við Dynamics 365 for Sales. Þá tilgreinir þú hvaða [!INCLUDE[d365fin](includes/d365fin_md.md)] viðskiptavinir passa við hvaða reikninga í Dynamics 365 for Sales.

Á ákveðnum sviðum byggir virknin á að þú tengir ákveðnar gagnasettir fyrir aðrar gagnasettir eins og sýnt er í eftirfarandi lista:

* Viðskiptavinir og reikningar  
  * Tengdu fyrst sölumenn við Dynamics 365 for Sales notendur  
* Vörur og forði  
  * Tengja mælieiningar með Dynamics 365 for Sales við einingahópa fyrst  
* Vörur og forðaverð  
  * Tengja verðlagshópa viðskiptavina með Dynamics 365 for Sales við verð fyrst  

> [!NOTE]  
>   Ef þú ert að nota verð í erlendum gjaldmiðlum skaltu ganga úr skugga um að þú tengir gjaldmiðla við Dynamics 365 for Sales viðskipta gjaldmiðla.

Dynamics 365 for Sales sölutilboð veltur á viðbótarupplýsingum eins og viðskiptavinum, mælieiningum, gjaldmiðlum, verðlagshópum viðskiptavina , vörum og / eða tilföngum. Í því skyni að láta Dynamics 365 for Sales sölufyrirmæli virka óaðfinnanlega verður þú að tengja viðskiptavini, mælieiningar, gjaldmiðla, verðlagshópa viðskiptavina, vörur og / eða tilföng fyrst.

### <a name="synchronizing-records-fully"></a>Samstilla skrár að fullu
Í lok aðstoðar uppsetningarleiðbeiningarinnar geturðu valið aðgerðina **Keyra fulla samstillingu** til að byrja að samstilla allar [!INCLUDE[d365fin](includes/d365fin_md.md)] færslur með öllum tengdum skrám í tengdu Dynamics 365 for Sales lausninni. Í **Yfirferð á fullri samstillingu tengslastjórnunar** gluggann, veldu **Ræsa** aðgerðina. Samstillingin byrjar síðan að framkvæma störf í samræmi við ósjálfstæði. Til dæmis eru gjaldeyrisskrár samstilltar fyrir viðskiptavinaskrár. Fullur samstilling getur tekið langan tíma og mun því birtast í bakgrunni þannig að þú getir haldið áfram að vinna í [!INCLUDE[d365fin](includes/d365fin_md.md)].

Til að kanna framvindu einstakra starfa í fullri samstillingu, skal fara á **Staða verkraðarfærslu**, **Í innri vinnslustöðu töflu**, eða **Úr innri vinnslustöðu töflu** í glugganum **Yfirferð á fullri samstillingu tengslastjórnunar**.

Frá gluggann í **Uppsetning Dynamics 365 for Sales-tengingar** er hægt að fá upplýsingar um fulla samstillingu hvenær sem er. Héðan er einnig hægt að opna gluggann **Vörpun samþættingartöflu** til að sjá upplýsingar um töflurnar í Dynamics NAV og í Dynamics 365 for Sales lausninni sem þarf að samstilla.

## <a name="handling-special-sales-order-data"></a>Afgreiðsla sérstakra sölupöntunargagna
Sölupantanir í Dynamics 365 for Sales verða fluttar sjálfkrafa í [!INCLUDE[d365fin](includes/d365fin_md.md)] ef gátreiturinn **Stofna sölupantanir sjálfkrafa** í glugganum **Uppsetning tengingar Microsoft Dynamics 365 for Sales** er valinn. Á slíkum sölupöntunum er reiturinn **Heiti** í upprunalegu pöntuninni fluttur og honum varpað í reitinn **Utanaðkomandi fylgiskjalsnúmer** á sölupöntuninni í [!INCLUDE[d365fin](includes/d365fin_md.md)].

Þetta getur líka virkað ef upprunalega sölupöntunin inniheldur innskriftarvörur, þ.e.a.s. vörur eða forða sem er skráður í hvorugri vörunni. Í því tilviki verður þú að fylla út reitina **Gerð innskriftarvöru** og **Nr. innskriftarvöru** í glugganum **Sölugrunnur**, til þess að slíkri óskráðri vörusölu sé varpað í tiltekið vöru-/forðanúmer fyrir fjárhagsgreiningu.

Ef vörulýsingin í upprunalegu sölupöntuninni er mjög löng er stofnuð ný sölupöntunarlína af gerðinni Athugasemd til þess að rúma allan texta sölupöntunarinnar í [!INCLUDE[d365fin](includes/d365fin_md.md)].

## <a name="see-also"></a>Sjá einnig
[Umsjón með venslum](marketing-relationship-management.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  
[Sérstillir [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-customizing-overview.md)  
[Hvernig á að: Vinna með notendur og heimildir](ui-how-users-permissions.md)    
[Nýliðaþjálfun fyrir fyrirtækið og notendur í Dynamics NAV (á netinu)](https://www.microsoft.com/en-US/Dynamics/crm-customer-center/onboard-your-organization-and-users-to-dynamics-365-online.aspx)  

##

