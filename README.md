<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8">
  <title>Nuck | سازنده QR کد هوشمند</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Vazirmatn:wght@400;700&display=swap');

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Vazirmatn', sans-serif;
    }

    body {
      background: linear-gradient(135deg, #0f0f1a, #1a1a2e);
      color: #ffffff;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 2rem;
      min-height: 100vh;
    }

    header {
      text-align: center;
      margin-bottom: 3rem;
    }

    header h1 {
      font-size: 2.5rem;
      color: #8b5cf6;
      margin-bottom: 0.5rem;
      animation: fadeInDown 1s ease;
    }

    header p {
      font-size: 1.1rem;
      color: #cccccc;
      animation: fadeInDown 1.5s ease;
    }

    .app-showcase {
      max-width: 400px;
      width: 90%;
      background-color: #1f1f2e;
      border-radius: 16px;
      padding: 2rem;
      box-shadow: 0 0 30px rgba(0,0,0,0.4);
      text-align: center;
      animation: fadeInUp 1.5s ease;
    }

    .app-showcase img {
      width: 200px;
      margin-bottom: 1rem;
      border-radius: 20px;
      transition: transform 0.3s ease;
    }

    .app-showcase img:hover {
      transform: scale(1.05);
    }

    .description {
      font-size: 1rem;
      color: #ddd;
      margin-bottom: 2rem;
      line-height: 1.8;
    }

    .download-btn {
      background-color: #8b5cf6;
      color: white;
      padding: 0.8rem 1.5rem;
      border-radius: 12px;
      text-decoration: none;
      font-size: 1rem;
      font-weight: bold;
      transition: background-color 0.3s ease, transform 0.2s;
    }

    .download-btn:hover {
      background-color: #6d28d9;
      transform: translateY(-3px);
    }

    footer {
      margin-top: 3rem;
      font-size: 0.9rem;
      color: #777;
      text-align: center;
    }

    @keyframes fadeInDown {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @media (max-width: 600px) {
      header h1 { font-size: 2rem; }
      .description { font-size: 0.95rem; }
    }
  </style>
</head>
<body>

  <header>
    <h1>Nuck - 4ai </h1>
    <p>ساده‌ترین راه برای ساخت QR کدهای هوشمند</p>
  </header>

  <div class="app-showcase">
    <img src="https://i.postimg.cc/y6RWS9nD/In-Shot.jpg" alt="Nuck App">
    <p class="description">
      با Nuck می‌تونی به‌راحتی QR کد بسازی، رنگ و اندازه‌اش رو تنظیم کنی، و حتی تاریخچه QRهای قبلی رو هم ببینی!
      طراحی مدرن، سرعت بالا و تجربه کاربری عالی منتظرته.
    </p>
    <a class="download-btn" href="http://cafebazaar.ir/app/?id=com.wNuckai_18751428&ref=share" target="_blank">
      دریافت از کافه بازار
    </a>
  </div>

  <footer>
    ساخته شده با ❤️ توسط 4ai
  </footer>

</body>
</html>
