---
title: "Hvernig á að bóka söluskjöl"
description: "Kynntu þér mismunandi bókunaraðferðir til að bóka söluskjöl."
documentationcenter: 
author: SusanneWindfeldPedersen
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 06/02/2017
ms.author: solsen
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 7261e8faca0c14330e66093f8db3d44935c4d141
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="posting-sales"></a>Sölubókun
Í **bókunarflokki** á söluskjali er hægt að velja milli eftirfarandi bókunaraðgerða:

* **Færsla**
* **Prófunarskýrsla**
* **Bóka og senda**
* **Bóka og prenta**
* **Bóka og senda í tölvupósti**
* **Bóka runu**
* **Forskoðun bókunar**

Þegar lokið hefur verið við allar línurnar og allar upplýsingar færðar á sölupöntunina er hægt að bóka hana. Þetta stofnar afhendingu og reikning.

Þegar sölupöntun er bókuð, eru reikningur viðskiptavinar, fjárhagurinn og birgðahöfuðbókarfærslur uppfærðar.

Sölufærsla er stofnuð í töflunni G/L Entry **fjárhagsfærsla** fyrir hverja sölupöntun. Færsla er einnig stofnuð í reikningi viðskiptamanns í töflunni **sérsniðin fjárhagsfærsla** og fjárhagsfærsla er stofnuð í viðeigandi safnreikningi viðskiptamanns. Auk þess getur bókun pöntunarinnar leitt til VSK-færslu og fjárhagsfærslu vegna afsláttar. Hvort færsla vegna afsláttar er bókuð fer eftir því sem er í glugganum **Afsláttarbókun** í töflunni **Sölugrunnur**.

Birgðafærsla er stofnuð í töflunni **birgðafærsla** fyrir hverja sölupöntunarlínu (ef línurnar eru með vörunúmerum) eða þá að fjárhagsfærsla er stofnuð í töflunni **Fjárhagsfærsla** (ef fjárhagsreikningur er í sölulínunum). Auk þess eru sölupantanir alltaf skráðar í töflunum **Söluafhendingarhaus** og **Sölureikningshaus**.

> [!IMPORTANT]  
>   Þegar pöntun er bókuð er hægt að búa til bæði afhendingu og reikning. Það er hægt að gera á sama tíma eða hvort í sínu lagi. Einnig er hægt að mynda hlutaafhendingu og gera hlutareikning með því að fylla út reitina **magn til að flytja** og/eða **magn til að reikningsfæra** í einstökum sölupöntunarlínum áður en bókað er. Bent er á að ekki er hægt að búa til reikning fyrir eitthvað sem ekki er afhent. Það er að segja, áður en hægt er að gera reikning verður afhending að vera skráð, nema afhending sé skráð um leið og reikningur er gerður.

Þegar bókun er lokið hverfa bókuðu sölulínurnar úr pöntuninni. Skilaboð segja til um hvenær bókun er lokið. Að þessu loknu verður hægt að sjá bókuðu færslurnar í ýmsum af þeim gluggum sem innihalda bókaðar færslur, eins og **Viðskiptamannafærslur**, **Fjárhagsfærslur**, **Birgðafærslur,**, **Bókuð söluafhending** og **Bók. sölureikningur**.

## <a name="see-also"></a>Sjá einnig
[Sala](sales-manage-sales.md)  
[Hvernig á að: Senda skjöl í tölvupósti](ui-how-send-documents-email.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)


