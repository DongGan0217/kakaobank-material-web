<!-- catalog-only-start --><!-- ---
name: Overview
title: Component Overview
order: 1
-----><!-- catalog-only-end -->

# 카카오뱅크 컴포넌트 전체 개요 (Component Overview)

카카오뱅크 디자인 시스템의 **18종 전수 웹 컴포넌트** 목록입니다. 모든 컴포넌트는 Google Material Web 3(M3) 아키텍처를 기반으로 카카오뱅크의 시그니처 옐로우(`#FFE100`), Pretendard Variable 웹폰트, 52px 모바일 터치 타깃이 완벽히 적용되어 있습니다.

<div class="kb-visual-container">
  <div class="kb-section-intro">
    <strong>💡 한눈에 보는 컴포넌트 쇼케이스:</strong> 각 카드의 미니 컴포넌트를 직접 클릭하고 동작을 확인해보세요. 상세 속성 및 실시간 옵션 변경은 <strong>[상세 가이드 보기 →]</strong> 링크를 통해 이동할 수 있습니다.
  </div>

  <div class="kb-overview-grid">
    <!-- 1. Button -->
    <div class="kb-overview-card">
      <div class="kb-overview-preview">
        <button type="button" class="kb-btn-demo filled" style="height: 48px; background: #FFE100; border: none; border-radius: 16px; padding: 0 20px; font-weight: 700; color: #191F28; cursor: pointer; box-shadow: 0 2px 6px rgba(0,0,0,0.06);">
          확인하기
        </button>
      </div>
      <div class="kb-overview-info">
        <span class="kb-overview-title">Button (버튼)</span>
        <p class="kb-overview-desc">핵심 금융 액션을 유도하는 52px 최적화 버튼</p>
        <div class="kb-overview-tags">
          <span class="kb-badge-sm">Filled</span>
          <span class="kb-badge-sm">Outlined</span>
          <span class="kb-badge-sm">Elevated</span>
          <span class="kb-badge-sm">52px Touch</span>
        </div>
        <a href="/components/button/" class="kb-overview-link">상세 가이드 & 샌드박스 →</a>
      </div>
    </div>

    <!-- 2. Checkbox -->
    <div class="kb-overview-card">
      <div class="kb-overview-preview">
        <label style="display: flex; align-items: center; gap: 8px; font-size: 14px; font-weight: 600; cursor: pointer;">
          <input type="checkbox" checked style="width: 20px; height: 20px; accent-color: #FFE100; cursor: pointer;" />
          약관 전체 동의
        </label>
      </div>
      <div class="kb-overview-info">
        <span class="kb-overview-title">Checkbox (체크박스)</span>
        <p class="kb-overview-desc">다중 선택 및 금융 약관 전체 동의 체크박스</p>
        <div class="kb-overview-tags">
          <span class="kb-badge-sm">Checked</span>
          <span class="kb-badge-sm">Indeterminate</span>
          <span class="kb-badge-sm">Error</span>
        </div>
        <a href="/components/checkbox/" class="kb-overview-link">상세 가이드 & 샌드박스 →</a>
      </div>
    </div>

    <!-- 3. Switch -->
    <div class="kb-overview-card">
      <div class="kb-overview-preview">
        <label style="position: relative; display: inline-block; width: 52px; height: 32px;">
          <input type="checkbox" checked style="opacity: 0; width: 0; height: 0;" onchange="this.nextElementSibling.style.background = this.checked ? '#FFE100' : '#E5E8EB'; this.nextElementSibling.children[0].style.transform = this.checked ? 'translateX(20px)' : 'translateX(0)';" />
          <span style="position: absolute; cursor: pointer; inset: 0; background-color: #FFE100; border-radius: 9999px; transition: .2s;">
            <span style="position: absolute; content: ''; height: 24px; width: 24px; left: 4px; bottom: 4px; background-color: #191F28; border-radius: 50%; transition: .2s; transform: translateX(20px);"></span>
          </span>
        </label>
      </div>
      <div class="kb-overview-info">
        <span class="kb-overview-title">Switch (스위치)</span>
        <p class="kb-overview-desc">알림 수신, 간편 로그인 등 On/Off 설정 토글</p>
        <div class="kb-overview-tags">
          <span class="kb-badge-sm">Selected</span>
          <span class="kb-badge-sm">Icons</span>
          <span class="kb-badge-sm">Haptic Feedback</span>
        </div>
        <a href="/components/switch/" class="kb-overview-link">상세 가이드 & 샌드박스 →</a>
      </div>
    </div>

    <!-- 4. Text Field -->
    <div class="kb-overview-card">
      <div class="kb-overview-preview" style="width: 100%;">
        <div style="background: #F9FAFB; border: 1.5px solid #D1D6DB; border-radius: 12px; padding: 10px 14px; width: 85%;">
          <div style="font-size: 11px; color: #4E5968; font-weight: 600;">받는 분 계좌번호</div>
          <div style="font-size: 14px; font-weight: 700; color: #191F28;">3333-01-1234567</div>
        </div>
      </div>
      <div class="kb-overview-info">
        <span class="kb-overview-title">Text Field (텍스트 필드)</span>
        <p class="kb-overview-desc">계좌번호, 이체 금액 입력 및 실시간 유효성 검증</p>
        <div class="kb-overview-tags">
          <span class="kb-badge-sm">Filled</span>
          <span class="kb-badge-sm">Outlined</span>
          <span class="kb-badge-sm">Amount Format</span>
        </div>
        <a href="/components/text-field/" class="kb-overview-link">상세 가이드 & 샌드박스 →</a>
      </div>
    </div>

    <!-- 5. Chip -->
    <div class="kb-overview-card">
      <div class="kb-overview-preview" style="gap: 8px;">
        <span style="background: #FFE100; color: #191F28; padding: 6px 12px; border-radius: 9999px; font-size: 12px; font-weight: 700;">#입출금통장</span>
        <span style="background: #F2F4F6; color: #4E5968; padding: 6px 12px; border-radius: 9999px; font-size: 12px; font-weight: 600;">#모임통장</span>
      </div>
      <div class="kb-overview-info">
        <span class="kb-overview-title">Chip (칩)</span>
        <p class="kb-overview-desc">카테고리 필터링, 추천 태그 및 금융 상품 선별</p>
        <div class="kb-overview-tags">
          <span class="kb-badge-sm">Assist</span>
          <span class="kb-badge-sm">Filter</span>
          <span class="kb-badge-sm">Input</span>
          <span class="kb-badge-sm">Suggestion</span>
        </div>
        <a href="/components/chip/" class="kb-overview-link">상세 가이드 & 샌드박스 →</a>
      </div>
    </div>

    <!-- 6. Dialog -->
    <div class="kb-overview-card">
      <div class="kb-overview-preview">
        <div style="background: #FFFFFF; border: 1px solid #E5E8EB; border-radius: 16px; padding: 14px 18px; box-shadow: 0 4px 16px rgba(0,0,0,0.08); text-align: center; width: 85%;">
          <strong style="font-size: 13px;">이체를 실행할까요?</strong>
          <div style="font-size: 11px; color: #76808E; margin-top: 4px;">50,000원 → 홍길동</div>
        </div>
      </div>
      <div class="kb-overview-info">
        <span class="kb-overview-title">Dialog (다이얼로그)</span>
        <p class="kb-overview-desc">송금 확인 및 중요 의사결정을 묻는 모달 대화상자</p>
        <div class="kb-overview-tags">
          <span class="kb-badge-sm">Confirmation</span>
          <span class="kb-badge-sm">Alert</span>
          <span class="kb-badge-sm">24px Radius</span>
        </div>
        <a href="/components/dialog/" class="kb-overview-link">상세 가이드 & 샌드박스 →</a>
      </div>
    </div>

    <!-- 7. Select -->
    <div class="kb-overview-card">
      <div class="kb-overview-preview" style="width: 100%;">
        <div style="background: #FFFFFF; border: 1.5px solid #D1D6DB; border-radius: 12px; padding: 10px 14px; width: 85%; display: flex; justify-content: space-between; align-items: center;">
          <span style="font-size: 13px; font-weight: 600;">카카오뱅크 입출금통장</span>
          <span style="font-size: 11px;">▼</span>
        </div>
      </div>
      <div class="kb-overview-info">
        <span class="kb-overview-title">Select (셀렉트)</span>
        <p class="kb-overview-desc">출금 계좌 선택, 은행 선택 드롭다운 메뉴</p>
        <div class="kb-overview-tags">
          <span class="kb-badge-sm">Filled</span>
          <span class="kb-badge-sm">Outlined</span>
          <span class="kb-badge-sm">Account Picker</span>
        </div>
        <a href="/components/select/" class="kb-overview-link">상세 가이드 & 샌드박스 →</a>
      </div>
    </div>

    <!-- 8. Slider -->
    <div class="kb-overview-card">
      <div class="kb-overview-preview" style="width: 100%;">
        <div style="width: 85%;">
          <div style="display: flex; justify-content: space-between; font-size: 11px; font-weight: 700; margin-bottom: 4px;">
            <span>대출 기간</span>
            <span style="color: #3182F6;">24개월</span>
          </div>
          <input type="range" min="1" max="60" value="24" style="width: 100%; accent-color: #FFE100; cursor: pointer;" />
        </div>
      </div>
      <div class="kb-overview-info">
        <span class="kb-overview-title">Slider (슬라이더)</span>
        <p class="kb-overview-desc">대출 한도 및 적금 만기 기간을 조절하는 슬라이더</p>
        <div class="kb-overview-tags">
          <span class="kb-badge-sm">Continuous</span>
          <span class="kb-badge-sm">Discrete</span>
          <span class="kb-badge-sm">Range</span>
        </div>
        <a href="/components/slider/" class="kb-overview-link">상세 가이드 & 샌드박스 →</a>
      </div>
    </div>

    <!-- 9. Icon & Icon Button -->
    <div class="kb-overview-card">
      <div class="kb-overview-preview" style="gap: 12px;">
        <button style="width: 40px; height: 40px; border-radius: 50%; border: 1px solid #E5E8EB; background: #FFFFFF; display: flex; align-items: center; justify-content: center; cursor: pointer;">
          <img src="/images/kb-icons/svg/kb_ic-call.svg" width="20" height="20" alt="call"/>
        </button>
        <button style="width: 40px; height: 40px; border-radius: 50%; border: none; background: #FFE100; display: flex; align-items: center; justify-content: center; cursor: pointer;">
          <img src="/images/kb-icons/svg/kb_ic-chevron-right.svg" width="20" height="20" alt="chevron"/>
        </button>
      </div>
      <div class="kb-overview-info">
        <span class="kb-overview-title">Icon & Icon Button</span>
        <p class="kb-overview-desc">카카오뱅크 140+종 공식 벡터 아이콘 및 원형 액션 버튼</p>
        <div class="kb-overview-tags">
          <span class="kb-badge-sm">140+ Icons</span>
          <span class="kb-badge-sm">Standard</span>
          <span class="kb-badge-sm">Filled</span>
          <span class="kb-badge-sm">Outlined</span>
        </div>
        <a href="/components/icon/" class="kb-overview-link">상세 가이드 & 갤러리 →</a>
      </div>
    </div>

    <!-- 10. List -->
    <div class="kb-overview-card">
      <div class="kb-overview-preview" style="width: 100%;">
        <div style="background: #FFFFFF; border: 1px solid #E5E8EB; border-radius: 12px; width: 85%; padding: 8px 12px;">
          <div style="display: flex; justify-content: space-between; font-size: 12px; font-weight: 700;">
            <span>스타벅스 강남점</span>
            <span style="color: #F04452;">-5,400원</span>
          </div>
          <span style="font-size: 10px; color: #76808E;">11월 15일 12:30</span>
        </div>
      </div>
      <div class="kb-overview-info">
        <span class="kb-overview-title">List (리스트)</span>
        <p class="kb-overview-desc">금융 거래 내역 및 계좌 목록 표준 리스트</p>
        <div class="kb-overview-tags">
          <span class="kb-badge-sm">Single Line</span>
          <span class="kb-badge-sm">Two Line</span>
          <span class="kb-badge-sm">Leading / Trailing</span>
        </div>
        <a href="/components/list/" class="kb-overview-link">상세 가이드 & 샌드박스 →</a>
      </div>
    </div>

    <!-- 11. Tabs -->
    <div class="kb-overview-card">
      <div class="kb-overview-preview" style="width: 100%;">
        <div style="display: flex; border-bottom: 2px solid #E5E8EB; width: 85%;">
          <span style="flex: 1; text-align: center; font-size: 12px; font-weight: 700; border-bottom: 3px solid #191F28; padding-bottom: 6px;">전체 거래</span>
          <span style="flex: 1; text-align: center; font-size: 12px; color: #76808E; padding-bottom: 6px;">입금만</span>
        </div>
      </div>
      <div class="kb-overview-info">
        <span class="kb-overview-title">Tabs (탭)</span>
        <p class="kb-overview-desc">금융 상품 및 거래 내역 뷰 전환 탭</p>
        <div class="kb-overview-tags">
          <span class="kb-badge-sm">Primary</span>
          <span class="kb-badge-sm">Secondary</span>
          <span class="kb-badge-sm">Scrollable</span>
        </div>
        <a href="/components/tabs/" class="kb-overview-link">상세 가이드 & 샌드박스 →</a>
      </div>
    </div>

    <!-- 12. Progress Indicators -->
    <div class="kb-overview-card">
      <div class="kb-overview-preview" style="width: 100%;">
        <div style="width: 85%;">
          <div style="height: 8px; background: #E5E8EB; border-radius: 9999px; overflow: hidden;">
            <div style="width: 70%; height: 100%; background: #FFE100; border-radius: 9999px;"></div>
          </div>
          <span style="font-size: 10px; color: #76808E; margin-top: 4px; display: block; text-align: right;">목표 달성 70%</span>
        </div>
      </div>
      <div class="kb-overview-info">
        <span class="kb-overview-title">Progress (진행 상태 바)</span>
        <p class="kb-overview-desc">26주 적금 달성도 및 비대면 서류 심사 진행률</p>
        <div class="kb-overview-tags">
          <span class="kb-badge-sm">Linear</span>
          <span class="kb-badge-sm">Circular</span>
          <span class="kb-badge-sm">Indeterminate</span>
        </div>
        <a href="/components/progress/" class="kb-overview-link">상세 가이드 & 샌드박스 →</a>
      </div>
    </div>
  </div>
</div>
