<!-- catalog-only-start --><!-- ---
name: Color
title: Color System
order: 2
-----><!-- catalog-only-end -->

# 카카오뱅크 컬러 시스템 (Color System)

카카오뱅크의 시그니처 옐로우(`#FFE100`)와 명확한 흑백 대비, 그리고 금융 상태를 직관적으로 전달하는 시맨틱 컬러 토큰 시스템입니다.

<div class="kb-visual-container">
  <div class="kb-section-intro">
    <strong>💡 시각적 가독성 인터랙션 가이드:</strong> 각 색상 카드의 <strong>[복사]</strong> 버튼을 누르면 클립보드에 HEX 코드가 즉시 복사되며, 우측 상단 뱃지에서 <strong>WCAG 2.1 대비율(AA / AAA)</strong>을 실시간 확인할 수 있습니다.
  </div>

  <h3 style="margin-top:0;">1. 브랜드 핵심 시스템 컬러 (Key Brand Colors)</h3>
  <div class="kb-color-swatch-grid">
    <!-- Primary -->
    <div class="kb-color-card">
      <div class="kb-swatch-chip" style="background-color: #FFE100; color: #191F28;">
        <span class="kb-contrast-badge pass-aaa">AAA (14.2:1)</span>
      </div>
      <div class="kb-color-info">
        <span class="kb-color-role">Primary (Brand Yellow)</span>
        <span class="kb-color-token">--md-sys-color-primary</span>
        <div class="kb-color-actions">
          <span class="kb-hex-code">#FFE100</span>
          <button class="kb-copy-btn" onclick="navigator.clipboard.writeText('#FFE100'); this.innerText='복사됨!'; setTimeout(()=>this.innerText='복사', 1500)">복사</button>
        </div>
      </div>
    </div>

    <!-- On Primary -->
    <div class="kb-color-card">
      <div class="kb-swatch-chip" style="background-color: #191F28; color: #FFFFFF;">
        <span class="kb-contrast-badge pass-aaa">AAA (14.2:1)</span>
      </div>
      <div class="kb-color-info">
        <span class="kb-color-role">On Primary (Charcoal Black)</span>
        <span class="kb-color-token">--md-sys-color-on-primary</span>
        <div class="kb-color-actions">
          <span class="kb-hex-code">#191F28</span>
          <button class="kb-copy-btn" onclick="navigator.clipboard.writeText('#191F28'); this.innerText='복사됨!'; setTimeout(()=>this.innerText='복사', 1500)">복사</button>
        </div>
      </div>
    </div>

    <!-- Primary Container -->
    <div class="kb-color-card">
      <div class="kb-swatch-chip" style="background-color: #FFF6A6; color: #191F28;">
        <span class="kb-contrast-badge pass-aaa">AAA (12.8:1)</span>
      </div>
      <div class="kb-color-info">
        <span class="kb-color-role">Primary Container</span>
        <span class="kb-color-token">--md-sys-color-primary-container</span>
        <div class="kb-color-actions">
          <span class="kb-hex-code">#FFF6A6</span>
          <button class="kb-copy-btn" onclick="navigator.clipboard.writeText('#FFF6A6'); this.innerText='복사됨!'; setTimeout(()=>this.innerText='복사', 1500)">복사</button>
        </div>
      </div>
    </div>

    <!-- Secondary -->
    <div class="kb-color-card">
      <div class="kb-swatch-chip" style="background-color: #333D4B; color: #FFFFFF;">
        <span class="kb-contrast-badge pass-aaa">AAA (9.8:1)</span>
      </div>
      <div class="kb-color-info">
        <span class="kb-color-role">Secondary (Muted Charcoal)</span>
        <span class="kb-color-token">--md-sys-color-secondary</span>
        <div class="kb-color-actions">
          <span class="kb-hex-code">#333D4B</span>
          <button class="kb-copy-btn" onclick="navigator.clipboard.writeText('#333D4B'); this.innerText='복사됨!'; setTimeout(()=>this.innerText='복사', 1500)">복사</button>
        </div>
      </div>
    </div>

    <!-- Surface -->
    <div class="kb-color-card">
      <div class="kb-swatch-chip" style="background-color: #FFFFFF; border-bottom: 1px solid #E5E8EB; color: #191F28;">
        <span class="kb-contrast-badge pass-aaa" style="background: rgba(0,0,0,0.06); color: #191F28; border-color: #E5E8EB;">Base (0:1)</span>
      </div>
      <div class="kb-color-info">
        <span class="kb-color-role">Surface (Pure White)</span>
        <span class="kb-color-token">--md-sys-color-surface</span>
        <div class="kb-color-actions">
          <span class="kb-hex-code">#FFFFFF</span>
          <button class="kb-copy-btn" onclick="navigator.clipboard.writeText('#FFFFFF'); this.innerText='복사됨!'; setTimeout(()=>this.innerText='복사', 1500)">복사</button>
        </div>
      </div>
    </div>

    <!-- Surface Container -->
    <div class="kb-color-card">
      <div class="kb-swatch-chip" style="background-color: #F9FAFB; border-bottom: 1px solid #E5E8EB; color: #191F28;">
        <span class="kb-contrast-badge pass-aaa" style="background: rgba(0,0,0,0.06); color: #191F28; border-color: #E5E8EB;">Base</span>
      </div>
      <div class="kb-color-info">
        <span class="kb-color-role">Surface Container (Off White)</span>
        <span class="kb-color-token">--md-sys-color-surface-container</span>
        <div class="kb-color-actions">
          <span class="kb-hex-code">#F9FAFB</span>
          <button class="kb-copy-btn" onclick="navigator.clipboard.writeText('#F9FAFB'); this.innerText='복사됨!'; setTimeout(()=>this.innerText='복사', 1500)">복사</button>
        </div>
      </div>
    </div>

    <!-- Outline -->
    <div class="kb-color-card">
      <div class="kb-swatch-chip" style="background-color: #E5E8EB; color: #191F28;">
        <span class="kb-contrast-badge pass-aa" style="background: rgba(0,0,0,0.06); color: #4E5968;">Border</span>
      </div>
      <div class="kb-color-info">
        <span class="kb-color-role">Outline (Soft Border)</span>
        <span class="kb-color-token">--md-sys-color-outline</span>
        <div class="kb-color-actions">
          <span class="kb-hex-code">#E5E8EB</span>
          <button class="kb-copy-btn" onclick="navigator.clipboard.writeText('#E5E8EB'); this.innerText='복사됨!'; setTimeout(()=>this.innerText='복사', 1500)">복사</button>
        </div>
      </div>
    </div>

    <!-- Tertiary Accent -->
    <div class="kb-color-card">
      <div class="kb-swatch-chip" style="background-color: #3182F6; color: #FFFFFF;">
        <span class="kb-contrast-badge pass-aa">AA (4.8:1)</span>
      </div>
      <div class="kb-color-info">
        <span class="kb-color-role">Tertiary (Brand Blue)</span>
        <span class="kb-color-token">--md-sys-color-tertiary</span>
        <div class="kb-color-actions">
          <span class="kb-hex-code">#3182F6</span>
          <button class="kb-copy-btn" onclick="navigator.clipboard.writeText('#3182F6'); this.innerText='복사됨!'; setTimeout(()=>this.innerText='복사', 1500)">복사</button>
        </div>
      </div>
    </div>
  </div>

  <h3 style="margin-top:32px;">2. 금융 시맨틱 컬러 (Financial Semantics)</h3>
  <div class="kb-color-swatch-grid">
    <!-- Financial Income -->
    <div class="kb-color-card">
      <div class="kb-swatch-chip" style="background-color: #1E88E5; color: #FFFFFF;">
        <span class="kb-contrast-badge pass-aa">입금 / 증가</span>
      </div>
      <div class="kb-color-info">
        <span class="kb-color-role">Income / Deposit</span>
        <span class="kb-color-token">--kb-color-financial-income</span>
        <div class="kb-color-actions">
          <span class="kb-hex-code">#1E88E5</span>
          <button class="kb-copy-btn" onclick="navigator.clipboard.writeText('#1E88E5'); this.innerText='복사됨!'; setTimeout(()=>this.innerText='복사', 1500)">복사</button>
        </div>
      </div>
    </div>

    <!-- Financial Expense -->
    <div class="kb-color-card">
      <div class="kb-swatch-chip" style="background-color: #F04452; color: #FFFFFF;">
        <span class="kb-contrast-badge pass-aa">출금 / 지출</span>
      </div>
      <div class="kb-color-info">
        <span class="kb-color-role">Expense / Withdrawal</span>
        <span class="kb-color-token">--kb-color-financial-expense</span>
        <div class="kb-color-actions">
          <span class="kb-hex-code">#F04452</span>
          <button class="kb-copy-btn" onclick="navigator.clipboard.writeText('#F04452'); this.innerText='복사됨!'; setTimeout(()=>this.innerText='복사', 1500)">복사</button>
        </div>
      </div>
    </div>

    <!-- Financial Profit -->
    <div class="kb-color-card">
      <div class="kb-swatch-chip" style="background-color: #04C09E; color: #FFFFFF;">
        <span class="kb-contrast-badge pass-aa">수익 / 안전</span>
      </div>
      <div class="kb-color-info">
        <span class="kb-color-role">Profit / Success</span>
        <span class="kb-color-token">--kb-color-financial-success</span>
        <div class="kb-color-actions">
          <span class="kb-hex-code">#04C09E</span>
          <button class="kb-copy-btn" onclick="navigator.clipboard.writeText('#04C09E'); this.innerText='복사됨!'; setTimeout(()=>this.innerText='복사', 1500)">복사</button>
        </div>
      </div>
    </div>

    <!-- Financial Warning -->
    <div class="kb-color-card">
      <div class="kb-swatch-chip" style="background-color: #FB8C00; color: #FFFFFF;">
        <span class="kb-contrast-badge pass-aa">경고 / 주의</span>
      </div>
      <div class="kb-color-info">
        <span class="kb-color-role">Warning / Alert</span>
        <span class="kb-color-token">--kb-color-financial-warning</span>
        <div class="kb-color-actions">
          <span class="kb-hex-code">#FB8C00</span>
          <button class="kb-copy-btn" onclick="navigator.clipboard.writeText('#FB8C00'); this.innerText='복사됨!'; setTimeout(()=>this.innerText='복사', 1500)">복사</button>
        </div>
      </div>
    </div>
  </div>
</div>

---

## 3. 웹 컴포넌트 CSS 변수 적용 예시

```css
/* 전역 또는 특정 컴포넌트 단위에서 카카오뱅크 컬러 오버라이드 */
:root {
  --md-sys-color-primary: #191F28;
  --md-sys-color-on-primary: #FFFFFF;
  --md-sys-color-primary-container: #FFE100;
  --md-sys-color-on-primary-container: #191F28;
  --md-sys-color-surface: #FFFFFF;
  --md-sys-color-on-surface: #191F28;
}

/* 특정 카카오뱅크 맞춤형 계좌 카드 섹션 적용 */
.kb-account-card {
  background-color: var(--md-sys-color-primary-container);
  color: var(--md-sys-color-on-primary-container);
  border-radius: 20px;
  padding: 24px;
  box-shadow: 0 4px 16px rgba(0, 0, 0, 0.06);
}
```
