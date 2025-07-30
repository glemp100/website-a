<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Glemp100</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet" />
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: linear-gradient(135deg, #3fa9f5, #d6eaff);
      color: #fff;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 2rem;
    }

    .card {
      background-color: rgba(255, 255, 255, 0.15);
      backdrop-filter: blur(10px);
      border-radius: 1rem;
      padding: 2rem;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2);
      max-width: 400px;
      width: 100%;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      cursor: default;
      user-select: none;
    }

    .card:hover {
      transform: translateY(-10px);
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.35);
    }

    h1 {
      color: #fff;
      font-size: 2rem;
      margin-bottom: 0.5rem;
    }

    p {
      font-size: 1rem;
      margin-bottom: 1.5rem;
      color: #f0f0f0;
    }

    .socials {
      display: flex;
      justify-content: center;
      gap: 1.5rem;
    }

    .social-icon {
      width: 50px;
      height: 50px;
      background-color: #ffd93d;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      transition: all 0.3s ease;
      cursor: pointer;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.15);
    }

    .social-icon:hover {
      transform: scale(1.15);
      background-color: #ffea80;
      box-shadow: 0 0 15px 3px #fff;
    }

    .social-icon img {
      width: 24px;
      height: 24px;
      pointer-events: none;
      filter: invert(1); /* Makes dark SVG icons white */
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>glemp100</h1>
    <p>16-year-old developer — contributed to 22M+ visits on Roblox</p>
    <div class="socials">
      <a class="social-icon" href="https://discord.com/users/856218467938467851" target="_blank" title="Discord" aria-label="Discord">
        <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/discord.svg" alt="Discord" />
      </a>
      <a class="social-icon" href="https://www.roblox.com/users/profile?username=glemp100" target="_blank" title="Roblox" aria-label="Roblox">
        <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/roblox.svg" alt="Roblox" />
      </a>
      <a class="social-icon" href="https://www.tiktok.com/@glemp100" target="_blank" title="TikTok" aria-label="TikTok">
        <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/tiktok.svg" alt="TikTok" />
      </a>
    </div>
  </div>
</body>
</html>
