---
title: "Tilgreina prentaraval fyrir skýrslur"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 55b48aef2bc108ced7f581f0ff6c11263ee467df
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---
    
# <a name="specify-printer-selection-for-reports"></a>Tilgreina prentaraval fyrir skýrslur
Hægt er að setja upp skýrslur þannig að það þurfi að prenta þær út á tilteknum prentara Hér á eftir koma nokkur dæmi um notkun prentaravals: 

- Hægt er að prenta skýrslur á sérstakt bréfsefni fyrirtækis.
- Hægt er að prenta færslur á mismunandi pappírstærðir.
- Hægt er að prenta skýrslur á sjálfgefnum prentara tiltekins starfsmanns.

Nota gluggann **prentaraval** til að stilla mismunandi gildi til að fá ólíka útkomu. Ef sértækt prentaraval er stillt hefur það forgang fram yfir almennt prentaraval. Til dæmis er hægt að stilla á prentaraval sem hefur gildi í reitunum **Kenni notanda**, **Kenni skýrslu** og **Prentaraheiti**. Þetta prentaraval hefur forgand yfir prentaraval með eyður í reitunum **Kenni notanda** eða **Kenni skýrslu**. 

Eftirfarandi tafla lýsir samsetningu gilda til að tilgreina hvenær eigi að setja upp prentaraval fyrir skýrslu.

|Til að                                                 |Stilla eftirfarandi gildi:                                             |
|---------------------------------------------------|---------------------------------------------------------------------|
|Prenta skýrslu í tilteknum prentara fyrir alla notendur |Tilgreinið gildi í reitunum **Kenni skýrslu** og **Prentaraheiti** og skiljið reitinn **Kenni notanda** eftir auðan.|
|Prenta allar skýrslur í tilteknum prentara fyrir tiltekinn notanda|Tilgreinið gildi í reitunum **Kenni notanda** og **Prentaraheiti** og skiljið reitinn **Kenni skýrslu** eftir auðan.|
|Stilla sjálfgefinn prentara fyrir allar skýrslur|Tilgreinið gildi í reitnum **Prentaraheiti** og skiljið reitina **Kenni notanda** og **Kenni skýrslu** eftir auða.|
|Prenta tiltekna skýrslu í sjálfgefnum prentara notandans|Tilgreinið gildi í reitnum **Kenni skýrslu** og skiljið reitina **Prentaraheiti** og **Kenni notanda** eftir auða.|
|Prenta tiltekna skýrslu í tilteknum prentara fyrir tiltekinn notanda|Tilgreinið gildi í öllum þremur reitunum.|

## <a name="see-also"></a>Sjá einnig
[Unnið með Dynamics NAV](ui-work-product.md)

