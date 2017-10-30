---
title: "Sérstilling viðmótsins fyrir notendur"
description: "Sem kerfisstjóri skaltu grunnstilla sjálfgefin notendaviðmót fyrirtækis með því að sérstilla síðuútlit fyrir mismunandi notendaforstillingar innan fyrirtækisins."
author: jswymer
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: customize pages, configure user interface, customize UI
ms.date: 07/01/2017
ms.author: jswymer
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 7ba3d45a856eb38fe99fc5012b4e2f2d8609f9ce
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="configuring-the-user-interface-ui-for-users"></a>Sérstilling viðmótsins fyrir notendur
Sem kerfisstjóri skal notandi grunnstilla sjálfgefin notendaviðmót fyrirtækis með því að sérstilla síðuútlit fyrir mismunandi notendaforstillingar innan fyrirtækisins. Til að framkvæma þetta verk, verður þú að vera stjórnandi með yfirheimild. Þar að auki, forstillingar verður að setja upp og viðeigandi notendur úthlutað til þeirra. Nánari upplýsingar eru á [Stjórnun notenda, forstillingar og Mitt hlutverk](admin-users-profiles-roles.md).  
  
Hægt er að grunnstilla notendaviðmót fyrir marga notendur fyrir tiltekna forstillingu sem notendum er úthlutað á. Þetta er gert með því að nota [!INCLUDE[nav_windows](includes/nav_windows_md.md)], og sérstilla á sama hátt að einstaka notendur sérstilli eigin vinnusvæði, þ.e. með því að nota eiginleikann **Sérstilla**. Munurinn er sá að þú opnar [!INCLUDE[nav_windows](includes/nav_windows_md.md)] í grunnstillingu. Dæmigerðar sérstillinga eru hvaða aðgerðir á að hafa á borðanum, hvernig reitir eru sett á flýtiflipa eða í upplýsingakassa og hvaða valmyndaratriði á að taka með í yfirlitssvæði. 

> [!TIP]  
>  Fljótleg leið til að framkvæma viðmótsstillingar fyrir forstillingu er ef þú hefur þegar skilgreiningarforstillingu í öðrum [!INCLUDE[d365fin](includes/d365fin_md.md)] gagnagrunni. Þú getur svo flutt forstillinguna út og síðan flutt hana inn í núverandi gagnagrunn. Frekari upplýsingar eru í [Útflutningur og innflutningur forstillinga](admin-profiles.md#ExportImportProfile).  
  
## <a name="general-information"></a>Almennar upplýsingar
Íhugaðu eftirfarandi upplýsingar áður en þú byrjar að grunnstilla viðmótið:
-   Áður en þú byrjar að stilla notendaviðmótið er hægt að stilla forritið til að sýna og fela viðmótseiningar (eins og reiti, flýtiflipa og upplýsingakassa) út frá leyfum eða notendaheimildum. Nánari upplýsingar um það hvernig þetta er gert er að finna í [Fjarlægja einingar frá notandaviðmóti samkvæmt leyfi](https://msdn.microsoft.com/en-us/dynamics-nav/removing-elements-from-the-user-interface-according-to-permissions).

    Til að sjá áhrif af Fjarlæging gagnastaka valkostsins getur þú skráð þig inn eins og prufunotandi með heimildasafn á forstillingunni ert að stilla. Ástæðan er að þú sem stjórnandi hefur SUPER-heimildasamstæðu og getur því ekki séð og sannprófað viðmótið sem notandinn fær þegar þú ert sjálf(ur) skráð(ur) inn.    
-   Þegar þú gerir breytingar á grunnstillingum síðu sem notandi hefur síðan sérsniðið eru viðmótssérstillingar notandans ekki afturkallaðar og þeim er ekki hnekkt af nýrri grunnstillingu síðuna. Eins er notendaviðmótssérstilling notanda ekki afturkölluð þegar hætt er við notendaviðmótsgrunnstillingu á síðu sem notandi hefur sérstillt.
-   Einu aðstæðurnar þegar viðmótsgrunnstilling hnekkir persónusniðnu viðmóti er þegar viðmótseining er fjarlægð með grunnstillingu. Til dæmis ef stjórnandi fjarlægir reit sem notandinn hefur endurnefnt eða fært er reiturinn áfram fjarlægður úr viðmóti notandans.
-   Hægt er að skrá margar viðmótsgrunnstillingar á sömu síðu, allt eftir mismunandi aðgengisstöðum að síðunni. Til dæmis er hægt að stilla gluggann **Sölupöntun** svo hann líti öðruvísi út þegar hann er opnaður úr glugganume **Viðskiptamannaspjald** en úr hlutverkinu **Sölupantanavinnsla**. Staðurinn þaðan sem þú ferð inn á síðuna sem á að persónusníða er skráður í persónusnið þeirrar síðu. Í samræmi geta verið margar síðusérstillingarfærslur í gagnagrunninum eins og sést í glugganum **Eyða notandasíðu skilgreining**.  
-   Ólíkt þegar notendur breyta stærð glugga eða breidd dálka á eigin tölvu, eru allar svo grunnbreytingar sem þú gerir á þinni viðmótsuppsetningu fyrir forstillingu ekki vistaðar á forstillinguna og mun ekki vera í boði fyrir notendur sem er úthlutað á forstillinguyna. Grunnbreytingar velta á tölvum.   

## <a name="configure-a-profile-with-the-includenavwindowsincludesnavwindowsmdmd-in-configuration-mode"></a>Grunnstilla forstillingu með [!INCLUDE[nav_windows](includes/nav_windows_md.md)] í skilgreiningarstillingu
1.  Opna skipanakvaðninguna og sláðu inn eftirfarandi skipun til að skipta yfir í uppsetningarmöppu [!INCLUDE[nav_windows](includes/nav_windows_md.md)]. Dæmi:  
  
    ```  
    cd C:\Program Files\(x86)\Microsoft Dynamics NAV\110\RoleTailored Client  
    ```  
  
2.  Sláðu inn eftirfarandi skipun til að ræsa [!INCLUDE[nav_windows](includes/nav_windows_md.md)] í grunnstillingu fyrir tiltekna forstillingu:  
  
    ```  
    Microsoft.Dynamics.Nav.Client.exe -configure -profile:"profileid"  
    ```  
  
     Skipta skal **kenni forstillingar** út fyrir heiti forstillingarinnar sem á að grunnstilla.  
  
     Til dæmis, til að skilgreina bókhaldsstjórnanda forstillingar, er þessi skipun notuð:  
  
    ```  
    Microsoft.Dynamics.Nav.Client.exe -configure -profile:"Accounting Manager"  
    ``` 

3. Nú getur þú byrjað að stilla viðmótið, sem þú gerir á sama hátt og einstakar notendur sérstilla eigin vinnusvæði. Frekari upplýsingar eru í [Sérstilling vinnusvæðisins þíns með [!INCLUDE[nav_windows](includes/nav_windows_md.md)]](ui-personalization-windows-client.md). 

## <a name="cancel-ui-configuration"></a>Hætta við grunnstillingu
Hægt er að afturkalla viðmótssérstillingu sem hefur verið gerð sem grunnstilling fyrir forstillingu með þrennum hætti.  
  
-   Hætta við allar viðmótssérstillingar sem þú hefur gert fyrir snið með því að nota **Hreinsa samskipaðar síður** hnappinn í glugganum **Forstillingarspjald**.  
  
-   Hætta við viðmótssérstillingu sem þú hefur gert fyrir ákveðnar síður fyrir snið með því að eyða raðir í **Eyða sniðskilgreiningu** glugga.  
  
-   Hætta viðmótssérstillingu sem þú hefur gert fyrir tiltekið viðmótssvæði fyrir snið með því að nota **Endurheimta sjálfgefið** hnappinn í glugganum **Sérstilling**.  
  
### <a name="general-information"></a>Almennar upplýsingar  
-   Notendur geta gera viðmótssérstillingar undir eigin notandanafni til að sérsníða notendaviðmót þeirra. Ef þú afturkallar viðmótsgrunnstillignar á síðu sem notandi hefur síðan sérsniðið eru viðmótssérstillingar notandans ekki afturkallaðar. Eins er notendaviðmótssérstilling notanda geymd þegar gerð er ný notendaviðmótsgrunnstilling á síðu sem notandi hefur sérstillt og ekki er skrifað yfir hana með nýrri grunnstillingu síðu.  

    Einu aðstæðurnar þegar viðmótsgrunnstilling hnekkir persónusniðnu viðmóti er þegar viðmótseining er fjarlægð með grunnstillingu. Til dæmis ef stjórnandi fjarlægir reit sem notandinn hefur endurnefnt eða fært er reiturinn áfram fjarlægður úr viðmóti notandans.  
  
-   Í **Eyða notandaaðlögun** glugganum og með hnappnum **Endurheimta sjálfgefið** í **Sérstilla** glugganum geta notendur hætt við viðmótssérstillingu  sem þeir hafa gert á síðum undir eigin notandanafni. Þegar það er gert er hönnun þeirra síðna endurstillt á allar viðmótssérstillingar sem stjórnandi hefur grunnstilt fyrir forstillinguna. Ef forstillingin hefur ekki verið grunnstillt er útlitið á síðum notandans endurstillt á grunnstillingu forstillingarinnar. Frekari upplýsingar um hvernig notendur geta hætt við sérstillingu er að finna í [Hætt við sérstillingu](ui-personalization-windows-client.md#CancelPersonalization).
  
### <a name="to-cancel-all-ui-customization-that-you-have-made-for-a-profile"></a>Að hætta við viðmótssérstillingu sem þú hefur gert fyrir forstillingu  
  
1.  Í reitnum **Leita** skal færa inn **Forstillingar** og velja síðan viðkomandi tengi.  
  
2.  Veldu forstillinguna sem þú vilt hætta við alla viðmótssérstillingar á og þá, á **Heim** flipanum, í hópnum  **Stjórna**  velja **Breyta**  
  
3.  Í glugganum **Forstillingarspjald** á flipanum **Aðgerðir** í flokknum **Eiginleikar** veljið **Hreinsa samskipaðar síður**.  
  
> [!NOTE]  
>  Hætt er við alla viðmótssérstillingu fyrir forstillinguna, bæði þær sem voru uppsettar með forritinu og þær sem voru gerðar af kerfisstjóra. Ekkert síðuútlit sem á við forstillinguna er til staðar í gagnagrunninum.  
  
### <a name="to-cancel-ui-customization-that-you-have-made-for-specific-page-for-a-profile"></a>Að hætta við viðmótssérstilling sem þú hefur gert fyrir forstillingu  
  
1.  Í reitnum **Leit** skal færa inn **Eyða grunnstillingu sniðs** og velja síðan viðkomandi tengil.  
  
2.  Veldu forstillingar-/síðusettið sem þú vilt hætta við viðmótssérstillingu, og þá, á flipanum **Heim** úr flokknum **Stjórna** veljið**Eyða**  
  
    > [!IMPORTANT]  
    >  Ef aðrar viðmótssérstillingar á sömu síðu hafa verið grunnstilltar á grunni annarra slóða að síðunni verður hver sérstilling síðu skráð í glugganum **Eyða samskipan lýsingar** með sömu upplýsingum. Engar upplýsingar eru til að bera kennsl á það hvaða röð tengist hvaða slóð. Því þarf að eyða hverri röð fyrir sig og fara yfir síðuna, eða eyða öllum röðum með viðmótssérstillingu fyrir forstillinguna/síðuna.
    >    
    >  Hætt er við alla viðmótssérstillingu fyrir síðuna fyrir forstillinguna sem gerð var við uppsetningu eða eftir að glugginn **Eyða samskipan forstillingar** síðast notaður. Hönnun síðunnar er endurstillt að hefðbundnu útliti síðuhlutarins.  
  
### <a name="to-cancel-ui-customization-that-you-have-made-for-a-specific-ui-area-for-a-specific-page-for-a-profile"></a>Að hætta viðmótssérstilling sem þú hefur gert fyrir ákveðna viðmótssvæði fyrir ákveðna síðu fyrir Forstillingu  
  
Hægt er að afturkalla breytingar á viðmótssérstillingu sem gerðar hafa verið fyrir tiltekið viðmótssvæði, svo sem borða, með því að nota hanppinn **Endurheimta sjálfgefið** í glugganum **Sérstilling**. Hætta við viðmótssérstillingu sem þú hefur gert fyrir snið með því að eyða raðir í **Eyða sniðskilgreiningu** glugga.  
  
Hætt er við viðmótssérstillingar fyrir forstillingu tiltekins viðmótssvæðis á viðkomandi síðu. Hönnun viðmótssvæðis síðunnar er endurstillt að sjálfgefinni grunnstillingu, eins og hún var gerð annað hvort af stjórnanda eða sett upp af forritinu.  
  
## <a name="see-also"></a>Sjá einnig  
[Sérstillir [!INCLUDE[navnow_md](includes/navnow_md.md)]](ui-customizing-overview.md)   
