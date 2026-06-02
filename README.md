# Airtable Design System — CSS

[Airtable의 `DESIGN.md` 사양](https://getdesign.md/airtable/design-md)을 그대로 옮긴 독립형 CSS 디자인 토큰 + 컴포넌트 스타일시트입니다.
흰 캔버스 + near-black CTA 위에 코럴·포레스트·다크네이비 시그니처 카드로 브랜드 전압을 주는 에디토리얼 워크플로우 UI.

## 미리보기 (GitHub Pages)

배포 후: `https://jenahappy.github.io/<repo>/`

## 구성

| 파일 | 설명 |
|---|---|
| `airtable.css` | 디자인 토큰(색상·타이포·간격·반경)을 CSS 변수로, 버튼/시그니처 카드/인풋/내비/요금제 컴포넌트 클래스 포함 |
| `index.html` | 토큰과 컴포넌트를 보여주는 데모/쇼케이스 페이지 |

## 사용법

```html
<link rel="stylesheet" href="airtable.css">
```

```html
<button class="btn btn-primary">Get started for free</button>
<button class="btn btn-secondary">Book demo</button>

<div class="signature-card signature-coral-card">
  <h2 class="card-title">Production apps at prototype speed</h2>
</div>
```

## 핵심 토큰

- **색채**: primary `#181d26` · coral `#aa2d00` · forest `#0a2e0e` · cream `#f5e9d4` · link `#1b61c9`(CTA 색 아님)
- **타이포**: Haas Grotesk(폴백 Inter Display / Windows는 Segoe UI), display는 굵게 쓰지 않음
- **반경**: lg 12 · md 10 · sm 6 · pill 9999 / **수직 리듬** 96px
- **원칙**: 그라데이션·메시 금지, 색-블록 우선(그림자 최소), hover 미정의(Default/Active만)

## 라이선스

CSS 구현은 자유롭게 사용하세요. 디자인 분석 출처는 [getdesign.md](https://getdesign.md/airtable/design-md)이며 Airtable 상표/브랜드 자산의 권리는 Airtable(Formagrid Inc.)에 있습니다.
