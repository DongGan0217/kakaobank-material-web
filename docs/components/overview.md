---
name: Overview
title: Component Overview
order: 1
---

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
        <span style="background: #FFE100; color: #191F28; font-size: 13px; font-weight: 700; padding: 6px 14px; border-radius: 20px; box-shadow: 0 1px 3px rgba(0,0,0,0.08);">#정기예금</span>
        <span style="background: #FFFFFF; color: #4E5968; font-size: 13px; font-weight: 500; padding: 6px 14px; border-radius: 20px; border: 1px solid #D1D6DB;">#비상금대출</span>
      </div>
      <div class="kb-overview-info">
        <span class="kb-overview-title">Chip (칩)</span>
        <p class="kb-overview-desc">금융 상품 키워드 필터링 및 옵션 다중 선택 태그</p>
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
        <div style="background: #FFFFFF; border: 1px solid #E5E8EB; border-radius: 16px; padding: 12px 16px; box-shadow: 0 8px 20px rgba(0,0,0,0.08); width: 85%;">
          <div style="font-size: 13px; font-weight: 700; color: #191F28;">이체 확인</div>
          <div style="font-size: 11px; color: #4E5968; margin: 4px 0 8px;">100,000원을 송금할까요?</div>
          <div style="display: flex; justify-content: flex-end; gap: 6px;">
            <span style="font-size: 10px; font-weight: 600; color: #4E5968; padding: 4px 8px;">취소</span>
            <span style="font-size: 10px; font-weight: 700; background: #FFE100; color: #191F28; padding: 4px 8px; border-radius: 6px;">확인</span>
          </div>
        </div>
      </div>
      <div class="kb-overview-info">
        <span class="kb-overview-title">Dialog (다이얼로그)</span>
        <p class="kb-overview-desc">송금 최종 확인, 본인 인증 및 중요 금융 알림 모달</p>
        <div class="kb-overview-tags">
          <span class="kb-badge-sm">Alert</span>
          <span class="kb-badge-sm">Confirmation</span>
          <span class="kb-badge-sm">24px Rounded</span>
        </div>
        <a href="/components/dialog/" class="kb-overview-link">상세 가이드 & 샌드박스 →</a>
      </div>
    </div>
    <!-- 7. Select -->
    <div class="kb-overview-card">
      <div class="kb-overview-preview" style="width: 100%;">
        <div style="background: #F9FAFB; border: 1.5px solid #D1D6DB; border-radius: 12px; padding: 10px 14px; width: 85%; display: flex; justify-content: space-between; align-items: center;">
          <span style="font-size: 13px; font-weight: 600; color: #191F28;">카카오뱅크 자유적금</span>
          <span style="font-size: 12px; color: #8B95A1;">▼</span>
        </div>
      </div>
      <div class="kb-overview-info">
        <span class="kb-overview-title">Select (셀렉트)</span>
        <p class="kb-overview-desc">출금 계좌 및 금융 상품 선택 드롭다운</p>
        <div class="kb-overview-tags">
          <span class="kb-badge-sm">Filled</span>
          <span class="kb-badge-sm">Outlined</span>
          <span class="kb-badge-sm">Product Picker</span>
        </div>
        <a href="/components/select/" class="kb-overview-link">상세 가이드 & 샌드박스 →</a>
      </div>
    </div>
    <!-- 8. Slider -->
    <div class="kb-overview-card">
      <div class="kb-overview-preview" style="width: 100%;">
        <div style="width: 85%;">
          <div style="display: flex; justify-content: space-between; font-size: 12px; font-weight: 700; margin-bottom: 4px;">
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
    <!-- 9. FAB (Floating Action Button) -->
    <div class="kb-overview-card">
      <div class="kb-overview-preview" style="gap: 12px;">
        <button type="button" style="height: 48px; border-radius: 16px; border: none; background: #FFE100; color: #191F28; padding: 0 16px; font-weight: 700; font-size: 13px; display: flex; align-items: center; gap: 8px; box-shadow: 0 6px 16px rgba(0,0,0,0.12); cursor: pointer;">
          <img src="/../images/kb-icons/svg/kb_ic-add.svg" width="18" height="18" alt="add" />
          <span>계좌 개설</span>
        </button>
      </div>
      <div class="kb-overview-info">
        <span class="kb-overview-title">FAB (플로팅 버튼)</span>
        <p class="kb-overview-desc">화면 상단/하단에 부유하는 핵심 진입 액션 버튼</p>
        <div class="kb-overview-tags">
          <span class="kb-badge-sm">Small</span>
          <span class="kb-badge-sm">Standard</span>
          <span class="kb-badge-sm">Extended</span>
          <span class="kb-badge-sm">Yellow Accent</span>
        </div>
        <a href="/components/fab/" class="kb-overview-link">상세 가이드 & 샌드박스 →</a>
      </div>
    </div>
    <!-- 10. Icon Button -->
    <div class="kb-overview-card">
      <div class="kb-overview-preview" style="gap: 12px;">
        <button style="width: 40px; height: 40px; border-radius: 50%; border: 1px solid #E5E8EB; background: #FFFFFF; display: flex; align-items: center; justify-content: center; cursor: pointer;">
          <img src="/../images/kb-icons/svg/kb_ic-call.svg" width="20" height="20" alt="call" />
        </button>
        <button style="width: 40px; height: 40px; border-radius: 50%; border: none; background: #FFE100; display: flex; align-items: center; justify-content: center; cursor: pointer;">
          <img src="/../images/kb-icons/svg/kb_ic-chevron-right.svg" width="20" height="20" alt="chevron" />
        </button>
      </div>
      <div class="kb-overview-info">
        <span class="kb-overview-title">Icon Button (아이콘 버튼)</span>
        <p class="kb-overview-desc">단독 또는 상단 앱바에 사용되는 원형 인터랙티브 액션 버튼</p>
        <div class="kb-overview-tags">
          <span class="kb-badge-sm">Standard</span>
          <span class="kb-badge-sm">Filled</span>
          <span class="kb-badge-sm">Tonal</span>
          <span class="kb-badge-sm">Outlined</span>
        </div>
        <a href="/components/icon-button/" class="kb-overview-link">상세 가이드 & 샌드박스 →</a>
      </div>
    </div>
    <!-- 11. Radio -->
    <div class="kb-overview-card">
      <div class="kb-overview-preview" style="flex-direction: column; gap: 8px; align-items: flex-start; padding-left: 36px;">
        <label style="display: flex; align-items: center; gap: 8px; font-size: 13px; font-weight: 600; cursor: pointer;">
          <input type="radio" name="demo-radio" checked style="accent-color: #FFE100; cursor: pointer; width: 18px; height: 18px;" />
          매월 지정일 이체
        </label>
        <label style="display: flex; align-items: center; gap: 8px; font-size: 13px; font-weight: 500; color: #76808E; cursor: pointer;">
          <input type="radio" name="demo-radio" style="accent-color: #FFE100; cursor: pointer; width: 18px; height: 18px;" />
          매주 특정 요일 이체
        </label>
      </div>
      <div class="kb-overview-info">
        <span class="kb-overview-title">Radio (라디오 버튼)</span>
        <p class="kb-overview-desc">복수 선택지 중 단일 옵션을 고르는 금융 주기/방식 선택기</p>
        <div class="kb-overview-tags">
          <span class="kb-badge-sm">Selected</span>
          <span class="kb-badge-sm">Unselected</span>
          <span class="kb-badge-sm">Yellow Accent</span>
        </div>
        <a href="/components/radio/" class="kb-overview-link">상세 가이드 & 샌드박스 →</a>
      </div>
    </div>
    <!-- 12. List -->
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
    <!-- 13. Tabs -->
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
    <!-- 14. Progress -->
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
    <!-- 15. Menu -->
    <div class="kb-overview-card">
      <div class="kb-overview-preview" style="width: 100%;">
        <div style="background: #FFFFFF; border: 1px solid #E5E8EB; border-radius: 12px; width: 80%; padding: 6px 0; box-shadow: 0 4px 16px rgba(0,0,0,0.08);">
          <div style="padding: 6px 12px; font-size: 12px; font-weight: 700; color: #191F28; background: #F8F9FA;">이체 내역 다운로드</div>
          <div style="padding: 6px 12px; font-size: 12px; color: #4E5968;">계좌 관리 설정</div>
        </div>
      </div>
      <div class="kb-overview-info">
        <span class="kb-overview-title">Menu (메뉴)</span>
        <p class="kb-overview-desc">더보기 및 부가 금융 기능 팝업 드롭다운</p>
        <div class="kb-overview-tags">
          <span class="kb-badge-sm">Dropdown</span>
          <span class="kb-badge-sm">Cascading</span>
          <span class="kb-badge-sm">Contextual</span>
        </div>
        <a href="/components/menu/" class="kb-overview-link">상세 가이드 & 샌드박스 →</a>
      </div>
    </div>
    <!-- 16. Divider -->
    <div class="kb-overview-card">
      <div class="kb-overview-preview" style="width: 100%; flex-direction: column; gap: 8px;">
        <span style="font-size: 11px; color: #76808E;">Full Width Divider</span>
        <div style="width: 85%; height: 1px; background: #E5E8EB;"></div>
        <span style="font-size: 11px; color: #76808E;">Inset Divider</span>
        <div style="width: 60%; height: 2px; background: #FFE100; border-radius: 2px;"></div>
      </div>
      <div class="kb-overview-info">
        <span class="kb-overview-title">Divider (구분선)</span>
        <p class="kb-overview-desc">콘텐츠 그룹 및 섹션을 명확히 분리하는 표준 디바이더</p>
        <div class="kb-overview-tags">
          <span class="kb-badge-sm">Full Width</span>
          <span class="kb-badge-sm">Inset</span>
          <span class="kb-badge-sm">Middle Inset</span>
        </div>
        <a href="/components/divider/" class="kb-overview-link">상세 가이드 & 샌드박스 →</a>
      </div>
    </div>
    <!-- 17. Elevation -->
    <div class="kb-overview-card">
      <div class="kb-overview-preview" style="gap: 12px;">
        <div style="width: 44px; height: 44px; background: #FFFFFF; border-radius: 12px; box-shadow: 0 1px 3px rgba(0,0,0,0.1); display: flex; align-items: center; justify-content: center; font-size: 11px; font-weight: 700;">L1</div>
        <div style="width: 44px; height: 44px; background: #FFFFFF; border-radius: 12px; box-shadow: 0 8px 24px rgba(0,0,0,0.12); display: flex; align-items: center; justify-content: center; font-size: 11px; font-weight: 700; border: 1.5px solid #FFE100;">L3</div>
      </div>
      <div class="kb-overview-info">
        <span class="kb-overview-title">Elevation (입체감 & 그림자)</span>
        <p class="kb-overview-desc">카카오뱅크 모던 카드의 0~5단계 깊이감 시스템</p>
        <div class="kb-overview-tags">
          <span class="kb-badge-sm">Level 0~5</span>
          <span class="kb-badge-sm">Soft Shadow</span>
          <span class="kb-badge-sm">Fintech Card</span>
        </div>
        <a href="/components/elevation/" class="kb-overview-link">상세 가이드 & 샌드박스 →</a>
      </div>
    </div>
    <!-- 18. Focus Ring & Ripple -->
    <div class="kb-overview-card">
      <div class="kb-overview-preview" style="gap: 12px;">
        <button style="height: 36px; padding: 0 12px; border-radius: 10px; border: none; background: #191F28; color: #FFFFFF; font-size: 12px; font-weight: 700; outline: 3px solid #FFE100; outline-offset: 2px; cursor: pointer;">
          Focus Ring
        </button>
      </div>
      <div class="kb-overview-info">
        <span class="kb-overview-title">Focus Ring & Ripple</span>
        <p class="kb-overview-desc">웹 접근성 키보드 포커스 링 및 터치 리플 피드백</p>
        <div class="kb-overview-tags">
          <span class="kb-badge-sm">A11y Focus</span>
          <span class="kb-badge-sm">Touch Ripple</span>
          <span class="kb-badge-sm">Yellow Ring</span>
        </div>
        <a href="/components/focus-ring/" class="kb-overview-link">상세 가이드 & 샌드박스 →</a>
      </div>
    </div>
  </div>
</div>
