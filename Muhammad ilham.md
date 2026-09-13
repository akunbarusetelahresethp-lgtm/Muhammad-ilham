<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Muhammad Ilham - Profil</title>

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
            padding: 20px;
        }

        .card {
            width: 100%;
            max-width: 420px;
            padding: 35px 25px;
            text-align: center;
            background: rgba(255, 255, 255, 0.1);
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 25px;
            backdrop-filter: blur(15px);
            box-shadow: 0 20px 50px rgba(0,0,0,0.4);
        }

        .profile {
            width: 110px;
            height: 110px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid white;
            margin-bottom: 15px;
        }

        h1 {
            font-size: 28px;
            margin-bottom: 8px;
        }

        .bio {
            color: #ddd;
            margin-bottom: 25px;
        }

        .button {
            display: block;
            width: 100%;
            padding: 15px;
            margin: 12px 0;
            border-radius: 14px;
            color: white;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }

        .tiktok {
            background: #000;
        }

        .info {
            background: rgba(255,255,255,0.15);
        }

        .button:hover {
            transform: scale(1.03);
            box-shadow: 0 8px 20px rgba(0,0,0,0.3);
        }

        footer {
            margin-top: 25px;
            color: #bbb;
            font-size: 13px;
        }
    </style>
</head>

<body>

    <div class="card">

        <!-- FOTO PROFIL -->
        <img src="foto.jpg" alt="Foto Muhammad Ilham" class="profile">

        <h1>Muhammad Ilham</h1>

        <p class="bio">
            Selamat datang di website profil saya 👋
        </p>

        <!-- TOMBOL TIKTOK -->
        <a
            href="https://www.tiktok.com/@ilhampreset99"
            target="_blank"
            class="button tiktok">
            🎵 TikTok Saya
        </a>

        <!-- TOMBOL INFO -->
        <a href="#" class="button info">
            👤 Tentang Saya
        </a>

        <footer>
            © 2026 Muhammad Ilham
        </footer>

    </div>

</body>
</html>
