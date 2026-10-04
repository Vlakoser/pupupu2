<!doctype html>
<html lang="ru">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>NEXUS CLOUD — Облачный гейминг</title>
<meta name="description" content="NEXUS CLOUD — облачный гейминг нового поколения. Играйте где угодно, без мощного ПК.">
<style>
:root{--bg:#050609;--panel:#0b0d12;--line:#1a1e27;--text:#f5f7fb;--muted:#9299a8;--accent:#8b5cf6;--accent2:#22d3ee}
*{box-sizing:border-box}html{scroll-behavior:smooth}body{margin:0;background:var(--bg);color:var(--text);font:15px/1.6 Inter,system-ui,-apple-system,Segoe UI,sans-serif;overflow-x:hidden}
body:before{content:"";position:fixed;inset:-30%;z-index:-2;background:radial-gradient(circle at 50% 35%,rgba(139,92,246,.16),transparent 24%),radial-gradient(circle at 75% 20%,rgba(34,211,238,.09),transparent 22%);filter:blur(35px)}
body:after{content:"";position:fixed;inset:0;z-index:-1;opacity:.23;background-image:linear-gradient(rgba(255,255,255,.025) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.025) 1px,transparent 1px);background-size:52px 52px;mask-image:linear-gradient(to bottom,black,transparent 75%)}
a{color:inherit;text-decoration:none}.wrap{max-width:1180px;margin:auto;padding:0 24px}
nav{height:76px;display:flex;align-items:center;justify-content:space-between;border-bottom:1px solid rgba(255,255,255,.06)}
.logo{font-weight:900;letter-spacing:.08em;font-size:18px}.logo span{color:var(--accent2)}
.links{display:flex;gap:28px;color:#aeb4c1}.links a{transition:.2s}.links a:hover{color:#fff}
.btn{display:inline-flex;align-items:center;justify-content:center;border:1px solid rgba(255,255,255,.12);padding:12px 19px;border-radius:12px;background:#10131a;color:#fff;font-weight:700;cursor:pointer;transition:.25s}
.btn:hover{transform:translateY(-2px);border-color:rgba(139,92,246,.7);box-shadow:0 0 28px rgba(139,92,246,.18)}
.btn.primary{border:0;background:linear-gradient(135deg,var(--accent),#5b3fc8);box-shadow:0 0 35px rgba(139,92,246,.25)}
.hero{min-height:calc(100vh - 77px);display:grid;place-items:center;text-align:center;padding:80px 0 100px;position:relative}
.orb{position:absolute;width:520px;height:520px;border-radius:50%;border:1px solid rgba(139,92,246,.13);box-shadow:0 0 100px rgba(139,92,246,.12),inset 0 0 100px rgba(34,211,238,.04);animation:float 8s ease-in-out infinite}
.orb:before,.orb:after{content:"";position:absolute;border-radius:50%;border:1px solid rgba(34,211,238,.13)}.orb:before{inset:45px}.orb:after{inset:105px}
@keyframes float{50%{transform:translateY(-14px) scale(1.02)}}
.hero-content{position:relative;z-index:1}.eyebrow{display:inline-flex;gap:8px;align-items:center;border:1px solid #202530;background:#0a0c11;border-radius:999px;padding:7px 12px;color:#b7bdc9;font-size:12px;letter-spacing:.12em;text-transform:uppercase}
.dot{width:7px;height:7px;border-radius:50%;background:#22d3ee;box-shadow:0 0 12px #22d3ee}
h1{font-size:clamp(48px,8vw,96px);line-height:.94;letter-spacing:-.055em;margin:24px 0 22px;max-width:1000px}
.gradient{background:linear-gradient(100deg,#fff 25%,#b89cff 55%,#57e8ff 90%);-webkit-background-clip:text;background-clip:text;color:transparent}
.lead{max-width:680px;margin:0 auto 34px;color:#9da5b5;font-size:18px}.actions{display:flex;gap:12px;justify-content:center;flex-wrap:wrap}
section{padding:100px 0;border-top:1px solid rgba(255,255,255,.06)}.section-head{display:flex;justify-content:space-between;gap:30px;align-items:end;margin-bottom:34px}
.kicker{color:#7e8797;text-transform:uppercase;letter-spacing:.14em;font-size:11px}.section-head h2{font-size:40px;line-height:1.05;margin:8px 0 0;letter-spacing:-.04em}.section-head p{max-width:430px;color:var(--muted);margin:0}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:14px}.card{background:linear-gradient(145deg,#0c0f15,#080a0e);border:1px solid var(--line);border-radius:20px;padding:26px;min-height:190px;position:relative;overflow:hidden}.card:after{content:"";position:absolute;width:130px;height:130px;right:-55px;bottom:-65px;border-radius:50%;background:rgba(139,92,246,.13);filter:blur(25px)}.icon{font-size:24px}.card h3{margin:25px 0 8px}.card p{color:var(--muted);margin:0}
.games{grid-template-columns:repeat(4,1fr)}.game{height:210px;border-radius:18px;border:1px solid var(--line);padding:18px;display:flex;align-items:end;background:linear-gradient(145deg,#111522,#07080b);position:relative;overflow:hidden}.game:nth-child(2){background:linear-gradient(145deg,#161022,#07080b)}.game:nth-child(3){background:linear-gradient(145deg,#0d1820,#07080b)}.game:nth-child(4){background:linear-gradient(145deg,#17130e,#07080b)}.game strong{font-size:17px}.game small{display:block;color:#858d9d;margin-top:3px}
.pricing{display:grid;grid-template-columns:repeat(3,1fr);gap:14px}.price{border:1px solid var(--line);background:#0a0c11;border-radius:20px;padding:28px}.price.featured{border-color:rgba(139,92,246,.6);box-shadow:0 0 40px rgba(139,92,246,.08)}.price .cost{font-size:38px;font-weight:800;margin:16px 0}.price ul{list-style:none;padding:0;color:#9ca4b4}.price li{margin:10px 0}.price li:before{content:"✓";color:#5eead4;margin-right:9px}
.faq{max-width:820px}.faq details{border-bottom:1px solid var(--line);padding:20px 0}.faq summary{cursor:pointer;font-weight:700}.faq p{color:var(--muted);max-width:700px}
.cta{text-align:center;padding:110px 20px}.cta h2{font-size:clamp(38px,6vw,70px);margin:0 0 16px;letter-spacing:-.05em}.cta p{color:var(--muted);margin:0 auto 28px;max-width:560px}
footer{border-top:1px solid var(--line);padding:28px 0;color:#707887;font-size:13px;display:flex;justify-content:space-between}
@media(max-width:800px){.links{display:none}.grid,.pricing{grid-template-columns:1fr}.games{grid-template-columns:repeat(2,1fr)}.section-head{display:block}.section-head p{margin-top:15px}.orb{width:340px;height:340px}h1{font-size:54px}.hero{padding-top:50px}}
@media(max-width:500px){.games{grid-template-columns:1fr}.wrap{padding:0 17px}.btn{width:100%}.actions{padding:0 20px}}

.tabs{display:flex;gap:4px;align-items:center;background:rgba(10,13,20,.72);border:1px solid rgba(255,255,255,.08);padding:5px;border-radius:14px;backdrop-filter:blur(14px)}
.tab{border:0;background:transparent;color:#8f97a7;padding:9px 12px;border-radius:10px;font:600 12px/1 inherit;cursor:pointer;transition:.2s;white-space:nowrap}
.tab:hover{color:#fff;background:rgba(255,255,255,.05)}
.tab.active{color:#fff;background:linear-gradient(135deg,rgba(139,92,246,.34),rgba(34,211,238,.12));box-shadow:inset 0 0 0 1px rgba(255,255,255,.08)}
.panel{display:none}.panel.active{display:block;animation:fade .35s ease}
@keyframes fade{from{opacity:0;transform:translateY(8px)}to{opacity:1;transform:none}}
.sport-hero{min-height:580px;display:grid;align-items:end;border-radius:28px;overflow:hidden;position:relative;background-image:linear-gradient(180deg,rgba(5,7,10,.08) 5%,rgba(5,7,10,.28) 42%,rgba(5,7,10,.94) 100%),url("https://easy-peasy.ai/cdn-cgi/image/quality%3D80%2Cformat%3Dauto%2Cwidth%3D1400/https%3A/fdczvxmwwjwpwbeeqcth.supabase.co/storage/v1/object/public/images/f557b0db-28e1-4738-b9a0-101a61000a5b/94d51381-d0fc-46e4-9177-186565c0d03e.png");background-size:cover;background-position:center;box-shadow:inset 0 0 100px rgba(0,0,0,.4),0 25px 80px rgba(34,211,238,.08)}
.sport-copy{padding:48px;max-width:720px}.sport-copy h2{font-size:clamp(44px,7vw,78px);line-height:.94;margin:12px 0;letter-spacing:-.05em}.sport-copy p{color:#d0d5df;font-size:17px;max-width:620px}
.news-card{display:grid;grid-template-columns:1.3fr 1fr;gap:14px}.news-main{min-height:360px;border-radius:22px;padding:30px;display:flex;align-items:end;background:linear-gradient(180deg,rgba(8,10,14,.05),rgba(8,10,14,.94)),url("https://easy-peasy.ai/cdn-cgi/image/quality%3D80%2Cformat%3Dauto%2Cwidth%3D1200/https%3A/fdczvxmwwjwpwbeeqcth.supabase.co/storage/v1/object/public/images/f557b0db-28e1-4738-b9a0-101a61000a5b/94d51381-d0fc-46e4-9177-186565c0d03e.png") center/cover}.news-main h3{font-size:32px;margin:8px 0}.news-side{display:grid;gap:14px}.news-item{border:1px solid var(--line);background:#0b0e14;border-radius:18px;padding:22px}.news-item h4{margin:8px 0}.news-item p{color:var(--muted);margin:0}
@media(max-width:1050px){.tabs{overflow:auto;max-width:62vw}.tab{padding:8px 10px}.news-card{grid-template-columns:1fr}}
@media(max-width:800px){.tabs{position:absolute;top:82px;left:17px;right:17px;max-width:none;justify-content:flex-start}.wrap{padding-top:0}nav{margin-bottom:62px}.sport-copy{padding:28px}.sport-hero{min-height:500px}}
</style>
</head>
<body>
<div class="wrap">
<nav>
  <a class="logo" href="#" data-tab="home">NEXUS<span>.CLOUD</span></a>
  <div class="tabs">
    <button class="tab active" data-tab="home">Главная</button>
    <button class="tab" data-tab="games">Игры</button>
    <button class="tab" data-tab="sport">Спорт</button>
    <button class="tab" data-tab="tech">Технологии</button>
    <button class="tab" data-tab="plans">Тарифы</button>
    <button class="tab" data-tab="news">Новости</button>
    <button class="tab" data-tab="faq">FAQ</button>
  </div>
  <button class="btn" data-tab="plans">Ранний доступ</button>
</nav>

<main id="home">

<section class="panel active" data-panel="home">
  <div class="hero">
    <div class="orb"></div>
    <div class="hero-content">
      <div class="eyebrow"><i class="dot"></i> Система запускается</div>
      <h1>Твой игровой ПК<br><span class="gradient">теперь в облаке.</span></h1>
      <p class="lead">Играйте в требовательные AAA-игры с любого устройства. Без апгрейдов, загрузок и компромиссов — только вы и игра.</p>
      <div class="actions"><button class="btn primary" data-tab="plans">Получить ранний доступ</button><button class="btn" data-tab="sport">Открыть арену</button></div>
    </div>
  </div>
  <div class="section-head"><div><div class="kicker">NEXUS / LIVE</div><h2>Игры. Спорт. Облако.</h2></div><p>Теперь главная страница ощущается как полноценный игровой портал, а не просто заглушка.</p></div>
  <div class="grid">
    <article class="card"><div class="icon">🎮</div><h3>Cloud Gaming</h3><p>Игровая мощность в облаке — открывайте библиотеку с любого экрана.</p></article>
    <article class="card"><div class="icon">🏆</div><h3>Cyber Arena</h3><p>Спортивная зона с футуристической атмосферой и киберспортивным вайбом.</p></article>
    <article class="card"><div class="icon">⚡</div><h3>Low Latency</h3><p>Минимум лишних движений между вашим контроллером и игрой.</p></article>
  </div>
</section>

<section class="panel" data-panel="games">
  <div class="section-head"><div><div class="kicker">Library</div><h2>Игры без<br>границ.</h2></div><p>Каталог можно подключить к реальному API позже.</p></div>
  <div class="grid games">
    <div class="game"><div><strong>CYBER // CITY</strong><small>Action RPG</small></div></div>
    <div class="game"><div><strong>VOID RUNNER</strong><small>Futuristic Shooter</small></div></div>
    <div class="game"><div><strong>STARFALL</strong><small>Space Adventure</small></div></div>
    <div class="game"><div><strong>DARK FRONT</strong><small>Strategy</small></div></div>
    <div class="game"><div><strong>NEON DRIFT</strong><small>Racing</small></div></div>
    <div class="game"><div><strong>RIFT ZERO</strong><small>Competitive FPS</small></div></div>
    <div class="game"><div><strong>AFTERLIGHT</strong><small>Open World</small></div></div>
    <div class="game"><div><strong>ORBITAL</strong><small>Simulation</small></div></div>
  </div>
</section>

<section class="panel" data-panel="sport">
  <div class="sport-hero">
    <div class="sport-copy">
      <div class="eyebrow"><i class="dot"></i> NEXUS / SPORT</div>
      <h2>Будущее спорта<br><span class="gradient">уже на арене.</span></h2>
      <p>Футбол, киберспорт и цифровые соревнования в одной футуристической атмосфере. Именно сюда можно добавить трансляции, турниры и рейтинги.</p>
      <button class="btn primary" data-tab="games">Смотреть игры</button>
    </div>
  </div>
</section>

<section class="panel" data-panel="tech">
  <div class="section-head"><div><div class="kicker">Technology</div><h2>Мощность там,<br>где она нужна.</h2></div><p>Вычисления происходят в дата-центре, а на устройство приходит игровой поток.</p></div>
  <div class="grid">
    <article class="card"><div class="icon">⚡</div><h3>Мгновенный старт</h3><p>Запускайте игру за секунды. Никаких десятков гигабайт на диске.</p></article>
    <article class="card"><div class="icon">◈</div><h3>4K / 120 FPS</h3><p>Высокое качество изображения и плавность там, где позволяет подключение.</p></article>
    <article class="card"><div class="icon">∞</div><h3>Любое устройство</h3><p>ПК, ноутбук, телевизор или смартфон — игровой мир всегда с вами.</p></article>
  </div>
</section>

<section class="panel" data-panel="plans">
  <div class="section-head"><div><div class="kicker">Plans</div><h2>Выберите свой<br>уровень мощности.</h2></div><p>Цены демонстрационные — замените их на реальные после запуска.</p></div>
  <div class="pricing">
    <article class="price"><div class="kicker">CORE</div><div class="cost">€9<span style="font-size:14px;color:#777">/мес</span></div><ul><li>1080p Streaming</li><li>До 60 FPS</li><li>RTX Gaming</li></ul><button class="btn">Скоро</button></article>
    <article class="price featured"><div class="kicker">PRO</div><div class="cost">€19<span style="font-size:14px;color:#777">/мес</span></div><ul><li>1440p Streaming</li><li>До 120 FPS</li><li>RTX + Ray Tracing</li></ul><button class="btn primary">Скоро</button></article>
    <article class="price"><div class="kicker">ULTRA</div><div class="cost">€29<span style="font-size:14px;color:#777">/мес</span></div><ul><li>4K Streaming</li><li>До 120 FPS</li><li>Максимальная мощность</li></ul><button class="btn">Скоро</button></article>
  </div>
</section>

<section class="panel" data-panel="news">
  <div class="section-head"><div><div class="kicker">NEXUS / NEWS</div><h2>Новости<br>вселенной.</h2></div><p>Здесь можно разместить новости запуска, турниров, новых игр и обновлений сервиса.</p></div>
  <div class="news-card">
    <article class="news-main"><div><div class="kicker">COMING SOON</div><h3>Новая эра облачного гейминга начинается здесь.</h3><p>Следите за стартом закрытого тестирования.</p></div></article>
    <div class="news-side">
      <article class="news-item"><div class="kicker">01 / UPDATE</div><h4>Новая игровая зона</h4><p>Добавлен футуристический спортивный раздел.</p></article>
      <article class="news-item"><div class="kicker">02 / ARENA</div><h4>Киберспортивные события</h4><p>В будущем здесь появятся турниры и расписание матчей.</p></article>
      <article class="news-item"><div class="kicker">03 / CLOUD</div><h4>Серверы нового поколения</h4><p>Больше мощности. Меньше ожидания.</p></article>
    </div>
  </div>
</section>

<section class="panel" data-panel="faq">
  <div class="section-head"><div><div class="kicker">FAQ</div><h2>Частые<br>вопросы.</h2></div></div>
  <div class="faq">
    <details open><summary>Когда запустится NEXUS.CLOUD?</summary><p>Сайт находится в режиме ожидания запуска. Здесь можно указать реальную дату или форму сбора заявок.</p></details>
    <details><summary>Нужен ли мощный компьютер?</summary><p>Нет. Для облачного гейминга достаточно совместимого устройства и стабильного интернет-соединения.</p></details>
    <details><summary>Можно ли играть с телефона?</summary><p>Да — интерфейс сервиса уже подготовлен для адаптивного отображения.</p></details>
    <details><summary>Можно ли добавить турниры?</summary><p>Да. Вкладка «Спорт» специально сделана как отдельная зона под матчи, рейтинги и трансляции.</p></details>
  </div>
</section>

<section class="cta">
  <div class="eyebrow"><i class="dot"></i> Скоро запуск</div>
  <h2>Готовы играть<br><span class="gradient">по-новому?</span></h2>
  <p>Сайт готов как визуальный прототип. Осталось подключить реальные данные, авторизацию и форму заявки.</p>
  <a class="btn primary" href="mailto:hello@example.com">Узнать о запуске</a>
</section>
</main>

<footer><span>© 2026 NEXUS.CLOUD</span><span>Cloud Gaming / Next Generation</span></footer>
</div>
<script>
const tabs=[...document.querySelectorAll('[data-tab]')];
const panels=[...document.querySelectorAll('[data-panel]')];
function openTab(name){
  panels.forEach(p=>p.classList.toggle('active',p.dataset.panel===name));
  document.querySelectorAll('.tab').forEach(t=>t.classList.toggle('active',t.dataset.tab===name));
  window.scrollTo({top:0,behavior:'smooth'});
  history.replaceState(null,'','#'+name);
}
tabs.forEach(el=>el.addEventListener('click',e=>{e.preventDefault();openTab(el.dataset.tab)}));
const initial=location.hash.slice(1);
if(initial && panels.some(p=>p.dataset.panel===initial)) openTab(initial);
</script>
</body>
</html>
