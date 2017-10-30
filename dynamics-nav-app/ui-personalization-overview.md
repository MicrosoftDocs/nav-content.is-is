---
title: "Sérstilling verksvæðis - Yfirlit"
description: "Lærðu hvernig á að aðlaga notendaviðmótið til að henta því hvernig þú vinnur."
documentationcenter: 
author: jswymer
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.date: 07/26/2017
ms.author: jswymer
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 04334d3bb50b37b9643b848ca4f59b015f03ad04
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="personalizing-your-workspace---overview"></a>Sérstilling verksvæðis - Yfirlit
Þú getur sérstillt eða *sérsniðið* vinnusvæðið þitt til að henta vinnu þinni og óskum með því að breyta útliti síðna þannig að þær birti einungis upplýsingarnar sem þú þarfnast þegar þú þarfnast þeirra. Breytingar á sérstillingum sem þú gerir mun aðeins hafa áhrif á það sem þú sérð, ekki hvað aðrir notendur sjá.

Sérsníddu vinnusvæðið þitt með Windows-biðlaranum [!INCLUDE[nav_windows_md](includes/nav_windows_md.md)] og [!INCLUDE[nav_web_md](includes/nav_web_md.md)]. Breytingar á sérstillingum sem þú hefur gert munu einnig sjást í [!INCLUDE[nav_phone_md](includes/nav_phone_md.md)] og [!INCLUDE[nav_web_md](includes/nav_phone_md.md)].
  
> [!NOTE]  
> Kerfisstjóri fyrirtækisins kann að hafa sérstillt notendaviðmót notanda fyrir hlutverkatengt útlit fyrir alla notendur sem eru með sömu forstillingu og viðkomandi notandi og nota sama Mitt hlutverk. Sérstillingar á viðmótinu þínu eru vistaðar undir notandareikningnum þínum svo þær séu einnig til staðar þó svo að stjórnandi kemur með nýtt hlutverkamiðað útlit í fyrirtækinu þínu. Nánari upplýsingar, sjá [Grunnstilling notandaviðmót](admin-configure-user-interface.md).

## <a name="comparing-personalization-in-the-dynamics-nav-windows-and-web-clients"></a>Sérstilling borin saman milli Dynamics NAV Windows og vefbiðlara
Eftir síðum er hægt að sérstilla marga hluta notendaviðmótsins, svo sem það hvaða reitir eða dálkar eru sýndir og hvar þeir eru, hvaða aðgerðir eru í borða og fleira. Margir þessara hluta er bæði hægt að gera í Windows-biðlaranum og vefbiðlaranum. Í eftirfarandi töflu er yfirlit yfir sérstilingaeiginleika í hverju biðlara.

|  Sérstilla  ||  Windows-biðlari  |  Vefbiðlari  |
|---------------|-|------------------|--------------|
|Reitir í flýtiflipum||||
||Bæta við, færa, fjarlægja |x|x|
||Sýna í samandregnum haus|x||
||Fela undir aðgerðinni **Sýna fleiri reiti**|x||
|Listar eða skjalalínur ||||
||Bæta við, færa, fjarlægja dálka  |x|x|
||Bæta við, færa, fjarlægja fest svæði  |x|x|
|Upplýsingakassar|||
||Færa, fjarlægja|x|x|
||Bæta við|x||
||Bæta við, færa, fjarlægja reiti|x|x|
|Bendingar||||
||Færa, fjarlægja|x|x|
||Bæta við |x||
|Myndrit||||
||Færa, fjarlægja|x|x|
||Bæta við|x| |
|Borðar og aðgerðir||x||
|Yfirlitssvæði||x||

Annar munur er að við sérstillingar með Windows-biðlaranum er hægt að hafa margar viðmótsútgáfur á sömu síðu, allt eftir mismunandi aðgengisstöðum að síðunni. Til dæmis er hægt að stilla síðuna **Sölupöntun** svo hún líti öðruvísi út þegar hún er opnuð úr glugganum **Viðskiptamannaspjald** en úr **Hlutverkamiðstöð - Sölupantanavinnsla**. Þegar þú sérstillir síðu með því að nota vefbiðlarann, er aðeins ein sérstillt útgáfa á hverri síðu, þannig að breytingarnar sjást á síðunni sama hvaðan hún er opnuð.

##  <a name="PersonalizationWinWeb"></a>Unnið með sérstillingu milli Dynamics NAV Windows og vefbiðlara
Áður en þú byrjar að sérstilla síður er mikilvægt að skilja hvernig sérstilling milli Windows-biðlara og vefbiðlara virkar. Ef þú notar eingöngu annaðhvort Windows-biðlara eða vefbiðlara eiga þessar upplýsingar ekki við. Hins vegar verður það mikilvægt ef þú byrjar að sérstilla síður með báðum biðlurum eða þegar skipt er úr Windows-biðlara í vefbiðlara varanlega.  

-   Ef þú notar Windows-biðlara til að sérstilla tiltekna síðu frá upphafi muntu einnig sjá breytingar á sérstillingum á síðunni í [!INCLUDE[nav_web_md](includes/nav_web_md.md)].

-   Meðan þú Windows-biðlara til að sérstilla síðuna munu allar breytingar á sérstillingu taka gildi á síðunni í vefbiðlaranum.

-   Um leið og þú byrjar að sérstilla síðuna með því að nota vefþjóninn verður sérstilling fyrir þá síðu aðskilin milli tveggja bilaranna og þú munt fá sérstillta útgáfu fyrir hvern biðlara. Í vefbiðlaranum eru fyrri sérstillingar á síðunni hreinsaðar sem þýðir að síðan mun fara í upphaflegt útlit og þú munt byrja að sérstilla síðuna frá grunni. Fyrri sérstillingar í Windows-biðlaranum eru óbreyttar.

- Frá þessum tímapunkti verður þú að sérstilla síðuna í Windows-biðlaranum óháð hvort öðru, sem þýðir að síðan kann hugsanlega að líta mismunandi út í hverjum biðlara. Símaf- og spjaldtölvubiðlara munu sýna sérstillingar sömu síðu eins og vefbiðlarinn.  

> [!Tip]  
>Ef þú opnar síðuna **Eyða sérstillingum notanda** geturðu séð allar síðurnar sem hafa verið sérstilltar af hverjum notanda. Dálkurinn **Eldri sérstilling** gefur þér vísbendingu um hvort sérstilling var gerð í Windows-biðlara eða vefbiðlara. Ef gátmerki er í dálkinum var sérstilling gerð í Windows-biðlara (eða í vefbiðlara fyrir [!INCLUDE[navnow_md](includes/navnow_md.md)]).

## <a name="see-also"></a>Sjá einnig
[Sérsníddu vinnusvæðið þitt í Dynamics NAV Windows-biðlaranum](ui-personalization-windows-client.md)  
[Sérsnídu vinnusvæðið þitt í Dynamics NAV vefbiðlaranum](ui-personalization-user.md)  
[Sérstillingum stjórnað](ui-personalization-manage.md)  
[Sérstillir Dynamics NAV](ui-customizing-overview.md)  

