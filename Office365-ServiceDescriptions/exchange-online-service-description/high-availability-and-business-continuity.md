---
title: 고가용성 및 비즈니스 연속성
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-high-availability-and-business-continuity
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7b03465e-3b9c-4500-8956-a83377f4c2c3
description: Microsoft Exchange Online은 광범위 한 보존 및 조직의 전자 메일 인프라에 대 한 복구 지원을 제공합니다. 데이터 센터에서 사서함 복제 여기에 포함 하 고 삭제 된 사서함 및 삭제 된 항목을 복원 하는 기능입니다.
ms.openlocfilehash: 3f926223a278bd671fa6121b2ee59b96da1f9fe1
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036544"
---
# <a name="high-availability-and-business-continuity"></a>고가용성 및 비즈니스 연속성

Microsoft Exchange Online은 광범위 한 보존 및 조직의 전자 메일 인프라에 대 한 복구 지원을 제공합니다. 데이터 센터에서 사서함 복제 여기에 포함 하 고 삭제 된 사서함 및 삭제 된 항목을 복원 하는 기능입니다.
  
## <a name="mailbox-replication-at-data-centers"></a>데이터 센터에서 사서함 복제

Exchange Online 사서함은 로컬 메시징 인프라에 오류가 발생했을 때 데이터를 복원할 수 있도록 지리적으로 분산된 Microsoft 데이터 센터에서 여러 데이터베이스 복사본으로 지속적으로 복제됩니다. 대규모 오류인 경우 서비스 연속성 관리 절차가 시작됩니다.
  
Microsoft의 데이터 보호 방식에 대한 자세한 내용은 [Office 365 보안 센터](https://go.microsoft.com/fwlink/p/?LinkId=299135)를 참조하세요. 21Vianet에서 운영하는 Office 365를 사용 중인 경우 [21Vianet 보안 센터](http://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl)를 참조하세요.
  
## <a name="deleted-mailbox-recovery"></a>삭제된 사서함 복구

관리자는 Office 365 관리 센터를 통해 해당하는 사용자 계정을 삭제하거나 Exchange Online 라이선스를 제거하여, 또는 원격 Windows PowerShell에서 **Remove-Mailbox** cmdlet을 사용하여 Exchange Online 사서함을 삭제할 수 있습니다. 사서함이 삭제되면 Exchange Online은 기본적으로 30일 동안 사서함 및 해당 콘텐츠를 보존하며, 30일 후에는 사서함을 복구할 수 없습니다. 복구된 사서함에는 삭제 당시에 저장된 모든 데이터가 포함됩니다. 관리자는 보존 기간 내에 Office 365 관리 센터를 사용하여 삭제된 사서함을 복구할 수 있습니다. 삭제된 사서함을 복구하려는 경우 관리자는 해당 Office 365 사용자 계정을 복원하거나 Exchange Online 라이선스를 사용자 계정에 다시 할당해야 합니다. 자세한 내용은 [Exchange Online에서 사용자 사서함 삭제 또는 복원](https://go.microsoft.com/fwlink/p/?LinkId=286992)을 참조하세요.
  
## <a name="deleted-item-recovery"></a>삭제된 항목 복구

Exchange Online에서는 지운 편지함 폴더를 비롯하여 전자 메일 폴더에서 삭제된 항목을 사용자가 복원할 수 있습니다. 삭제된 항목은 사용자의 지운 편지함 폴더에 보관되며, 사용자가 수동으로 제거하거나 보존 정책에 의해 자동으로 제거될 때까지 유지됩니다. 관리자는 EAC 또는 원격 Windows PowerShell을 사용하여 보존 정책을 사용자 지정할 수 있습니다.
  
지운 편지함 폴더에서 제거된 항목은 휴지통 폴더에서 14일 동안 보관되었다가 영구적으로 제거되지만 관리자는 원격 Windows PowerShell을 사용하여 이 기간을 최대 30일까지 연장할 수 있습니다. 사용자는 이 기간에 Outlook Web App 또는 Outlook의 삭제된 항목 복구 기능을 사용하여 항목을 복구할 수 있습니다. [삭제된 항목 보존 기간 변경](https://go.microsoft.com/fwlink/p/?LinkId=286940) 방법을 알아보세요.
  
사용자가 휴지통 폴더에서 항목을 수동으로 제거한 경우 관리자는 원격 Windows PowerShell을 사용하는 단일 항목 복구 기능을 통해 그와 동일한 기간 내에 항목을 복구할 수 있습니다. 기본적으로 사서함을 만들 때 단일 항목 복구는 사용하도록 설정됩니다. 자세한 내용은 [사서함에 대해 단일 항목 복구를 사용하거나 사용하지 않도록 설정](https://go.microsoft.com/fwlink/p/?LinkID=286941)을 참조하세요.
  
30일보다 오랫동안 복구 가능한 항목 폴더에 메시지를 보존하려는 조직에서는 장기 전자 메일 보존 또는 시간 기반 원본 위치 유지를 구현할 수 있습니다. [사서함을 원본 위치 유지 상태로 설정](https://go.microsoft.com/fwlink/p/?LinkId=271746)하는 방법을 알아보세요.
  
## <a name="feature-availability"></a>기능 가용성

Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션별로 기능 가용성을 확인하려면 [Exchange Online 서비스 설명](exchange-online-service-description.md)을 참조하세요.
  
