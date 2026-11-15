<!-- catalog-only-start --><!-- ---
name: Typography
title: Typography System
order: 3
-----><!-- catalog-only-end -->

# 카카오뱅크 타이포그래피 시스템 (Typography)

카카오뱅크는 가독성이 뛰어나고 현대적인 **Pretendard Variable** 산세리프 웹폰트를 표준 폰트로 채택하고 있으며, 한글 금융 텍스트에 최적화된 **밀착 자간(`-0.03em`)**을 전역에 적용합니다.

---

## 1. 폰트 패밀리 사양 (Font Family)

카카오뱅크 디자인 시스템의 기본 타이포그래피 토큰은 가변 두께(Variable Weight 100~900)를 지원하는 `Pretendard Variable`을 1순위로 선언합니다.

```css
:root {
  --md-ref-typeface-brand: 'Pretendard Variable', Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, sans-serif;
  --md-ref-typeface-plain: 'Pretendard Variable', Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, sans-serif;
  letter-spacing: -0.03em;
}
```

---

## 2. 15단계 타입스케일 매트릭스 (15 Typescale Roles)

| 롤 (Role) | CSS 토큰 | 크기 (Font Size) | 줄높이 (Line Height) | 두께 (Weight) | 주요 용도 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Display Large** | `--md-sys-typescale-display-large` | `57px` | `64px` | 800 (ExtraBold) | 대형 마케팅 헤드라인 |
| **Display Medium** | `--md-sys-typescale-display-medium` | `45px` | `52px` | 700 (Bold) | 프로모션 타이틀 |
| **Display Small** | `--md-sys-typescale-display-small` | `36px` | `44px` | 700 (Bold) | 통장 잔액 강조 숫자 |
| **Headline Large** | `--md-sys-typescale-headline-large` | `32px` | `40px` | 700 (Bold) | 섹션 메인 헤딩 |
| **Headline Medium** | `--md-sys-typescale-headline-medium` | `28px` | `36px` | 600 (SemiBold) | 뷰 타이틀, 모달 타이틀 |
| **Headline Small** | `--md-sys-typescale-headline-small` | `24px` | `32px` | 600 (SemiBold) | 계좌 카드 명칭 |
| **Title Large** | `--md-sys-typescale-title-large` | `22px` | `28px` | 600 (SemiBold) | 리스트 그룹 헤더 |
| **Title Medium** | `--md-sys-typescale-title-medium` | `16px` | `24px` | 600 (SemiBold) | 서브 타이틀, 항목명 |
| **Title Small** | `--md-sys-typescale-title-small` | `14px` | `20px` | 600 (SemiBold) | 소제목, 카드 부제목 |
| **Body Large** | `--md-sys-typescale-body-large` | `16px` | `24px` | 400 (Regular) | 본문 기본 텍스트 |
| **Body Medium** | `--md-sys-typescale-body-medium` | `14px` | `20px` | 400 (Regular) | 상품 설명, 거래 내역 |
| **Body Small** | `--md-sys-typescale-body-small` | `12px` | `16px` | 400 (Regular) | 부가 설명, 유의사항 |
| **Label Large** | `--md-sys-typescale-label-large` | `16px` | `20px` | 700 (Bold) | 52px 액션 버튼 텍스트 |
| **Label Medium** | `--md-sys-typescale-label-medium` | `12px` | `16px` | 600 (SemiBold) | 상태 배지, 인풋 라벨 |
| **Label Small** | `--md-sys-typescale-label-small` | `11px` | `16px` | 500 (Medium) | 캡션, 타임스탬프 |

---

## 3. 웹폰트 로드 및 CDN 가이드

카카오뱅크 웹 컴포넌트를 사용하기 위해 HTML `<head>`에 Pretendard Variable 웹폰트를 로드합니다.

```html
<link 
  rel="stylesheet" 
  as="style" 
  crossorigin 
  href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/variable/pretendardvariable-dynamic-subset.css" 
/>
```
