---
title: "Hvernig á að skipuleggja tínslur á vinnublaðinu"
description: "Ef vöruhúsið er sett upp með bæði tínslu- og afhendingarvinnslu er hægt að velja að línurnar á afhendingarskjölum flytjist ekki sjálfkrafa í tínsluleiðbeiningar heldur verði þess í stað tiltækar á vinnublaði tínslunnar."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/21/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 9483eda38a9db7cd50d7167b45d0c6b6d21ace8c
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-plan-picks-in-worksheets"></a>Hvernig á að skipuleggja Tínslur á vinnublaðinu
Ef vöruhúsið er sett upp með bæði tínslu- og afhendingarvinnslu er hægt að velja að línurnar á afhendingarskjölum flytjist ekki sjálfkrafa í tínsluleiðbeiningar heldur verði þess í stað tiltækar á vinnublaði tínslunnar.  

> [!NOTE]  
>  Hafi tínsluleiðbeiningar vöruhúss þegar verið stofnaðar og sameina á þær í stakar skilvirkar tínsluleiðbeiningar þarf að eyða hverri vöruhúsatínslu fyrir sig. Línurnar sem á að tína má nú lista á vinnublaðinu.  

Á tínsluvinnublaðinu er hægt að setja upp tínslulista fyrir starfsmenn sem minnkar tímann sem starfsmaðurinn notar til að fara um vöruhúsið og tína vörur. Það eru reitir með upplýsingum varðandi tiltækt magn af vörum í hjáskipunarhólfunum. Þetta er gagnlegt við hjáskipun þegar skipuleggja á verkúthlutanir þar sem kerfið leggur alltaf til að tínt sé úr hjáskipunarhólfi á undan öðrum hólfum, óháð mælieiningum. Línurnar á vinnublaðinu geta komið úr ýmsum upprunaskjölum og þeim má raða eftir vöru, hillunúmeri., upprunaskjali, gjalddaga eða sendist-til aðsetri.  

Ef raðað er eftir gjalddaga er hægt að eyða öllum línum öðrum en þeim sem sinna þarf strax af vinnublaðinu. Minna áríðandi línum er ekki eytt þannig séð, heldur fara þær aftur á vinnublaðið **Tínsluval**. Þegar tínslan er stofnuð hefur línunum þegar verið raðað eftir gjalddaga og hægt er að úthluta tínslunni á tiltekinn starfsmann.  

> [!NOTE]  
>  Tínsla fyrir vöruhúsaafhendingu vara sem settar eru saman úr sölupöntuninni sem verið er að afenda fylgir sömu aðferð og hefðbundin vöruhúsatínsla fyrir afhendingu eins og lýst er í þessu efnisatriði. Hins vegar gæti fjöldi tínslulína miðað við afhendingarmagn verið af gerðinni n:1 þar sem íhlutar eru tíndir en ekki samsetningarvaran.  
>   
>  Vöruhúsatínslulínurnar eru stofnaðar fyrir gildið í reitnum **Eftirstöðvar** í línum samsetningarpöntunarinnar sem tengist sölupöntunarlínunni sem verið er að afhenda. Þetta tryggir að allir íhlutir eru tíndir í einni aðgerð.  
>   
>  Nánari upplýsingar eru í hlutanum „Meðhöndlun íhluta pantanasamsetninga í afhendingum vöruhúss” í afhendingum vöruhúss .  
>   
>  Upplýsingar um almenna tínslu íhluta fyrir samsetningarpantanir, þar á meðal þegar samsetningaríhlutur er ekki hluti af söluafhendingu, eru í [Hvernig skal: tína fyrir framleiðslu eða samsetningu í grunngerð ítarlegs vöruhúss](warehouse-how-to-pick-for-internal-operations-in-advanced-warehousing.md).  

## <a name="to-plan-picks-in-the-worksheet"></a>Tínslur skipulagðar á vinnublaðinu:  
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Vinnublað tínslu** og velja svo viðeigandi tengil.  
2.  Valið er **Sækja vöruhúsaskjöl** aðgerðin.  
3.  Afhendingarnar sem undirbúa á tínslu fyrir eru valdar. Nú er hægt að raða línunum upp að vissu marki en röðunin sem hér er gerð flyst ekki áfram í tínsluleiðbeiningarnar. Einnig er hægt að eyða línum til að gera tínsluna skilvirkari. Til dæmis, ef til eru línur með vörum í hjáskipunarhólfum er hægt að stofna tínslu fyrir allar línur sem tengjast þeim línum. Hjáskipunarvörurnar verða sendar (ásamt hinum vörunum í afhendingunum) og hjáskipunarhólfin hafa pláss fyrir fleiri vörur.  
4.  Velja aðgerðina **Stofna tínslu** og beiðniglugginn **Stofna tínslu** er fylltur út. Röðunin hér raðar tínslulínunum sem stofnaðar eru. Til dæmis er hægt að stofna eina tínslu fyrir hvert svæði og raða línum eftir hólfaflokkum innan hverrar tínslu.  
5.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Tínsla** og velja svo viðeigandi tengil. Glugginn **Tínsla** opnast.  
6.  Nú er hægt að finna tínsluúthlutunina sem stofnuð var með því að velja tínsluna með hæsta númerinu.  
7.  Í tínslunni er hægt að breyta notandakenninu og röðun línanna ef þess þarf.  
8.  Veldu hnappinn **Prenta** til þess að prenta tínsluleiðbeiningarnar.  
9. Þegar tínslunni er lokið skal velja aðgerðina **Skrá**.  

Hafi hólfin verið númeruð í samræmi við eiginlegt skipulag vöruhússins flýtir röðun lína eftir hólfakóta tínslu á nokkrum afhendingum í einni ferð um vöruhúsið. Starfsmaðurinn tekur tilskilinn fjölda af vörum fyrir hverja afhendingu úr hverju hólfi og setur þær með hinum vörunum í afhendingunni. Tínslumaður getur sparað mikinn tíma með því að tína í nokkrar afhendingar í einni ferð í hólfið.  

Önnur skilvirk röðun er eftir hólfaflokkun ef eiginlegt skipulag vöruhússins samsvarar hólfaflokkun meira en hólfakótum.  

Á vinnublaði tínslunnar er einnig hægt að raða eftir sendist-til aðsetrum þannig að hægt sé tína í og senda pantanir til viðskiptamanna sem lengst eru frá fyrst.  

## <a name="see-also"></a>Sjá einnig
[Vöruhúsastjórnun](warehouse-manage-warehouse.md)  
[Birgðir](inventory-manage-inventory.md)  
[Vöruhúsastjórnun sett upp](warehouse-setup-warehouse.md)     
[Samsetningardeild](assembly-assemble-items.md)    
[Hönnunarupplýsingar vöruhúsakerfi](design-details-warehouse-management.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

