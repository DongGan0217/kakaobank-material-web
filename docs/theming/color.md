<!-- catalog-only-start --><!-- ---
name: Color
title: Color System
order: 2
-----><!-- catalog-only-end -->

# 카카오뱅크 컬러 시스템 (Color System)

카카오뱅크의 시그니처 옐로우(`#FFE100`)와 명확한 흑백 대비, 그리고 금융 상태를 직관적으로 전달하는 시맨틱 컬러 토큰 시스템입니다.

## 1. 브랜드 핵심 컬러 (Key Brand Colors)

카카오뱅크는 사용자의 금융 경험에서 가장 신뢰할 수 있고 친근한 인터페이스를 제공하기 위해 노란색을 기본 식별 컬러로 사용하며, 금융 수치와 텍스트의 가독성을 위해 순수 블랙을 기본 전경색으로 사용합니다.

| 역할 | CSS 토큰 | 색상 코드 | 용도 |
| :--- | :--- | :--- | :--- |
| **Primary** | `--md-sys-color-primary` | `#FFE100` | 핵심 액션 버튼, 강조 배지, 탭 활성화 |
| **On Primary** | `--md-sys-color-on-primary` | `#000000` | 옐로우 배경 위의 텍스트 및 아이콘 |
| **Primary Container**| `--md-sys-color-primary-container` | `#FFF7B2` | 계좌 카드 배경, 알림 배너 하이라이트 |
| **On Primary Container**| `--md-sys-color-on-primary-container` | `#000000` | 옐로우 컨테이너 내부 전경 텍스트 |
| **Secondary** | `--md-sys-color-secondary` | `#222222` | 서브 액션 버튼, 네비게이션 헤더 |
| **On Secondary** | `--md-sys-color-on-secondary` | `#FFFFFF` | 다크 배경 위의 반전 텍스트 |
| **Surface** | `--md-sys-color-surface` | `#FFFFFF` | 메인 페이지 바탕 및 모달 배경 |
| **Surface Container** | `--md-sys-color-surface-container` | `#F8F9FA` | 카드 배경, 입력 폼 필드 배경 |
| **Outline** | `--md-sys-color-outline` | `#E5E7EB` | 카드 테두리, 구분선, 아웃라인 버튼 선 |

---

## 2. 금융 시맨틱 컬러 (Financial Semantics)

입출금, 수익률, 경고 및 거래 상태를 사용자가 즉각 인지할 수 있도록 직관적인 금융 상태 컬러를 표준화하였습니다.

| 상태 | CSS 토큰 | 색상 코드 | 설명 및 적용처 |
| :--- | :--- | :--- | :--- |
| **입금 / 증가** | `--kb-color-financial-income` | `#1E88E5` | 통장 잔액 증가, 계좌 입금 내역 |
| **출금 / 감소** | `--kb-color-financial-expense` | `#E53935` | 계좌 출금, 카드 승인, 지출 내역 |
| **수익 / 안전** | `--kb-color-financial-success` | `#43A047` | 펀드 수익, 안전한 인증 통과 상태 |
| **경고 / 주의** | `--kb-color-financial-warning` | `#FB8C00` | 이상 거래 탐지 경고, 이체 한도 초과 주의 |

---

## 3. 웹 컴포넌트 CSS 변수 적용 예시

```css
/* 전역 또는 특정 컴포넌트 단위에서 카카오뱅크 컬러 오버라이드 */
:root {
  --md-sys-color-primary: #FFE100;
  --md-sys-color-on-primary: #000000;
  --md-sys-color-surface: #FFFFFF;
  --md-sys-color-on-surface: #111111;
}

/* 특정 카카오뱅크 맞춤형 섹션 적용 */
.kb-account-highlight {
  background-color: var(--md-sys-color-primary-container);
  color: var(--md-sys-color-on-primary-container);
  border-radius: 20px;
  padding: 24px;
}
```
