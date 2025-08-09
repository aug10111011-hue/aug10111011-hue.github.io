<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <title>아이유 유튜브 채널 안내</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@400;700&family=Roboto:wght@400;700&display=swap" rel="stylesheet" />
  <style>
    body {
      background: linear-gradient(135deg, #ff69b4 0%, #ff1493 100%);
      font-family: 'Noto Sans KR', 'Roboto', sans-serif;
      color: white;
      margin: 0; 
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .container {
      background: rgba(26, 26, 26, 0.85);
      padding: 48px 68px 40px 68px;
      border-radius: 22px;
      max-width: 430px;
      width: 100%;
      text-align: center;
      box-shadow: 0 8px 24px rgba(255, 20, 147, 0.4), 0 0 36px rgba(255, 20, 147, 0.18);
      animation: fadeIn 1.2s ease;
    }
    .profile-img {
      width: 120px;
      height: 120px;
      object-fit: cover;
      border-radius: 50%;
      border: 5px solid #ff1493;
      box-shadow: 0 0 15px #ff69b4;
      margin-bottom: 25px;
    }
    .youtube-logo {
      width: 90px;
      margin: 0 auto 20px auto;
      filter: drop-shadow(0 0 6px #ff69b4);
      display: block;
    }
    h1 {
      font-size: 2.2rem;
      font-weight: bold;
      margin-bottom: 16px;
      letter-spacing: -2px;
      text-shadow: 2px 3px 11px rgba(0,0,0,0.45);
    }
    p {
      font-size: 1.15rem;
      line-height: 1.65;
      margin: 10px 0 16px 0;
      text-shadow: 1px 2px 4px rgba(0,0,0,0.3);
    }
    .action-link {
      display: inline-block;
      background: #ff1493;
      color: #fff;
      font-weight: bold;
      font-size: 1.17rem;
      padding: 16px 50px;
      border-radius: 65px;
      text-decoration: none;
      margin-top: 32px;
      box-shadow: 0 6px 15px rgba(255, 20, 147, 0.7), inset 0 -4px 10px rgba(255, 20, 147, 0.38);
      transition: background 0.23s, box-shadow 0.23s;
    }
    .action-link:hover,
    .action-link:focus {
      background: #e0117a;
      box-shadow: 0 10px 28px rgba(224, 17, 122, 0.78), inset 0 -6px 14px rgba(224,17,122,0.81);
      outline: none;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(30px);}
      to { opacity: 1; transform: translateY(0);}
    }
    /* 반응형! */
    @media (max-width:600px){
      .container {padding:18px 6vw;}
      h1 {font-size:1.5rem;}
      .profile-img {width:78px; height:78px;}
      .youtube-logo {width:60px;}
      .action-link {padding:13px 18vw; font-size:1rem;}
    }
  </style>
</head>
<body>
  <main class="container" role="main" aria-label="아이유 유튜브 채널 안내">
    <img 
      class="profile-img" 
      src="https://yt3.ggpht.com/ytc/AKedOLTdrP26NutZvmHCQiGuOxDIxWV2AQA9ecI4FiG1=s88-c-k-c0x00ffffff-no-rj" 
      alt="아이유 공식 유튜브 프로필 사진" 
      width="120" height="120" 
    />

    <svg class="youtube-logo" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" aria-hidden="true"><path d="M10 15l5.19-3L10 9v6z" fill="#fff"/><path fill="#fff" fill-opacity="0.7" fill-rule="evenodd" clip-rule="evenodd" d="M21.8 7.2s-.2-1.4-.82-2.01c-.78-.82-1.66-.82-2.06-.87C15.52 4 12 4 12 4s-3.52 0-6.92.32c-.4.05-1.28.05-2.06.87C2.4 5.8 2.2 7.2 2.2 7.2S2 9.08 2 10.95v2.1c0 1.87.2 3.75.2 3.75s.2 1.4.82 2.01c.78.82 1.81.8 2.27.9 1.65.12 7.01.33 7.01.33s3.52 0 6.92-.32c.4-.05 1.28-.05 2.06-.87.62-.61.82-2.01.82-2.01s.2-1.88.2-3.75v-2.1c0-1.87-.2-3.75-.2-3.75z"/></svg>

    <h1>아이유 유튜브 채널 안내</h1>
    <p>이 페이지는 <strong>아이유 공식 유튜브 채널</strong> 정보를 안내합니다.<br />
       아래 버튼을 클릭하면 공식 채널로 이동합니다.</p>

    <a class="action-link" href="https://www.youtube.com/@dlwlrma" target="_blank" rel="noopener" aria-label="아이유 유튜브 채널로 이동">
      채널로 이동
    </a>
  </main>
</body>
</html>
