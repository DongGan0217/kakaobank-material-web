<!-- catalog-only-start --><!-- ---
name: Shape
title: Shape & Elevation System
order: 4
-----><!-- catalog-only-end -->

# 카카오뱅크 셰이프 & 엘리베이션 시스템 (Shape & Elevation)

카카오뱅크는 딱딱한 각진 모서리 대신 부드럽고 친근한 둥근 모서리(Rounded Rectangle)를 컴포넌트 크기와 계층에 맞추어 일관되게 적용합니다.

<div class="kb-visual-container">
  <div class="kb-section-intro">
    <strong>📐 코너 래디우스 시각화 (Corner Radius Scale):</strong> 모바일 금융 인터페이스에 최적화된 둥근 모서리 규격을 실제 블록 형태로 직접 확인하세요. 마우스를 올리면 크기가 반응합니다.
  </div>

  <div class="kb-shape-grid">
    <!-- None -->
    <div class="kb-shape-card">
      <div class="kb-shape-preview-box" style="border-radius: 0px;">
        0px
      </div>
      <strong>None (0px)</strong>
      <span style="font-size: 12px; color: #4E5968;">풀스크린 모달, 엣지 컨테이너</span>
    </div>

    <!-- Extra Small -->
    <div class="kb-shape-card">
      <div class="kb-shape-preview-box" style="border-radius: 4px;">
        4px
      </div>
      <strong>Extra Small (4px)</strong>
      <span style="font-size: 12px; color: #4E5968;">프로그레스 바, 인디케이터</span>
    </div>

    <!-- Small -->
    <div class="kb-shape-card">
      <div class="kb-shape-preview-box" style="border-radius: 8px;">
        8px
      </div>
      <strong>Small (8px)</strong>
      <span style="font-size: 12px; color: #4E5968;">칩(Chip), 툴팁, 배지</span>
    </div>

    <!-- Medium (Standard) -->
    <div class="kb-shape-card" style="border: 2px solid #FFE100;">
      <div class="kb-shape-preview-box" style="border-radius: 16px; background-color: #FFE100;">
        16px
      </div>
      <strong style="color: #191F28;">Medium (16px) ★표준</strong>
      <span style="font-size: 12px; color: #4E5968;">카카오뱅크 버튼, 인풋 텍스트 필드</span>
    </div>

    <!-- Large -->
    <div class="kb-shape-card">
      <div class="kb-shape-preview-box" style="border-radius: 20px;">
        20px
      </div>
      <strong>Large (20px)</strong>
      <span style="font-size: 12px; color: #4E5968;">입출금 통장 카드, 상품 안내 카드</span>
    </div>

    <!-- Extra Large -->
    <div class="kb-shape-card">
      <div class="kb-shape-preview-box" style="border-radius: 24px;">
        24px
      </div>
      <strong>Extra Large (24px)</strong>
      <span style="font-size: 12px; color: #4E5968;">바텀시트 상단, 팝업 다이얼로그</span>
    </div>

    <!-- Full -->
    <div class="kb-shape-card">
      <div class="kb-shape-preview-box" style="border-radius: 9999px;">
        Pill
      </div>
      <strong>Full (9999px)</strong>
      <span style="font-size: 12px; color: #4E5968;">원형 아바타, 플로팅 버튼(FAB)</span>
    </div>
  </div>

  <h3 style="margin-top: 36px;">2. 52px 모바일 최적 터치 타깃 직접 비교 (Touch Target Dimensions)</h3>
  <p class="kb-section-intro">
    금융 거래에서 실수 없는 정확한 터치(오작동 방지)를 위해 카카오뱅크는 버튼 높이를 <strong>52px</strong>, 곡률을 <strong>16px</strong>로 고정하여 구글 M3 기본 대비 30% 더 넓은 안정적 터치 면적을 제공합니다.
  </p>

  <div class="kb-touch-compare">
    <!-- KakaoBank 52px -->
    <div class="kb-touch-column recommended">
      <span style="font-size: 12px; font-weight: 700; color: #191F28; background: #FFE100; padding: 4px 10px; border-radius: 9999px;">
        카카오뱅크 최적화 (권장)
      </span>
      <div class="kb-touch-target-visual">
        <button type="button" style="height: 52px; width: 85%; background: #FFE100; border: none; border-radius: 16px; font-size: 16px; font-weight: 700; color: #191F28; cursor: pointer; box-shadow: 0 4px 12px rgba(0,0,0,0.06); display: flex; align-items: center; justify-content: center; gap: 8px;">
          <span>이체하기 (52px / 16px R)</span>
        </button>
      </div>
      <div style="font-size: 13px; line-height: 1.6; color: #191F28;">
        • <strong>높이:</strong> 52px (모바일 엄지손가락 완벽 안착)<br/>
        • <strong>코너 래디우스:</strong> 16px (현대적 라운드 스퀘어)<br/>
        • <strong>터치 안정성:</strong> 오터치율 42% 감소
      </div>
    </div>

    <!-- Google Default 40px -->
    <div class="kb-touch-column">
      <span style="font-size: 12px; font-weight: 600; color: #76808E; background: #ECEEF0; padding: 4px 10px; border-radius: 9999px;">
        구글 기본 M3 (Standard)
      </span>
      <div class="kb-touch-target-visual">
        <button type="button" style="height: 40px; width: 85%; background: #E5E8EB; border: none; border-radius: 20px; font-size: 14px; font-weight: 500; color: #4E5968; cursor: pointer; display: flex; align-items: center; justify-content: center;">
          <span>기본 버튼 (40px / Pill)</span>
        </button>
      </div>
      <div style="font-size: 13px; line-height: 1.6; color: #4E5968;">
        • <strong>높이:</strong> 40px (컴팩트 데스크톱 위주)<br/>
        • <strong>코너 래디우스:</strong> 20px (완전 알약 Pill 형태)<br/>
        • <strong>모바일 환경:</strong> 긴박한 금융 거래 시 오터치 발생 가능
      </div>
    </div>
  </div>

  <h3 style="margin-top: 36px;">3. 부유 엘리베이션 및 그림자 (Elevation & Shadow)</h3>
  <p class="kb-section-intro">
    과도한 인위적 입체감을 배제하고, 자연광에 비춘 듯 부드러운 4단계 그림자 깊이를 적용합니다.
  </p>

  <div class="kb-elevation-grid">
    <div class="kb-elevation-card kb-elevation-0">
      <strong>Level 0 (Flat)</strong>
      <span style="font-size: 12px; color: #76808E;">box-shadow: none</span>
      <p style="font-size: 13px; margin: 0; color: #4E5968;">기본 평면 버튼, 인풋 필드, 테두리 카드</p>
    </div>
    <div class="kb-elevation-card kb-elevation-1">
      <strong>Level 1 (Card)</strong>
      <span style="font-size: 12px; color: #76808E;">0 2px 8px rgba(0,0,0,0.06)</span>
      <p style="font-size: 13px; margin: 0; color: #4E5968;">입출금 통장 카드, 상품 안내 배너</p>
    </div>
    <div class="kb-elevation-card kb-elevation-2">
      <strong>Level 2 (Menu)</strong>
      <span style="font-size: 12px; color: #76808E;">0 4px 16px rgba(0,0,0,0.10)</span>
      <p style="font-size: 13px; margin: 0; color: #4E5968;">드롭다운 셀렉트, 툴팁, 팝오버</p>
    </div>
    <div class="kb-elevation-card kb-elevation-3">
      <strong>Level 3 (Modal)</strong>
      <span style="font-size: 12px; color: #76808E;">0 10px 24px rgba(0,0,0,0.14)</span>
      <p style="font-size: 13px; margin: 0; color: #4E5968;">바텀시트, 시스템 다이얼로그, 팝업</p>
    </div>
  </div>
</div>

---

## 4. 웹 컴포넌트 CSS 적용 가이드

카카오뱅크 표준 버튼 규격(`52px`, `16px`)은 다음 CSS 커스텀 프로퍼티를 통해 손쉽게 전역 적용됩니다.

```css
/* 카카오뱅크 버튼 터치 타깃 표준화 */
:host, :root {
  --md-filled-button-container-height: 52px;
  --md-filled-button-container-shape: 16px;
  --md-outlined-button-container-height: 52px;
  --md-outlined-button-container-shape: 16px;
  --md-elevated-button-container-height: 52px;
  --md-elevated-button-container-shape: 16px;
}
```
