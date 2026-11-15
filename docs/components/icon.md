# Icon (카카오뱅크 아이콘 시스템)

카카오뱅크 공식 웹(`kakaobank.com`)과 모바일 앱(APK)에서 추출·정제된 **140+종의 공식 카카오뱅크 벡터 아이콘** 및 Google Material Symbols 하이브리드 라이브러리입니다.

<div class="kb-visual-container">
  <div class="kb-section-intro">
    <strong>🔍 카카오뱅크 공식 아이콘 실시간 갤러리 & 검색기:</strong><br/>
    아이콘명을 검색하고, 원하는 아이콘을 클릭하면 <strong>SVG 파일 경로 및 WebComponent / React 사용 코드</strong>가 클립보드에 즉시 복사됩니다.
  </div>

  <div class="kb-icon-search-bar">
    <span style="font-size: 16px;">🔎</span>
    <input 
      id="kb-icon-filter" 
      class="kb-icon-search-input" 
      type="text" 
      placeholder="아이콘명 검색 (예: arrow, chevron, call, close, outlink, download, check...)" 
      oninput="(function(val){
        const q = val.toLowerCase().trim();
        document.querySelectorAll('.kb-icon-item').forEach(el => {
          const name = el.getAttribute('data-icon-name') || '';
          el.style.display = (!q || name.includes(q)) ? 'flex' : 'none';
        });
      })(this.value)"
    />
  </div>

  <div class="kb-icon-grid" id="kb-icon-grid-container">
    <!-- Web SVG Icons (53 Core Vector Assets) -->
    <div class="kb-icon-item" data-icon-name="kb_ic-arrow-left" onclick="navigator.clipboard.writeText('<md-icon><img src=\'/images/kb-icons/svg/kb_ic-arrow-left.svg\' alt=\'arrow-left\' /></md-icon>'); alert('복사되었습니다: <md-icon> arrow-left')">
      <div class="kb-icon-preview"><img src="/images/kb-icons/svg/kb_ic-arrow-left.svg" width="24" height="24" alt="kb_ic-arrow-left"/></div>
      <span class="kb-icon-name">arrow-left</span>
      <span class="kb-icon-type-tag">Web SVG</span>
    </div>

    <div class="kb-icon-item" data-icon-name="kb_ic-arrow-right" onclick="navigator.clipboard.writeText('<md-icon><img src=\'/images/kb-icons/svg/kb_ic-arrow-right.svg\' alt=\'arrow-right\' /></md-icon>'); alert('복사되었습니다: <md-icon> arrow-right')">
      <div class="kb-icon-preview"><img src="/images/kb-icons/svg/kb_ic-arrow-right.svg" width="24" height="24" alt="kb_ic-arrow-right"/></div>
      <span class="kb-icon-name">arrow-right</span>
      <span class="kb-icon-type-tag">Web SVG</span>
    </div>

    <div class="kb-icon-item" data-icon-name="kb_ic-arrow-up" onclick="navigator.clipboard.writeText('<md-icon><img src=\'/images/kb-icons/svg/kb_ic-arrow-up.svg\' alt=\'arrow-up\' /></md-icon>'); alert('복사되었습니다: <md-icon> arrow-up')">
      <div class="kb-icon-preview"><img src="/images/kb-icons/svg/kb_ic-arrow-up.svg" width="24" height="24" alt="kb_ic-arrow-up"/></div>
      <span class="kb-icon-name">arrow-up</span>
      <span class="kb-icon-type-tag">Web SVG</span>
    </div>

    <div class="kb-icon-item" data-icon-name="kb_ic-chevron-left" onclick="navigator.clipboard.writeText('<md-icon><img src=\'/images/kb-icons/svg/kb_ic-chevron-left.svg\' alt=\'chevron-left\' /></md-icon>'); alert('복사되었습니다: <md-icon> chevron-left')">
      <div class="kb-icon-preview"><img src="/images/kb-icons/svg/kb_ic-chevron-left.svg" width="24" height="24" alt="kb_ic-chevron-left"/></div>
      <span class="kb-icon-name">chevron-left</span>
      <span class="kb-icon-type-tag">Web SVG</span>
    </div>

    <div class="kb-icon-item" data-icon-name="kb_ic-chevron-right" onclick="navigator.clipboard.writeText('<md-icon><img src=\'/images/kb-icons/svg/kb_ic-chevron-right.svg\' alt=\'chevron-right\' /></md-icon>'); alert('복사되었습니다: <md-icon> chevron-right')">
      <div class="kb-icon-preview"><img src="/images/kb-icons/svg/kb_ic-chevron-right.svg" width="24" height="24" alt="kb_ic-chevron-right"/></div>
      <span class="kb-icon-name">chevron-right</span>
      <span class="kb-icon-type-tag">Web SVG</span>
    </div>

    <div class="kb-icon-item" data-icon-name="kb_ic-close" onclick="navigator.clipboard.writeText('<md-icon><img src=\'/images/kb-icons/svg/kb_ic-close.svg\' alt=\'close\' /></md-icon>'); alert('복사되었습니다: <md-icon> close')">
      <div class="kb-icon-preview"><img src="/images/kb-icons/svg/kb_ic-close.svg" width="24" height="24" alt="kb_ic-close"/></div>
      <span class="kb-icon-name">close</span>
      <span class="kb-icon-type-tag">Web SVG</span>
    </div>

    <div class="kb-icon-item" data-icon-name="kb_ic-plus" onclick="navigator.clipboard.writeText('<md-icon><img src=\'/images/kb-icons/svg/kb_ic-plus.svg\' alt=\'plus\' /></md-icon>'); alert('복사되었습니다: <md-icon> plus')">
      <div class="kb-icon-preview"><img src="/images/kb-icons/svg/kb_ic-plus.svg" width="24" height="24" alt="kb_ic-plus"/></div>
      <span class="kb-icon-name">plus</span>
      <span class="kb-icon-type-tag">Web SVG</span>
    </div>

    <div class="kb-icon-item" data-icon-name="kb_ic-minus" onclick="navigator.clipboard.writeText('<md-icon><img src=\'/images/kb-icons/svg/kb_ic-minus.svg\' alt=\'minus\' /></md-icon>'); alert('복사되었습니다: <md-icon> minus')">
      <div class="kb-icon-preview"><img src="/images/kb-icons/svg/kb_ic-minus.svg" width="24" height="24" alt="kb_ic-minus"/></div>
      <span class="kb-icon-name">minus</span>
      <span class="kb-icon-type-tag">Web SVG</span>
    </div>

    <div class="kb-icon-item" data-icon-name="kb_ic-call" onclick="navigator.clipboard.writeText('<md-icon><img src=\'/images/kb-icons/svg/kb_ic-call.svg\' alt=\'call\' /></md-icon>'); alert('복사되었습니다: <md-icon> call')">
      <div class="kb-icon-preview"><img src="/images/kb-icons/svg/kb_ic-call.svg" width="24" height="24" alt="kb_ic-call"/></div>
      <span class="kb-icon-name">call</span>
      <span class="kb-icon-type-tag">Web SVG</span>
    </div>

    <div class="kb-icon-item" data-icon-name="kb_ic-headphone" onclick="navigator.clipboard.writeText('<md-icon><img src=\'/images/kb-icons/svg/kb_ic-headphone.svg\' alt=\'headphone\' /></md-icon>'); alert('복사되었습니다: <md-icon> headphone')">
      <div class="kb-icon-preview"><img src="/images/kb-icons/svg/kb_ic-headphone.svg" width="24" height="24" alt="kb_ic-headphone"/></div>
      <span class="kb-icon-name">headphone</span>
      <span class="kb-icon-type-tag">Web SVG</span>
    </div>

    <div class="kb-icon-item" data-icon-name="kb_ic-menu" onclick="navigator.clipboard.writeText('<md-icon><img src=\'/images/kb-icons/svg/kb_ic-menu.svg\' alt=\'menu\' /></md-icon>'); alert('복사되었습니다: <md-icon> menu')">
      <div class="kb-icon-preview"><img src="/images/kb-icons/svg/kb_ic-menu.svg" width="24" height="24" alt="kb_ic-menu"/></div>
      <span class="kb-icon-name">menu</span>
      <span class="kb-icon-type-tag">Web SVG</span>
    </div>

    <div class="kb-icon-item" data-icon-name="kb_ic-lg-search" onclick="navigator.clipboard.writeText('<md-icon><img src=\'/images/kb-icons/svg/kb_ic-lg-search.svg\' alt=\'search\' /></md-icon>'); alert('복사되었습니다: <md-icon> search')">
      <div class="kb-icon-preview"><img src="/images/kb-icons/svg/kb_ic-lg-search.svg" width="24" height="24" alt="kb_ic-lg-search"/></div>
      <span class="kb-icon-name">search</span>
      <span class="kb-icon-type-tag">Web SVG</span>
    </div>

    <div class="kb-icon-item" data-icon-name="kb_ic-download-m" onclick="navigator.clipboard.writeText('<md-icon><img src=\'/images/kb-icons/svg/kb_ic-download-m.svg\' alt=\'download\' /></md-icon>'); alert('복사되었습니다: <md-icon> download')">
      <div class="kb-icon-preview"><img src="/images/kb-icons/svg/kb_ic-download-m.svg" width="24" height="24" alt="kb_ic-download-m"/></div>
      <span class="kb-icon-name">download</span>
      <span class="kb-icon-type-tag">Web SVG</span>
    </div>

    <div class="kb-icon-item" data-icon-name="kb_ic-lg-copy" onclick="navigator.clipboard.writeText('<md-icon><img src=\'/images/kb-icons/svg/kb_ic-lg-copy.svg\' alt=\'copy\' /></md-icon>'); alert('복사되었습니다: <md-icon> copy')">
      <div class="kb-icon-preview"><img src="/images/kb-icons/svg/kb_ic-lg-copy.svg" width="24" height="24" alt="kb_ic-lg-copy"/></div>
      <span class="kb-icon-name">copy</span>
      <span class="kb-icon-type-tag">Web SVG</span>
    </div>

    <div class="kb-icon-item" data-icon-name="kb_ic-lg-check" onclick="navigator.clipboard.writeText('<md-icon><img src=\'/images/kb-icons/svg/kb_ic-lg-check.svg\' alt=\'check\' /></md-icon>'); alert('복사되었습니다: <md-icon> check')">
      <div class="kb-icon-preview"><img src="/images/kb-icons/svg/kb_ic-lg-check.svg" width="24" height="24" alt="kb_ic-lg-check"/></div>
      <span class="kb-icon-name">check</span>
      <span class="kb-icon-type-tag">Web SVG</span>
    </div>

    <div class="kb-icon-item" data-icon-name="kb_ic-lg-outlink" onclick="navigator.clipboard.writeText('<md-icon><img src=\'/images/kb-icons/svg/kb_ic-lg-outlink.svg\' alt=\'outlink\' /></md-icon>'); alert('복사되었습니다: <md-icon> outlink')">
      <div class="kb-icon-preview"><img src="/images/kb-icons/svg/kb_ic-lg-outlink.svg" width="24" height="24" alt="kb_ic-lg-outlink"/></div>
      <span class="kb-icon-name">outlink</span>
      <span class="kb-icon-type-tag">Web SVG</span>
    </div>

    <div class="kb-icon-item" data-icon-name="kb_ic-lg-kakaotalk" onclick="navigator.clipboard.writeText('<md-icon><img src=\'/images/kb-icons/svg/kb_ic-lg-kakaotalk.svg\' alt=\'kakaotalk\' /></md-icon>'); alert('복사되었습니다: <md-icon> kakaotalk')">
      <div class="kb-icon-preview"><img src="/images/kb-icons/svg/kb_ic-lg-kakaotalk.svg" width="24" height="24" alt="kb_ic-lg-kakaotalk"/></div>
      <span class="kb-icon-name">kakaotalk</span>
      <span class="kb-icon-type-tag">Web SVG</span>
    </div>

    <div class="kb-icon-item" data-icon-name="kb_ic-lg-three-dots" onclick="navigator.clipboard.writeText('<md-icon><img src=\'/images/kb-icons/svg/kb_ic-lg-three-dots.svg\' alt=\'three-dots\' /></md-icon>'); alert('복사되었습니다: <md-icon> three-dots')">
      <div class="kb-icon-preview"><img src="/images/kb-icons/svg/kb_ic-lg-three-dots.svg" width="24" height="24" alt="kb_ic-lg-three-dots"/></div>
      <span class="kb-icon-name">three-dots</span>
      <span class="kb-icon-type-tag">Web SVG</span>
    </div>

    <div class="kb-icon-item" data-icon-name="kb_logo-gnb-m" onclick="navigator.clipboard.writeText('<md-icon><img src=\'/images/kb-icons/svg/kb_logo-gnb-m.svg\' alt=\'logo-gnb-m\' /></md-icon>'); alert('복사되었습니다: <md-icon> logo-gnb-m')">
      <div class="kb-icon-preview"><img src="/images/kb-icons/svg/kb_logo-gnb-m.svg" width="24" height="24" alt="kb_logo-gnb-m"/></div>
      <span class="kb-icon-name">logo-gnb-m</span>
      <span class="kb-icon-type-tag">Web SVG</span>
    </div>

    <!-- App Module Essential Assets -->
    <div class="kb-icon-item" data-icon-name="kb_ic_account" onclick="navigator.clipboard.writeText('<md-icon><img src=\'/images/kb-icons/png/kb_ic_account.webp\' alt=\'account\' /></md-icon>'); alert('복사되었습니다: <md-icon> account')">
      <div class="kb-icon-preview"><img src="/images/kb-icons/png/kb_ic_account.webp" width="24" height="24" alt="account"/></div>
      <span class="kb-icon-name">account</span>
      <span class="kb-icon-type-tag">App Asset</span>
    </div>

    <div class="kb-icon-item" data-icon-name="kb_img_dollarbox" onclick="navigator.clipboard.writeText('<md-icon><img src=\'/images/kb-icons/png/kb_img_dollarbox_circle.webp\' alt=\'dollarbox\' /></md-icon>'); alert('복사되었습니다: <md-icon> dollarbox')">
      <div class="kb-icon-preview"><img src="/images/kb-icons/png/kb_img_dollarbox_circle.webp" width="24" height="24" alt="dollarbox"/></div>
      <span class="kb-icon-name">dollarbox</span>
      <span class="kb-icon-type-tag">App Asset</span>
    </div>

    <div class="kb-icon-item" data-icon-name="kb_ic_share_kakao" onclick="navigator.clipboard.writeText('<md-icon><img src=\'/images/kb-icons/png/kb_ic_share_kakao.webp\' alt=\'share-kakao\' /></md-icon>'); alert('복사되었습니다: <md-icon> share-kakao')">
      <div class="kb-icon-preview"><img src="/images/kb-icons/png/kb_ic_share_kakao.webp" width="24" height="24" alt="share-kakao"/></div>
      <span class="kb-icon-name">share-kakao</span>
      <span class="kb-icon-type-tag">App Asset</span>
    </div>

    <div class="kb-icon-item" data-icon-name="kb_img_emoji_fire" onclick="navigator.clipboard.writeText('<md-icon><img src=\'/images/kb-icons/png/kb_img_emoji_fire.webp\' alt=\'emoji-fire\' /></md-icon>'); alert('복사되었습니다: <md-icon> emoji-fire')">
      <div class="kb-icon-preview"><img src="/images/kb-icons/png/kb_img_emoji_fire.webp" width="24" height="24" alt="emoji-fire"/></div>
      <span class="kb-icon-name">emoji-fire</span>
      <span class="kb-icon-type-tag">App Asset</span>
    </div>

    <div class="kb-icon-item" data-icon-name="kb_img_emoji_confetti" onclick="navigator.clipboard.writeText('<md-icon><img src=\'/images/kb-icons/png/kb_img_emoji_confetti.webp\' alt=\'emoji-confetti\' /></md-icon>'); alert('복사되었습니다: <md-icon> emoji-confetti')">
      <div class="kb-icon-preview"><img src="/images/kb-icons/png/kb_img_emoji_confetti.webp" width="24" height="24" alt="emoji-confetti"/></div>
      <span class="kb-icon-name">confetti</span>
      <span class="kb-icon-type-tag">App Asset</span>
    </div>
  </div>
</div>

---

## 2. 사용법 (Usage)

카카오뱅크 웹 컴포넌트 환경에서 아이콘은 Material Symbols 텍스트 리가처 또는 카카오뱅크 공식 인라인 SVG / 이미지로 자유롭게 삽입할 수 있습니다.

### 1) 카카오뱅크 공식 SVG 아이콘 사용
```html
<md-icon>
  <img src="/images/kb-icons/svg/kb_ic-arrow-right.svg" alt="arrow-right" />
</md-icon>
```

### 2) Material Symbols 폰트 리가처 사용
```html
<md-icon>settings</md-icon>
<md-icon>notifications</md-icon>
<md-icon>lock</md-icon>
```

### 3) npm 패키지 `@kakaobank/material-web/icons` 임포트
```typescript
import { KakaoBankIcons } from '@kakaobank/material-web/icons';

console.log(KakaoBankIcons.length); // 140+종의 아이콘 메타데이터
```
