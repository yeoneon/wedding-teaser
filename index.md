---
layout: none
---
<!doctype html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>모바일 청첩장 준비중</title>

<!-- 카카오톡/문자 등으로 링크 공유 시 미리보기에 쓰이는 태그입니다.
     아래 og:url, og:image는 배포 후 실제 주소로 바꿔주세요. -->
<meta property="og:type" content="website">
<meta property="og:title" content="모바일 청첩장 준비중">
<meta property="og:description" content="현재 모바일 청첩장을 준비중이에요">
<meta property="og:image" content="https://YOUR_USERNAME.github.io/YOUR_REPO/assets/background.jpg">
<meta property="og:url" content="https://YOUR_USERNAME.github.io/YOUR_REPO/">

<style>
  * { margin: 0; padding: 0; box-sizing: border-box; }

  html, body {
    height: 100%;
  }

  body {
    font-family: "Nanum Myeongjo", "Apple SD Gothic Neo", "Malgun Gothic", serif;
    background: #000;
  }

  .page {
    position: relative;
    min-height: 100vh;
    min-height: 100dvh;
    display: flex;
    align-items: flex-end;
    justify-content: center;
    background-image: url("assets/background.jpg");
    background-size: cover;
    background-position: center;
  }

  .page::after {
    content: "";
    position: absolute;
    inset: 0;
    background: linear-gradient(to top, rgba(0,0,0,0.65) 0%, rgba(0,0,0,0.15) 45%, rgba(0,0,0,0.05) 70%);
  }

  .message {
    position: relative;
    z-index: 1;
    color: #fff;
    text-align: center;
    padding: 0 24px 14vh;
    font-size: clamp(18px, 4.6vw, 26px);
    line-height: 1.7;
    letter-spacing: 0.02em;
    text-shadow: 0 2px 12px rgba(0,0,0,0.35);
  }
</style>
</head>
<body>
  <div class="page">
    <p class="message">현재 모바일 청첩장을<br>준비중이에요</p>
  </div>
</body>
</html>
