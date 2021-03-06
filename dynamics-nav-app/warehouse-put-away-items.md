---
title: "Frágangur á vörum"
description: "Vöruhúsaaðgerðin að ganga frá vörum eftir að tekið er á móti þeim, eða frálag, er framkvæmd með mismunandi hætti eftir því hvernig aðgerðir vöruhúsakerfis eru grunnstilltar."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/31/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 0b68ef1b4c73eef1ac82d59587011a0fcdead096
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="putting-items-away"></a>Vörufrágangur
Vöruhúsaaðgerðin að ganga frá vörum eftir að tekið er á móti þeim, eða frálag, er framkvæmd með mismunandi hætti eftir því hvernig aðgerðir vöruhúsakerfis eru grunnstilltar. Flækjustigið getur verið allt frá engum vöruhúsaaðgerðum, gegnum einfaldar grunngerðum vöruhúss með meðhöndlun pöntun fyrir pöntun í einni eða fleiri aðgerðum einvörðungu, til ítarlegra grunnstillinga þar sem allar vöruhúsaaðgerðir eru framkvæmdar í beinu verkflæði. Nánari upplýsingar er að finna í [Uppsetning vöruhúsastjórnunar](warehouse-setup-warehouse.md).

Ef ákveðið er að skipuleggja og skrá frágangsupplýsingar með fylgiskjölum í kerfinu er sett gátmerki í reitinn **Krefjast frágangs** á birgðageymsluspjaldinu. Þetta segir kerfinu að þegar um er að ræða vörur sem koma inn í vöruhúsið með upprunaskjali á innleið, að þú vilt að fráganginum af þessum vörum sé stjórnað af kerfinu. Upprunaskjalið á innleið getur verið innkaupapöntun, söluvöruskilapöntun, millifærslupöntun á innleið eða framleiðslupöntun þar sem úttakið er tilbúið til frágangs.  

Þegar birgðageymslan er sett upp þannig að hún noti frágangsvinnslu en ekki móttökuvinnslu skal nota gluggann **Birgðafrágangur** til að skipuleggja frágangsupplýsingar, prenta þær, færa inn niðurstöður af raunverulegum frágangi og bóka frágangsupplýsingar, sem á móti bóka móttökuupplýsingar fyrir upprunaskjalið. Ef um er að ræða framleiðslupöntun, bókar bókunarferlið frálag pöntunarinnar og lýkur henni.

Ef vöruhúsið er sett upp þannig að það krefjist bæði móttökuvinnslu og frágangsvinnslu þannig að merkt hefur verið bæði við **Krefjast móttöku** og **Krefjast frágangs** á birgðageymsluspjaldinu er ferlið við frágang á vörum annað. Í því tilviki er glugginn **Vöruhúsafrágangur** notaður til að sjá um frágang. Vöruhúsafrágangur er svipaður birgðafrágangi, nema í stað þess að bóka upplýsingarnar er frágangurinn skráður. Athugið að skráning á frágangi vöruhúsins bókar ekki móttöku varanna. Það uppfærir aðeins innihald hólfsins. Sem stjórnandi vöruhúss, geturðu notað frágangsvinnublað til að flokka frágangsupplýsingar áður en þú stofnar einstakar frágangsleiðbeiningar vöruhússins.

Eftirfarandi tafla lýsir röð verkefna með tenglum í efnisatriði þar sem þeim er lýst.   

|**Til að**|**Sjá**|  
|------------|-------------|  
|Bóka móttöku vöru beint frá pantanaskjali á innleið, og um leið skrá fráganginn, því engar vöruhúsaskilgreiningar eru fyrir hendir.|[Hvernig á að: Taka á við vörum](warehouse-how-receive-items.md)|  
|Ganga frá vöru pöntun fyrir pöntun og bóka móttöku í sömu aðgerð, í einfaldri vöruhúsagrunnstillingu.|[Hvernig á að ganga frá vörum með birgðarfrágangi](warehouse-how-to-put-items-away-with-inventory-put-aways.md)|  
|Ganga frá vörum fyrir margar pantanir í ítarlegri vöruhúsagrunnstillingu.|[Hvernig á að ganga frá vörum með vöruhúsafrágangi](warehouse-how-to-put-items-away-with-warehouse-put-aways.md)|  
|Ganga frá framleiðslu eða samsetningu vörur í einfaldri eða ítarlegri vöruhúsagrunnstillingu.|[Hvernig skal: Ganga frá framleiðslu eða samsetningarfrálagi](warehouse-how-to-put-away-production-output.md)|
|Áætla leiðbeiningar um besta frágang fyrir margar bókaðar vöruhúsainnhreyfingar í stað þess að starfsmenn vöruhúss vinni beint með innhreyfingar.|[Hvernig á að áætla frágang á vinnublöðum](warehouse-how-to-plan-put-aways-in-worksheets.md)|  
|Skila aftur vörum sem voru tíndar í innanhússtínslu, til dæmis fyrir framleiðslupöntun sem notaði ekki væntanlegt magn.|[Hvernig skal: tína og ganga frá án upprunaskjals](warehouse-how-to-create-put-aways-from-internal-put-aways.md)|
|Skipta frágangslínu til þess að setja hluta af frágangsmagninu í tiltækt hólf því merkta hólfið er orðið fullt.|[Hvernig á að skipta vöruhúsaaðgerðalínum](warehouse-how-to-split-warehouse-activity-lines.md)|
|Fá tafarlausan aðgang að frágangi sem notandi hefur fengið úthlutað sem starfsmaður vöruhúss.|[Hvernig á að finna vöruhúsaúthlutanir](warehouse-how-to-find-your-warehouse-assignments.md)|    

## <a name="see-also"></a>Sjá einnig  
[Vöruhúsastjórnun](warehouse-manage-warehouse.md)  
[Birgðir](inventory-manage-inventory.md)  
[Vöruhúsastjórnun sett upp](warehouse-setup-warehouse.md)     
[Samsetningardeild](assembly-assemble-items.md)    
[Hönnunarupplýsingar vöruhúsakerfi](design-details-warehouse-management.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

