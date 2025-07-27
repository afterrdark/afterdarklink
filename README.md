# afterdarklink
лучшее что может с тобой произойти 
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>SLEPTENY</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      height: 100vh;
      background: linear-gradient(-45deg, #0e0e0e, #1a1a1a, #121212, #000000);
      background-size: 400% 400%;
      animation: gradient 15s ease infinite;
      color: #fff;
      font-family: 'Arial', sans-serif;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
    }

    @keyframes gradient {
      0% {background-position: 0% 50%;}
      50% {background-position: 100% 50%;}
      100% {background-position: 0% 50%;}
    }

    h1 {
      font-size: 36px;
      margin-bottom: 30px;
      letter-spacing: 2px;
    }

    .links {
      display: flex;
      flex-direction: column;
      gap: 20px;
      margin-top: 30px;
    }

    a {
      color: #fff;
      text-decoration: none;
      padding: 12px 24px;
      border: 1px solid #fff;
      border-radius: 8px;
      transition: 0.3s ease;
      font-size: 18px;
    }

    a:hover {
      background: #fff;
      color: #000;
    }

    .scythe {
      width: 100px;
      height: 100px;
      margin-top: 20px;
      animation: float 4s ease-in-out infinite;
    }

    @keyframes float {
      0% { transform: translateY(0px) rotate(0deg); }
      50% { transform: translateY(-10px) rotate(3deg); }
      100% { transform: translateY(0px) rotate(0deg); }
    }
  </style>
</head>
<body>

  <h1>SLEPTENY</h1>

  <!-- SVG Косы смерти -->
  <div class="scythe">
    <svg viewBox="0 0 64 64" fill="white" xmlns="http://www.w3.org/2000/svg">
      <path d="M32 2L30 10H20V14H29L27 24H19V28H26L23 42L25 46L28 32H36L39 46L41 42L38 28H45V24H37L35 14H44V10H34L32 2Z"/>
    </svg>
  </div>

  <div class="links">
    <a href="https://www.instagram.com/slepteny" target="_blank">Instagram</a>
    <a href="https://t.me/linkaftetdar" target="_blank">Telegram</a>
    <a href="https://on.soundcloud.com/zywlp7ztZ1faiJKuPR" target="_blank">SoundCloud</a>
  </div>

</body>
</html>
