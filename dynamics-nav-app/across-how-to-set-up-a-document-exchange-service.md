---
title: "Hvernig á að setja upp skjalaskiptaþjónustu"
description: "Notaður er ytri þjónustuveitandi til að skiptast á rafrænum skjölum við viðskiptafélögum."
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/18/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 3f5fe8fc4c14e63b54ee0dce34278f2f13535265
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-a-document-exchange-service"></a>Hvernig á að setja upp skjalaskiptaþjónustu
Notaður er ytri þjónustuveitandi til að skiptast á rafrænum skjölum við viðskiptafélögum. Frekari upplýsingar eru í [Rafræn gagnaskipti](across-data-exchange.md).  

## <a name="to-set-up-a-document-exchange-service"></a>Setja upp skjalaskiptaþjónustu  
1. Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Uppsetning skjalaskiptaþjónustu** og velja svo viðeigandi tengil.  
2. Fylla inn í reitina eins og lýst er í eftirfarandi töflu.  

    |Svæði|Description|  
    |---------------------------------|---------------------------------------|  
    |**Notandagerandi**|Færa inn allan texta sem hægt er að nota til að auðkenna fyrirtækið í skjalaskiptaferlinu.|  
    |**Leigjandakenni gagnaskipti**|Færa skal inn leigjanda í skjalaþjónustan sem stendur fyrir fyrirtækið. Hann er gefinn upp af hálfu veitanda skjalaskiptiþjónustunnar.|  
    |**Virk**|Tilgreina hvort þjónustan er virkjuð. **Athugið:** Þegar þjónustan er virkjuð eru minnst tvær verkraðarfærslur stofnaðar til að vinna með umferð rafrænna skjala inn og út úr [!INCLUDE[d365fin](includes/d365fin_md.md)]. Þegar þú slekkur á þjónustu er verkraðarfærslum eytt.|  
    |**Skráningarvefslóð**|Tilgreina vefsíðuna þar sem nýskráning fyrir skjalskiptiþjónustuna fer fram.|  
    |**Vefslóð þjónustu**|Tilgreina veffang skjalaskiptiþjónustunna sem verður kölluð þegar rafræn skjöl eru send og tekið við þeim.|  
    |**Innskráningarvefslóð**|Tilgreina innskráningarsíðu fyrir skjalaskiptiþjónustuna, sem er þar sem slegið er inn notandanafn og aðgangsorð fyrirtækis til að skrá sig inn í þjónustuna.|  
    |**Lykill neytanda**|Færa skal inn þríliða OAuth-lykilinn fyrir neytendalykilinn. Hann er gefinn upp af hálfu veitanda skjalaskiptiþjónustunnar.|  
    |**Leyndarmál neytanda**|Færa skal inn leyndarmálið sem verndar neytendalykilinn. Hann er gefinn upp af hálfu veitanda skjalaskiptiþjónustunnar.|  
    |**Tákn**|Færa skal inn þríliða OAuth-lykilinn fyrir tákn. Hann er gefinn upp af hálfu veitanda skjalaskiptiþjónustunnar.|  
    |**Leyndarmál greiðslueiningar**|Færa skal inn leyndarmálið sem verndar táknið. Hann er gefinn upp af hálfu veitanda skjalaskiptiþjónustunnar.|  

> [!NOTE]  
>  Mælt er með því að vernda innskráningarupplýsingar sem slegnar eru inn í **uppsetning VAN-þjónustu** gluggann. Hægt er að dulrita gögn á  netþjóninum með því að stofna nýjan dulritunarlykil eða flytja inn fyrirliggjandi lykla sem eru virkjaðir er á netþjónstilviki sem tengist við gagnagrunninn. Þessu er lýst í eftirfarandi ferli.  

## <a name="to-encrypt-your-logon-information"></a>Til að dulrita innskráningarupplýsingar  
1. Í **uppsetning fyrir VAN-þjónusta** glugganum, veldu **stjórnun dulritunar**.  
2.  Í glugganum **gagnadulritun**, virkja dulritun gagnanna. <!--For more information, see [Manage Data Encryption](../manage-data-encryption.md).-->  

## <a name="see-also"></a>Sjá einnig  
[Setja upp gagnaskipti](across-set-up-data-exchange.md)  
[Rafræn gagnaskipti](across-data-exchange.md)

