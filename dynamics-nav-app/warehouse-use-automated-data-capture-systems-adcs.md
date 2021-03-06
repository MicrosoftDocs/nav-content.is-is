---
title: "Nota sjálfvirkt gagnatökukerfi (ADCS)"
description: "Hægt er að nota sjálfvirka gagnatökukerfið (ADCS) til að skrá alla hreyfingu á vörum í vöruhúsinu og skrá sumar færslubókaraðgerðir, s.s. leiðréttingar á magni í birgðabók vöruhússins og raunbirgðir."
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/18/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 2e5fb701013f75557302b7a26ba8c6f2972806a3
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-enable-automated-data-capture-systems-adcs"></a>Hvernig skal: Virkja Sjálfvirkt gagnatökukerfi (ADCS)
Hægt er að nota sjálfvirka gagnatökukerfið (ADCS) til að skrá alla hreyfingu á vörum í vöruhúsinu og skrá sumar færslubókaraðgerðir, s.s. leiðréttingar á magni í birgðabók vöruhússins og raunbirgðir.  

Ef nota á ADCS þarf að gefa öllum vörum í vöruhúsinu vörukenni. Einnig þarf að setja upp smáglugga, handtölvuaðgerðir, gagnaskipti og tilgreina stillingar fyrir svæði sem stýra ADCS Notandinn tilgreinir hvort eigi að nota í ADCS spjaldi birgðageymslunnar vöruhúsi.

Magn upplýsinga sem birtar eru í handtölvunni er skilgreint í smágluggauppsetningu hverrar einstakrar handtölvu í samræmi við þarfir vöruhússins. Eftirfarandi eru dæmi um upplýsingar sem hægt er að birta:  

- Gögn úr töflum innan [!INCLUDE[d365fin](includes/d365fin_md.md)], til dæmis lista yfir tínsluskjöl sem notandinn valið úr.  
- Textaupplýsingar.  
- Skilaboð til að sýna staðfestingar eða villurnar um verkþætti sem framkvæmdir eru og skráðir af handtölvu notanda.

Frekari upplýsingar eru í [Grunnstilla sjálfvirkt gagantökukerfi](https://msdn.microsoft.com/en-us/library/dd338742.aspx) á MSDN.

## <a name="to-set-up-a-warehouse-to-use-adcs"></a>að setja vöruhús upp fyrir notkun ADCS  
Ef nota á ADCS verður að tilgreina hvaða birgðageymslur nota tæknina.  

> [!NOTE]  
>  Mælt er með að vöruhús séu ekki sett upp til að nota ADCS ef vöruhúsið hefur einnig hólfagetureglu.

1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn  **Birgðageymslur** og velja svo viðeigandi tengil.
2.  Veljið vöruhús af listanum sem á að gera ADCS virkt fyrir og veljið svo aðgerðina **Breyta**.
3. Í glugganum **birgðageymsluspjald** veljið **Nota ADCS** gátreitur.  

## <a name="to-specify-an-item-to-use-adcs"></a>Tilgreina vöru til að nota ADCS  
Hver vara í vöruhúsi sem nota á með ADCS verður að fá úthlutaðan auðkenningarkótanum til að tengja skjalið ásamt vörunúmerinu. Til dæmis er hægt að nota strikamerki vörunnar sem auðkenniskóta. Vara getur einnig haft margar auðkenniskóta. Þetta getur komið að gagni í tilfellum þar sem vara er tiltæki í ýmsum mælieiningu, s.s. stykkjum og brettum. Í þessu tilfelli er úthlutað auðkenniskóta fyrir hvern.    

1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Vörur** og velja svo viðeigandi tengil.  
2.  Veljið vöru af listanum sem er hluti af ADCS-lausninni, og síðan aðgerðina **Breyta**.
3. Í glugganum **Birgðaspjald** skal velja aðgerðina **Kennimerki**.
4. Í glugganum **Vörur Kennimerki** skal velja aðgerðina **Nýtt**.
5. Í reitnum **Kóði** skal tilgreina auðkenni vörunnar. Til dæmis gæti kennið verið strikamerkisnúmer vörunnar.  

    Einnig er hægt að færa inn **Afbrigðiskóti** og **Mælieiningu**.  

6. Ef þörf krefur skal færa inn marga kóta fyrir hverja vöru.
7. Velja hnappinn **Í lagi**.  
8.  Til að fara yfir upplýsingarnar skal velja reitinn **Kennimerkiskóði** til að opna gluggann **Vörukennimerki**.

## <a name="to-add-an-adcs-user"></a>Til að bæta við ADCS notanda  
Hægt er að bæta hvaða notanda við sem notanda sjálfvirks gagnatökukerfis (ADCS). Þegar það er gert verður notandinn einnig að gefa upp aðgangsorð. Einnig er hægt að bjóða upp á tengingu sem auðkennir ADCS-notandann sem starfsmann vöruhúss. Aðgangsorð notanda ADCS getur verið frábrugðið Windows-aðgangsorði notandans. Nánari upplýsingar eru í [Hvernig á að: Vinna með notendur og heimildir](ui-how-users-permissions.md).

1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **ADCS Notendur** og velja svo viðeigandi tengil.  
2. Valið er **Nýtt** aðgerð.  
3.  Á svæðinu **Heiti** skal færa inn heiti fyrir notandann. Heitið getur ekki innihaldið meira en 20 stafi, með bilum.  
4.  Í reitnum **Lykilorð** er lykilorð fært inn. Aðgangsorðið er falið.  

### <a name="to-specify-that-a-warehouse-employee-is-an-adcs-user"></a>Til að tilgreina að starfsmaður vöruhúss sé ADCS notandi  
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **starfsmenn vöruhúss** og velja svo viðeigandi tengil.  
2.  Ef þörf krefur skal bæta við nýjum starfsmanni vöruhúss. Frekari upplýsingar eru í [Hvernig á að: Setja upp starfsmenn vöruhúss](warehouse-how-to-set-up-warehouse-employees.md).  
3.  Veldu aðgerðina **Breyta lista**.  
4.  Veljið vöruhúsastarfsmann af listanum. Í reitnum **ADCS notandi** er valið felliörina og veljið svo nafnið á ADCS-notanda af listanum.  

> [!NOTE]  
>  Sjálfgefið vöruhús fyrir starfsmanninn ætti að nota ADCS.

## <a name="to-create-and-customize-miniforms"></a>Hvernig á að búa til og sérsníða smáglugga
Smágluggar eru notaðir til að gefa lýsa upplýsingum sem birtar eru á lófatækjum. Til dæmis er hægt að stofna smáglugga til að styðja vöruhúsaaðgerðina að tína vörur. Þegar búið er að stofna smáglugga er hægt að bæta við hann virkni fyrir algengar aðgerðir sem notandinn gerir með handtölvum, eins og flutningur upp eða niður línu.  

Til að innleiða eða breyta virkni smágluggaaðgerðar þarf að búa til nýja kóðaeiningu eða breyta kóðaeiningu sem þegar er til að framkvæma aðgerðina eða svarið sem beðið er um. Hægt er að læra meira um aðgerðir ADCS með því að skoða codeunit eins og 7705, sem er í umsýslu kóðaeining fyrir innskráningu. Kótaeining 7705 sýnir hvernig smágluggi af spjaldtegund virkar.  

### <a name="to-create-a-miniform-for-adcs"></a>Til að búa til smáglugga fyrir ADCS  
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Smágluggar** og velja svo viðeigandi tengil.  
2. Valið er **Nýtt** aðgerð.  
3.  Í reitnum **Kóði** er færður inn kóði fyrir smáglugganum. Einnig er hægt að færa gildi inni í alla aðra reiti.  

    Velja skal gátreitinn **Ræsa smáglugga** til að gefa til kynna að smáglugginn sé fyrsta skjámyndin sem notandinn sér við innskráningu.  

4.  Á flýtiflipanum **Línur** skilgreinið svæðin sem birtast á smáglugganum. Röðin sem þú færir inn línur er sú röð sem línurnar birtast í handtölvunni.  

Þegar búið er að búa til smáglugga, eru næstu skref er að stofna aðgerðir og tengja virkni fyrir ýmsan lyklaborðsinnslátt.  

### <a name="to-add-support-for-a-function-key"></a>Til að bæta við stuðningi fyrir aðgerðalykil  
1.  Bæta við kóta sem svipar til eftirfarandi dæmis í xsl-skránni fyrir tengjuna. Þetta stofnar aðgerð fyrir **F6** lykil. Upplýsingarnar um lykilröðina má fá frá framleiðanda búnaðarins.  
    ```  
    <xsl:template match="Function[.='F6']">  
      <Function Key1="27" Key2="91" Key3="49" Key4="55" Key5="126" Key6="0"><xsl:value-of select="."/></Function>  
    </xsl:template>  

    ```  
2.  Í [!INCLUDE[d365fin](includes/d365fin_md.md)] þróunarumhverfi, opnið töflu 7702 og bætið við kóta fyrir nýjan lykil. Í þessu dæmi, er stofnaður lykil sem er með heitinu **F6**.  
3.  Bæta við C/AL-kóta í viðeigandi aðgerð kótaeiningar viðeigandi smáglugga til að sjá um aðgerðalykilinn  

### <a name="to-customize-miniform-functions"></a>Til að sérsníða aðgerðir smáglugga  
1.  Velja skal ![Leit að síðu eða skýrslu](media/ui-search/search_small.png "Leit að síðu eða skýrslu táknið") tákn, slá inn **Smágluggar** og velja svo viðeigandi tengil.  
2.  Veljið smáglugga af listanum og veljið svo aðgerðina **Breyta**.  
3.  Velja aðgerðina **Aðgerðir**.  
4.  Í fellilistanum **Aðgerðakóði** skal velja kóða fyrir aðgerð sem á að tengja við smáglugga. Til dæmis er hægt að velja ESC, sem tengir aðgerðir við það að stutt er á ESC-lykilinn.  

Í [!INCLUDE[d365fin](includes/d365fin_md.md)] þróunarumhverfi, breytið kóta fyrir reitinn **Afgreiða kóðaeiningu** til að stofna eða breyta kóta til að framkvæma umbeðna aðgerð eða svar.

Frekari upplýsingar eru í [Grunnstilla sjálfvirkt gagantökukerfi](https://msdn.microsoft.com/en-us/library/dd338742.aspx) á MSDN.

## <a name="see-also"></a>Sjá einnig  
[Vöruhúsastjórnun](warehouse-manage-warehouse.md)  
[Birgðir](inventory-manage-inventory.md)  
[Vöruhúsastjórnun sett upp](warehouse-setup-warehouse.md)     
[Samsetningardeild](assembly-assemble-items.md)    
[Hönnunarupplýsingar vöruhúsakerfi](design-details-warehouse-management.md)  
[Unnið með [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

