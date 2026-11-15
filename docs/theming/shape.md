<!-- catalog-only-start --><!-- ---
name: Shape
title: Shape & Elevation System
order: 4
-----><!-- catalog-only-end -->

# 카카오뱅크 셰이프 시스템 (Shape & Elevation)

카카오뱅크는 딱딱한 각진 모서리 대신 부드럽고 친근한 둥근 모서리(Rounded Rectangle)를 컴포넌트 크기와 계층에 맞추어 일관되게 적용합니다.

---

## 1. 코너 래디우스 스케일 (Corner Radius Scale)

Google M3의 완전한 알약(Pill 9999px) 형태와 차별화하여, 모바일 금융 터치에 가장 안정감을 주는 `16px` 라운드를 버튼 표준으로 채택합니다.

| 분류 | CSS 토큰 | 값 | 주요 적용 컴포넌트 |
| :--- | :--- | :--- | :--- |
| **None** | `--md-sys-shape-corner-none` | `0px` | 풀스크린 모달, 엣지 투 엣지 컨테이너 |
| **Extra Small** | `--md-sys-shape-corner-extra-small`| `4px` | 프로그레스 바, 인디케이터 |
| **Small** | `--md-sys-shape-corner-small` | `8px` | 칩(Chips), 툴팁, 배지(Badge) |
| **Medium (Standard)** | `--md-sys-shape-corner-medium`| **`16px`** | **Filled/Outlined 버튼, 인풋 텍스트 필드** |
| **Large** | `--md-sys-shape-corner-large` | **`20px`** | 입출금 통장 카드, 상품 안내 카드 |
| **Extra Large** | `--md-sys-shape-corner-extra-large`| **`24px`** | 바텀시트(상단), 팝업 다이얼로그(Dialog) |
| **Full** | `--md-sys-shape-corner-full` | `9999px` | 프로필 아바타, 원형 플로팅 액션 버튼 |

---

## 2. 52px 모바일 최적 터치 타깃 (Touch Target Dimensions)

금융 거래에서 실수 없는 정확한 터치를 보장하기 위해, 모든 주요 인터랙션 요소의 기본 높이를 52px로 표준화하였습니다.

```css
/* 카카오뱅크 버튼 터치 타깃 */
:host {
  --md-filled-button-container-height: 52px;
  --md-filled-button-container-shape: 16px;
  --md-outlined-button-container-height: 52px;
  --md-outlined-button-container-shape: 16px;
}
```

---

## 3. 엘리베이션 및 그림자 (Elevation & Shadow)

과도한 입체감 대신 평면성과 은은한 부드러운 그림자를 사용하여 시각적 피로를 줄입니다.

- **Level 0 (Flat)**: `box-shadow: none;` (기본 버튼 및 입력 필드)
- **Level 1 (Card)**: `0 4px 16px rgba(0, 0, 0, 0.04);` (계좌 목록 카드)
- **Level 2 (Dropdown/Menu)**: `0 8px 24px rgba(0, 0, 0, 0.08);` (선택 메뉴)
- **Level 3 (Modal/Sheet)**: `0 16px 40px rgba(0, 0, 0, 0.16);` (바텀시트 및 팝업)
