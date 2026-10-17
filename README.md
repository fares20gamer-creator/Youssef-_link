# Youssef-_link
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>يوسف أحمد غزال | Yousef Ghazal</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg-color: #0f172a;
      --card-bg: rgba(30, 41, 59, 0.7);
      --accent-color: #38bdf8;
      --text-color: #f8fafc;
      --text-muted: #94a3b8;
    }
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Cairo', sans-serif; }
    body {
      background: radial-gradient(circle at top, #1e1b4b, #0f172a);
      color: var(--text-color);
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 20px;
    }
    .container {
      width: 100%;
      max-width: 480px;
      background: var(--card-bg);
      backdrop-filter: blur(16px);
      border: 1px solid rgba(255, 255, 255, 0.1);
      border-radius: 24px;
      padding: 32px 24px;
      text-align: center;
      box-shadow: 0 20px 40px rgba(0,0,0,0.5);
    }
    .profile-img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 3px solid var(--accent-color);
      margin: 0 auto 16px;
      background: #1e293b;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .profile-img svg { width: 80px; height: 80px; fill: var(--accent-color); }
    h1 { font-size: 24px; font-weight: 800; margin-bottom: 4px; }
    p.tagline { color: var(--text-muted); font-size: 14px; margin-bottom: 24px; }
    .links-container { display: flex; flex-direction: column; gap: 14px; }
    .link-card {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 14px 20px;
      border-radius: 16px;
      background: rgba(255, 255, 255, 0.05);
      border: 1px solid rgba(255, 255, 255, 0.08);
      color: var(--text-color);
      text-decoration: none;
      font-weight: 600;
      transition: all 0.3s ease;
    }
    .link-card:hover {
      background: rgba(56, 189, 248, 0.15);
      border-color: var(--accent-color);
      transform: translateY(-2px);
    }
    .link-card i { font-size: 22px; width: 30px; }
    .whatsapp { color: #25D366; }
    .facebook { color: #1877F2; }
    .tiktok { color: #EE1D52; }
    .instagram { color: #E1306C; }
  </style>
</head>
<body>
  <div class="container">
    <div class="profile-img">
      <svg viewBox="0 0 24 24"><path d="M12 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0 2c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4z"/></svg>
    </div>
    <h1>يوسف أحمد غزال</h1>
    <p class="tagline">الصفحة الشخصية والروابط الرسمية</p>

    <div class="links-container">
      <a href="https://wa.me/201002223383" target="_blank" class="link-card">
        <i class="fab font-awesome-logo-full whatsapp"></i>
        <span>واتساب / WhatsApp</span>
        <i class="fas fa-arrow-left"></i>
      </a>

      <a href="https://www.facebook.com/share/19kaD7tdSX/" target="_blank" class="link-card">
        <i class="fab fa-facebook facebook"></i>
        <span>فيسبوك / Facebook</span>
        <i class="fas fa-arrow-left"></i>
      </a>

      <a href="https://www.tiktok.com/@theyoussef67?_r=1&_t=ZS-9AcrrhQk4gy" target="_blank" class="link-card">
        <i class="fab fa-tiktok tiktok"></i>
        <span>تيك توك / TikTok</span>
        <i class="fas fa-arrow-left"></i>
      </a>

      <a href="https://www.instagram.com/yousef__ahmed__ghazal?dlrf=MXZjdWxkMGY5Y3E3bg==" target="_blank" class="link-card">
        <i class="fab fa-instagram instagram"></i>
        <span>إنستغرام / Instagram</span>
        <i class="fas fa-arrow-left"></i>
      </a>
    </div>
  </div>
</body>
</html>
