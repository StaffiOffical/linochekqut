<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Полынь — кофейня на обжарке</title>
<style>
  :root{
    --bark:#241812;
    --roast:#3d2a1e;
    --cream:#f2e9d8;
    --ash:#8a7c68;
    --ember:#c65a2e;
    --font-display: Georgia, 'Times New Roman', serif;
    --font-body: -apple-system, 'Segoe UI', sans-serif;
  }
  *{box-sizing:border-box; margin:0; padding:0;}
  body{background:var(--bark); color:var(--cream); font-family:var(--font-body); line-height:1.6;}
  a{color:inherit;}
  .wrap{max-width:1000px; margin:0 auto; padding:0 24px;}

  header{padding:28px 0; border-bottom:1px solid rgba(242,233,216,0.12);}
  header .wrap{display:flex; justify-content:space-between; align-items:center;}
  .logo{font-family:var(--font-display); font-size:22px; letter-spacing:0.04em;}
  nav a{margin-left:28px; text-decoration:none; font-size:14px; color:var(--ash); transition:color .2s;}
  nav a:hover{color:var(--cream);}

  .hero{padding:100px 0 80px; position:relative;}
  .hero .eyebrow{color:var(--ember); text-transform:uppercase; font-size:13px; letter-spacing:0.18em; margin-bottom:18px;}
  .hero h1{font-family:var(--font-display); font-size:clamp(38px,7vw,72px); line-height:1.05; max-width:720px; font-weight:400;}
  .hero h1 em{color:var(--ember); font-style:normal;}
  .hero p{max-width:480px; margin-top:24px; color:var(--ash); font-size:17px;}
  .roast-line{display:flex; gap:2px; margin-top:56px; height:4px;}
  .roast-line span{flex:1; background:var(--roast);}
  .roast-line span.active{background:var(--ember);}

  .beans{padding:70px 0; border-top:1px solid rgba(242,233,216,0.1); border-bottom:1px solid rgba(242,233,216,0.1);}
  .beans .grid{display:grid; grid-template-columns:repeat(3,1fr); gap:36px;}
  .bean-card .origin{font-size:12px; color:var(--ember); letter-spacing:0.12em; text-transform:uppercase;}
  .bean-card h3{font-family:var(--font-display); font-size:26px; margin:10px 0 8px; font-weight:400;}
  .bean-card p{color:var(--ash); font-size:14px;}

  .visit{padding:90px 0; text-align:center;}
  .visit h2{font-family:var(--font-display); font-size:40px; font-weight:400; margin-bottom:20px;}
  .visit p{color:var(--ash); max-width:460px; margin:0 auto 32px;}
  .btn{display:inline-block; padding:14px 34px; background:var(--ember); color:var(--bark); text-decoration:none; font-weight:600; font-size:14px; letter-spacing:0.03em;}

  footer{padding:32px 0; border-top:1px solid rgba(242,233,216,0.12); font-size:13px; color:var(--ash); display:flex; justify-content:space-between;}

  @media(max-width:700px){
    .beans .grid{grid-template-columns:1fr;}
    nav a{margin-left:16px;}
    footer{flex-direction:column; gap:8px; text-align:center;}
  }
</style>
</head>
<body>

<header>
  <div class="wrap">
    <div class="logo">Полынь</div>
    <nav>
      <a href="#beans">Обжарка</a>
      <a href="#visit">Адрес</a>
    </nav>
  </div>
</header>

<section class="hero">
  <div class="wrap">
    <div class="eyebrow">Кофейня · собственная обжарочная</div>
    <h1>Кофе, который <em>помнят</em>, а не просто пьют</h1>
    <p>Обжариваем небольшими партиями раз в неделю. Каждая пачка — с датой обжарки и картой вкуса, а не маркетинговым текстом.</p>
    <div class="roast-line">
      <span class="active"></span><span class="active"></span><span class="active"></span>
      <span></span><span></span><span></span><span></span><span></span>
    </div>
  </div>
</section>

<section class="beans" id="beans">
  <div class="wrap">
    <div class="grid">
      <div class="bean-card">
        <div class="origin">Эфиопия · Йиргачеффе</div>
        <h3>Светлая обжарка</h3>
        <p>Жасмин, бергамот, лёгкая кислинка. Для фильтра и пуровера.</p>
      </div>
      <div class="bean-card">
        <div class="origin">Колумбия · Уила</div>
        <h3>Средняя обжарка</h3>
        <p>Карамель, красное яблоко, мягкое тело. Универсальный вариант.</p>
      </div>
      <div class="bean-card">
        <div class="origin">Бразилия · Серрадо</div>
        <h3>Тёмная обжарка</h3>
        <p>Тёмный шоколад, орех, плотное тело. Для эспрессо и молочных.</p>
      </div>
    </div>
  </div>
</section>

<section class="visit" id="visit">
  <div class="wrap">
    <h2>Заходите на чашку</h2>
    <p>Открыты каждый день с 8:00 до 21:00. Своё зерно можно забрать с собой в зёрнах или молотым.</p>
    <a class="btn" href="#">Маршрут до кофейни</a>
  </div>
</section>

<footer>
  <div class="wrap" style="display:flex; justify-content:space-between; width:100%;">
    <span>© Полынь, кофейня</span>
    <span>ул. Примерная, 12</span>
  </div>
</footer>

</body>
</html>
