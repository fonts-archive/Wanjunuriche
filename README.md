# 완주누리체

[배포처 바로가기](https://www.wanju.go.kr/index.wanju?menuCd=DOM_000000105002006000)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Wanjunuriche`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/Wanjunuriche/Wanjunuriche.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/Wanjunuriche/Wanjunuriche.css');
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'Wanjunuriche';
  font-weight: normal;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Wanjunuriche/Wanjunuriche.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Wanjunuriche/Wanjunuriche.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Wanjunuriche/Wanjunuriche.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Wanjunuriche/Wanjunuriche.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/Wanjunuriche/subsets/Wanjunuriche-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/Wanjunuriche/subsets/Wanjunuriche-dynamic-subset.css");
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "Wanjunuriche", -apple-system, BlinkMacSystemFont, "Segoe UI",Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
완주대둔산체, 완주누리체의 지적 재산권은 완주군청에 있습니다. 완주대둔산체, 완주누리체는 개인 및 기업 사용자를 포함한 모든 사용자에게 무료로 제공되며 자유롭게 사용할 수 있고 상업적 이용이 가능합니다.  

공공누리 제1유형 "공공저작물의 자유 이용 가능" 
출처 표시 의무 
상업적, 비상업적 이용 가능 
변형 등 2차적 저작물 작성 가능  

[출처 표시에 관한 주의 사항] 
① 이용자는 공공저작물을 이용할 경우, 다음과 같이 출처 또는 저작권자를 표시해야 합니다. 
ex) "본 저작물은 'OOO(기관명)'에서 'OO년'작성하여 공공누리 제O유형으로 개방한 '저작물명(작성자:OOO)'을 이용하였으며, 해당 저작물은 'OOO(기관명),OOO(홈페이지주소)'에서 무료로 다운받으실 수 있습니다." 
② 온라인에서 출처 웹사이트에 대한 하이퍼링크를 제공하는 것이 가능한 경우에는 링크를 제공하여야 합니다. 
③ 이용자는 공공기관이 이용자를 후원한다거나 공공기관과 이용자가 특수한 관계에 있는 것처럼 제3자가 오인하게 하는 표시를 해서는 안됩니다.
```
