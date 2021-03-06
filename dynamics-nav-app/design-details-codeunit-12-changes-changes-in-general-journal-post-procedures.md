---
title: "Hönnunarupplýsingar - Kóðaeining 12 Breytingar á bókunaraðferðum í færslubók"
description: "Eftirfarandi breytingar hafa verið settar í þessa útgáfu af [!INCLUDE[d365fin](includes/d365fin_md.md)]."
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
ms.openlocfilehash: 19bbc6eb4939fa7f4e0180a62b03998cd2f386b6
ms.contentlocale: is-is
ms.lasthandoff: 10/16/2017

---
# <a name="codeunit-12-changes-changes-in-general-journal-post-procedures"></a>Kóðaeining 12 Breytingar: Breytingar á bókunaraðferðum í færslubók
Eftirfarandi breytingar hafa verið settar í þessa útgáfu af [!INCLUDE[d365fin](includes/d365fin_md.md)].  

|**Microsoft Dynamics NAV 2009 R2**|**Microsoft Dynamics NAV 2013 R2**|**Athugasemd**|  
|----------------------------------------|----------------------------------------|-----------------|  
|GetGLReg|GetGLReg|Uppfært|  
|RunWithCheck|RunWithCheck|Uppfært|  
|RunWithoutCheck|RunWithoutCheck|Uppfært|  
|Code|Code|Uppfært|  
||PostGenJnlLine|Bætt við|  
||InitAmounts|Bætt við|  
||InitLastDocDate|Bætt við|  
|InitVAT|InitVAT|Uppfært|  
|PostVAT|PostVAT|Uppfært|  
|InsertVAT|InsertVAT|Uppfært|  
|SummarizeVAT|SummarizeVAT|Uppfært|  
|InsertSummarizedVAT|InsertSummarizedVAT|Uppfært|  
|PostGLAcc|PostGLAcc|Uppfært|  
|PostCust|PostCust|Uppfært|  
|PostVend|PostVend|Uppfært|  
|PostBankAcc|PostBankAcc|Uppfært|  
|PostFixedAsset|PostFixedAsset|Uppfært|  
|PostICPartner|PostICPartner|Uppfært|  
|InitCodeUnit|StartPosting|Uppfært|  
||ContinuePosting|Bætt við|  
|FinishCodeunit|FinishPosting|Uppfært|  
||PostUnrealizedVAT|Bætt við|  
||CheckPostUnrealizedVAT|Bætt við|  
||ExchangeAccounts|Bætt við|  
|InitGLEntry|InitGLEntry|Uppfært|  
||InitGLEntryVAT|Bætt við|  
||InitGLEntryVATCopy|Bætt við|  
|InsertGLEntry|InsertGLEntry|Uppfært|  
||CreateGLEntry|Bætt við|  
||CreateGLEntryBalAcc|Bætt við|  
||CreateGLEntryVAT|Bætt við|  
||CreateGLEntryVATCollectAdj|Bætt við|  
||CreateGLEntryFromVATEntry|Bætt við|  
||UpdateCheckAmounts|Bætt við|  
|ApplyCustLedgEntry|ApplyCustLedgEntry|Uppfært|  
||CalcPmtDiscPossible|Bætt við|  
||CalcPmtTolerancePossible|Bætt við|  
|CalcPmtTolerance|CalcPmtTolerance|Uppfært|  
|CalcPmtDisc|CalcPmtDisc|Uppfært|  
|CalcPmtDiscIfAdjVAT|CalcPmtDiscIfAdjVAT|Uppfært|  
|CalcPmtDiscTolerance|CalcPmtDiscTolerance|Uppfært|  
||CalcPmtDiscVATBases|Bætt við|  
||CalcPmtDiscVATAmounts|Bætt við|  
||InsertPmtDiscVATForVATEntry|Bætt við|  
||InsertPmtDiscVATForGLEntry|Bætt við|  
|CalcCurrencyApplnRounding|CalcCurrencyApplnRounding|Uppfært|  
|FindAmtForAppln|FindAmtForAppln|Uppfært|  
|CalcCurrencyUnrealizedGainLoss|CalcCurrencyUnrealizedGainLoss|Uppfært|  
|CalcCurrencyRealizedGainLoss|CalcCurrencyRealizedGainLoss|Uppfært|  
|CalcApplication|CalcApplication|Uppfært|  
|CalcRemainingPmtDisc|CalcRemainingPmtDisc|Fært í Codeunit 426 Stjórnun greiðsluvikmarka|  
|CalcAmtLCYAdjustment|CalcAmtLCYAdjustment|Bætt við|  
|InitNewCVLedgEntry|InitFromGenJnlLine|Fært í töflu 383 Biðminni sundurl. VL-færslu|  
|InitOldCVLedgEntry|CopyFromCVLedgEntryBuf|Fært í töflu 383 Biðminni sundurl. VL-færslu|  
|InsertDtldCVLedgEntry|InsertDtldCVLedgEntry|Fært í töflu 383 Biðminni sundurl. VL-færslu|  
||InitBankAccLedgEntry|Bætt við|  
||InitCheckLedgEntry|Bætt við|  
||InitCustLedgEntry|Bætt við|  
||InitVendLedgEntry|Bætt við|  
||InsertDtldCustLedgEntry|Bætt við|  
||InsertDtldVendLedgEntry|Bætt við|  
|CustUnrealizedVAT|CustUnrealizedVAT|Uppfært|  
|CustPostApplyCustLedgEntry|CustPostApplyCustLedgEntry|Uppfært|  
||PrepareTempCustLedgEntry|Bætt við|  
|UnapplyCustLedgEntry|UnapplyCustLedgEntry|Uppfært|  
|TransferCustLedgEntry|CopyFromGenJnlLine|Fært í töflu 21 Viðskm.færsla|  
|PostDtldCustLedgEntries|PostDtldCustLedgEntries|Uppfært|  
||PostDtldCustLedgEntry|Bætt við|  
||PostDtldCustLedgEntryUnapply|Bætt við|  
||GetDtldCustLedgEntryAccNo|Bætt við|  
|ZeroTransNoDtldCustLedgEntries|SetZeroTransNo|Fært í töflu 379 Sundurliðuð viðskm.færsla|  
|AutoEntrForDtldCustLedgEntries||Endurbætur á PostDtldCustLedgEntryUnapply|  
|CustUpdateDebitCredit|UpdateDebitCredit|Fært í töflu 379 Sundurliðuð viðskm.færsla|  
|ApplyVendLedgEntry|ApplyVendLedgEntry|Uppfært|  
||PrepareTempVendLedgEntry|Bætt við|  
|VendPostApplyVendLedgEntry|VendPostApplyVendLedgEntry|Uppfært|  
|UnapplyVendLedgEntry|UnapplyVendLedgEntry|Uppfært|  
|TransferVendLedgEntry|CopyFromGenJnlLine|Fært í töflu 25 Lánardr.færsla|  
|PostDtldVendLedgEntries|PostDtldVendLedgEntries|Uppfært|  
||PostDtldVendLedgEntry|Bætt við|  
||PostDtldVendLedgEntryUnapply|Bætt við|  
||GetDtldVendLedgEntryAccNo|Bætt við|  
||PostDtldCVLedgEntry|Bætt við|  
||PostDtldCustVATAdjustment|Bætt við|  
||PostDtldVendVATAdjustment|Bætt við|  
|ZeroTransNoDtldVendLedgEntries|SetZeroTransNo|Fært í töflu 380 Sundurliðuð lánardr.færsla|  
|AutoEntrForDtldVendLedgEntries||Endurbætur á PostDtldVendLedgEntryUnapply|  
|VendUpdateDebitCredit|UpdateDebitCredit|Fært í töflu 380 Sundurliðuð lánardr.færsla|  
|VendUnrealizedVAT|VendUnrealizedVAT|Uppfært|  
||PostUnrealVATEntry|Bætt við|  
||PostApply|Bætt við|  
|PostUnrealVATByUnapply|PostUnrealVATByUnapply|Uppfært|  
||PostUnapply|Bætt við|  
||InsertDtldCustLedgEntryUnapply|Bætt við|  
||InsertDtldVendLedgEntryUnapply|Bætt við|  
||InsertTempVATEntry|Bætt við|  
||ProcessTempVATEntry|Bætt við|  
||UpdateCustLedgEntry|Bætt við|  
||UpdateVendLedgEntry|Bætt við|  
|UpdateCalcInterest|UpdateCalcInterest|Uppfært|  
|UpdateCalcInterest2|UpdateCalcInterest2|Uppfært|  
|GLCalcAddCurrency|GLCalcAddCurrency|Uppfært|  
|HandleAddCurrResidualGLEntry|HandleAddCurrResidualGLEntry|Uppfært|  
|CalcLCYToAddCurr|CalcLCYToAddCurr|Uppfært|  
|CalcAddCurrFactor||Eytt|  
|GetCurrencyExchRate|GetCurrencyExchRate|Uppfært|  
|ExchAmount|ExchangeAmount|Fært í töflu 330 Gengi gjaldmiðils|  
|ExchangeAmtLCYToFCY2|ExchangeAmtLCYToFCY2|Uppfært|  
|CalcAddCurrForUnapplication|CalcAddCurrForUnapplication|Uppfært|  
|CheckNonAddCurrCodeOccurred|CheckNonAddCurrCodeOccurred|Uppfært|  
|CheckCalcPmtDisc||Fært í Codeunit 426 Stjórnun greiðsluvikmarka|  
|CheckCalcPmtDiscCVCust||Fært í Codeunit 426 Stjórnun greiðsluvikmarka|  
|CheckCalcPmtDiscCust||Fært í Codeunit 426 Stjórnun greiðsluvikmarka|  
|CheckCalcPmtDiscGenJnlCust||Fært í Codeunit 426 Stjórnun greiðsluvikmarka|  
|CheckCalcPmtDiscCVVend||Fært í Codeunit 426 Stjórnun greiðsluvikmarka|  
|CheckCalcPmtDiscVend||Fært í Codeunit 426 Stjórnun greiðsluvikmarka|  
|CheckCalcPmtDiscGenJnlVend||Fært í Codeunit 426 Stjórnun greiðsluvikmarka|  
|Reverse|Reverse|Fært í Codeunit 17 Gen. Jnl.-Post Reverse|  
|ReverseCustLedgEntry|ReverseCustLedgEntry|Fært í Codeunit 17 Gen. Jnl.-Post Reverse|  
|ReverseVendLedgEntry|ReverseVendLedgEntry|Fært í Codeunit 17 Gen. Jnl.-Post Reverse|  
|ReverseBankAccLedgEntry|ReverseBankAccLedgEntry|Fært í Codeunit 17 Gen. Jnl.-Post Reverse|  
|ReverseVAT|ReverseVAT|Fært í Codeunit 17 Gen. Jnl.-Post Reverse|  
|SetReversalDescription|SetReversalDescription|Fært í Codeunit 17 Gen. Jnl.-Post Reverse|  
|ApplyCustLedgEntryByReversal|ApplyCustLedgEntryByReversal|Fært í Codeunit 17 Gen. Jnl.-Post Reverse|  
|ApplyVendLedgEntryByReversal|ApplyVendLedgEntryByReversal|Fært í Codeunit 17 Gen. Jnl.-Post Reverse|  
|PostPmtDiscountVATByUnapply|PostPmtDiscountVATByUnapply|Fært í Codeunit 17 Gen. Jnl.-Post Reverse|  
||CheckDimComb|Bætt í Codeunit 17 Gen. Jnl.-Post Reverse|  
||CopyCustLedgEntry|Bætt í Codeunit 17 Gen. Jnl.-Post Reverse|  
||CopyVendLedgEntry|Bætt í Codeunit 17 Gen. Jnl.-Post Reverse|  
||CopyBankAccLedgEntry|Bætt í Codeunit 17 Gen. Jnl.-Post Reverse|  
|HandlDtlAddjustment|HandleDtldAdjustment|Uppfært|  
|CollectAddjustment|CollectAdjustment|Uppfært|  
|SetOverDimErr|SetOverDimErr|Uppfært|  
|PostJob|PostJob|Uppfært|  
|InsertVATEntriesFromTemp|InsertVATEntriesFromTemp|Uppfært|  
|CaptureOrRefundCreditCardPmnt|CaptureOrRefundCreditCardPmnt|Uppfært|  
|UpdateDOPaymentTransactEntry|UpdateDOPaymentTransactEntry|Uppfært|  
|ABSMin|ABSMin|Uppfært|  
|GetApplnRoundPrecision|GetApplnRoundPrecision|Uppfært|  
|CheckDimValueForDisposal|CheckDimValueForDisposal|Uppfært|  
|CalculateCurrentBalance|CalculateCurrentBalance|Uppfært|  
|IncludeVATAmount||Fært í töflu 81 Almenn færslubókarlína|  
|CalcVATAmountFromVATEntry|CalcVATAmountFromVATEntry|Uppfært|  
||TotalVATAmountOnJnlLines|Bætt við|  
||SetGLRegReverse|Bætt við|  
||GetGLSetup|Bætt við|  
||ReadGLSetup|Bætt við|  
||CheckSalesExtDocNo|Bætt við|  
||CheckPurchExtDocNo|Bætt við|  
||CheckGLAccDimError|Bætt við|  
||GetCurrency|Bætt við|  
||PostDtldAdjustment|Bætt við|  
||GetNextEntryNo|Bætt við|  
||GetNextTransactionNo|Bætt við|  
||GetNextVATEntryNo|Bætt við|  
||IncrNextVATEntryNo|Bætt við|  
||IsNotPayment|Bætt við|  
||IsTempGLEntryBufEmpty|Bætt við|  
||IsVATAdjustment|Bætt við|  
||IsVATExcluded|Bætt við|  
||UpdateDimensions|Bætt við|  
||UpdateDimensionsFromCustLedgEntry|Bætt við|  
||UpdateDimensionsFromVendLedgEntry|Bætt við|  
||UpdateTotalAmounts|Bætt við|  
||CreateGLEntriesForTotalAmounts|Bætt við|  

## <a name="see-also"></a>Sjá einnig  
 [Hönnunarupplýsingar: Kóðaeining 12 Breytingar: Vörpun altækra breyta fyrir bókunarlínu færslubókar](design-details-codeunit-12-changes-mapping-global-variables-for-general-journal-post-line.md)

