---
title: Exchange Online Protection 서비스 설명
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: Exchange Online Protection의 기능 및 요구 사항에 대해 알아봅니다. 여기에는 Exchange Online Protection을 제공 하는 계획 목록과 이러한 요금제의 기능 비교가 포함 되어 있습니다.
ms.openlocfilehash: c385ef02d7d3c28a37b71162daace04a0cee800c
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 11/26/2019
ms.locfileid: "39260923"
---
# <a name="exchange-online-protection-service-description"></a>Exchange Online Protection 서비스 설명

Exchange Online Protection의 기능 및 요구 사항에 대해 알아봅니다. 여기에는 Exchange Online Protection을 제공 하는 계획 목록과 이러한 요금제의 기능 비교가 포함 되어 있습니다.

Microsoft EOP(Exchange Online Protection)는 스팸 및 맬웨어로부터 조직을 보호하는 클라우드 기반 전자 메일 필터링 서비스로, 메시징 정책 위반으로부터 조직을 보호하는 기능을 포함합니다. EOP를 사용하면 메시징 환경을 쉽게 관리하고 온-프레미스 하드웨어 및 소프트웨어 유지 관리 시의 부담을 대부분 완화할 수 있습니다.

다음 목록에서는 메시징 보호를 위해 EOP을 사용할 수 있는 기본 방법에 대해 설명 합니다.

- **독립 실행형 시나리오에서**EOP는 온-프레미스 전자 메일 환경 (Exchange Server 또는 기타 온-프레미스 SMTP 전자 메일 솔루션)에 대해 클라우드 기반 전자 메일 보호 기능을 제공 합니다.

- **Microsoft Exchange online의 일부로**, EOP는 기본적으로 Exchange Online 클라우드 호스트 사서함을 보호 합니다. Exchange Online에 대 한 자세한 내용은 [Exchange online 서비스 설명을](../exchange-online-service-description/exchange-online-service-description.md)참조 하세요.

- **하이브리드 배포에서**: 온-프레미스 및 클라우드 사서함을 함께 사용 하는 경우 메시징 환경을 보호 하 고 메일 라우팅을 제어 하도록 EOP를 구성할 수 있습니다.

계획 간에 기능을 비교하려면 [Office 365 비즈니스 에디션 계획 비교](https://products.office.com/business/compare-more-office-365-for-business-plans)를 참조하세요.

Exchange Online Protection을 구입하려면 [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection)을 참조하세요.

> [!NOTE]
> EOP가 FOPE (Forefront Online Protection for Exchange)를 대체 했습니다. 모든 FOPE 고객은 EOP로 전환됩니다.

## <a name="whats-new-in-exchange-online-protection-eop"></a>EOP(Exchange Online Protection)의 새로운 기능

[업무용 Office 365 로드맵](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx)에서는 예정된 새로운 기능에 대한 정보를 제공합니다.

## <a name="exchange-online-protection-eop-plans"></a>EOP(Exchange Online Protection) 계획

EOP는 다음의 구독 계획을 통해 사용할 수 있습니다.

|**계획**|**설명**|
|:-----|:-----|
|[EOP 독립 실행형](https://products.office.com/exchange/exchange-email-security-spam-protection)|온-프레미스 전자 메일 조직을 보호 하는 별도의 클라우드 기반 서비스입니다.|
|[Exchange Online의 EOP 기능](https://products.office.com/exchange/compare-microsoft-exchange-online-plans)|Exchange Online 클라우드 호스팅 사서함에 대 한 기본 제공 보호입니다.|
|[Exchange Enterprise CAL with Services](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)|EOP 및 기타 클라우드 기반 기능을 포함 하는 온-프레미스 Exchange 조직에 대해 구매한 추가 기능 라이선스 (자세한 내용은 다음 섹션 참조).|

### <a name="exchange-enterprise-cal-with-services-features"></a>Exchange Enterprise CAL with Services 기능

Microsoft Exchange Enterprise CAL with Services는 EOP의 전자 메일 보호 기능과 다음과 같은 추가 클라우드 기반 기능을 제공 합니다.

- [DLP(데이터 손실 방지)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [웹 서비스를 사용하여 보고](reporting-and-message-trace.md#reporting-using-web-services)

Exchange Enterprise CAL with Services 라이선스에 대 한 자세한 내용은 [Exchange Server 라이선스](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)를 참조 하세요.

Exchange Enterprise CAL (서비스 라이선스 포함)이 있고 EOP를 프로 비전 하려는 경우에는 [Set up THE EOP service](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-your-eop-service)의 지침을 따르세요. 설정 단계는 EOP 독립 실행형 설정 단계와 동일합니다.

> [!NOTE]
> Exchange Enterprise CAL with Services의 새 기능은 EOP 독립 실행형이 아닌 Exchange Online과 같은 시기에 배포됩니다. EOP 독립 실행형과 Exchange Online/Exchange Enterprise CAL with Services의 배포 일정은 약간 다를 수도 있습니다.

## <a name="requirements-for-exchange-online-protection-eop"></a>EOP(Exchange Online Protection)에 대한 요구 사항

EOP는 Microsoft Exchange Server와 같은 SMTP 메일 전송 에이전트에서 사용할 수 있습니다. EOP에서 지원 되는 운영 체제, 웹 브라우저 및 언어에 대 한 자세한 내용은 exchange [Online Protection의 exchange 관리 센터](https://docs.microsoft.com/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)에서 "지원 되는 브라우저" 및 "지원 되는 언어" 섹션을 참조 하십시오.

## <a name="limits"></a>제한

EOP의 제한에 대 한 내용은 [Exchange Online Protection 제한을](exchange-online-protection-limits.md)참조 하세요.

## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>EOP(Exchange Online Protection) 계획에서의 기능 가용성

각 기능은 아래와 같습니다. EOP 기능에 대한 자세한 내용을 보려면 표에 있는 링크를 클릭하세요. Exchange Online이 언급된 경우 대개 Office 365 Enterprise 서비스 제품군을 지칭하는 것입니다.

|||||
|:-----|:-----|:-----|:-----|
|**기능**|**EOP 독립 실행형**|**Exchange Online의 <br/> EOP 기능**|**Exchange Enterprise <br/> CAL (서비스 포함)**|
|[메일 받는 사람](recipient-domain-and-company-management.md#mail-recipients)|예<sup>1</sup>|예<sup>1</sup>|예|
|[관리자 역할 그룹 권한](recipient-domain-and-company-management.md#admin-role-group-permissions)|예<sup>2</sup>|예|예|
|[도메인 관리](recipient-domain-and-company-management.md#domain-management)|예<sup>3</sup>|예<sup>3</sup>|예<sup>3</sup>|
|[하위 도메인 일치](recipient-domain-and-company-management.md#match-subdomains)|예|예|아니요|
|[DBEB(디렉터리 기반 Edge 차단)](recipient-domain-and-company-management.md#directory-based-edge-blocking-dbeb)|예|예|예|
|[메일 흐름 규칙](../exchange-online-service-description/message-policy-and-compliance.md#mail-flow-rules)|예<sup>4</sup>|예<sup>4, 6</sup>|예|
|[감사 로깅](messaging-policy-and-compliance-servicedesc.md#audit-logging)|예<sup>5</sup>|예|예|
|[DLP(데이터 손실 방지)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)|아니요|있음|예<sup>6</sup>|
|[Office 365 메시지 암호화](messaging-policy-and-compliance-servicedesc.md#office-365-message-encryption)|예<sup>12</sup>|예|예<sup>12</sup>|
|[스팸 방지 보호 기능](anti-spam-and-anti-malware-protection-eop.md#anti-spam-protection)(기본 제공)|예|예|예|
|[스팸 방지 정책 사용자 지정](anti-spam-and-anti-malware-protection-eop.md#customize-anti-spam-policies)|예<sup>7</sup>|예|예|
|[맬웨어 방지 보호 기능](anti-spam-and-anti-malware-protection-eop.md#anti-malware-protection)(기본 제공)|예<sup>13</sup>|예|예|
|[맬웨어 방지 정책 사용자 지정](anti-spam-and-anti-malware-protection-eop.md#customize-anti-malware-policies)|예|예|예|
|[격리](anti-spam-and-anti-malware-protection-eop.md#quarantine): 관리자 관리|예|예|예|
|[격리](anti-spam-and-anti-malware-protection-eop.md#quarantine): 최종 사용자 자기 관리|예|예|예|
|[Outlook 용 보고서 메시지 추가 기능](anti-spam-and-anti-malware-protection-eop.md#report-message-add-in-for-outlook)|예|예|예|
|[웹용 Outlook에서 정크 메일 보고](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-in-outlook-on-the-web)|예|예|예|
|[Office 365와 자체 메일 서버 간의 이메일 라우팅](mail-flow-eop.md#routing-email-between-office-365-and-your-own-email-servers)|예|예|예|
|[신뢰할 수 있는 파트너와의 보안 메시징](mail-flow-eop.md#secure-messaging-with-a-trusted-partner)|예|예|예|
|[수신 허용 목록에 파트너의 IP 주소 추가](mail-flow-eop.md#safe-listing-a-partners-ip-address)|예|예|예|
|[조건부 메일 라우팅](mail-flow-eop.md#conditional-mail-routing)|예|예|예|
|[하이브리드 메일 라우팅](mail-flow-eop.md#hybrid-mail-routing)|예|예|예|
|[Microsoft 365 관리 센터 보고서](reporting-and-message-trace.md#microsoft-365-admin-center-reports)<br/> |예<sup>9</sup>|예<sup>10</sup>|예 <sup>9, 10</sup>|
|[웹 서비스를 사용하여 보고](reporting-and-message-trace.md#reporting-using-web-services)|아니요|예|예|
|[메시지 추적](reporting-and-message-trace.md#message-trace)|예<sup>15</sup>|예<sup>15</sup>|예|
|[Microsoft 365 관리 센터에 대 한 액세스 권한](administration-and-management-eop.md#access-to-the-microsoft-365-admin-center)|예|예|예|
|[Exchange 관리 센터에 대 한 액세스 권한](administration-and-management-eop.md#access-to-the-exchange-admin-center (EAC))|예|예|예|
|[Remote Windows PowerShell access](administration-and-management-eop.md#remote-windows-powershell-access)|예|예|예|

<sup>1</sup> 메일 사용자는 "사서함"으로 정의되며 외부 메일 연락처와 마찬가지로 EAC(Exchange 관리 센터)에서 직접 추가, 제거 및 관리할 수 있습니다. <br/>
<sup>2</sup> RBAC 사용자 지정은 해당하지 않습니다. 관리자 역할만 해당합니다. <br/>
<sup>3</sup> EAC에서 관리되는 도메인을 볼 수 있으며 도메인 유형을 편집할 수 있습니다. 다른 모든 도메인 관리는 Microsoft 365 관리 센터에서 수행 해야 합니다.<br/>
<sup>4</sup> EOP의 메일 흐름 규칙 (전송 규칙이 라고도 함)은 [Exchange Online Protection의 메일 흐름 규칙 (전송 규칙)](https://docs.microsoft.com/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0)에 설명 되어 있습니다. 사용할 수 있는 메일 흐름 규칙 조건, 예외 및 작업은 EOP과 Exchange Online 간에 약간씩 다릅니다. Exchange online의 메일 [흐름 규칙 조건 및 예외 (조건자)](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) 에서는 exchange online의 메일 흐름 [규칙 동작](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions)에 나와 있습니다.<br/>
<sup>5</sup> EOP 감사 보고서는 사서함에 대한 정보가 제외된, Exchange Online 감사 보고서의 하위 집합입니다. <br/>
<sup>6</sup> Exchange Enterprise CAL with Services 고객은 DLP 정책 팁을 사용할 수 없습니다.  <br/>
<sup>7</sup> 기본 콘텐츠 필터 동작은 스팸 메시지를 받는 사람의 정크 메일 폴더로 이동하는 것입니다. 이를 위해 온-프레미스 Exchange 사서함을 사용 하려면 EOP에서 추가 된 스팸 헤더를 검색 하도록 온-프레미스 Exchange 조직에서 두 개의 전송 규칙을 구성 해야 합니다. 자세한 내용은 [스팸이 각 사용자의 정크 메일 폴더로 라우팅되도록](https://docs.microsoft.com/microsoft-365/security/office-365-security/ensure-that-spam-is-routed-to-each-user-s-junk-email-folder)합니다 .를 참조 하세요. <br/>
<sup>9</sup> EOP 보고서는 사서함에 대한 정보를 제외한 Exchange Online 보고서의 하위 집합입니다.<br/>
<sup>10</sup> DLP 보고서가 포함됩니다. <br/>
<sup>12</sup> Azure Information protection을 구입 하 고 Exchange online Protection을 사용 하 여 exchange online을 통해 전자 메일을 라우팅하는 온-프레미스 고객에 게 지원 됩니다. <br/>
<sup>13</sup> 인바운드 및 아웃바운드 메시지는 검사하지만 조직의 보낸 사람이 조직의 받는 사람에게 보낸 내부 메시지는 검사하지 않습니다. <br/>
<sup>15</sup> 하이브리드 설치는 하이브리드 마법사를 통해 사용할 수 없지만 Exchange SP1이 있는 경우에는 수동으로 설정할 수 있습니다.
