---
title: 보고 및 메시지 추적
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: Microsoft Exchange Online Protection (EOP)은 하는데 도움이 되는 여러 다른 보고서의 전반적인 상태 확인 하 여 조직의 제공 합니다. Exchange 관리 센터 (EAC)에서 사용할 수 있는 다른 사용자에 게 하는 동안 일부 보고서는 Microsoft Office 365 관리 센터에서 사용할 수 있습니다.
ms.openlocfilehash: ead40ff8932d6f10ca91bd871e34ef9070c6b2db
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036606"
---
# <a name="reporting-and-message-trace"></a>보고 및 메시지 추적

Microsoft Exchange Online Protection (EOP)은 하는데 도움이 되는 여러 다른 보고서의 전반적인 상태 확인 하 여 조직의 제공 합니다. Exchange 관리 센터 (EAC)에서 사용할 수 있는 다른 사용자에 게 하는 동안 일부 보고서는 Microsoft Office 365 관리 센터에서 사용할 수 있습니다.
  
모든 EOP 기능에 대한 자세한 내용은 [Exchange Online Protection 서비스 설명](exchange-online-protection-service-description.md)을 참조하세요.
  
## <a name="office-365-admin-center-reports"></a>Office 365 관리 센터 보고서
<a name="BKMK_office365admincenterreports"> </a>

Office 365 관리 센터의 보고서 페이지에서는 메시지 트래픽, 스팸 및 맬웨어 감지, Exchange 전송 규칙이나 DLP(데이터 손실 방지) 정책의 영향을 받는 메시지에 대한 정보가 제공됩니다. 보호, 규칙 및 DLP에 대한 향상된 보고서에서는 EOP 관리자에게 대화형 보고 환경이 제공됩니다. 이러한 보고서에서는 개별 메시지에 대한 세부 정보로 드릴다운할 수 있는 기능과 함께 요약 데이터가 제공됩니다.
  
이러한 보고서에 대한 자세한 내용은 [Office 365의 메일 보호 보고서를 사용하여 맬웨어, 스팸 및 규칙 감지에 대한 데이터 보기](https://go.microsoft.com/fwlink/p/?LinkID=401102)를 참조하세요.
  
## <a name="excel-download-application-reports"></a>Excel 다운로드 응용 프로그램 보고서
<a name="BKMK_exceldownloadapplicationreports"> </a>

드릴다운 기능이 있는 요약 보고서가 제공되는 Excel 2013 보호 통합 문서에서도 전자 메일 보호 보고서를 사용할 수 있습니다. 그러나 이 보고서 대신 향상된 Office 365 관리 센터 보고서를 사용하는 것이 좋습니다. Excel 2013 보고 통합 문서는 향후 더 이상 사용되지 않을 예정입니다. 
  
개요에 대한 자세한 내용과 통합 문서를 다운로드 및 설치하기 위한 링크는 [Office 365용 메일 보호 보고서](https://go.microsoft.com/fwlink/p/?LinkId=271776)를 참조하세요. 통합 문서 사용 방법에 대한 자세한 내용은 [Excel 보고 통합 문서를 사용한 메일 보호 보고서](https://go.microsoft.com/fwlink/p/?LinkId=285211)를 참조하세요.
  
## <a name="reporting-using-web-services"></a>웹 서비스를 사용하여 보고
<a name="BKMK_reportingusingwebservices"> </a>

EOP 독립 실행형 고객에게는 제공되지 않습니다. REST/OData 테넌트 보고 웹 서비스를 사용하여 메시징 데이터에 대한 요약 및 상세 보고서를 프로그래밍 방식으로 수집할 수 있으며, 사용자 지정 관리 웹 포털의 웹 페이지에 데이터를 표시할 수 있습니다. 자세한 내용은 [Office 365 보고 웹 서비스](https://go.microsoft.com/fwlink/?LinkId=279926)를 참조하세요.
  
## <a name="message-trace"></a>메시지 추적
<a name="BKMK_messagetrace"> </a>

관리자는 EAC의 메시지 추적 기능을 사용하여 EOP를 통과하는 전자 메일 메시지를 추적할 수 있습니다. 이렇게 하면 서비스에서 대상 전자 메일 메시지를 수신, 거부, 지연 또는 배달했는지 여부를 확인하는 데 도움이 되며, 또한 메시지가 최종 상태에 도달하기 전 메시지에 수행된 작업을 확인할 수 있습니다. 특정 메시지에 대한 자세한 정보를 파악하면 사용자 질문에 효과적으로 대답하고, 메일 흐름 문제를 해결하며, 정책 변경 사항의 유효성을 검사할 수 있을 뿐만 아니라 기술 지원 서비스에 지원을 문의해야 하는 수고를 덜 수 있습니다. 자세한 내용은 [전자 메일 메시지 추적](https://go.microsoft.com/fwlink/p/?LinkID=282262)을 참조하세요.
  
## <a name="feature-availability"></a>기능 가용성
<a name="BKMK_messagetrace"> </a>

Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션별로 기능 가용성을 확인하려면 [Exchange Online Protection 서비스 설명](exchange-online-protection-service-description.md)을 참조하세요.
  
