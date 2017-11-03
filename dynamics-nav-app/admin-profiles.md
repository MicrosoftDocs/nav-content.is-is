---
title: "Stjórnun forstillinga og Mitt hlutverk"
description: "Lærið að meðhöndla notendur og hlutverkamiðstöðvar í Dynamics NAV."
author: jswymer
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: profiles, roles, role centers, user roles
ms.date: 09/01/2017
ms.author: jswymer
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: a657c409c9cd361a505f1fd61dbb5254b25c5144
ms.contentlocale: is-is
ms.lasthandoff: 10/26/2017

---
# <a name="managing-profiles-and-role-centers"></a>Stjórnun forstillinga og Mitt hlutverk
Forstillingar eru söfn [!INCLUDE[navnow_md](includes/navnow_md.md)] notenda sem hafa sömu hlutverkamiðstöð (Mitt hlutverk). Mitt hlutverk er tegund síðu þar sem notandi getur sett mismunandi hluta. Hver hluti er geymir þar sem hægt er að hýsa aðrar síður eða forskilgreinda kerfishluta eins og Outlook-hluta eða íhluti til að bæta við verkum, tilkynningum eða athugasemdum.  

## <a name="about-profiles-and-role-centers"></a>Um forstillingar og Mitt hlutverk
Forstillingar tengja notendur við fyrirfram skilgreind hlutverk (Mitt hlutverk). Mitt hlutverk er heimasíða fyrir alla notendur forstillingar, sem hefur verið grunnstillt til að endurspegla verkefnin og forgang notenda forstillingarinnar. Til dæmis hefur hlutverkamiðstöð pöntunargjörva verið grunnstilltur þannig að hann endurspegli verk og forgang pöntunagjörva. Mitt hlutverk veitir einfaldan aðgang að upplýsingum sem notendur þurfa til að sinna daglegu starfi sínu. Til dæmis ákvarðar Mitt hlutverk bunka, eða reiti, sem sýna hvenær notendur skrá sig fyrst inn og tengla á leiðsögnarsíðunni.

Forstillingin sem er notuð í haus aðalsvæðisins í Hlutverkamiðstöð. Kerfisstjóri getur sérstillt þessa hlutverkamiðstöð til að uppfylla þarfir tiltekins hlutverks innan tiltekins fyrirtækis. Hægt er að sérsníða Mitt hlutverk í pantanavinnslu frekar á einni tölvu til að mæta þörf einstaklings sem er að vinna við verkið sem afgreiðslumaður pantana. Einstaklingurinn getur sérstillt Mitt hlutverk með því að vista fyrirspurnir, bæta við afmörkunum og bæta við eða fjarlægja reiti.

Forstillingar og Mitt hlutverk eru sniðin að hlutverkum og ábyrgð innan fyrirtækis. [!INCLUDE[navnow_md](includes/navnow_md.md)] er með nokkrar sjálfgefnar forstillingar, hver samsvarar og tengist hlutverki (Mitt hlutverk). Stjórnendur geta breytt forstillingum eða búið til nýjar.  

> [!NOTE]  
>  Forstillingar eru ekki tengdar sérstaklega hlutverkunum og heimildunum sem mynda öryggiskerfið en notendur forstillinga verða að hafa heimildir sem tengjast hlutverkum þeirra í öryggiskerfinu. Nánari upplýsingar er að finna í [Öryggi í hlutverkamiðuðu umhverfi](http://go.microsoft.com/fwlink?LinkId=147633) í MSDN-safninu.

## <a name="to-create-a-profile"></a>Forstilling stofnuð
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Forstillingar** og velja svo viðeigandi tengil.  

2.  Velja skal **Nýtt** aðgerðina til að opna gluggann **Nýtt forstillingarspjald**.  

3.  Í reitnum **Kenni forstillingar** færið inn nafn sem lýsir ætluðum hlutverk notanda.  

4.  Í reitinn **Lýsing** er slegin inn lýsing á kenni forstillingar, t.d. **Pantanavinnsla**.  

5.  Stilltu **Kenni fyrir Mitt hlutverk** reitinn á Mitt hlutverk sem þú vilt tengja við forstillinguna.  

6.  Til að gera þetta hlutverk að sjálfgefinni forstillingu skal velja gátreitinn **Sjálfgefið Mitt hlutverk**.  

7.  Velja hnappinn **Í lagi**. .  

Ferlið til þess að breyta fyrirliggjandi forstillingu er hið sama, nema að valin er eldri forstilling á síðunni Forstillingar í stað þess að velja aðgerðina **Nýtt**.  


##<a name="copying-a-profile"></a>Afritun forstillingar
Afritun forstillingar getur sparað tíma ef nota á sambærilegar stillingar á forstillingu og eingöngu á að breyta nokkrum stillingum.

1.  Opnaðu forstillinguna sem þú vilt afrita og veldu svo **Afrita forstillingu** aðgerðina.

2.  Í reitnum **Nýtt kenni forstillingar** er slegið inn nafn á forstillingunni sem á að afrita.

3.  Stilltu **Nýtt umfang forstillingar** reitinn á eitt af eftirfarandi:

    - **Kerfi** til að gera nýja forstillingu aðgengilega fyrir alla gagnagrunna leigjenda sem nota forritið.
    - **Leigjandi** til að gera nýja forstillingu aðgengilega aðeins fyrir núverandi gagnagrunn leigjenda.
4. Veldu **Í lagi** hnappinn að því loknu.

## <a name="ExportImportProfile"></a>Útflutningur og innflutningur forstillinga

Hægt er að flytja forstillingu inn og út sem XML-skrár til og frá [!INCLUDE[d365fin](includes/d365fin_md.md)] gagnagrunninum. Inn- og útflutningur forstillingar getur sparað þér tíma þegar þú stillir notendaviðmótið þar sem þú endurnýjar núverandi uppsetningu stillingar í stað þess að þurfa að stilla forstillingu frá grunni. Ef þú ert með forstillingu sem er stillt í [!INCLUDE[d365fin](includes/d365fin_md.md)] gagnagrunni og vilt endurnýta allar eða nokkrar uppsetningarstillingar í öðrum gagnagrunni getur þú flutt sniðið út í XML-skrá. Þá er hægt að flytja inn XML-skrá forstillingarinnar í hinn gagnagrunninn.

-   Til að flytja út forstillingu er leitin opnuð og svo **Flytja út forstillingar** síðan, forstillingin valin af listanum og svo aðgerðin **Flytja út**. Vistið XML-skrána á stað í tölvu eða á neti.

-   Til að flytja inn forstillingu er leitin opnuð og svo **Flytja inn forstillingar** síðan, XML-skrá forstillingarinnar valin og svo aðgerðin **Í lagi**.

    > [!NOTE]  
    >  Ekki er hægt að flytja inn forstillingu sem þegar er til í gagnagrunninum, jafnvel þótt XML-skráin hafi annað heiti eða annað innihald. Eyða verður forstillingumsem fyrir eru áður en hægt er að flytja inn nýju forstillinguna.



## <a name="see-also"></a>Sjá einnig  
[Hvernig á að: vinna með notendur og heimildir](ui-how-users-permissions.md)  
[Sérstilling notandaviðmótsins](ui-customizing-overview.md)   
<!--[Security Overview](../Security%20Overview.md)-->

