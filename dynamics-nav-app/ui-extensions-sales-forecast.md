---
title: "Spá um sölu og birgðir"
author: edupont04
ms.custom: na
ms.date: 09/23/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 765527ed4f4800acec20f0abbd4374e95c9c36dc
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="sales-and-inventory-forecast-for-dynamics-nav"></a>Spá um sölu og birgðir fyrir Dynamics NAV
Birgðastjórnun er málamiðlun á milli notendaþjónustu og stjónun kostnaðar. Ein hliðin er sú að lágar birgðir krefjast minna veltufés, en, á hinn bóginn getur birgðaskortur hugsanlega leitt til tapaðrar sölu. Viðbótin fyrir sölu- og birgðaspá sér fyrir hugsanlegar sölur með því að nota söguleg gögn og veitir skýrt yfirlit yfir viðbúinn birgðaskort. Samkvæmt spá, aðstoðar viðbótin að stofna áfyllingarbeiðnir til lánardrottna þinna og sparar þér tíma.  

## <a name="setting-up-forecasting"></a>Spáruppsetning
Í Dynamics NAV verður að setja upp tengingu við Azure Machine Learning (Azure ML). Nánari upplýsingar eru í [Hvernig á að: Skrá Dynamics NAV í Azure stjórnunargátt](ui-how-register-dynamics-nav-azure.md). Þegar tengingu hefur verið komið á er hægt að grunnstilla spá til að nota aðra tímabilsgerð til að gefa skýrslur samkvæmt, eins og að breyta úr spám samkvæmt mánuðum í spám samkvæmt ársfjórðungum. Einnig er hægt að velja fjölda tímabila sem á að reikna spá eftir, eftir því hversu grófgerð spáin á að vera. Við að leggja til að spá eftir mánuðum og með 12 mánaða sjóndeildarhring fyrir spána.  

## <a name="using-the-forecasts"></a>Notkun spáa
Þessi viðbót notar Azure ML getu til að spá fyrir um framtíðar sölu byggt á söluferli þínum til að hjálpa þér að komast hjá birgðaskorti. Til dæmis þegar valið er vöru í glugganum **Vörur** , í sýnir grafið á **vöruspá** svæðinu áætlaða sölu vörunnar á komandi tímabili. Þannig má sjá ef líklegt er að varan klárist fljótlega hjá þér.  

Einnig má nota viðbótina til að leggja til þegar þarf að fylla á birgðir. T.d. ef þú stofnar innkaupapöntun Fabrikam af því þú vilt kaupa nýja skrifstofustólinn þeirra, mun sölu- og birgðaspárviðbótin leggja til að þú bætir einnig á birgðir LONDON-snúningsstólsins sem þú kaupir yfirleitt frá þessum lánardrottni. Það er vegna þess viðbótin spáir að þú munir klára úr birgðum þennan London-snúningsstól á næstu tveimur mánuðum, svo þú gætir viljað panta fleiri stóla nú þegar.  

## <a name="see-also"></a>Sjá einnig
[Stjórna sölu](sales-manage-sales.md)  
[Stjórna birgðum](inventory-manage-inventory.md)  
[Sérstilling Dynamics NAV með viðbótum](ui-extensions.md)  
[Hvernig á að: Skrá Dynamics NAV í Azure stjórnunargáttinni](ui-how-register-dynamics-nav-azure.md)  

