# 한림명조체

[배포처 바로가기](https://www.hallym.or.kr/hallymuniv_sub.asp?left_menu=left_about&screen=ptp117_3_2)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Hallym Myeongjo`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/HallymMyeongjo/HallymMyeongjo.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/HallymMyeongjo/HallymMyeongjo.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Hallym Myeongjo';
    font-weight: 400;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/HallymMyeongjo/HallymMyeongjo-Regular.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/HallymMyeongjo/HallymMyeongjo-Regular.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/HallymMyeongjo/HallymMyeongjo-Regular.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/HallymMyeongjo/HallymMyeongjo-Regular.ttf') format('truetype');
}
@font-face {
    font-family: 'Hallym Myeongjo';
    font-weight: 700;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/HallymMyeongjo/HallymMyeongjo-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/HallymMyeongjo/HallymMyeongjo-Bold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/HallymMyeongjo/HallymMyeongjo-Bold.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/HallymMyeongjo/HallymMyeongjo-Bold.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/HallymMyeongjo/subsets/HallymMyeongjo-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/HallymMyeongjo/subsets/HallymMyeongjo-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "Hallym Myeongjo", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
한림체의 지적재산권은 학교법인일송학원에 있고 기업 및 개인사용자를 포함한 모든 사용자에게 무료로 제공되며 판매하는 것을 제외한 상업적인 사용이 가능합니다. 
 
한림고딕/명조체는 별도의 승인 없이 인쇄·출판·영상·웹·모바일 등 다양한 매체에서 개인 및 기업 사용자에 관계없이 누구나 자유롭게 사용할 수 있습니다. 
단, 해당 글꼴의 디자인을 임의로 변경해 배포하거나 폰트 파일의 수정 및 변형을 포함한 개작·개명을 통한 사용, 허락 없이 유료로 판매·대여하는 등의 상업적 행위를 할 수 없으며 개발 취지에 어긋나는 유해 매체에서의 사용은 금지합니다.
```
