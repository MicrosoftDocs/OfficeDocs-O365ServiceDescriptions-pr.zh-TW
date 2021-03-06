---
title: Exchange Online 封存中的封存功能
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- archive-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 38abfbd2-5aaa-444a-a431-5e71c566f3e4
description: 瞭解 Microsoft Exchange Online 封存中可用的封存功能。
ms.openlocfilehash: da7b9fd7583904424300dff010117e50a6193552
ms.sourcegitcommit: e342174df76128430dfc8c971716da5c4b2942ac
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/28/2020
ms.locfileid: "48293649"
---
# <a name="archive-features-in-exchange-online-archiving"></a>Exchange Online 封存中的封存功能

下列各節說明 Microsoft Exchange Online 封存的封存功能。
  
## <a name="archive-mailbox"></a>封存信箱

Exchange Online Archiving 以封存信箱功能的形式，為使用者提供進階封存功能。 封存信箱是一種特殊的信箱，會出現在 Outlook 或網頁型 Outlook 中使用者的主要信箱資料夾旁。 使用者可以像存取主要信箱一樣來存取封存。 此外，使用者可以同時在封存和主要信箱中進行搜尋。
  
系統管理員可以使用 Exchange 系統管理中心 (EAC) 或遠端 Windows PowerShell，為特定使用者啟用封存功能。如需詳細資訊，請參閱[啟用或停用 Exchange Online 中的封存信箱](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)。
  
> [!IMPORTANT]
>  禁止透過日誌記錄、傳輸規則或自動轉寄規則，將郵件複製到 Exchange Online Archiving信箱中進行封存。 <br/>
>  使用者的封存信箱僅供該使用者使用。 Microsoft 保留在使用者的封存信箱用來儲存其他使用者的封存資料或其他不適當用途的情況下，拒絕無限封存的權利。
  
### <a name="move-messages-to-exchange-online-archiving"></a>將郵件移至 Exchange Online 封存

使用者可以將郵件從 .pst 檔案拖放至封存中，以方便進行線上存取。 使用者也可以使用「封存原則」，自動將電子郵件項目從主要信箱中移至封存信箱中，以減少主要信箱的大小並改善其效能。 
  
### <a name="import-data-to-the-archive"></a>將資料匯入封存

使用者可以使用下列方式將資料匯入封存：
  
- 使用 Outlook 的「匯入及匯出」精靈，從 .pst 檔案匯入資料。
    
- 將電子郵件訊息從 .pst 檔案拖曳至封存中。
    
- 將電子郵件訊息從主要信箱拖曳至封存中。
    
- 讓封存原則根據電子郵件訊息的已存留時間，自動將郵件移出主要信箱。如需詳細資訊，請參閱[保留標記和保留原則](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies)。
    
> [!NOTE]
> 系統管理員也可以使用 Office 365 匯入服務，將 .pst 檔案匯入到使用者的雲端型封存信箱。如需詳細資訊，請參閱[使用網路上傳將 PST 檔案匯入 Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files)。 
  
## <a name="deleted-item-recovery"></a>復原已刪除的項目

使用者可以在封存中還原已從任何電子郵件資料夾中刪除的郵件。郵件遭刪除時，會保留在封存的 [刪除的郵件] 資料夾中。該郵件會一直留在該處，直到遭使用者手動移除或遭保留原則自動移除為止。
  
After an item has been removed from the archive's Deleted Items folder, the item is kept in the archive's Recoverable Items folder for an additional 14 days before being permanently removed. 使用者可以使用 Microsoft Outlook 或 web 上的 Outlook 中的 [ **復原刪除的郵件** ] 功能來復原這些專案。 
  
如果使用者已從 [可復原的項目] 資料夾中手動清除某個郵件，則系統管理員可以透過名為「單一項目復原」的功能，同樣在這 14 天內復原郵件。此功能可讓系統管理員搜尋多個信箱來尋找已清除的郵件，然後使用  `Search-Mailbox` Windows PowerShell Cmdlet 將郵件從探索信箱移至使用者的信箱。如需詳細資訊，請參閱 [為信箱啟用或停用單一項目復原](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files)。
  
> [!NOTE]
>  單一項目復原期間預設為 14 天，但在某些情況下，您可加以自訂。 <br/>
>  如果系統管理員將使用者的信箱設為 In-Place 保留或訴訟資料暫留狀態，就會無限期保留清除的專案，且不會套用14天的視窗。 
  
## <a name="deleted-mailbox-recovery"></a>復原已刪除的信箱

當系統管理員從內部部署 Exchange Server 中刪除使用者時，使用者的封存也會遭到刪除。 如果需要復原已刪除的封存信箱，則 Microsoft 支援小組可以執行此修復。 復原的封存信箱將包含遭刪除時所有儲存在該信箱內的郵件。
  
> [!IMPORTANT]
> 自刪除使用者的信箱起，系統管理員有 30 天的時間可以要求復原封存信箱。超過 30 天後，就無法復原封存信箱。 
  
## <a name="mailbox-service-redundancy"></a>信箱服務備援

Exchange Online Archiving 中的封存信箱會複寫至多個資料庫副本 (位於不同地區的 Microsoft 資料中心內)，以防萬一訊息基礎結構故障，還有辦法可以還原資料。 對於大規模的故障，則有永續營運管理程序。 
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱 [Exchange Online 封存服務說明](exchange-online-archiving-service-description.md)。
  
