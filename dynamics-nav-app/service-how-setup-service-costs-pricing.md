---
title: "Setja upp verð og kostnað fyrir þjónustu"
description: "Lærðu hvernig á að setja verð og aukakostnað fyrir þjónustu."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: service, cost, service order
ms.date: 08/22/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 014445360336ac00e00e5569a48e4866fc843afb
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---

# <a name="how-to-set-up-pricing-and-additional-costs-for-services"></a>Hvernig á að: setja upp verðlagningu og aukakostnað fyrir þjónustu
Hægt er að nota verðlagningareiginleika [!INCLUDE[d365fin](includes/d365fin_md.md)] til að setja upp og sérstilla forritið svo hægt sé að nota og stilla verðlagningu fyrir þjónustuvörur, viðgerðir og pantanir. Auðvelt er síðan að senda þessar verðlagningarákvarðanir yfir í reikningsfærsluferlið.  
  
Hægt er að setja upp verðlagningarflokka og varpa þeim á ákveðin tímabil, viðskiptamenn eða gjaldmiðil eftir þörfum þínum. Hægt er að setja upp fasta, lágmarks- eða hámarksverðlagningu eftir þeim þjónustusamningum sem gerðir voru við viðskiptamenn. Að lokum er hægt að skoða og samþykkja breytingar á verðlagi áður en þær eru færðar inn í fjárhaginn.  

## <a name="to-set-up-a-service-price-group"></a>Uppsetning þjónustuverðflokka
Setja má upp hópa með þjónustuvöru sem á að njóta sömu sérþjónustuverðlagningar. Þjónustuverðflokkar eru úthlutaðir þjónustuvöru í þjónustuvörulínum. Einnig er hægt að úthluta þjónustuverðflokkum til þjónustuvöruflokka.  

1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Þjónustuverðflokkar** og velja svo viðeigandi tengil.  
2. Nýr þjónustuverðflokkur er stofnaður.  
3. Fyllt er í reitina **Kóti** og **Lýsing**.  
4. Veldu aðgerðina **Uppsetning**.  
5. Fyllið inn í reitina eftir þörfum. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

   > [!Tip]
   > Reitirnir **Leiðréttingargerð** og **Upphæð** vinna saman til að tilgreina hvort leiðrétting feli í sér fasta upphæð eða eigi aðeins við þegar heildarþjónustuverð er hærra eða lægra en upphæðin í reitnum **Upphæð**.  

## <a name="to-set-up-a-service-price-adjustment-group"></a>Uppsetning þjónustuverðleiðréttingarflokka  
Þú getur setja upp verðleiðréttingaflokka til að leiðrétta þjónustuverðlagningu vegna þjónustuvöru. Til dæmis má setja upp verðleiðréttingarflokka sem leiðrétta verð á flutningi eða varahlutum.  
  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Þjónustuverðleiðréttingarflokkar** og velja svo viðeigandi tengil.  
2. Nýr þjónustuverðleiðréttingarflokkur er stofnaður.  
3. Fyllt er í reitina **Kóti** og **Lýsing**.  
4. Í reitnum **Tegund** er færð inn tegund færslunnar sem á að leiðrétta.  
  
    * Til að leiðrétta aðeins eina tiltekna færslu er númer þessarar færslu fært inn í reitinn **Nr.** . Ef reiturinn er hafður auður leiðréttir leiðréttingarflokkurinn allar færslur af tegundinni sem skilgreind er í reitnum **Tegund**.  
    * Til að leiðrétta þjónustuverð sem tengjast aðeins einni tiltekinni gerð þjónustu þarf að fylla út reitinn **Tegund vinnu**. Ef reiturinn er hafður auður verður hann hundsaður.  
  
5. Í reitinn **Lýsing** má færa inn stutta lýsingu á þjónustuverðleiðréttingunni.  
6. Til að leiðrétta þjónustuverð sem tengjast aðeins einum tilteknum almennum vörubókunarflokki þarf að fylla út reitinn **Alm. vörubókunarflokkur**.

> [!Tip]
> Þú getur valið **Upplýsingar** til að bæta við upplýsingum um leiðréttingarflokkinn. Til dæmis er hægt að tilgreina hvaða vara tilheyri þjónustuverðleiðréttingarflokki og hvort um sé að ræða vöru, forða, forðaflokks eða þjónustugjald.  

## <a name="to-set-up-additional-costs-for-services"></a>Setja upp  aukakostnað fyrir þjónustu
Þegar unnið er við þjónustuvöru og þjónustupöntunum getur þurft að skrá aukakostnað, eins og ferðakostnað til ákveðinna þjónustusvæða eða startkostnað. Þegar þú stofnar þjónustupöntun, geturðu fært inn þennan kostnað og lína með tegundina **Kostnaður** verður bætt við pöntunina. Að öðrum kosti, ef þú vilt úthluta kostnaðinum til allra þjónustupantana, geturðu sett upp sjálfvirkan kostnað. Ef þú vilt til dæmis alltaf úthluta startkostnaði.
  
### <a name="to-set-up-service-costs"></a>Setja upp þjónustukostnað
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Þjónustukostnaður** og velja svo viðeigandi tengil. 
2. Fyllið inn í reitina eftir þörfum. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

### <a name="to-specify-a-default-cost-for-service-orders"></a>Tilgreina sjálfgefinn kostnaðar vegna þjónustupantana
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Uppsetning þjónustu** og velja svo viðeigandi tengil. 
2. Í reitnum **Upphafsgjald þjónustupöntunar** skal velja viðeigandi startkostnað.

## <a name="see-also"></a>Sjá einnig
[Þjónustustýring sett upp](service-setup-service.md)  
[Þjónustukerfi](service-service.md)  

