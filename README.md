# menu❤️black❤️coffee❤️    
<!DOCTYPE html>
<html lang="fa">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>سایت موبایلی من</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>سلام 👋</h1>
    <p>به سایت موبایلی من خوش اومدی</p>
  </header>

  <main>
    <button>شروع کن</button>
  </main>

</body>
</html>

<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>کافه بلک | منو</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Vazirmatn:wght@300;400;500;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --dark: #0f0f0f;
      --darker: #0a0a0a;
      --green: #6ecb43;
      --orange: #f58220;
      --light: #f8f8f8;
      --card-bg: #141414;
      --price-bg: rgba(110, 203, 67, 0.15);
      --border: rgba(255,255,255,0.06);
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Vazirmatn', sans-serif;
      background: var(--darker);
      color: white;
      line-height: 1.5;
      padding: 0;
      overflow-x: hidden;
    }

    .container {
      max-width: 960px;
      margin: 0 auto;
      padding: 1.8rem 1rem;
    }

    header {
      text-align: center;
      margin-bottom: 2rem;
    }

    header h1 {
      font-weight: 600;
      font-size: 2.4rem;
      letter-spacing: -0.5px;
      background: linear-gradient(to right, #fff, #ccc);
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
      margin-bottom: 0.4rem;
    }

    .logo-divider {
      width: 80px;
      height: 2px;
      background: var(--green);
      margin: 0.6rem auto;
      border-radius: 1px;
    }

    .menu-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.4rem;
      margin-bottom: 2rem;
    }

    .section {
      background: var(--card-bg);
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 12px rgba(0,0,0,0.3);
    }

    .section-header {
      padding: 0.7rem 1.3rem;
      font-weight: 600;
      font-size: 1.15rem;
      color: var(--green);
      position: relative;
    }

    .section-header::after {
      content: "";
      position: absolute;
      bottom: 0;
      right: 1.3rem;
      width: 30px;
      height: 2px;
      background: var(--green);
      border-radius: 1px;
    }

    .items-list {
      padding: 0.8rem 0;
    }

    .item {
      display: flex;
      justify-content: space-between;
      padding: 0.6rem 1.3rem;
      border-bottom: 1px solid var(--border);
      transition: background 0.2s;
    }

    .item:last-child {
      border-bottom: none;
    }

    .item:hover {
      background: rgba(110, 203, 67, 0.04);
    }

    .item-name {
      font-weight: 500;
      font-size: 0.95rem;
      flex: 1;
    }

    .item-price {
      background: var(--price-bg);
      color: var(--green);
      font-weight: 600;
      padding: 0.25rem 0.7rem;
      border-radius: 6px;
      min-width: 44px;
      text-align: center;
      font-size: 0.9rem;
    }

    footer {
      text-align: center;
      padding: 1.5rem 0 1rem;
      margin-top: 1.5rem;
      border-top: 1px solid var(--border);
      font-size: 0.9rem;
      color: #aaa;
    }

    .social {
      display: inline-flex;
      align-items: center;
      gap: 0.5rem;
      background: rgba(245, 130, 32, 0.15);
      color: var(--orange);
      padding: 0.4rem 1rem;
      border-radius: 30px;
      font-weight: 500;
      margin-top: 0.6rem;
      transition: all 0.2s;
    }

    .social:hover {
      background: rgba(245, 130, 32, 0.25);
      transform: scale(1.03);
    }

    .social svg {
      width: 18px;
      height: 18px;
    }

    @media (max-width: 600px) {
      .menu-grid {
        grid-template-columns: 1fr;
      }
      header h1 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>

  <div class="container">
    <header>
      <h1>کافه بلک</h1>
      <div class="logo-divider"></div>
    </header>

    <div class="menu-grid">

      <!-- صبحانه -->
      <div class="section">
        <div class="section-header">صبحانه</div>
        <div class="items-list">
          <div class="item"><span class="item-name">املت تکنفره</span><span class="item-price">۱۳۰</span></div>
          <div class="item"><span class="item-name">املت دونفره</span><span class="item-price">۱۷۰</span></div>
          <div class="item"><span class="item-name">نیمرو</span><span class="item-price">۹۰</span></div>
          <div class="item"><span class="item-name">سوسیس تخم‌مرغ</span><span class="item-price">۱۳۰</span></div>
          <div class="item"><span class="item-name">سینی ایرانی</span><span class="item-price">۱۵۰</span></div>
          <div class="item"><span class="item-name">سینی انگلیسی</span><span class="item-price">۲۳۰</span></div>
          <div class="item"><span class="item-name">عدسی</span><span class="item-price">۸۰</span></div>
        </div>
      </div>

      <!-- قهوه‌ها -->
      <div class="section">
        <div class="section-header">قهوه‌ها</div>
        <div class="items-list">
          <div class="item"><span class="item-name">اسپرسو سینگل</span><span class="item-price">۵۰</span></div>
          <div class="item"><span class="item-name">اسپرسو دبل</span><span class="item-price">۷۰</span></div>
          <div class="item"><span class="item-name">آمریکانو</span><span class="item-price">۸۵</span></div>
          <div class="item"><span class="item-name">لاته</span><span class="item-price">۱۰۰</span></div>
          <div class="item"><span class="item-name">موکا</span><span class="item-price">۱۲۰</span></div>
          <div class="item"><span class="item-name">آفاگاتو</span><span class="item-price">۹۵</span></div>
          <div class="item"><span class="item-name">کارامل ماکیاتو</span><span class="item-price">۱۲۰</span></div>
          <div class="item"><span class="item-name">کاپوچینو</span><span class="item-price">۹۵</span></div>
          <div class="item"><span class="item-name">آیس کافی</span><span class="item-price">۱۰۰</span></div>
          <div class="item"><span class="item-name">آیس لاته</span><span class="item-price">۱۰۰</span></div>
          <div class="item"><span class="item-name">ایس موکا</span><span class="item-price">۱۲۰</span></div>
          <div class="item"><span class="item-name">آیس کارامل</span><span class="item-price">۱۲۰</span></div>
          <div class="item"><span class="item-name">آیس آمریکانو</span><span class="item-price">۸۵</span></div>
        </div>
      </div>

      <!-- نوشیدنی گرم -->
      <div class="section">
        <div class="section-header">نوشیدنی گرم</div>
        <div class="items-list">
          <div class="item"><span class="item-name">چای سیاه</span><span class="item-price">۴۰</span></div>
          <div class="item"><span class="item-name">چای سبز</span><span class="item-price">۵۰</span></div>
          <div class="item"><span class="item-name">دمنوش آرامش</span><span class="item-price">۶۰</span></div>
          <div class="item"><span class="item-name">دمنوش سلامت</span><span class="item-price">۶۰</span></div>
          <div class="item"><span class="item-name">هات چاکلت</span><span class="item-price">۹۰</span></div>
          <div class="item"><span class="item-name">وایت چاکلت</span><span class="item-price">۹۰</span></div>
          <div class="item"><span class="item-name">چای ماسالا</span><span class="item-price">۹۵</span></div>
          <div class="item"><span class="item-name">چای کرک</span><span class="item-price">۱۲۰</span></div>
        </div>
      </div>

      <!-- عصرانه -->
      <div class="section">
        <div class="section-header">عصرانه</div>
        <div class="items-list">
          <div class="item"><span class="item-name">اسنک مخصوص</span><span class="item-price">۱۴۵</span></div>
          <div class="item"><span class="item-name">اسنک رست‌بیف</span><span class="item-price">۱۸۵</span></div>
          <div class="item"><span class="item-name">اسنک مرغ</span><span class="item-price">۱۷۵</span></div>
        </div>
      </div>

      <!-- دسر -->
      <div class="section">
        <div class="section-header">دسر</div>
        <div class="items-list">
          <div class="item"><span class="item-name">کیک شکلاتی</span><span class="item-price">۱۰۰</span></div>
          <div class="item"><span class="item-name">کیک روز</span><span class="item-price">۱۰۰</span></div>
        </div>
      </div>

      <!-- شیک‌ها -->
      <div class="section">
        <div class="section-header">شیک‌ها</div>
        <div class="items-list">
          <div class="item"><span class="item-name">شیک سوییتی رزبری</span><span class="item-price">۱۶۰</span></div>
          <div class="item"><span class="item-name">شیک نوتلا</span><span class="item-price">۱۴۰</span></div>
          <div class="item"><span class="item-name">شیک شکلات</span><span class="item-price">۱۲۰</span></div>
          <div class="item"><span class="item-name">شیک موز شکلات</span><span class="item-price">۱۴۰</span></div>
        </div>
      </div>

    </div>

    <footer>
      <div class="social">
        <svg viewBox="0 0 24 24" fill="currentColor">
          <path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.07 1.265.07 1.645.07 4.849 0 3.205 0 3.584-.07 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.07-1.645.07-4.85.07-3.205 0-3.584 0-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.072-1.265-.072-1.644-.072-4.849 0-3.204 0-3.584.072-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.072 1.645-.072 4.84-.072zm0-2.163c-3.259 0-3.667 0-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.072 1.28-.072 1.688-.072 4.948 0 3.259 0 3.668.072 4.947.2 4.358 2.618 6.78 6.98 6.98 1.281.072 1.689.072 4.948.072 3.259 0 3.667 0 4.947-.072 4.354-.2 6.781-2.618 6.979-6.98.073-1.28.073-1.689.073-4.948 0-3.259 0-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.073-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/>
        </svg>
        black.coffee.one
      </div>
    </footer>

  </div>

</body>
</html>

