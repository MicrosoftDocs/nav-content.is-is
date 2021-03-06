---
title: "Flytja gögn frá Dynamics GP með Gagnaflutningaviðbótinni"
description: "Nota Dynamics GP Gagnaflutningaviðbótina til að flytja viðskiptamenn, lánardrottna, birgðir og reikninga úr Dynamics GP í Dynamics NAV."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms. search.keywords: app, add-in, manifest, customize, import, implement
ms.date: 03/29/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 0156ec040b96f007674161361e4368b81f7c42d9
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="the-dynamics-gp-data-migration-extension-for-dynamics-nav"></a>Viðbótin Dynamics GP gagnaflutningarviðbót fyrir Dynamics NAV
Þessi viðbót gerir það auðvelt að flytja viðskiptamenn, lánardrottna, birgðir og reikninga úr Dynamics GP í [!INCLUDE[d365fin](includes/d365fin_md.md)]. Ef fyrirtækið notar Dynamics GP er hægt að flytja út viðeigandi aðalfærslur og opna síðan leiðarvísi fyrir uppsetningu með hjálp til að bæta gögnunum við [!INCLUDE[d365fin](includes/d365fin_md.md)]. Nánari upplýsingar eru í [Yfirfæra viðskiptagögn úr öðrum fjárhagskerfum](upload-data.md).

## <a name="exporting-data-from-dynamics-gp"></a>Flytja út gögn úr Dynamics GP
Þú verður að hafa flutt einhverja eða alla viðskiptamenn þína, söluaðila, birgðavörur og reikninga í skrá með því að nota Dynamics GP virkni fyrir útflutning gagna. Fyrir [!INCLUDE[d365fin](includes/d365fin_md.md)] er hægt að flytja út eftirfarandi gerðir gagna:

* Reikningur  
* Viðskiptavinur  
* Atriði  
* Lánardrottinn  

Dynamics GP Data Migration viðbót varpar sjálfkrafa útfluttm gögn þannig að þú hafir skjótan aðgang að gögnunum þínum í nýja [!INCLUDE[d365fin](includes/d365fin_md.md)] fyrirtækinu. Meðan á ferlinu stendur eru uppsetningarupplýsingar stofnaðar, svo sem bókunarflokkar. Birgðavörur verða fluttar inn í kerfið með FIFO sem villuleitaraðferð kostnaðar. Lyklar verða settar upp sem aðalreikningslyklar úr Dynamics GP með víddum vegna þess að [!INCLUDE[d365fin](includes/d365fin_long_md.md)] er ekki með lyklahluta.

## <a name="see-also"></a>Sjá einnig
[Innflutningur viðskiptagagna úr öðrum fjárhagskerfum](upload-data.md)  
[Sérstilling [!INCLUDE[d365fin](includes/d365fin_md.md)] með viðbótum ](ui-extensions.md)  

