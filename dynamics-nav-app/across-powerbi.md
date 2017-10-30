---
title: Notkun Dynamics NAV efnispakka fyrir Power BI
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: ad9519b8ce9c244480308ccc99c05e78e4926b06
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---

# <a name="using-the-dynamics-nav-content-pack-for-power-bi"></a>Notkun Dynamics NAV efnispakka fyrir Power BI
Það er auðvelt að fá innsýn í Dynamics NAV gögnin þín með Power BI og Dynamics NAV efnispakkanum. Power BI sækir gögn þín og býr svo til út-fyrir-kassann yfirlit og skýrslur sem byggist á þeim gögnum.  

Efnispakkinn er forstilltur til að vinna með sölugögnum og fjárhagsgögnum úr sýnifyrirtæki sem þú færð þegar þú nýskráir þig fyrir Dynamics NAV forskoðun.  

- Velja hvaða sjónræna hlutinn á yfirlitinu til að kalla fram einn af sjö undirliggjandi skýrslum.  
- Síða skýrsluna eða bæta við reitum sem eiga að fylgjast með.  
- Festu þetta sérsniðna yfirlit á yfirlitið til að halda áfram rakning á.  
Yfirlitið og skýrslunum endurnýja undirliggjandi eru uppfærð daglega. Hægt er að stjórna uppfærsluáætlun og breyta tiíðninni á gagnamengi.  

## <a name="accessing-dynamics-nav-in-power-bi"></a>Aðgangur að Dynamics NAV í Power BI
Til að skoða þitt Dynamics NAV gögn í Power BI, verður þú að hafa eftirfarandi:  

- Aðgang að Dynamics NAV. Frekari upplýsingar eru í [Dynamics NAV](http://go.microsoft.com/fwlink/?LinkID=759714).  
- Aðgang að Power BI Nánari upplýsingar eru í [Power BI](https://powerbi.microsoft.com), .

Á vefsvæði Power BI má finna viðbótarupplýsingar um [bæta Dynamics NAV efnispakka við Power BI](http://go.microsoft.com/fwlink/?LinkID=760850).  

Til að fá aðgang að Dynamics NAV efnispakka í Power BI, í tengingaglugganum, verður að tilgreina eftirfarandi upplýsingar:

| Reitur       | Lýsing              |
|-------------|--------------------------|
|**OData streymisvefslóð**|Odata vefslóð svo Power BI geti fengið aðgang að gögnum úr fyrirtæki þínu, eins og https://mybusiness.com:7048/MS/OData/Company('CRONUS%20US').|
|**Sannvottunaraðferð**|Velja **Grunn**.|
|**Notandanafn**|Tölvupóstur sem var notuð til að skrá sig í Dynamics NAV, á borð við *me@mybusiness.com*.|
|**Aðgangsorð**|Þetta er aðgangslykill vefþjónustu fyrir notandareikningur þinn í Dynamics NAV.|

Þetta þýðir fá þarf tvö stykki af upplýsingar úr Dynamics NAV: OData vefslóð og aðgangslykill vefþjónustu fyrir notandareikning.  
**Veffangið sótt**  
Þegar Dynamics NAV er bætt við Power BI verður þú að tilgreina vefslóð þannig að Power Bi geti fá aðgang að gögnum fyrirtækisins. Í tengingarglugganum, er vísað til vefslóðar sem **OData streymisvefslóð**, og hann verður að vera á eftirfarandi sniði:

         https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')  
Í þessu dæmi er *mittfyrirtæki* heiti Dynamics NAV þjónustu, og *CRONUS U.S.* er heiti sýndarfyrirtækinu með *%20* sem táknar bil í heitinu.   
Til að fá vefslóð, í Dynamics NAV, leita að og opna gluggann **vefþjónustur**. Í þessum glugga er listi yfir vefþjónustur sem eru nú tiltækar og hægt er að afrita tengillinn úr reitnum **OData vefslóð** fyrir eina af sjálfgefnu OData vefþjónustunum.  
**Að komast yfir aðgangslykil vefþjónustu**  
Til að nota gögn úr Dynamics NAV, í Power BI, í **Tengjast við Dynamics NAV** glugganum, verður að tilgreina notandanafn þitt, sem er tölvupóstreikningur þinn, og aðgangsorð. Aðgangsorðið er aðgangslykill vefþjónustu sem er sett upp fyrir notandareikning þinn í verkefni Dynamics NAV.  
Til að fá aðgangslykill vefþjónustu, í Dynamics NAV, leita að **Notendur** glugganum og síðan opna spjald fyrir notandareikning þinn. Í á **aðgangur vefþjónustu** Flýtiflipanum, afrita efni reitsins á **aðgangslykill vefþjónustu** reit. Ef reiturinn er auður, í borðanum skaltu velja **Breyta aðgangslykill vefþjónustu**, velja **Lykillinn Rennur Aldrei út** og velja síðan hnappinn í lagi. Síðan er hægt að afrita lykill  

## <a name="getting-data-from-dynamics-nav"></a>Sækja gögnum frá Dynamics NAV
Dynamics NAV yfirlitið sýnir flestar dæmigerðum skýrslur sem þú munt vilja nota til að fylgjast með fyrirtækið þitt. Gögnin eru fengin úr þínu Dynamics NAV fyrirtæki með því að nota vefþjónustur til að lesa lifandi gögn. Í Dynamics NAV, sýnir **vefþjónustur** glugginn þær vefþjónustur sem hafa verið settar upp fyrir þig, þar á meðal eftirfarandi sem er notað af efnispakkanum í Power BI:  

- ItemSalesAndProfit  
- ItemSalesByCustomer  
- powerbifinance-setup  
- SalesDashboard  
- SalesOpportunities  
- SalesOrdersBySalesPerson  
- TopCustomerOverview  

**Athuga skal að**: Ef þú breytir heiti einhverra þessara vefþjónusta munu gögnin ekki birtast í Power BI.  
Ef þú vilt bæta við nota önnur gögn í Power BI, verður þú að finna töflurnar í Dynamics NAV, sýna þær sem vefþjónustur og síðan bæta þeim við efnispakkann. Þetta eru aðstæður fyrir lengra komna, og við mælum með að þú byrjar með gögn sem er nú þegar í boði í Power BI.  

## <a name="troubleshooting"></a>Úrræðaleit
Power BI yfirlitið byggir á birtum vefþjónustum sem eru hér að ofan skráðar, og það mun sýna gögn sýnifyrirtæki eða eigin fyrirtæki þitt ef þú flytja inn gögn úr núverandi fjárhagsuppsetningarlausn þinni. Hins vegar, ef eitthvað fer úrskeiðis, þessi kafli gefur lausn fyrir dæmigerður vandamál.  

**„Sannprófun færibreyta tókst ekki, vinsamlegast vertu viss um að allar færibreytur séu gildar“**  
Ef þú sérð þessa villumeldingu eftir að þú færir inn þína Dynamics NAV vefslóð, skaltu tryggja að eftirfarandi skilyrði séu uppfyllt:  

- Veffangið fylgir nákvæmlega þessum mynstri:

    https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')  
- Eyða öllum texti á eftir heiti fyrirtækis í svigum  
- Ganga þarf úr skugga um að engin skaástrik komi í kjölfar vefslóðar  
- tryggja skal að um sé að ræða öruggra tengingu eins og tilgreint af Veffangið sem byrjar á *https*.  


**„Innskráning mistókst“**  
Ef þú færð „innskráning mistókst“ villu þegar þú skráir þig inn í yfirlitið, með því að nota þínar Dynamics NAV innskráningarupplýsingar, þá getur eitt af eftirfarandi vandamálum valdið þessu:

* Reikningur sem verið er að nota er ekki með heimildir til að lesa Dynamics NAV gögnin úr reikninginn þinn.

    Staðfesta notandareikning í Dynamics NAV, og ganga úr skugga um að notaðar hafa verið rétt aðgangslykill vefþjónustu sem aðgangsorð og reyndu síðan aftur.  
* Dynamics NAV tilvikið sem verið er að reyna að tengjast er ekki með gilt SLL vottorð. Í þessu tilviki sérðu nákvæmari villuboð ("ekki er hægt að stofna traust SSL samband").

    **Athuga skal að**: sjálfárituð vottorð eru ekki studd.  


**"Úps"**  
Ef þú sérð "Úps" villuglugga þegar þú ert kominn framhjá sannvottunarglugganum, er þetta oftast vegna vandamáls við að tengjast gögnum fyrir efnispakkann.

* Sannprófa að vefslóð er samkvæmt mynstri sem var tilgreint áður.

    https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')  
* Algeng mistök eru að tilgreina fulla vefslóð fyrir tiltekna vefþjónustu.

    https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')/powerbifinance-setup  
* Eða þú gætir hafa gleymt að tilgreina heiti fyrirtækis.

    https://mybusiness.projectmadeira.com:7048/MS/OData/  


## <a name="see-also"></a>Sjá einnig
[Velkomin(n) í Dynamics NAV](across-get-started.md)  

