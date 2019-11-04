---
title: Microsoft 365 合規性-GCC 的計劃
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ROBOTS: NOINDEX, NOFOLLOW
description: 本指南適用於 IT 專業人員所主導部署的 Office 365 美國聯邦、 狀態、 本機、 部落，或就政府實體或其他處理政府法規和需求，受限於的資料的實體位置 Microsoft 使用365 government-GCC 會適用於符合這些需求。
ms.openlocfilehash: 50649287df37afe20b58f98333a10bc7885b417d
ms.sourcegitcommit: f69656f34dcb4f4e9a5857d8c4236084c94a05b1
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/31/2019
ms.locfileid: "37890475"
---
# <a name="plan-for-microsoft-365-compliance--gcc"></a>規劃 Microsoft 365 合規性 – GCC

本指南適用於 IT 專業人員所主導部署的 Office 365 美國聯邦、 狀態、 本機、 部落，或就政府實體或其他處理政府法規和需求，受限於的資料的實體位置 Microsoft 使用365 government-GCC 會適用於符合這些需求。

> [!NOTE]
> 如果您的組織已符合 Microsoft 365 政府版-GCC 資格需求和適用於並被接受到程式，您可以略過步驟 1 和 2，並直接跳到步驟 3。

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---gcc-and-meets-eligibility-requirements"></a>步驟 1。 判斷您的組織是否需要 Microsoft 365 Government-GCC，且符合資格需求

Microsoft 365 政府版-GCC 環境遵守美國政府雲端服務需求的包括 FedRAMP 中度和司法正義與聯邦稅務資訊系統 （CJI 和 FTI 資料類型） 的需求。

除了享受的功能和 Office 365 的功能，組織會受益於對 Microsoft 365 政府 GCC 都是唯一的下列功能：

- 貴組織的客戶內容和會以邏輯方式區隔來自 Microsoft 的商業 Office 365 服務中的客戶內容。

- 組織的客戶內容儲存於美國境內。

- 只有經過篩選的 Microsoft 人員可以存取組織的客戶內容。

- Microsoft 365 Government-GCC 遵守認證和資格鑑定美國公共部門客戶所要求的。

您可以找到 Microsoft 365 政府版-GCC 提供在[Office 365 政府方案](https://products.office.com/government/compare-office-365-government-plans)，包括資格 US Government 客戶需求的詳細資訊。

[Office 365 US Government 服務描述](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government)說明平台的好處，置符合美國境內的合規性需求。

> [!TIP]
> 您可能想要傳送到 Excel 活頁簿的資料表中的服務描述的資訊，並新增兩個資料行： **我的組織是/否相關** ，且 **符合 Y/N 我組織的需求**。 然後您可以檢閱此清單與同事確認這項服務，符合貴組織的需求。

> [!NOTE]
> Microsoft 365 Government-GCC 只有在美國境內。 非 – US Government 客戶可以選擇從數個[Office 365 政府版計劃](https://products.office.com/government/compare-office-365-government-plans)。

**決策點**： <br/>
- *決定 Microsoft 365 政府 GCC 是否適合貴組織。*
- *確認您的組織符合資格的需求。*

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a>步驟 2。 適用於 Microsoft 365 Government-GCC

具有決定，這項服務適合貴組織中，啟動[套用此服務](https://products.office.com/government/eligibility-validation)的程序。

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a>步驟 3： 了解 Microsoft 365 Government-GCC 預設安全性設定

我們建議您，一點時間進行仔細檢閱您的系統及安全性設定，再修改它們的預設安全性設定進行任何變更之前，請考慮對合規性的影響。

**決策點**：*決定是否將修改任何預設的 Microsoft 365 政府 GCC 安全性設定，先了解影響的任何變更您解決可能會使。*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc"></a>步驟 4。 了解哪些功能是目前無法使用或預設會在 Microsoft 365 政府版 – GCC 中停用

若要容納我們政府雲端客戶的需求，有一些差異 Microsoft 365 Government-GCC 和企業版計劃。 請參閱下表以查看哪些功能可用。

|                                         | **功能**                                     | **GCC 狀態**         |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **資訊保護 & 控管** | 封存                                       | 可以使用              |
|                                         | 手動標籤和原則                      | 可以使用              |
|                                         | 自動應用程式的標籤                      | 在 [工程待處理項目 |
|                                         | 根據敏感資訊類型的標籤            | 在 [工程待處理項目 |
|                                         | 標籤和相關聯的查詢為基礎的原則 | 在 [工程待處理項目 |
|                                         | 檔案計畫                                       | 在 [工程待處理項目 |
|                                         | 建議的原則                            | 在 [工程待處理項目 |
|                                         | 智慧匯入篩選器                            | 在 [工程待處理項目 |
|                                         | 事件型保留                           | 在 [工程待處理項目 |
|                                         | 處置檢閱                              | 在 [工程待處理項目 |
|                                         | 資訊屏障                            | 可以使用              |
|                                         | 資料外洩防護 (DLP) 檔案和電子郵件  | 可以使用              |
|                                         | 小組聊天和通道交談的 DLP    | 可以使用              |
| **測試人員風險管理**             | 進階的郵件加密                     | 可以使用              |
|                                         | 通訊合規性                        | 在 [工程待處理項目 |
|                                         | 客戶加密箱                                | 可以使用              |
|                                         | 客戶金鑰                                    | 可以使用              |
|                                         | 特殊權限存取管理                    | 在 [工程待處理項目 |
| **探索 & 回應**                  | 就地保留項目                            | 可以使用              |
|                                         | 專案管理                                 | 可以使用              |
|                                         | 搜尋                                          | 可以使用              |
|                                         | 匯出                                          | 可以使用              |
|                                         | RMS 解密                                  | 可以使用              |
|                                         | 原生匯出                                   | 可以使用              |
|                                         | 稽核                                        | 可以使用              |
|                                         | 執行進階的處理                             | 在 [工程待處理項目 |
|                                         | 電子郵件執行緒                                 | 在 [工程待處理項目 |
|                                         | 近似重複的識別碼                   | 在 [工程待處理項目 |
|                                         | 佈景主題                                          | 在 [工程待處理項目 |
|                                         | 預測撰寫程式碼                               | 在 [工程待處理項目 |
|                                         | 處理的匯出以載入檔案                 | 在 [工程待處理項目 |
|                                         | 標記                                         | 在 [工程待處理項目 |
|                                         | 檢視程式                                         | 在 [工程待處理項目 |
|                                         | Redactions                                      | 在 [工程待處理項目 |
|                                         | 篩選                                       | 在 [工程待處理項目 |
|                                         | Custodian 與工作負載之間的對應                   | 在 [工程待處理項目 |
|                                         | Custodian 通訊                        | 在 [工程待處理項目 |
|                                         | 檢閱設定                                     | 在 [工程待處理項目 |
|                                         | 檢閱並加上註解                             | 在 [工程待處理項目 |
|                                         | 非 Office 365 擷取                        | 在 [工程待處理項目 |
|                                         | 搜尋字詞報告                              | 在 [工程待處理項目 |

**決策點**：*決定的符合性功能是否符合貴組織的需求。*