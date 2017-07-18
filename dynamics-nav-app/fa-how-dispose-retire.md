---
title: "Hvernig á að: afskrá eða innkalla eignir"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 795bb23e7c0b46be095b2bbdfe7705b3d7b1e4ee
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-dispose-of-or-retire-fixed-assets"></a>Hvernig á að: afskrá eða innkalla eignir
Þegar eign er seld eða afskráð með öðrum hætti verður að bóka afskráningarverðmæti hennar til að reikna út og skrá hagnað eða tap. Afskráningarfærsla verður að vera síðasta færslan sem bókuð er vegna eignar. Vegna eigna sem eru að hluta afskráðar er hægt að bóka eina eða fleiri afskráningarfærslur. Samtala allra bókaðra afskráningarupphæða verður að vera kreditupphæð.

 **Athugasemd**: Ef ný eign kemur í stað annarar verður að skrá bæði söluna á gömlu eigninni (afskráning) og innkaupin á þeirri nýju (kaup). Nánari upplýsingar eru í [Hvernig á að: komast ufir eignir](fa-how-acquire.md).

## <a name="to-post-a-disposal-from-the-fixed-asset-gl-journal"></a>Bóka afskráningu úr fjárhagsbók eigna  
1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **fjárhagsbók eigna**, og velja síðan viðeigandi tengil.  
2. Stofnaður er upprunaleg Færslubókarlína og reitirnir fylltir út eftir þörfum. Velja reit til að lesa inn stutta lýsingu á reitnum eða tengil í frekari upplýsingar.
3. Í reitnum **Eignabókunartegund** er valinn **afskráning**.
4. Valið er **Setja inn mótreikn. eigna** aðgerð. Seinni færslubókarlína er búin til fyrir mótreiknings sem er sett upp fyrir bókun afskráningar.

    **Athugasemd**: skref 4 virkar eingöngu ef búið er að setja upp eftirfarandi: Í **Eignabókunarflokksspjald** glugganum fyrir bókunarflokkur eigna, inniheldur reiturinn **afskráningarreikningur** debetreikning fjárhags og reikningurinn **Mótreikning afskráningar** inniheldur fjárhagsreikninginn sem á að bóka mótfærslur í fyrir uppfærslu. Nánari upplýsingar eru í "setja upp bókunarflokka eigna" hlutanum í [Hvernig: Setja Upp almennar upplýsingar um eignir](fa-how-setup-general.md).
5. Valið er **bóka** aðgerð.

Ef hluti eignar er seldur eða afskráður verður að skipta eigninni upp í hluta áður en hægt er að afskrá. Nánari upplýsingar eru í [Hvernig á að: skipta upp, eða sameina eignir](fa-how-trans-split-combine.md).

## <a name="to-view-disposal-ledger-entries"></a>Skoðun afskráningarfærslna:  
Þegar eign er seld eða afskráð með öðrum hætti er afskráningarverðmæti hennar bókað í fjárhags þar sem má sjá niðurstöðurnar.   

1. Í efra hægra horni skal velja táknið **Leita að síðu eða skýrslu**, slá inn **eignir**, og velja síðan viðeigandi tengil.  
2. Valin er eignin sem á að skoða færslur fyrir og veldu síðan aðgerðina **afskriftabækur**.
3. Valin er afskriftabók sem á að skoða færslur fyrir og veldu síðan aðgerðina **fjárhagsfærslur**.
4. Í reitnum **Eignabókunarflokkur** er valin línan þar sem stendur **Afskráning** og síðan smellt á aðgerðina **Skoða**.  
5. Í glugganum **skoða** er valin línan Fjárhagsfærsla og síðan smellt á aðgerina **Sýna**.
Glugginn **Fjárhagsfærslur** opnastþa sem sjást færslurnar sem afskráningarfærslan hefur myndað.

## <a name="see-also"></a>Sjá einnig
[Eignastjórnun](fa-manage.md)  
[Uppsetning eigna](fa-setup.md)  
[Fjármál](finance-setup.md)  
[Velkomin í Dynamics NAV](across-get-started.md)

