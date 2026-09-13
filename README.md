<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Muhammad Ilham</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(135deg, #111827, #312e81, #7c3aed);
      color: white;
    }

    .card {
      width: 90%;
      max-width: 420px;
      padding: 35px 25px;
      text-align: center;
      background: rgba(255, 255, 255, 0.12);
      border: 1px solid rgba(255, 255, 255, 0.2);
      border-radius: 25px;
      backdrop-filter: blur(15px);
      box-shadow: 0 20px 50px rgba(0,0,0,0.4);
    }

    .avatar {
      width: 100px;
      height: 100px;
      margin: auto;
      display: flex;
      justify-content: center;
      align-items: center;
      border-radius: 50%;
      background: linear-gradient(135deg, #8b5cf6, #ec4899);
      font-size: 42px;
      font-weight: bold;
      box-shadow: 0 10px 30px rgba(0,0,0,0.3);
    }

    h1 {
      margin-top: 20px;
      font-size: 30px;
    }

    .bio {
      margin: 10px 0 25px;
      color: #ddd;
      font-size: 15px;
    }

    .button {
      display: block;
      width: 100%;
      padding: 15px;
      margin: 12px 0;
      border-radius: 14px;
      text-decoration: none;
      color: white;
      font-weight: bold;
      background: rgba(255,255,255,0.15);
      border: 1px solid rgba(255,255,255,0.2);
      transition: 0.3s;
    }

    .button:hover {
      transform: translateY(-3px);
      background: rgba(255,255,255,0.25);
    }

    .tiktok {
      background: linear-gradient(135deg, #111, #333);
    }

    footer {
      margin-top: 25px;
      font-size: 12px;
      color: #bbb;
    }
  </style>
</head>

<body>

  <div class="card">

    <div class="avatar">MI</div>

    <h1>Muhammad Ilham</h1>

    <p class="bio">
      Selamat datang di website profil saya 👋<br>
      Terima kasih sudah berkunjung!
    </p>

    <a class="button tiktok"
       href="https://www.tiktok.com/@ilhampreset99"
       target="_blank">
      🎵 TikTok Saya
    </a>

    <a class="button"
       href="https://www.google.com"
       target="_blank">
      🌐 Google
    </a>

    <footer>
      © 2026 Muhammad Ilham
    </footer>

  </div>

</body>
</html>
