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
<meta property="og:description" content="현재 모바일 청첩장은 준비중입니다.">
<meta property="og:image" content="https://YOUR_USERNAME.github.io/YOUR_REPO/assets/background.jpg">
<meta property="og:url" content="https://YOUR_USERNAME.github.io/YOUR_REPO/">

<style>
  * { margin: 0; padding: 0; box-sizing: border-box; }

  html, body {
    height: 100%;
  }

  body {
    min-height: 100vh;
    min-height: 100dvh;
    background: #e9e7e2;
    font-family: "Nanum Myeongjo", "Apple SD Gothic Neo", "Malgun Gothic", serif;
  }

  .card {
    max-width: 480px;
    min-height: 100vh;
    min-height: 100dvh;
    margin: 0 auto;
    background: #fff;
    display: flex;
    flex-direction: column;
  }

  @media (min-width: 481px) {
    body {
      display: flex;
      justify-content: center;
      padding: 32px 0;
    }
    .card {
      min-height: auto;
      border-radius: 12px;
      box-shadow: 0 8px 40px rgba(0,0,0,0.12);
      overflow: hidden;
    }
  }

  .photo {
    display: block;
    width: 100%;
    height: auto;
  }

  .message {
    text-align: center;
    padding: 56px 24px;
    color: #333;
    font-size: clamp(17px, 4.6vw, 22px);
    line-height: 1.7;
    letter-spacing: 0.02em;
  }
</style>
</head>
<body>
  <div class="card">
    <img class="photo" src="assets/background.jpg" alt="">
    <p class="message">현재 모바일 청첩장은<br>준비중입니다.</p>
  </div>
</body>
</html>
