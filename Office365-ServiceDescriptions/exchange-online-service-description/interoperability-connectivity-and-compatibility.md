---
title: 互通性、連線性和相容性
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: 5308770ff7fc6ab6c44f27293ff89ebbffa6e72f
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132747"
---
# <a name="interoperability-connectivity-and-compatibility"></a>互通性、連線性和相容性

## <a name="interoperability-with-other-microsoft-products"></a>與其他 Microsoft 產品互通性

### <a name="skype-for-business-online"></a>商務用 Skype Online

針對在內部部署 Microsoft Lync Server 2010、Lync Server 2013 或 Microsoft Office Communications Server 2007 R2 的客戶，Microsoft Office Communicator 可以藉由 Exchange Web 服務連線至 Microsoft Exchange Online，以存取郵件答錄機訊息和行事曆資料。
  
內部部署的 Lync Server 2010 和 Lync Server 2013 可以使用另外兩種方式與 Exchange Online 交互操作：
  
- Outlook 網頁版中的 IM 和目前狀態互通性
    
- 語音信箱互通性
    
如需要更多關於如何利用 Exchange Online 設定 商務用 Skype Server 2015 的資訊，請參閱[設定內部部署商務用 Skype Server 2015 與 Exchange Online 的整合](https://go.microsoft.com/fwlink/p/?LinkId=271804)。如需混合式組態的詳細資訊，請參閱[支援的商務用 Skype Server 2015 混合式組態](https://go.microsoft.com/fwlink/?LinkID=513084)。
  
### <a name="microsoft-sharepoint"></a>Microsoft SharePoint

若客戶已部署 Microsoft SharePoint Server 或 SharePoint 線上做為訂閱計畫的一部分，SharePoint 可連線至 Exchange Online 的整合式服務。
  
如需有關如何將 SharePoint 與 Exchange Online 連線的更多資訊，請參閱[在自訂網域中使用 SharePoint Online 與其他服務](https://go.microsoft.com/fwlink/?LinkId=271805)。
  
## <a name="features-for-external-connectivity"></a>外部連線功能

為了與外部應用程式和設備連線，Exchange Online 提供下列功能：
  
- **透過 MAPI over HTTP、SMTP、POP3、IMAP4 這類訊息通訊協定或 Exchange Web 服務** 在內部部署、Azure 或其他託管服務中執行的外部應用程式，可以透過 MAPI over HTTP、SMTP、POP3 和 IMAPv4 這類訊息通訊協定存取以 Exchange Online 儲存的資料。應用程式部署時，建議使用 Exchange Web 服務或 Exchange Web 服務管理的 API。 
    
- **如同 SMTP 轉送** Exchange Online 可以被設定成 SMTP 傳遞服務，用以轉送從傳真閘道、網路設備和自訂應用程式寄來的電子郵件訊息。 
    
### <a name="exchange-web-services"></a>Exchange Web 服務

Exchange Web Services (EWS) 是適合用於 Exchange Server 和 Exchange Online 開發的 API。 系統管理員可以使用 EWS 或 EWS 管理的 API，從內部部署、Azure 或其他託管服務中執行的應用程式，存取以 Exchange Online 儲存的資料。 EWS 可讓系統管理員執行特殊的動作，例如查詢信箱內容、發佈行事曆事件、建立任務，或根據電子郵件的內容觸發特定動作。 Exchange Online 可藉由將應用程式權限授予客戶帳號以啟用 EWS 功能。 這些權限允許客戶的應用程式存取應用程式信箱並新增內容。 Exchange 模擬 是一種用來授予應用程式權限的方式。 關於如何以 Exchange Online 使用 Exchange Web Services 的細節，請參閱 Exchange Online 開發人員中心的技術文章。
  
### <a name="smtp-relay"></a>SMTP 轉送

Exchange Online 可以當作 SMTP 傳遞服務使用，用以轉送從傳真閘道、網路設備和自訂應用程式寄來的電子郵件訊息。舉例來說，如果企業營運應用程式寄送電子郵件警示給使用者，可以將其設定成使用 Exchange Online 作為郵件傳送系統。應用程式或服務必需透過有效且已獲授權之 Exchange Online 信箱的使用者名稱和密碼來進行驗證，並使用傳輸層安全性 (TLS) 連線。
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online 服務說明](exchange-online-service-description.md)。
  

