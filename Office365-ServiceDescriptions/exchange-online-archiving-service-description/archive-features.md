---
title: Exchange Online 보관의 보관 기능
ms.author: sharik
author: skjerland
manager: mnirkhe
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
description: 다음 섹션에서는 Microsoft Exchange Online 보관의 보관 기능에 대해 설명 합니다.
ms.openlocfilehash: aa3a43a0af668f84adaf14c69ad5b38d7c5cb1eb
ms.sourcegitcommit: 0abb96f4771fd2e2a674589059ddc43c50f55d98
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/08/2020
ms.locfileid: "40987580"
---
# <a name="archive-features-in-exchange-online-archiving"></a>Exchange Online 보관의 보관 기능

다음 섹션에서는 Microsoft Exchange Online 보관의 보관 기능에 대해 설명 합니다.
  
## <a name="archive-mailbox"></a>보관 사서함

Exchange Online Archiving에서는 보관 사서함 기능과 함께 고급 보관 기능을 사용자에게 제공합니다. 보관 사서함은 Outlook 또는 웹용 Outlook에서 사용자의 기본 사서함 폴더 옆에 표시 되는 특수 한 사서함입니다. 사용자는 기본 사서함에 액세스하는 방법으로 보관 사서함에도 액세스할 수 있습니다. 또한 보관 사서함과 기본 사서함을 모두 검색할 수 있습니다.
  
관리자는 EAC(Exchange 관리 센터)나 원격 Windows PowerShell을 통해 특정 사용자가 보관 기능을 사용하도록 설정할 수 있습니다. 자세한 내용은 [Exchange Online의 보관 사서함을 사용하거나 사용하지 않도록 설정](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)을 참조하세요.
  
> [!IMPORTANT]
>  보관 목적으로 저널링, 전송 규칙 또는 자동 전달 규칙을 사용하여 Exchange Online Archiving에 메시지를 복사할 수는 없습니다. <br/>
>  사용자의 보관 사서함은 해당 사용자만을 위한 것입니다. Microsoft는 사용자의 보관 사서함이 다른 사용자의 보관 데이터를 저장 하는 데 사용 되거나 부적절 하 게 사용 되는 경우를 제외 하 고 무제한 보관을 거부할 수 있는 권한을 보유 합니다.
  
### <a name="move-messages-to-exchange-online-archiving"></a>Exchange Online Archiving으로 메시지 이동

사용자는 온라인에서 간편하게 액세스하기 위해 .pst 파일에서 메시지를 끌어 보관 사서함에 놓을 수 있습니다. 또한 보관 정책을 사용하여 전자 메일 항목을 자동으로 기본 사서함에서 보관 사서함으로 이동해서, 기본 사서함의 크기를 줄이고 성능을 개선할 수도 있습니다. 
  
### <a name="import-data-to-the-archive"></a>보관 사서함으로 데이터 가져오기

사용자는 다음과 같은 방법으로 보관 사서함에 데이터를 가져올 수 있습니다.
  
- Outlook의 가져오기 및 내보내기 마법사를 사용하여 .pst 파일에서 데이터를 가져옵니다.
    
- 전자 메일 메시지를 .pst 파일에서 보관 사서함으로 끕니다.
    
- 기본 사서함에서 보관 사서함으로 전자 메일 메시지를 끌어 놓습니다.
    
- 메시지가 기본 사서함에 보관된 기간을 기준으로 기본 사서함의 전자 메일 메시지를 자동으로 이동하도록 보관 정책을 설정합니다. 자세한 내용은 [보존 태그 및 보존 정책](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies)을 참조하세요.
    
> [!NOTE]
> 관리자는 Office 365 가져오기 서비스를 사용하여 .pst 파일을 사용자의 클라우드 기반 보관 사서함에 가져올 수도 있습니다. 자세한 내용은 [네트워크 업로드를 사용하여 PST 파일을 Office 365에 가져오기](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files)를 참조하세요. 
  
## <a name="deleted-item-recovery"></a>삭제된 항목 복구

사용자는 전자 메일 폴더에서 삭제된 항목을 보관 사서함에서 복원할 수 있습니다. 삭제된 항목은 보관 사서함의 지운 편지함 폴더에 보관되고, 사용자가 수동으로 제거하거나 보존 정책에 따라 자동으로 제거될 때까지 해당 폴더에 보관됩니다.
  
보관 사서함의 지운 편지함 폴더에서 제거된 항목은 보관 사서함의 복구 가능한 항목 폴더에서 14일 동안 더 보관되었다가 영구적으로 제거됩니다. 사용자는 Microsoft Outlook 또는 웹용 Outlook에서 **삭제 된 항목 복구** 기능을 사용 하 여 이러한 항목을 복구할 수 있습니다. 
  
사용자가 복구 가능한 항목 폴더에서 항목을 수동으로 제거한 경우 관리자는 단일 항목 복구라는 기능을 사용하여 같은 기간(14일) 내에 항목을 복구할 수 있습니다. 관리자는 이 기능을 통해 여러 사서함 검색을 수행하여 제거된 항목을 찾은 다음  `Search-Mailbox` Windows PowerShell cmdlet을 사용해 검색 사서함에서 사용자 사서함으로 항목을 이동할 수 있습니다. 자세한 내용은 [사서함에 대한 단일 항목을 사용하거나 사용하지 않도록 설정](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files)을 참조하세요.
  
> [!NOTE]
>  단일 항목 복구 기간은 기본적으로 14일이지만 경우에 따라 사용자가 지정할 수 있습니다. <br/>
>  관리자가 사용자의 사서함에 원본 위치 유지 또는 소송 보존을 적용 한 경우 제거 된 항목은 무기한 유지 되 고, 14 일 동안 지속 되지 않습니다. 
  
## <a name="deleted-mailbox-recovery"></a>삭제된 사서함 복구

관리자가 사용자를 온-프레미스 Exchange Server에서 삭제하면 해당 사용자의 보관 사서함도 삭제됩니다. 삭제된 보관 사서함을 복구해야 하는 경우 Office 365 지원 팀이 해당 복구를 수행할 수 있습니다. 복구된 보관 사서함에는 삭제 당시에 저장되어 있던 모든 메일이 포함됩니다.
  
> [!IMPORTANT]
> 관리자는 사용자 사서함이 삭제된 시점부터 30일 동안 보관 사서함의 복구를 요청할 수 있습니다. 30일 후에는 보관 사서함을 복구할 수 없습니다. 
  
## <a name="mailbox-service-redundancy"></a>사서함 서비스 중복

Exchange Online Archiving의 보관 사서함은 메시징 인프라에 오류가 발생했을 때 데이터를 복원할 수 있도록 지리적으로 분산된 Microsoft 데이터 센터에서 여러 데이터베이스 복사본으로 복제됩니다. 대규모 오류인 경우 비즈니스 연속성 관리가 시작됩니다. 
  
## <a name="feature-availability"></a>기능 가용성

Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션 별로 기능 가용성을 확인 하려면 [Exchange Online 보관 서비스 설명을](exchange-online-archiving-service-description.md)참조 하세요.
  
