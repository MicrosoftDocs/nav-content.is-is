---
title: "Stofna innkaupareikning úr sölureikningi til að kaupa vörur fyrir sölu"
description: "Úr sölureikningi, til að kaupa vörur, geturðu stofnað innkaupareikning fyrir lánardrottinn eða birgja."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: supply planning, sales demand, replenish
ms.date: 05/16/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: a6380570c9fb2bc5880bf531b4311fbf6e9cf4ec
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-purchase-items-for-a-sale"></a>Hvernig á að: Kaupa vörur fyrir sölu.
Frá sölupöntunum og sölureikningum geturðu notað aðgerð til stofna á skjótan hátt innkaupaskjöl fyrir vörumagn sem vantar en er krafist við söluna. Hægt er að nota tvær mismunandi aðgerðir, eftir gerð skjalsins.

|Virkni|Description|
|--------|-----------|
|**Stofna innkaupapantanir**|Frá sölupöntun, stofnar þessi aðgerð innkaupapöntun fyrir hvern lánardrottinn vöru á sölupöntuninni. Þú getur breytt innkaupamagninu áður en þú stofnar innkaupapantanirnar. Aðeins er ótiltækt sölumagn lagt til.
|**Stofna innkaupareikning**|Úr sölupöntun og úr sölureikningi getur þessi aðgerð stofnað innkaupareikning fyrir valinn lánardrottinn fyrir allar línur eða valdar línur í söluskjalinu. Lagt er til fullt sölumagn.|

## <a name="to-create-one-or-more-purchase-orders-from-a-sales-order"></a>Stofna eina eða fleiri innkaupapöntun úr sölupöntun
Til að stofna innkaupapöntun fyrir hvert ótiltækt vörumagn í sölupöntuninni, notarðu **Stofna innkaupapantanir** aðgerðina.

1. Á heimasíðunni skal velja **áframhaldandi Sölupöntun** gluggareit.
2. Opnuð er sölupöntun sem þú vilt kaupa vörur fyrir.
3. Velja **stofna innkaupapantanir** aðgerð.

    Glugginn **stofna innkaupapantanir** opnast og birtir eina línu fyrir hverja vöru í sölupöntuninni. Línur fyrir bæði fullkomlega tiltækt sölumagn og ótiltækt sölumagn (grámaðar) eru sýndar að sjálfgefnu. Þú getur valið **sýna ótiltækt** aðgerðina til að sjá aðeins línur fyrir ótiltækt sölumagn.

    Reiturinn **Magn til innkaupa** inniheldur ótiltækt sölumagn að sjálfgefnu.
4. Til að kaupa annað magn en ótiltækt sölumagn, skal breyta gildinu í **Magn til innkaupa** reitnum.

    > [!NOTE]  
   >   Þú getur líka breytt **Magn til innkaupa** reitnum á grámuðum línum jafnvel þótt þær sýni fullkomlega tiltækt sölumagn.
5. Velja hnappinn **Í lagi**.

    Innkaupapöntun er stofnuð fyrir hvern lánardrottinn vöru á sölupöntuninni, og í henni eru allar magnbreytingar sem þú kannt að hafa gert í **Stofna innkaupapöntun** glugganum.
6. Halda áfram að vinna innkaupapöntun eða pantanir, til dæmis með því að breyta eða bæta við innkaupareikningslínum. Nánari upplýsingar eru í [Hvernig á að: Skrá innkaup](purchasing-how-record-purchases.md).


## <a name="to-create-a-purchase-invoice-from-a-sales-order-or-sales-invoice"></a>Stofna innkaupareikning úr sölupöntun eða sölureikningi
Til að stofna stakan innkaupareikning fyrir eina eða fleiri línur í söluskjali með því að velja fyrst hvaða lánardrottni skal kaupa af, notarðu **Stofna innkaupareikning** aðgerðina.

> [!NOTE]  
>   Þessi aðgerð stofnar innkaupareikning fyrir nákvæmlega það vörumagn sem er á valda söluskjalinu. Til að breyta innkaupamagninu, þarftu að breyta innkaupareikningnum eftir að þú stofnar hann.  

1. Í reitnum heimasíða , velja **áframhaldandi Sölupöntun** gluggareit.
2. Opnuð er sölureikningur sem þú vilt kaupa vörur fyrir.
3. Veldu eitt eða fleiri sölureikningslínur sem þú vilt nota á innkaupareikningur. Til að nota alla sölureikningslínur, velja annaðhvort í heild eða ekki velja neinar línur.
4. Velja **stofna innkaupareikning** aðgerð.
5. Veldu annað hvort **Allar línur** eða  **valdar línur** og velja svo **Í lagi** hnappinn.  
6. Í listanum yfir lánardrottna sem birtist skaltu velja lánardrottin sem þú vilt kaupa allar vörurnar af, og þá velja **Í lagi** hnappinn.

    Innkaupareikningur er stofnaður með eina, fleiri eða allar línur sölureikningsins.
7. Halda áfram að vinna innkaupareikning, til dæmis með því að breyta eða bæta við innkaupareikningslínum. Nánari upplýsingar eru í [Hvernig á að: Skrá innkaup](purchasing-how-record-purchases.md).

## <a name="see-also"></a>Sjá einnig
[Innkaup](purchasing-manage-purchasing.md)  
[Hvernig á að skrá kaup](purchasing-how-record-purchases.md)  
[Hvernig er reikningsfært](sales-how-invoice-sales.md)  
[Hvernig á að Skrá nýja lánardrottna](purchasing-how-register-new-vendors.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

