<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ayoub Website</title>

  <!-- خط عربي -->
  <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;700;900&display=swap" rel="stylesheet">

  <!-- تحسين الظهور في محركات البحث -->
  <meta name="description" content="موقع شخصي احترافي لعرض الخدمات والأعمال بشكل عصري وأنيق">
  <meta name="keywords" content="تصميم مواقع, برمجة, Ayoub, موقع شخصي">
  <meta name="author" content="Ayoub Mahboub">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Tajawal', sans-serif;
    }

    body {
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: #fff;
      line-height: 1.8;
    }

    header {
      padding: 40px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 40px;
      font-weight: 900;
      margin-bottom: 10px;
    }

    header p {
      font-size: 18px;
      opacity: 0.9;
    }

    .container {
      max-width: 1100px;
      margin: auto;
      padding: 20px;
    }

    .card {
      background: rgba(255, 255, 255, 0.08);
      border-radius: 15px;
      padding: 25px;
      margin-bottom: 25px;
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
      background: rgba(255, 255, 255, 0.12);
    }

    .card h2 {
      margin-bottom: 15px;
      color: #00eaff;
      font-size: 26px;
    }

    .services ul {
      list-style: none;
    }

    .services li {
      padding: 8px 0;
      font-size: 18px;
    }

    .cta {
      text-align: center;
      margin: 40px 0;
    }

    .cta a {
      display: inline-block;
      padding: 14px 30px;
      background: #00eaff;
      color: #000;
      border-radius: 30px;
      text-decoration: none;
      font-weight: 700;
      transition: 0.3s;
    }

    .cta a:hover {
      background: #fff;
      color: #000;
    }

    footer {
      text-align: center;
      padding: 20px;
      font-size: 14px;
      opacity: 0.7;
    }
  </style>
</head>

<body>

  <header>
    <h1>Ayoub Website</h1>
    <p>موقع شخصي احترافي – تصميم عصري وظهور قوي</p>
  </header>

  <div class="container">

    <div class="card">
      <h2>👋 مرحبًا</h2>
      <p>
        هذا موقع شخصي احترافي لعرض الخدمات والأعمال بطريقة بسيطة،
        أنيقة ومتجاوبة مع جميع الأجهزة.
      </p>
    </div>

    <div class="card services">
      <h2>💼 الخدمات</h2>
      <ul>
        <li>✔️ تصميم مواقع HTML / CSS</li>
        <li>✔️ مواقع شخصية وتجارية</li>
        <li>✔️ تصميم عصري وسريع</li>
        <li>✔️ متوافق مع الهاتف والكمبيوتر</li>
      </ul>
    </div>

    <div class="card">
      <h2>🚀 لماذا هذا الموقع؟</h2>
      <p>
        الموقع خفيف، سريع، بدون تعقيد، ومهيأ لمحركات البحث
        ويعمل على جميع المتصفحات مثل Firefox وChrome.
      </p>
    </div>

    <div class="cta">
      <a href="https://github.com/mahboubayoub2012-code" target="_blank">
        زيارة GitHub
      </a>
    </div>

  </div>

  <footer>
    © 2026 – Ayoub Mahboub | All Rights Reserved
  </footer>

</body>
</html>
