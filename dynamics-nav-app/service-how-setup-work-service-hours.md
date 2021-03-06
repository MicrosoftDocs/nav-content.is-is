---
title: "Hvernig á að Setja upp vinnustundir og þjónustustundir"
description: "Þú getur tilgreint venjulegan þjónustuvinnustundir í fyrirtækinu. Stuðst er við þessar þjónustustundir við útreikning á svardagsetningu og tíma vegna þjónustupantana og tilboða og til að senda viðvörunarboð vegna svartíma."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 7b4d813f734fbaa53bc185e2477ca73705872097
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-work-hours-and-service-hours"></a>Hvernig skal: Setja upp vinnustundir og þjónustustundir
Þjónustukerfi rekur yfirleitt forðastundir og stöðu þjónustupantana til að spá fyrir um vinnuálag og þjónustuþarfir. [!INCLUDE[d365fin](includes/d365fin_md.md)] er með innbyggð verkfæri sem hægt er að sérstilla til að skrá þessa gerð upplýsinga.  
  
Eftir að sjálfgefinn þjónustutími fyrirtækisins hefur verið stilltur er hægt að reikna út svartíma þjónustupantana eða senda út viðvaranir þegar þjónustusímtöl berast. Viðvörunareiginleikinn er notaður samhliða verktímasetningu.   
  
Þegar þú vinnur að þjónustupöntun, muntu vilja uppfæra stöðu hennar svo þú getir fylgst með ferlinu. Þjónustupöntunarstaðan sýnir viðgerðarstöðu allra þjónustuvara í þjónustupöntuninni. Frekari upplýsingar eru í [Skilja þjónustupöntun og viðgerðarstöðu](service-order-repair-status.md). 

## <a name="to-set-up-default-service-hours"></a>Uppsetning sjálfgefinna þjónustustunda  
Glugginn **Sjálfgefinn þjónustutími** er notaður til að setja upp venjulegan þjónustutíma í fyrirtækinu. Stuðst er við þessar þjónustustundir við útreikning á svardagsetningu og tíma vegna þjónustupantana og tilboða og til að senda viðvörunarboð vegna svartíma. Kerfið notar sjálfgefinn þjónustutíma í þjónustusamninga nema sérstakar þjónustustundir séu tilgreindar vegna samnings.  
  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Sjálfgefnar þjónustustundir** og velja svo viðeigandi tengil.  
2. Fyllið inn í reitina eftir þörfum. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  
  
> [!IMPORTANT]  
>  Ef línurnar í glugganum **Sjálfgefinn þjónustutími** eru auðar eru 24 stundir sem sjálfgefið gildi sem gildir aðeins á virkum dögum.  
  
## <a name="to-set-up-work-hour-templates"></a>Uppsetning vinnutímasniðmáta
Nota má gluggann **Vinnutímasniðmát** til að setja upp sniðmát með dæmigerðum vinnustundum í fyrirtækinu. Til dæmis má stofna sniðmát fyrir tæknimenn í fullu starfi og í hlutastarfi. Vinnutímasniðmát má nota þegar getu er bætt við forða.  
  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **vinnustundasniðmát** og velja svo viðeigandi tengil.  
2. Fyllið inn í reitina eftir þörfum. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  
  
> [!Note]
> Eftir að þú færir inn vinnustundir fyrir hvern dag, er reiturinn **Heildarstundir á viku** reiknaður út sjálfkrafa.  

## <a name="to-set-up-contract-specific-service-hours"></a>Uppsetning samningsbundinna þjónustutíma  
Hægt er að nota gluggann **Þjónustutími** til að setja upp tiltekna þjónustutíma fyrir viðskiptamanninn sem á þjónustusamninginn. Kerfið styðst við þjónustutíma þegar það reiknar út svardagsetningu og svartíma vegna þjónustupantana og tilboða sem tilheyra þjónustusamningnum.  
  
Ef ekki eru tilgreindar sérstakar þjónustustundir vegna þjónustusamningsins er notaður sjálfgefinn þjónustutími vegna þjónustusamninga.  
  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Þjónustusamningar** og velja svo viðeigandi tengil.  
2. Opna skal þjónustusamning sem setja á upp sérststakar þjónustustundir fyrir og veldu **Þjónustustundir**.  
4. Ef setja á upp þjónustustundir sem byggjast á sjálfgefnum þjónustutíma er smellt á **Afrita sjálfgefinn þjónustutíma** aðgerðina.  
5. Breyta reitunum í þjónustutímafærslunum. Bæta við eða eyða færslum til að setja upp þjónustustundafjölda fyrir samninginn. Athugið að reitirnir **Dagur**, **Upphafstími** og **Lokatími** eru nauðsynlegir fyrir hverja línu.  
6. Ef þjónustutíminn á að gilda frá tiltekinni dagsetningu þarf að fylla út reitinn **Upphafsdagsetning**.  
7. Ef þjónustutíminn á að gilda á frídögum er merkt í gátreitinn í reitnum **Gildir á frídögum**.  

## <a name="see-also"></a>Sjá einnig  
[Skilja úthlutunarstaða og viðgerðarstaða](service-allocation-status-and-repair-status.md)  
[Þjónustustýring sett upp](service-setup-service.md)  
[Skilja þjónustupöntun og viðgerðarstöðu](service-order-repair-status.md).  

