---
title: 메일 흐름[EOP]
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: 대부분의 조직 Office 365를 사용 하는 사용자 사서함을 호스팅하는 및 메일 흐름을 처리 합니다. 가장 단순한 구성 하 고 Office 365 모든 사서함을 관리 하는 것을 의미 하 고 필터링 합니다. 그러나 일부 조직에서는 온-프레미스 모든 사서함을 유지 해야하는 비즈니스 합니다. Exchange Online Protection (EOP)를 수행할 수 하 고 클라우드에서 처리 하는 바이러스 백신 및 스팸 방지 메일을 제공 합니다. 자세한 내용은 및 EOP를 구입 하려면 Exchange Online Protection로 이동 합니다.
ms.openlocfilehash: 6c43d308db3c4f62e4c6891cb87263560d9478a7
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036470"
---
# <a name="mail-floweop"></a>메일 흐름[EOP]

대부분의 조직 Office 365를 사용 하는 사용자 사서함을 호스팅하는 및 메일 흐름을 처리 합니다. 가장 단순한 구성 하 고 Office 365 모든 사서함을 관리 하는 것을 의미 하 고 필터링 합니다. 그러나 일부 조직에서는 온-프레미스 모든 사서함을 유지 해야하는 비즈니스 합니다. Exchange Online Protection (EOP)를 수행할 수 하 고 클라우드에서 처리 하는 바이러스 백신 및 스팸 방지 메일을 제공 합니다. 자세한 내용은 및 EOP를 구입 하려면 [Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection)로 이동 합니다.
  
도메인 관리 또는 DBEB(디렉터리 기반 Edge 차단)에 대한 정보를 확인하려면 [받는 사람, 도메인 및 회사 관리](recipient-domain-and-company-management.md)을 참조하세요. 모든 EOP 기능에 대한 자세한 내용은 [Exchange Online Protection 서비스 설명](exchange-online-protection-service-description.md)을 참조하세요.
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a>Office 365와 자체 메일 서버 간의 이메일 라우팅
<a name="BKMK_outboundmailrouting"> </a>

Office 365(Exchange Online 또는 EOP 포함)와 SMTP 기반 메일 서버(예: Exchange) 간에 메일 흐름을 사용하도록 커넥터를 구성할 수 있습니다. 이에 대한 자세한 정보는 [Do I need a connector](http://technet.microsoft.com/library/16731ae9-c909-49dd-bffc-a46e6151fc29.aspx)? 및 [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx)을 참조하세요.
  
## <a name="secure-messaging-with-a-trusted-partner"></a>신뢰할 수 있는 파트너와의 보안 메시징
<a name="BKMK_securemessagingwithatrustedpartner"> </a>

EOP 고객은 Office 365 커넥터를 사용하여 신뢰할 수 있는 파트너와 보안 메일 흐름을 설정할 수 있습니다. Office 365는 TLS(전송 계층 보안)을 통한 보안 통신을 지원합니다. TLS를 통해 암호화를 적용하기 위해 커넥터를 만들 수 있습니다.[TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx)는 인터넷을 통한 통신에 보안을 제공하는 암호화 프로토콜입니다. 커넥터를 사용하면 자체 서명된 인증서 또는 CA(인증 기관) 확인 인증서를 통해 강제로 받거나 보내는 TLS를 모두 구성할 수 있습니다. 도메인 이름 또는 파트너 조직에서 메일을 보내는 IP 주소 범위를 지정하는 것과 같은 기타 보안 제한을 적용할 수도 있습니다. 
  
자세한 내용은 [파트너 조직과 함께 보안 메일 흐름에 대한 커넥터 설정](https://technet.microsoft.com/en-us/library/dn751021%28v=exchg.150%29.aspx)을 참조하세요.
  
## <a name="safe-listing-a-partners-ip-address"></a>수신 허용 목록에 파트너의 IP 주소 추가
<a name="BKMK_safelistingapartnersipaddress"> </a>

신뢰할 수 있는 파트너의 IP 주소를 수신 허용 목록에 추가하여 해당 파트너가 보내는 메시지에 스팸 필터링이 적용되지 않도록 할 수 있습니다. 이렇게 하려면 연결 필터의 IP 허용 목록을 사용하면 됩니다. 자세한 내용은 [연결 필터 정책 구성](https://go.microsoft.com/fwlink/p/?LinkID=287108)을 참조하세요.
  
## <a name="conditional-mail-routing"></a>조건부 메일 라우팅
<a name="BKMK_conditionalmailrouting"> </a>

조건에 따라 메일을 특정 사이트로 라우팅하는 전송 규칙을 사용하여 커넥터를 구성할 수 있습니다. 자세한 내용은 [Scenario: Conditional email routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx)을 참조하세요.
  
## <a name="hybrid-mail-routing"></a>하이브리드 메일 라우팅
<a name="BKMK_hybridmailrouting"> </a>

하이브리드란 사서함의 일부분을 온-프레미스에서, 다른 일부분은 클라우드(Exchange Online)에서 호스트하는 것을 의미합니다. 독립 실행형(온-프레미스) 배포에서 하이브리드 배포로 이동할 수 있습니다.
  
하이브리드 배포를 사용하는 경우 EOP를 통해 클라우드 및 온-프레미스 사서함을 보호할 수 있습니다. EOP를 통해 보호되는 온-프레미스 사서함에는 독립 실행형 라이선스가 필요합니다. 하이브리드 배포의 메일 라우팅에 대한 자세한 내용은 [Exchange 하이브리드 배포의 전송 라우팅](https://go.microsoft.com/fwlink/p/?LinkId=271757)을 참조하세요.
  
[Microsoft Exchange Server 배포 도우미](https://go.microsoft.com/fwlink/p/?LinkId=287036) 또한 자세한 하이브리드 배포 프로비전 및 하이브리드 메시지 전송 지침을 제공합니다. 
  
## <a name="feature-availability"></a>기능 가용성
<a name="BKMK_hybridmailrouting"> </a>

Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션별로 기능 가용성을 확인하려면 [Exchange Online Protection 서비스 설명](exchange-online-protection-service-description.md)을 참조하세요.
  
