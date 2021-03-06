---
title: Exchange Online 封存服務說明
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-archiving-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 21ebd4bb-7d88-489f-a8aa-376e2536900c
description: 請閱讀本文以瞭解 Microsoft Exchange Online 封存。
ms.openlocfilehash: 4c83a11a953f29c20c6e7e743403985c465d0aad
ms.sourcegitcommit: e342174df76128430dfc8c971716da5c4b2942ac
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/28/2020
ms.locfileid: "48293629"
---
# <a name="exchange-online-archiving-service-description"></a>Exchange Online 封存服務說明

Microsoft Exchange Online 封存是 Microsoft 365 雲端型企業級封存解決方案，適用于已部署 Microsoft Exchange Server 2019、Microsoft Exchange Server 2016、Microsoft Exchange Server 2013、Microsoft Exchange server 2010 (SP2 以上) 或訂閱特定 Exchange Online 或 Microsoft365 方案的組織。 Exchange Online Archiving可為這些組織在封存、符合性、法規及 eDiscovery 挑戰等方面提供協助，同時可簡化內部部署基礎結構，進而降低成本和減輕 IT 重擔。
  
做為 Microsoft online 服務時，Exchange Online 封存的設計目的是為了協助滿足強健的安全性、可靠性和使用者生產力的需求。 如需 Microsoft 365 的詳細資訊（包括所有 Microsoft online 服務通用的功能），請參閱 [microsoft 365 和 Office 365 平臺服務說明](../office-365-platform-service-description/office-365-platform-service-description.md)。
  
若要購買 Exchange Online 封存，請參閱 [Exchange online 封存 for server](https://products.office.com/exchange/microsoft-exchange-online-archiving-email)。
  
若要跨方案比較功能，請參閱 [強大的工具來支援您的企業](https://products.office.com/business/compare-more-office-365-for-business-plans)。
  
> [!TIP]
> 您可以匯出、儲存及列印服務描述中的頁面。 瞭解如何 [匯出內容搜尋結果](https://docs.microsoft.com/office365/securitycompliance/export-search-results)。 
  
## <a name="exchange-online-archiving-plans"></a>Exchange Online 封存計劃

您可透過下列計劃使用 Exchange Online Archiving。<br><br>
  
| 方案 | 描述 |
|:-----|:-----|
|**Exchange Server 適用的 Exchange Online 封存** <br/> |在 Exchange server 2019、Exchange Server 2016、Exchange Server 2013 或 Exchange 2010 (SP2 或更新版本) 中，具有主要信箱之使用者的雲端式封存。  <br/> 如果您想要將雲端型封存新增至位於內部部署 Exchange 伺服器的主要信箱，您需要設定混合部署。 如需有關混合部署的詳細資訊，請參閱 [Exchange Server 混合部署](https://docs.microsoft.com/exchange/exchange-hybrid)。  <br/> |
|**Exchange Server 適用的 Exchange Online 封存 (透過企業 CAL 套件)** <br/> |在 Exchange server 2019、Exchange Server 2016、Exchange Server 2013 或 Exchange 2010 (SP2 或更新版本) 中，具有主要信箱之使用者的雲端式封存。 如需詳細資訊，請參閱 [Client Access 授權和管理授權](https://www.microsoft.com/licensing/product-licensing/client-access-license)。  <br/> |
|**Exchange Online 適用的 Exchange Online 封存** <br/> | 雲端式封存和就地保留做為下列方案<sup>1、2</sup>的附加元件：<br/>  Exchange Online Plan 1  <br/>  Exchange Online Kiosk  <br/>  Microsoft 365 商務基本版  <br/>  Microsoft 365 商務標準版  <br/>  Office 365 企業版 E1  <br/>  Office 365 企業版 F3  <br/> Microsoft 365 Enterprise F3<br/> <b>附注：</b> 下列計畫已包含封存，而且不需要 Exchange Online 封存做為附加元件：<br/>Office 365 教育版 A1 <br/>Office 365 Education A3 <br/>  Office 365 教育版 A5 <br/>  Office 365 企業版 E3 <br/>  Office 365 企業版 E5 <br/>  Exchange Online Plan 2 <br/> Microsoft 365 商務進階版 <br/>Microsoft 365 企業版 E3 <br/> Microsoft 365 企業版 E5 <br/>如需 Exchange Online 信箱之封存功能的詳細資訊，請參閱 [Exchange online 封存中的封存功能](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-archiving-service-description/archive-features)。           |
   
>[!NOTE]
><sup>1</sup> 組織只採用雲端 (即組織中沒有信箱位於內部部署 Exchange 伺服器) 時不一定要採用混合部署。 不過，如果內部部署信箱已存在，則需要混合部署。
<br/>
<sup>2</sup> Exchange Online plan 1 和 Microsoft 365 應用程式計畫在信箱和封存上有大小限制。 如需詳細資訊，請參閱 [Exchange Online 限制](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits)。 Exchange Online 適用的Exchange Online Archiving附加元件增加了無限量雲端型封存和 [就地保留與訴訟暫止](compliance-and-security-features.md#in-place-hold-and-litigation-hold)。
  
尋找所有 Microsoft 365 方案的相關資訊嗎？ Microsoft 365 提供各種可滿足您組織需求的最佳方案。 如需不同計畫的相關資訊，包括獨立計畫選項及從一個計畫移至另一個計畫的資訊，請參閱 [Office 365 plan options](../office-365-platform-service-description/office-365-plan-options.md)。
  
## <a name="requirements"></a>需求

若要將 Exchange Online 封存用於 Exchange Server，使用者信箱必須位於 Exchange Server 2019、Exchange Server 2016、Exchange Server 2013 或 Exchange Server 2010 (SP2 或更新版本) 上。
  
### <a name="federated-identity-and-single-sign-on"></a>同盟身分識別和單一登入

系統管理員可以使用單一登入方法，以內部部署 Active Directory 進行驗證。 若要做到這一點，管理員可以設定內部部署 Active Directory Federation Services （Microsoft Windows Server &reg; 2008 service）以與 Microsoft Federation Gateway 同盟。 設定 Active Directory Federation Services 後，其身分識別的所有使用者都可以使用其現有的公司登入，以自動驗證 Office 365。
  
### <a name="user-subscriptions"></a>使用者訂閱

每位存取 Exchange Online Archiving 服務的使用者皆必須具有 Exchange Online Archiving 訂閱。每項電子郵件封存訂閱皆僅能用來儲存一位使用者的郵件資料。
  
## <a name="unlimited-archive-storage-quota"></a>無限制封存儲存配額

 「無限封存」功能 (稱為「 *自動展開* 封存」) 會在封存信箱中提供額外的儲存空間。 每位 Exchange Online Archiving 訂閱者初始會獲得 100 GB 的封存信箱儲存空間。 當自動展開的封存開啟時，當達到 100 GB 的儲存容量時，會自動新增額外的儲存空間。 在 Exchange 混合式部署中，只有在內部部署使用者的信箱位於 Exchange Server 2019、Exchange Server 2016 或 Exchange Server 2013 (SP1 或更新版本) 時，雲端式封存信箱才支援自動展開封存。 如需詳細資訊，請參閱 [無限期封存一覽](https://docs.microsoft.com/office365/securitycompliance/unlimited-archiving)。
  
> [!IMPORTANT]
> 系統管理員無法調整儲存空間配額。<br/>
> 位於 Exchange Server 2010 上的信箱不支援自動擴充封存。
  
> [!IMPORTANT]
> [！注意] 只有針對個別使用者或共用信箱所用的信箱，才支援自動展開封存，其增長率為 * &nbsp; 每日未超過 1 GB*。 禁止透過日誌記錄、傳輸規則或自動轉寄規則，將郵件複製到 Exchange Online Archiving信箱中進行封存。 使用者的封存信箱僅供該使用者使用。 Microsoft 保留在使用者的封存信箱用來儲存其他使用者的封存資料或其他不適當用途的情況下，拒絕無限封存的權利。
  
## <a name="feature-availability-across-exchange-online-archiving-plans"></a>各 Exchange Online 封存計劃中可用的功能

| 功能 | Exchange Server 適用的 Exchange Online Archiving<sup>1</sup> | Exchange Online 適用的 Exchange Online Archiving<sup>2</sup> |
|:-----|:-----|:-----|
|**[Exchange Online 封存中的封存功能](archive-features.md)** <br/> |||
|封存信箱  <br/> |是  <br/> |是  <br/> |
|使用封存原則移動郵件  <br/> |是  <br/> |是  <br/> |
|將資料匯入封存  <br/> |是  <br/> |是  <br/> |
|復原已刪除的項目  <br/> |是  <br/> |是  <br/> |
|復原已刪除的信箱  <br/> |是  <br/> |是  <br/> |
|信箱備份  <br/> |是  <br/> |是  <br/> |
|**[Exchange Online 封存中的用戶端功能](client-features.md)** <br/> |||
|Outlook<sup>3</sup> <br/> |是  <br/> |是  <br/> |
|Outlook 網頁版  <br/> |是  <br/> |是  <br/> |
|**[Exchange Online 封存中的合規性和安全性功能](compliance-and-security-features.md)** <br/> |||
|保留原則  <br/> |是  <br/> |是  <br/> |
|就地保留與訴訟資料暫留<sup>6</sup> <br/> |是  <br/> |是  <br/> |
|就地 eDiscovery  <br/> |是  <br/> |是  <br/> |
|內部部署伺服器與 Exchange Online 封存之間的加密  <br/> |是  <br/> |是  <br/> |
|用戶端與 Exchange Online 封存之間的加密  <br/> |是  <br/> |是  <br/> |
|加密：S/MIME 和 PGP  <br/> |是  <br/> |是  <br/> |
|使用 Azure 資訊保護 的 IRM  <br/> |否  <br/> |否<sup>4</sup> <br/> |
|使用 Windows Server AD RMS 的 IRM  <br/> |是<sup>5</sup> <br/> |是<sup>5</sup> <br/> |
|稽核  <br/> |是  <br/> |是  <br/> |
   

<sup>1</sup> 使用者信箱必須位於 Exchange 2010 SP2 或更新版本上。
<br/>
<sup>2</sup> In-Place 封存僅可用於封存已套用授權之單一使用者或實體的郵件。 禁止使用「就地封存」來儲存多個使用者或實體的郵件。 例如，IT 系統管理員不能建立共用信箱，再由使用者純粹為了封存的目的來複製 (透過 [副本] 或 [密件副本] 欄位，或透過傳輸規則) 共用信箱。 <br/> 
<sup>3</sup> 如需支援的 Microsoft Outlook 版本清單，請參閱 [Exchange Online 封存中的用戶端功能](client-features.md)。 <br/>
<sup>4</sup> 不包含 Azure 資訊保護，但可以個別的附加元件形式購買，並且會啟用支援的資訊版權管理 (IRM) 功能。 部分 Azure 資訊保護功能需要訂閱 Microsoft 365 應用程式，但不包含在 Microsoft 365 Business Basic、Microsoft 365 Business Standard、Office 365 企業版 E1、Office 365 教育版或 Office 365 Enterprise F3 中。 <br/>
<sup>5</sup> Windows Server AD RMS 是內部部署伺服器，必須個別採購並管理，以便啟用支援的 IRM 功能。 <br/>
<sup>6</sup> 當您對信箱進行就地保留或訴訟資料暫留時，會同時保留主要和封存信箱。 
