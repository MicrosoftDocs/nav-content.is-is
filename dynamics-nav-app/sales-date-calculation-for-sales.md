---
title: "Dagsetning útreiknings fyrir sölu."
description: "Forritið reiknar sjálfkrafa daginn sem verður að panta vöru svo hún sé til í birgðum á tilteknum degi. Þetta er dagsetningin sem vænta má þess að vara sem pöntuð er á tilteknum degi verði tiltæk til tínslu."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 72e8f2a2f1d2d6427c716205da7ecee58b85bcc6
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="date-calculation-for-sales"></a>Dagsetning útreiknings fyrir sölu.
[!INCLUDE[d365fin](includes/d365fin_md.md)] reiknar sjálfkrafa út hvenær hægt er að afhenda vöru á sölupöntunarlínu í fyrsta lagi.

Hafi viðskiptamaðurinn farið fram á tiltekna afgreiðsludagsetningu þá er reiknuð út sú dagsetning sem vörurnar þurfa að vera tilbúnar þannig að afgreiðsla geti farið fram á þeim degi.

Hafi viðskiptamaðurinn ekki farið fram á tiltekna afgreiðsludagsetningu þá er dagsetning sem hægt er að afgreiða vörurnar reiknuð út frá deginum sem vörurnar verða tilbúnar.

## <a name="calculating-a-requested-delivery-date"></a>Reiknar ósk um afhendingardag
Ef tilgreindur er afgreiðsludagsetning á sölupöntunarlínunni notar forritið þessa dagsetningu sem upphafspunkt fyrir eftirfarandi útreikninga.

- Umbeðin afgreiðsludagsetning – Flutningstími = Áætluð afhendingardagsetning
- sfhendingardagsetning + afgr.tími vara á útl. úr vöruh. = afh.dags.

Ef varan er tiltæk til tínslu á afhendingardagsetningu þá getur söluferlið haldið áfram.

Ef varan er ekki tiltæk til tínslu á afhendingardegi þá birtist viðvörun um að varan sé uppseld.

## <a name="calculating-the-earliest-possible-delivery-date"></a>Reiknar fyrsta mögulega afgreiðsludag
Ef ekki er tilgreind umbeðin afgreiðsludagsetning á sölupöntunarlínunni, eða ef ekki er hægt að verða við umbeðinni afgreiðsludagsetningu, er reiknuð fyrsta dagsetningin sem vörurnar eru tiltækar. Sú dagsetning er færð inn í reitinn Afhendingardagsetning á línuna og eftirtaldar reiknireglur eru síðan notaðar til að reikna út hvenær áætlað er að senda vörurnar ásamt því á hvaða degi viðskiptamaðurinn fær þær afhentar.

- Afhendingardagsetning + afgr.tími vara á útl. úr vöruh. = Áætluð afhendingardagsetning
- áætluð afhendingardagsetning + flutningstími = áætluð afgreiðsludagsetning


## <a name="see-also"></a>Sjá einnig  
 [Dagsetning útreiknings fyrir kaup.](purchasing-date-calculation-for-purchases.md)   
 [Hvernig á að: Reikna dagsetningu pöntunarloforðs](sales-how-to-calculate-order-promising-dates.md)  
 [Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

