<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Глина и Свет — керамика ручной работы</title>
<style>
  :root{
    --sage:#5c6b52;
    --paper:#f6f4ee;
    --clay:#a9765a;
    --ink:#2b2b26;
    --line:#dcd8c9;
    --font-display: 'Palatino Linotype', Georgia, serif;
    --font-body: -apple-system, 'Segoe UI', sans-serif;
  }
  *{box-sizing:border-box; margin:0; padding:0;}
  body{background:var(--paper); color:var(--ink); font-family:var(--font-body);}
  .wrap{max-width:1080px; margin:0 auto; padding:0 24px;}

  header{padding:22px 0; border-bottom:1px solid var(--line);}
  header .wrap{display:flex; justify-content:space-between; align-items:center;}
  .brand{font-family:var(--font-display); font-size:20px; color:var(--sage);}
  .cart{font-size:13px; border:1px solid var(--ink); padding:8px 16px; cursor:pointer;}

  .banner{padding:60px 0 50px; text-align:center;}
  .banner h1{font-family:var(--font-display); font-size:clamp(30px,5vw,48px); font-weight:400; max-width:560px; margin:0 auto 16px;}
  .banner p{color:#7a7668; max-width:420px; margin:0 auto;}

  .products{padding:20px 0 80px;}
  .grid{display:grid; grid-template-columns:repeat(3,1fr); gap:34px;}
  .card{background:#fff; border:1px solid var(--line);}
  .thumb{aspect-ratio:1/1; background:linear-gradient(150deg,#efe9d8,#d8cfb2); position:relative;}
  .thumb::after{content:''; position:absolute; left:50%; top:50%; width:38%; height:55%; transform:translate(-50%,-50%); border-radius:50% 50% 45% 45%/60% 60% 40% 40%; background:var(--clay); opacity:0.55;}
  .info{padding:18px;}
  .info .cat{font-size:11px; text-transform:uppercase; letter-spacing:0.1em; color:var(--sage);}
  .info h3{font-family:var(--font-display); font-weight:400; font-size:19px; margin:8px 0 6px;}
  .info .price{font-size:15px; font-weight:600;}
  .info .desc{font-size:13px; color:#8a8574; margin-top:6px;}
  .add{margin-top:14px; width:100%; padding:10px; background:var(--ink); color:var(--paper); border:none; font-size:13px; cursor:pointer;}
  .add:hover{background:var(--sage);}

  .strip{background:var(--sage); color:var(--paper); text-align:center; padding:50px 24px;}
  .strip h2{font-family:var(--font-display); font-weight:400; font-size:26px; margin-bottom:10px;}
  .strip p{opacity:0.85; font-size:14px;}

  footer{padding:30px 0; text-align:center; font-size:13px; color:#8a8574;}

  @media(max-width:760px){ .grid{grid-template-columns:1fr 1fr;} }
  @media(max-width:480px){ .grid{grid-template-columns:1fr;} }
</style>
</head>
<body>

<header>
  <div class="wrap">
    <div class="brand">Глина и Свет</div>
    <div class="cart">Корзина (0)</div>
  </div>
</header>

<section class="banner">
  <div class="wrap">
    <h1>Керамика для дома, сделанная руками, а не станком</h1>
    <p>Каждая чашка и тарелка — в единственном экземпляре. Обжиг в собственной мастерской.</p>
  </div>
</section>

<section class="products">
  <div class="wrap">
    <div class="grid">
      <div class="card">
        <div class="thumb"></div>
        <div class="info">
          <div class="cat">Чашки</div>
          <h3>Чашка «Туман»</h3>
          <div class="price">1 450 ₽</div>
          <div class="desc">Матовая глазурь, объём 250 мл</div>
          <button class="add">В корзину</button>
        </div>
      </div>
      <div class="card">
        <div class="thumb"></div>
        <div class="info">
          <div class="cat">Тарелки</div>
          <h3>Тарелка «Поле»</h3>
          <div class="price">1 890 ₽</div>
          <div class="desc">Диаметр 24 см, песочный тон</div>
          <button class="add">В корзину</button>
        </div>
      </div>
      <div class="card">
        <div class="thumb"></div>
        <div class="info">
          <div class="cat">Вазы</div>
          <h3>Ваза «Стебель»</h3>
          <div class="price">2 600 ₽</div>
          <div class="desc">Ручная лепка, высота 22 см</div>
          <button class="add">В корзину</button>
        </div>
      </div>
      <div class="card">
        <div class="thumb"></div>
        <div class="info">
          <div class="cat">Чашки</div>
          <h3>Чашка «Глина»</h3>
          <div class="price">1 350 ₽</div>
          <div class="desc">Необожжённая текстура снаружи</div>
          <button class="add">В корзину</button>
        </div>
      </div>
      <div class="card">
        <div class="thumb"></div>
        <div class="info">
          <div class="cat">Тарелки</div>
          <h3>Сет из 4 тарелок</h3>
          <div class="price">6 200 ₽</div>
          <div class="desc">Разный оттенок каждой тарелки</div>
          <button class="add">В корзину</button>
        </div>
      </div>
      <div class="card">
        <div class="thumb"></div>
        <div class="info">
          <div class="cat">Вазы</div>
          <h3>Ваза «Капля»</h3>
          <div class="price">2 100 ₽</div>
          <div class="desc">Компактная форма, высота 14 см</div>
          <button class="add">В корзину</button>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="strip">
  <div class="wrap">
    <h2>Доставка по всей России</h2>
    <p>Бережно упаковываем и отправляем в течение 2 дней после заказа</p>
  </div>
</section>

<footer>© Глина и Свет, мастерская керамики</footer>

</body>
</html>
