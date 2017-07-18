---
title: "Söluskattur og skattflokkar í Bandaríkjunum og Kanada"
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: f70a191fc8392bf1685c08c7e905ac96ba7ed069
ms.contentlocale: is-is
ms.lasthandoff: 06/26/2017

---

# <a name="sales-tax-and-tax-groups-in-the-us-and-canada"></a>Söluskattur og skattflokkar í Bandaríkjunum og Kanada
Þegar fyrst er byrjað að nota Dynamics NAV er hægt að keyra hjálparuppsetningu til að setja upp söluskattsupplýsingar á einfaldan hátt fyrir fyrirtækið þitt, einnig viðskiptamenn og lánardrottna. Á nokkrum mínútur, er hægt að stofna söluskjöl og innkaupaskjölum með rétt reiknaðan söluskatt.
Ef þú færir yfir í tóma mitt fyrirtæki, mælum við með að þú byrjir að nota hvern og einn hjálparuppsetningarleiðbeiningar, þar á meðan einn fyrir VSK. Ef kosið er að setja upp söluskattur sjálfur, útskýrir þessi grein hvað þarf að taka tillit til.  

## <a name="tax-groups-tax-areas-and-tax-jurisdictions"></a>Skattflokka, Skattsvæði og Skattlögsögur
Í Dynamics NAV táknar skattflokk birgðir eða forða sem lúta sömu skattlagningu. Til dæmis er hægt að setja upp skattflokkur fyrir vörur sem eru skattskyld og aðrar óskattskyldar vörur. Þú Verður að úthluta skattflokkskóði fyrir vörur í birgðum og fjárhagsreikninga. Á sama hátt verður að úthluta skattsvæðiskóðum til viðskiptamanna, staðsetninga og eigin stillingar fyrirtækis. Uppsetningar með hjálp hjálpa þér að gera þetta.  

Hver skattsvæði er flokkaskipan söluskattslögsagnarumdæma sem byggðar eru á tiltekna landsvæði. Til dæmis innifela skattsvæði Miami, Florida þrjú lögsagnarumdæmi söluskatts: (Miami) bær, sýsla (Dade) og sýsla (Florida). Dynamics NAV felur í sér takmarkað safn skattsvæða, með sjálfgefinnar grunnstillingar, en hægt að breyta þeim og bæta við nýjum skattsvæði.  

Ef sett er upp ný skattsvæði og skattlögsögur þarf að ganga úr skugga um að fylla út reitina rétt. Í Bandaríkjunum, geta ríki, sýslur og bæir og bæjarfélag rukkað VSK. Í Canada, getur alríkisstjórnin og sveitarfélög rukkað söluskatt. Stofnanir safna og standa skil söluskattur til þessara stjórnvalda fyrir vörur seldar til notenda Söluskattur er einnig hægt að greiða til núverandi söluskattur. Til dæmis, skatta má reikna á sölureikningi upphæð sem þegar inniheldur skatt frá öðrum löndum.  

Í Kanada, verður skattfjárhæðirnar að vera ítarlegar fyrir hvern skattalögsögu. Allt að fjórir lögsagnarumdæmi hægt að sýna í skjali, og lögsagnarumdæmi sem hafa sama prenta röð eru sameinuð þegar þeir eru prentaðir.

## <a name="tax-details"></a>Skattsundurliðun
Í **Skattasundurliðanir** glugginn sýnir mismunandi samsetningar söluskattlögsagaa og söluskatthópa til að finna gengi söluskatts. Fyrir hverja skatta lögsögu, mælum við með að þú stillir upp einn skatt hóp fyrir venjulega söluskattur, annar skatthópur fyrir vörur eða þjónustu sem ekki eru skattlagðar, og til viðbótar skatthóp fyrir hverja tegund af hlut eða þjónustu sem er stjórnað með mismunandi söluskatthlutfalli í þeirri lögsögu.  

Í Bandaríkjunum, þegar þú selur til viðskiptavina á stað þar sem þú þarft ekki að hafa *situs* - eða löglega staðsetningu í því ríki - innheimtirðu ekki VSK. Að stöðum þar sem þú ert ekki með situs, skal tryggja að bæði **skattur undir lágmarki** og **skattur yfir hámarki** reitir eru 0.00.  

## <a name="see-also"></a>Sjá einnig
[Fjármál](finance-setup.md)  
[Uppsetning fjármála](finance-setup-setup-finance-setup.md)  
[Söluskattur og vöru- og þjónustuskattur í Kanada](ca-finance-setup-tax.md)  
[Uppsetning söluskatts gerð auðveld](https://madeira.microsoft.com/en-us/blog/sales-tax-setup-made-easy)  

