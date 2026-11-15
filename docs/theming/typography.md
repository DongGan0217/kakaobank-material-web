<!-- catalog-only-start --><!-- ---
name: Typography
title: Typography System
order: 3
-----><!-- catalog-only-end -->

# 카카오뱅크 타이포그래피 시스템 (Typography)

카카오뱅크는 가독성이 뛰어나고 현대적인 **Pretendard Variable** 산세리프 웹폰트를 표준 폰트로 채택하고 있으며, 한글 금융 텍스트에 최적화된 **밀착 자간(`-0.03em`)**을 전역에 적용합니다.

<div class="kb-visual-container">
  <div class="kb-section-intro">
    <strong>✨ 실시간 타이포그래피 인터랙티브 샌드박스:</strong> 아래 텍스트 입력창에 원하는 문구를 입력하면 15개 타입스케일의 실제 Pretendard Variable 렌더링 결과가 실시간으로 동기화됩니다.
  </div>

  <div class="kb-sandbox-input-box">
    <label for="kb-type-tester">미리보기 텍스트 입력:</label>
    <input 
      id="kb-type-tester" 
      class="kb-sandbox-input" 
      type="text" 
      value="카카오뱅크 편리한 모바일 금융 1,234,567원" 
      placeholder="텍스트를 입력하여 글꼴 스케일을 테스트해보세요" 
      oninput="document.querySelectorAll('.kb-type-target-text').forEach(el => el.innerText = this.value || '카카오뱅크 편리한 모바일 금융 1,234,567원')"
    />
  </div>

  <div class="kb-type-scale-list">
    <!-- Display Large -->
    <div class="kb-type-scale-card">
      <div class="kb-type-meta">
        <span class="kb-type-role">Display Large</span>
        <span class="kb-type-specs">57px / 64px / ExtraBold (800)</span>
      </div>
      <p class="kb-type-target-text" style="font-size: 57px; line-height: 64px; font-weight: 800;">
        카카오뱅크 편리한 모바일 금융 1,234,567원
      </p>
    </div>

    <!-- Display Medium -->
    <div class="kb-type-scale-card">
      <div class="kb-type-meta">
        <span class="kb-type-role">Display Medium</span>
        <span class="kb-type-specs">45px / 52px / Bold (700)</span>
      </div>
      <p class="kb-type-target-text" style="font-size: 45px; line-height: 52px; font-weight: 700;">
        카카오뱅크 편리한 모바일 금융 1,234,567원
      </p>
    </div>

    <!-- Display Small -->
    <div class="kb-type-scale-card">
      <div class="kb-type-meta">
        <span class="kb-type-role">Display Small</span>
        <span class="kb-type-specs">36px / 44px / Bold (700)</span>
      </div>
      <p class="kb-type-target-text" style="font-size: 36px; line-height: 44px; font-weight: 700;">
        카카오뱅크 편리한 모바일 금융 1,234,567원
      </p>
    </div>

    <!-- Headline Large -->
    <div class="kb-type-scale-card">
      <div class="kb-type-meta">
        <span class="kb-type-role">Headline Large</span>
        <span class="kb-type-specs">32px / 40px / Bold (700)</span>
      </div>
      <p class="kb-type-target-text" style="font-size: 32px; line-height: 40px; font-weight: 700;">
        카카오뱅크 편리한 모바일 금융 1,234,567원
      </p>
    </div>

    <!-- Headline Medium -->
    <div class="kb-type-scale-card">
      <div class="kb-type-meta">
        <span class="kb-type-role">Headline Medium</span>
        <span class="kb-type-specs">28px / 36px / SemiBold (600)</span>
      </div>
      <p class="kb-type-target-text" style="font-size: 28px; line-height: 36px; font-weight: 600;">
        카카오뱅크 편리한 모바일 금융 1,234,567원
      </p>
    </div>

    <!-- Headline Small -->
    <div class="kb-type-scale-card">
      <div class="kb-type-meta">
        <span class="kb-type-role">Headline Small</span>
        <span class="kb-type-specs">24px / 32px / SemiBold (600)</span>
      </div>
      <p class="kb-type-target-text" style="font-size: 24px; line-height: 32px; font-weight: 600;">
        카카오뱅크 편리한 모바일 금융 1,234,567원
      </p>
    </div>

    <!-- Title Large -->
    <div class="kb-type-scale-card">
      <div class="kb-type-meta">
        <span class="kb-type-role">Title Large</span>
        <span class="kb-type-specs">22px / 28px / SemiBold (600)</span>
      </div>
      <p class="kb-type-target-text" style="font-size: 22px; line-height: 28px; font-weight: 600;">
        카카오뱅크 편리한 모바일 금융 1,234,567원
      </p>
    </div>

    <!-- Title Medium -->
    <div class="kb-type-scale-card">
      <div class="kb-type-meta">
        <span class="kb-type-role">Title Medium</span>
        <span class="kb-type-specs">16px / 24px / SemiBold (600)</span>
      </div>
      <p class="kb-type-target-text" style="font-size: 16px; line-height: 24px; font-weight: 600;">
        카카오뱅크 편리한 모바일 금융 1,234,567원
      </p>
    </div>

    <!-- Title Small -->
    <div class="kb-type-scale-card">
      <div class="kb-type-meta">
        <span class="kb-type-role">Title Small</span>
        <span class="kb-type-specs">14px / 20px / SemiBold (600)</span>
      </div>
      <p class="kb-type-target-text" style="font-size: 14px; line-height: 20px; font-weight: 600;">
        카카오뱅크 편리한 모바일 금융 1,234,567원
      </p>
    </div>

    <!-- Body Large -->
    <div class="kb-type-scale-card">
      <div class="kb-type-meta">
        <span class="kb-type-role">Body Large</span>
        <span class="kb-type-specs">16px / 24px / Regular (400)</span>
      </div>
      <p class="kb-type-target-text" style="font-size: 16px; line-height: 24px; font-weight: 400;">
        카카오뱅크 편리한 모바일 금융 1,234,567원
      </p>
    </div>

    <!-- Body Medium -->
    <div class="kb-type-scale-card">
      <div class="kb-type-meta">
        <span class="kb-type-role">Body Medium</span>
        <span class="kb-type-specs">14px / 20px / Regular (400)</span>
      </div>
      <p class="kb-type-target-text" style="font-size: 14px; line-height: 20px; font-weight: 400;">
        카카오뱅크 편리한 모바일 금융 1,234,567원
      </p>
    </div>

    <!-- Body Small -->
    <div class="kb-type-scale-card">
      <div class="kb-type-meta">
        <span class="kb-type-role">Body Small</span>
        <span class="kb-type-specs">12px / 16px / Regular (400)</span>
      </div>
      <p class="kb-type-target-text" style="font-size: 12px; line-height: 16px; font-weight: 400;">
        카카오뱅크 편리한 모바일 금융 1,234,567원
      </p>
    </div>

    <!-- Label Large -->
    <div class="kb-type-scale-card">
      <div class="kb-type-meta">
        <span class="kb-type-role">Label Large (버튼 텍스트)</span>
        <span class="kb-type-specs">16px / 20px / Bold (700)</span>
      </div>
      <p class="kb-type-target-text" style="font-size: 16px; line-height: 20px; font-weight: 700;">
        카카오뱅크 편리한 모바일 금융 1,234,567원
      </p>
    </div>

    <!-- Label Medium -->
    <div class="kb-type-scale-card">
      <div class="kb-type-meta">
        <span class="kb-type-role">Label Medium (배지 라벨)</span>
        <span class="kb-type-specs">12px / 16px / SemiBold (600)</span>
      </div>
      <p class="kb-type-target-text" style="font-size: 12px; line-height: 16px; font-weight: 600;">
        카카오뱅크 편리한 모바일 금융 1,234,567원
      </p>
    </div>

    <!-- Label Small -->
    <div class="kb-type-scale-card">
      <div class="kb-type-meta">
        <span class="kb-type-role">Label Small (캡션 및 날짜)</span>
        <span class="kb-type-specs">11px / 16px / Medium (500)</span>
      </div>
      <p class="kb-type-target-text" style="font-size: 11px; line-height: 16px; font-weight: 500;">
        카카오뱅크 편리한 모바일 금융 1,234,567원
      </p>
    </div>
  </div>
</div>

---

## 3. 웹폰트 로드 및 CSS 전역 선언 가이드

카카오뱅크 웹 컴포넌트를 사용할 때 HTML `<head>`에 Pretendard Variable 웹폰트를 로드하고 다음과 같이 전역 폰트 및 자간(`letter-spacing: -0.03em`)을 설정합니다.

```html
<link 
  rel="stylesheet" 
  as="style" 
  crossorigin 
  href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/variable/pretendardvariable-dynamic-subset.css" 
/>
```

```css
:root {
  font-family: 'Pretendard Variable', Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, sans-serif;
  --md-ref-typeface-brand: 'Pretendard Variable', Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, sans-serif;
  --md-ref-typeface-plain: 'Pretendard Variable', Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, sans-serif;
  letter-spacing: -0.03em;
}
```
