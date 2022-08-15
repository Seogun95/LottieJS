# Lottie js

## 목차

1. [library](#library)
2. [import](#import)
3. [html](#html)

`lottie JS`를 사용하여 `html`에 벡터 이미지를 `json`형태로 불러와, 웹사이트에 구현하는 코드 입니다.

`lottie JS`는 [lottie file](https://lottiefiles.com/) 에서 더 많은 기능을 확인할 수 있습니다.

오픈소스 라이브러리는 [이곳](https://lottiefiles.com/featured)을 참조하세요.

## library

`lottie json` 은 `html`, `webflow`, `android`, `iOS` 환경에서 이용할 수 있습니다.

### import

```html
<script src="https://unpkg.com/@lottiefiles/lottie-player@latest/dist/lottie-player.js"></script>
```

### html

```html
<div class="lottie-container">
    <lottie-player src="./bell.json" background="transparent" speed="1" loop autoplay></lottie-player>
</div>
```
