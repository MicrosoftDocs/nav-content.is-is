---
title: "Sýna hluti sem vefþjónustu"
description: "Birtu [!INCLUDE[d365fin](includes/d365fin_md.md)] hluti sem vefþjónustu, þeir undir eins í boði á dreifikerfinu."
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/01/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 7c2bb65caeed819088382f811eb179eaeda35a7c
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-publish-a-web-service"></a>Hvernig á að: Birta vefþjónustu
Vefþjónustur eru létt leið til að gera virkni forrita aðgengilega ýmsum utanaðkomandi kerfum og notendum. [!INCLUDE[d365fin](includes/d365fin_md.md)] inniheldur fjölda hluta sem eru sýndir sem vefþjónusta að sjálfgefnu vegna samþættingu við Microsoft þjónustu, en þú getur einnig bætt við annarri vefþjónustu.  

Hægt er að setja upp vefþjónustu í Windows-biðlaranum eða í vefbiðlaranum. Þá verður að gefa vefþjónustuna út til að hún geti tekið við þjónustubeiðnum á netinu. Notendur geta fundið vefþjónustu með því að beina vafra að staðsetningu vefþjóns og biðja um lista yfir þjónustu í boði. Þegar gefa á út vefþjónustu verður hún samstundis virk á netinu fyrir sannvottaða notendur. Allir heimilaðir notendur geta opnað lýsigögn fyrir vefþjónustu, en aðeins notendur með nægilegar heimildir geta opnað raungögn.

## <a name="creating-and-publishing-a-web-service"></a>Vefþjónusta stofnuð og gefin út  
 Eftirfarandi skref skýra hvernig vefþjónusta er búin til og gefin út.  

#### <a name="to-create-and-publish-a-web-service"></a>Til að stofna og gefa út vefþjónustu  

1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Vefþjónusta** og velja svo viðeigandi tengil.  

2.  Á síðunni **Vefþjónusta** skal velja **Nýtt**. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

    > [!NOTE]  
    >  **Kótaeining** og **Síða** eru gildar tegundir fyrir SOAP-vefþjónustu. **Síða** og **Fyrirspurn** eru gildar gerðir fyrir OData-vefþjónustu.  
    Ef gagnagrunnurinn inniheldur mörg fyrirtæki er hægt að velja Kenni hlutar sem á aðeins við eitt af fyrirtækjunum.  
    Ef heiti þjónustunnar sýnilegt notendum vefþjónustunnar og það gegnir mikilvægu hlutverki í að auðkenna og þekkja vefþjónustuna. Því skaltu gefa henni merkingarbært heiti.

3.  Veldu gátreitinn í dálkinum **Útgefið**.  

     Þegar vefþjónusta er gefin út sjást þær vefslóðir sem voru myndaðar fyrir hana í reitunum **OData-vefslóð** og **SOAP-vefslóð**. Hægt er að prófa vefþjónustuna strax með því að velja tengla í reitunum **OData-vefslóð** og **SOAP-vefslóð**. Einnig er hægt að afrita gildið í reitnum og vista það til notkunar síðar.  

Eftir að þú birtir vefþjónustu, hafa ytri aðilar aðgang að henni. Hægt er að staðfesta að vefþjónustan sé tiltæk með því að nota vafra eða með því að velja tengilinn í reitunum **OData-vefslóð** og **SOAP-vefslóð** í glugganum **Vefþjónusta**. Eftirfarandi ferli sýnir hvernig hægt er að staðfesta aðgengi að vefþjónustunni fyrir notkun síðar.  

#### <a name="to-verify-the-availability-of-a-web-service"></a>Til að staðfesta aðgengi að vefþjónustu  

1.  Viðeigandi vefslóð er slegin inn í vafrann. Eftirfarandi tafla lýsir tegundum vefslóða sem hægt er að færa inn. Fyrir SOAP vefþjónustur skal nota eftirfarandi sniðmát fyrir þína vefslóð.  

    <table>
    <tr>
    <th>Tegund vefþjónustu</th>
    <th>Málskipan</th>
    <th>Dæmi</th>
    </tr>
    <tr>
    <td>SOAP</td>
    <td>https://*Server*:*SOAPWebServicePort*/*ServerInstance*/WS/*CompanyName*/salesDocuments/</td>
    <td>https://mycompany.financials.dynamics.com:7047/MS/WS/MyCompany/Page/salesDocuments?tenant=mycompany.financials.dynamics.com</td>
    </tr>
    <tr>
    <td>OData</td>
    <td>https://*Server*:*ODataWebServicePort*/*ServerInstance*/OData/Company('*CompanyName*')</td>
    <td>https://MyCompany.financials.dynamics.com:7048/MS/OData/Company('MyCompany')/salesDocuments?tenant=MyCompany.financials.dynamics.com

         The company name is case-sensitive.</td>
    </tr>
    </table>

2.  Fara skal yfir upplýsingarnar sem birtast í vafranum. Staðfesta skal að heiti vefþjónustunnar sem var búin til sjáist.  

 Þegar þú ferð inn á vefþjónustu og vilt skrifa gögn aftur til [!INCLUDE[d365fin](includes/d365fin_md.md)], verður þú að taka fram heiti fyrirtækis. Hægt er að tilgreina fyrirtækið í URI-slóð eins og sýnt er í dæmunum eða tilgreina það í færibreytum fyrirspurnarinnar. Eftirfarandi vefslóðir vísa t.d. á sama OData vefþjónustuna og eru báðar gildar vefslóðir.  

```  
https://localhost:7048/server/OData/Company('CRONUS International Ltd.')/Customer  
```  

```  
https://localhost:7048/server/OData/Customer?company='CRONUS International Ltd.'  
```  

## <a name="see-also"></a>Sjá einnig  
[Uppsetning og stjórnun í Dynamics NAV](admin-setup-and-administration.md)  

