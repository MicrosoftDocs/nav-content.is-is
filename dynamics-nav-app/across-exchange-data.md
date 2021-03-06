---
title: Gagnaskipti
description: "Hægt er að skipta á gögnum á milli [!INCLUDE[d365fin](includes/d365fin_md.md)] og ytri skráa eða strauma í tengslum við algeng viðskiptaverk, s.s. að senda og taka á móti rafrænum skjölum og flytja inn og út bankaskrár."
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/18/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: d83e68f31edf2dee9e3e5bc5b73a4861cfe919d7
ms.contentlocale: is-is
ms.lasthandoff: 10/23/2017

---
# <a name="exchanging-data"></a>Gagnaskipti
Hægt er að skipta á gögnum á milli [!INCLUDE[d365fin](includes/d365fin_md.md)] og ytri skráa í tengslum við algeng viðskiptaverk, s.s. að senda og taka á móti rafrænum skjölum og flytja inn og út bankaskrár.  

Áður en hægt er að senda og taka á móti rafrænum skjölum eða flytja inn og út bankaskrár verður að setja upp gagnaskiptaramma til að vinna úr umræddum gagnaskjölum eða straumum. Auk þess verður að setja upp tengd svæði. Þau gætu t.d. verið aðalgögn fyrir viðskiptamenn sem fá senda rafræna reikninga eða umskráningarþjónusta fyrir bankagögn ef umbreytingu bankaskráa er dreift á ytri þjónustuveitur. Nánari upplýsingar er að finna í [Uppsetning gagnaskipta](across-set-up-data-exchange.md).  

 Eftirfarandi tafla lýsir röð verkefna með tenglum í efnisatriði þar sem þeim er lýst.  

|**Til að**|**Sjá**|  
|------------|-------------|  
|Umbreyta söluskjalafærslum í [!INCLUDE[d365fin](includes/d365fin_md.md)] í staðlað snið og senda þær sem rafræn skjöl sem viðskiptamenn geta fengið inn í kerfið sitt.|[Hvernig á að: Senda rafræn skjöl](sales-how-to-send-electronic-documents.md)|  
|Nota OCR-þjónustu til að breyta PDF eða myndaskrám í rafræn skjöl sem hægt er að breyta í færslur fyrir skjöl í [!INCLUDE[d365fin](includes/d365fin_md.md)].|[Hvernig á að: Nota OCR til að breyta PDF og myndaskrám í rafræn skjöl](across-how-use-ocr-pdf-images-files.md)|  
|Taka á móti rafrænum skjölum, annaðhvort úr OCR-þjónusta eða skjalaskiptaþjónusta, í stöðluðu sniði sem umbreytt er í viðeigandi innkaupaskjalsfærslu í [!INCLUDE[d365fin](includes/d365fin_md.md)].|[Hvernig á að: Taka við pg umbreyta rafræn skjölum](purchasing-how-to-receive-and-convert-electronic-documents.md)|  
|Flytjið bankayfirlitsskrá inn í gluggann **greiðsluafstemmingarbók** sem fyrsta skrefið í afstemmingu greiðsla eða inn í gluggann **Afstemming bankareiknings** sem fyrsta skrefið í að afstemma bankareikninga.|[Jafna greiðslur sjálfkrafa og afstemma bankareikninga](receivables-apply-payments-auto-reconcile-bank-accounts.md)|  
|Flytja greiðslur úr **greiðslubók** glugganum í bankaskrá sem er hlaðið upp á rafrænan bankareikning til vinnslu.|[Hvernig á að: Flytja út greiðslur í bankaskrá](payables-how-export-payments-bank-file.md)|  
|Gefið bankanum fyrirmæli um að flytja greiðsluupphæðir af bankareikningum viðskiptavina á bankareikninga fyrirtækisins í samræmi við uppsetningu SEPA-beingreiðslna.|[Hvernig á að: Stofna SEPA-innheimtufærslur fyrir beingreiðslur og flytja út í bankaskrá](finance-how-create-sepa-direct-debit-collection-entries-export-bank-file.md)|  
|Nota gengi þjónustuveitu gengi gjaldmiðla til að uppfæra **gengi** gluggann.|[Hvernig á að: Uppfæra gengi](finance-how-update-currencies.md)|  
|Skoðið hvaða skráareiginleikar eru varpaðir á reiti í [!INCLUDE[d365fin](includes/d365fin_md.md)] við innflutning SEPA CAMT yfirlitsskráa.|[Reitarvörpum við innflutning SEPA CAMT skráa](across-field-mapping-when-importing-sepa-camt-files.md)|  
|Skoðið hvaða reitir í [!INCLUDE[d365fin](includes/d365fin_md.md)] hefur verið varpað á skráareiginleika við útflutning greiðsluskráa með umreikningsþjónustu bankadagsetninga.|[Reitarvörpun við útflutning greiðsluskrá með umskráningarþjónusta fyrir bankagögn](across-field-mapping-when-exporting-payment-files-using-bank-data-conversion-service.md)|  

## <a name="see-also"></a>Sjá einnig  
[Setja upp gagnaskipti](across-set-up-data-exchange.md)  
[Rafræn gagnaskipti](across-data-exchange.md)  
[Hvernig er reikningsfært](sales-how-invoice-sales.md)   
[Hvernig á að skrá kaup](purchasing-how-record-purchases.md)  
[Skjöl á innleið](across-income-documents.md)  
[Almenn viðskiptavirkni](ui-across-business-areas.md)  

