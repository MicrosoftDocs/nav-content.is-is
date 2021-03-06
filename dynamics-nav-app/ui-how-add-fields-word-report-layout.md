---
title: "Hvernig á að bæta reitum við Word-skýrsluútlit"
description: "Lýsir ferlinu við að bæta reitum í gagnasafni skýrslu við fyrirliggjandi Word-skýrsluútlit fyrir skýrslu."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 1085c5390cf6f20cc2bd5c2a95057e6499dbac8c
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-add-fields-to-a-word-report-layout"></a>Hvernig á að bæta reitum við Word-skýrsluútlit
Gagnasafn skýrslu getur samanstaðið af reitum sem birta merki, gögn og myndir. Þetta efnisatriði lýsir ferlinu við að bæta reitum í gagnasafni skýrslu við fyrirliggjandi Word-skýrsluútlit fyrir skýrslu. Reitum er bætt við með því að nota Word sérsniðinn XML-hluta fyrir skýrsluna og bæta við efnisstjórnun sem varpar í reiti gagnamengis skýrslunnar. Bæting reita þarfnast einhverrar þekkingar á gagnamengi skýrslunnar þannig að hægt er að bera kennsl á reitina sem á að bæta við útlitið.  
  
> [!NOTE]  
>  Ekki er hægt að breyta innbyggðu skýrsluútliti<!--Onprem. Built-in layouts can only be modified by using the development environment-->.  

##  <a name="OpenXMLPart"></a>Til að opna sérsniðinn XML-hluta fyrir skýrsluna í Word  
  
1.  Ef það er ekki þegar opið skal opna Word-sniðmátsskjal fyrir skýrslu í Word.  
  
     Nánari upplýsingar er að finna í [Hvernig á að: Búa til og breyta sérsniðið skýrsluútlit](ui-how-create-custom-report-layout.md).  
  
2.  Sýna flipann **Hönnuður** á borða Microsoft Word.  
  
     Sjálfgefið er að **Hönnuður** er ekki sýnilegur í borðanum. Nánari upplýsingar eru í [Hvernig á að sýna flipann Developer á borðanum](http://go.microsoft.com/fwlink/?LinkID=389631).  
  
3.  Á flipanum **Developer** skal velja **XML-vörpunarsvæði**.  
  
4.  Á svæðinu **XML-vörpun**, á fellilistanum **Sérsniðinn XML-hluti** velurðu sérsniðinn XML-hluta fyrir ADD INCLUDE<!--[!INCLUDE[navnow](../../includes/navnow_md.md)]-->-skýrslu, sem er vanalega síðast á listanum. Heiti sérstillta XML-hlutans er á eftirfarandi sniði:  
  
     urn:microsoft-dynamics-nav/reports/*skýrslu_heiti*/*/Kenni*  
  
     *skýrsluheiti* er heitið sem er úthlutað á skýrsluna<!--OnPrem as specified by the report's [Name Property-duplicate](../FullExperience/nav_dev_long_md.md)]--> í skýrslunni.  
  
     *Auðkenni* er kenninúmer skýrslunnar.  
  
     Eftir að þú velur sérsniðna XML-hlutann sýnir XML-vörpunarglugginn merki og reitastjórnun sem er í boði fyrir skýrsluna.  
  
### <a name="to-add-a-label-or-data-field"></a>Til að bæta við merki eða gagnareit  
  
1.  Setja skal bendilinn á skjalið þar sem þú vilt setja inn stjórnhnapp.  
  
2.  Á svæðinu **XML-vörpun** skal hægrismella á stjórnhnappinn sem á að bæta við, velja **Fella inn í efnisstjórnun** og velja svo **Ósniðinn texti**.  
  
    > [!NOTE]  
    >  Ekki er hægt að bæta við reit með því að slá handvirkt inn heiti gagnamengisreits í efnisstjórnun. Þú verður að nota **XML-vörpun** svæðið til að varpa reitunum.  
  
### <a name="to-add-repeating-rows-of-data-fields-to-create-a-list"></a>Til að bæta við endurteknum línum gagnareita til að búa til lista  
  
1.  Í töflunni skal bæta við töflulínu sem inniheldur dálk fyrir hvern reit sem á að endurtaka.  
  
     Þessi lína virkar sem staðgengill fyrir endurtekna reiti.  
  
2.  Veldu alla röðina.  
  
3.  Á svæðinu **XML-vörpun** skal hægrismella á stjórnhnappinn sem samsvarar skýrslugagnaatriðinu sem inniheldur reitina sem á að endurtaka, velja **Fella inn í efnisstjórnun** og velja svo **Endurtaka**.  
  
4.  Bættu endurtekna reitinum við röð svona:  
  
    1.  Bendillinn er settur á dálk.  
  
    2.  Á svæðinu **XML-vörpun** skal hægrismella á stjórnhnappinn sem á að bæta við, velja **Fella inn í efnisstjórnun** og velja svo **Ósniðinn texti**.  
  
    3.  Endurtakið skref a og b fyrir hvern reit.  
  
## <a name="adding-image-fields"></a>Bæat avið myndareitum  
 Gagnasafn skýrslu getur innihaldið reit sem inniheldur mynd, t.d. fyrirtækjamerki eða mynd af hlut. Til að bæta við mynd úr skýrslugagnamenginu er sett inn efnisstjórnunin **Mynd**.  
  
 Myndir birtast efst í hægra horni efnisstýringar og laga stærð sína sjálfvirkt þannig að þær passi við mörk efnisstjórnunar.  
  
> [!IMPORTANT]  
>  Aðeins er hægt að bæta við myndum á sniði sem Word styður, t.d. .bmp, .jpeg, og .png skráargerðir. Ef þú bætir við mynd á sniði sem Word styður ekki færðu villu þegar þú keyrir skýrsluna úr ADD INCLUDE<!--[!INCLUDE[navnow](../../includes/navnow_md.md)]--> biðlaranum.  
  
#### <a name="to-add-an-image"></a>Til að bæta við mynd  
  
1.  Setja skal bendilinn á skjalið þar sem þú vilt setja inn stjórnhnapp.  
  
2.  Á svæðinu **XML-vörpun** skal hægrismella á stjórnhnappinn sem á að bæta við, velja **Fella inn í efnisstjórnun** og velja svo **Mynd**.  
  
3.  Til að auka eða minnka myndastærðina dregurðu stærðarhandfang frá eða að miðju efnisstjórnunar.  

## <a name="custom-xml-part-overview"></a>Sérsniðinn XML-hluti yfirlit
Word-skýrsluútlit byggja á *sérsniðnum XML-hlutum*. Sérsniðinn XML-hluti fyrir skýrslu samanstendur af þáttum sem samsvara gagnahlutum, dálkum og merkingum sem saman mynda gagnamengi skýrslunnar. <!--OnPrem The data as defined in the Report Dataset Designer in Microsoft Dynamics NAV Development Environment. -->Sérsniðinn XML-hluti er notaður til að varpa gögnunum í skýrslu þegar skýrslan er keyrð.

  
### <a name="xml-structure-of-custom-xml-part"></a>XML bygging sérsniðins XML-hluta  
Eftirfarandi tafla sýnir einfaldað yfirlit yfir XML af sérsniðnum XML-hluta.  
  
|XML-einingar|Description|  
|------------------|-----------------|  
|`<?xml version="1.0" encoding="utf-16"?>`|Haus|  
|`<WordReportXmlPart xmlns="urn:microsoft-dynamics-365/report/<reportname>/<id>/"`|XML nafnbil tilgreint. `<reportname>` er heitið sem er úthlutað á skýrsluna. `<id>` er auðkennið sem tengt er úthlutað á skýrsluna.|  
|`..<Labels>`<br /><br /> `....<ColumnNameCaption>ColumnNameCaption</ColumnNameCaption>`<br /><br /> `....<LabelName>LabelCaption</LabelName>`<br /><br /> `..</Labels>`|Inniheldur öll merki fyrir skýrsluna.<!--OnPren The element includes labels that are related to columns that have the [IncludeCaption Property](../FullExperience/Name%20Property-duplicate.md).--><br />-   Merkjaeiningar sem tengjast dálkum hafa sniðið `<ColumnNameCaption>ColumnNameCaption</ColumnNameCaption>`<!--OnPrem where `ColumnName` is determined by the column's Name Property.-->.<br />-  Merkjaeiningar hafa sniðið `<LabelName>LabelName</LableName`<!--OnPrem where LabelName is determined by the label's Name Property.-->.<br />-   Merkimiðar eru skráðir í stafrófsröð.|  
|`..<DataItem1>`<br /><br /> `....<DataItem1Column1>DataItem1Column1</DataItem1Column1>`|Gögn og dálkar á efsta stigi Dálkar eru listaðir í stafrófsröð.<!--OnPrem <br /><br /> The element names and values are determined by the [Name Property-duplicate](../FullExperience/Name%20Property-duplicate.md) of the data item or column.-->|  
|`....<DataItem2>`<br /><br /> `......<DataItem2Column1>DataItem2Column1</DataItem2Column1>`<br /><br /> `....</DataItem2>`<br /><br /> `....<DataItem3>`<br /><br /> `......<DataItem3Column1>DataItem3Column1</DataItem3Column1>`<br /><br /> `....</DataItem3>`|Gögn og dálkar sem eru ívafin á efsta stigi gagnahlutar. Dálkar eru listaðir í stafrófsröð undir viðkomandi gagnahlut.|  
|`..</DataItem1>`<br /><br /> `</WordReportXmlPart>`|Lokar atriði.|  
  
### <a name="custom-xml-part-in-word"></a>Sérsniðinn XML-hluti í Word  
 Í Word opnarðu sérsniðinn XML-hluta á svæðinu **XML-vörpun** og notar svo svæðið til að varpa einingum í efnisstjórnun í Word-skjalinu. Svæðið **XML-vörpun** er aðgengilegt úr flipanum **Hönnuður** (nánari upplýsingar er að finna í [Hvernig á sýna flipann Hönnuður á borðanum](http://go.microsoft.com/fwlink/?LinkID=389631)).  
  
 Einingarnar í **XML vörpun** svæðinu birtast með uppsetningu sem svipar til XML upprunans. Merkimiðareitir eru flokkaðir saman undir sameiginlegri einingu í **Merkimiðar** og gagnaatriðum og dálkum er raðað í stigveldisskipan sem samsvarar XML-upprunanum, með dálkar í stafrófsröð. Einingar eru auðkenndar af heiti sínu eins og það er skilgreint í eiginleikanum Heiti í innbyggða skýrsluhönnuðinum í ADD INCLUDE<!--[!INCLUDE[nav_dev_short](../../includes/nav_dev_short_md.md)]-->.  
  
 Eftirfarandi mynd sýnir einfaldan sérsniðinn XML-hluta úr fyrri hluta í **XML-vörpun** svæðinu í Word skjali.  
  
 ![Hluti af XML vörpunarsvæði í word](media/nav_reportlayout_xmlmappingpane.png "NAV_SkýrslaÚtlit_XMLVörpunarSvæði")  
  
-   Til að bæta merki eða reit við útlitið er sett inn efnisstjórnun sem varpar í eininguna á svæðinu **XML-vörpun**.  
  
-   Til að búa til endurteknar raðir af dálkum skal setja inn **Endurtekna** efnisstjórnun fyrir yfirgögn einingarinnar, og bæta svo við efnisstjórnun fyrir dálkana.  
  
-   Fyrir merki er sá texti sem birtist í skýrslunni sem mynduð er gildi eiginleikans **Myndatexti** fyrir reitinn í gagnaatriðatöflunni (ef merkið tengist dálki í skýrslugagnamenginu), eða merki í Report Label Designer, (ef merkið tengist ekki dálki í gagnamenginu).  
  
-   Tungumál merkisins sem birtist þegar skýrslan er keyrð fer eftir tungumálsstillingu skýrsluhlutarins. <!--OnPrem For more information, see [Multiple Document Languages](../FullExperience/Viewing%20the%20Application%20in%20Different%20Languages.md).-->  
  
## <a name="see-also"></a>Sjá einnig  
 [Hvernig á að: Búa til og breyta sérsniðið skýrsluútlit](ui-how-create-custom-report-layout.md).   
