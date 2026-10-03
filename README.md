
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Guía interactiva sobre los lirios Lilium: características, tipos, cuidados, significado y curiosidades.">
<title>Lirios — Belleza que florece</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@500;600;700&family=Montserrat:wght@400;500;600;700&display=swap" rel="stylesheet">

<style>
:root{
  --green-dark:#244638;
  --green:#668d73;
  --green-light:#dfece2;
  --cream:#fbfaf6;
  --pink:#f6e5e8;
  --lilac:#e9e2f2;
  --gold:#b99a5b;
  --text:#2c3630;
  --muted:#69736c;
  --white:#fff;
  --shadow:0 15px 40px rgba(36,70,56,.10);
  --radius:24px;
}
*{box-sizing:border-box;margin:0;padding:0;scroll-behavior:smooth}
body{
  font-family:"Montserrat",sans-serif;
  color:var(--text);
  background:var(--cream);
  line-height:1.7;
}
img{width:100%;display:block}
a{text-decoration:none;color:inherit}
button{font:inherit}
.container{width:min(1120px,92%);margin:auto}
section{padding:95px 0;scroll-margin-top:80px}
.section-tag{
  color:var(--gold);font-size:.78rem;font-weight:700;letter-spacing:2.5px;
  text-transform:uppercase;margin-bottom:10px
}
.section-title{
  font-family:"Cormorant Garamond",serif;font-size:clamp(2.5rem,5vw,4rem);
  line-height:1.05;color:var(--green-dark);margin-bottom:18px
}
.section-intro{max-width:700px;color:var(--muted);margin-bottom:45px}
.navbar{
  position:fixed;top:0;left:0;width:100%;z-index:1000;
  background:rgba(251,250,246,.88);backdrop-filter:blur(14px);
  border-bottom:1px solid rgba(36,70,56,.08)
}
.nav-inner{height:76px;display:flex;align-items:center;justify-content:space-between}
.logo{
  font-family:"Cormorant Garamond",serif;font-size:1.8rem;font-weight:700;
  color:var(--green-dark);display:flex;align-items:center;gap:9px
}
.logo span{color:var(--gold)}
.nav-links{display:flex;gap:24px;align-items:center}
.nav-links a{font-size:.82rem;font-weight:600;color:#526158;transition:.25s}
.nav-links a:hover{color:var(--green-dark)}
.menu-btn{display:none;border:0;background:none;font-size:1.7rem;color:var(--green-dark);cursor:pointer}

.hero{
  min-height:100vh;padding-top:76px;display:grid;align-items:center;
  background:
    radial-gradient(circle at 10% 15%,rgba(223,236,226,.8),transparent 28%),
    radial-gradient(circle at 90% 80%,rgba(233,226,242,.65),transparent 30%);
  overflow:hidden
}
.hero-grid{display:grid;grid-template-columns:1fr 1fr;gap:65px;align-items:center}
.hero-text{animation:fadeUp .9s ease both}
.hero-kicker{color:var(--gold);font-weight:700;letter-spacing:3px;text-transform:uppercase;font-size:.8rem}
.hero h1{
  font-family:"Cormorant Garamond",serif;font-size:clamp(4rem,8vw,7rem);
  line-height:.85;color:var(--green-dark);margin:18px 0 28px
}
.hero h1 em{font-weight:500;color:#8c789f}
.hero p{font-size:1.05rem;color:var(--muted);max-width:580px}
.btn{
  display:inline-flex;align-items:center;gap:9px;margin-top:30px;
  padding:14px 25px;border-radius:50px;background:var(--green-dark);color:white;
  font-weight:600;font-size:.9rem;border:1px solid var(--green-dark);
  transition:.3s;cursor:pointer
}
.btn:hover{transform:translateY(-3px);box-shadow:0 10px 25px rgba(36,70,56,.2)}
.hero-image{
  position:relative;animation:fadeIn 1.1s ease .15s both
}
.hero-image img{height:650px;object-fit:cover;border-radius:45% 45% 24px 24px;box-shadow:var(--shadow)}
.hero-image:before{
  content:"";position:absolute;inset:-18px 18px 18px -18px;border:1px solid #b7cbb9;
  border-radius:45% 45% 24px 24px;z-index:-1
}
.float-note{
  position:absolute;bottom:35px;left:-30px;background:rgba(255,255,255,.94);
  padding:16px 20px;border-radius:18px;box-shadow:var(--shadow);font-size:.78rem
}
.float-note strong{display:block;color:var(--green-dark);font-size:1rem}

.about-grid{display:grid;grid-template-columns:.9fr 1.1fr;gap:65px;align-items:center}
.about-image{position:relative}
.about-image img{height:530px;object-fit:cover;border-radius:25px}
.about-card{
  position:absolute;right:-25px;bottom:25px;background:white;padding:22px;
  width:190px;border-radius:20px;box-shadow:var(--shadow)
}
.about-card b{font-family:"Cormorant Garamond";font-size:2.2rem;color:var(--green-dark)}
.about-card small{display:block;color:var(--muted);font-size:.7rem}
.info-box{background:white;padding:38px;border-radius:var(--radius);box-shadow:var(--shadow)}
.info-box p{margin-bottom:17px;color:var(--muted)}
.info-box p:last-child{margin:0}
.info-box strong{color:var(--green-dark)}

.features{background:#f1f5f0}
.feature-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:18px}
.feature{
  background:white;padding:30px 23px;border-radius:22px;border:1px solid rgba(36,70,56,.06);
  transition:.3s
}
.feature:hover{transform:translateY(-7px);box-shadow:var(--shadow)}
.feature-icon{font-size:2rem;margin-bottom:18px}
.feature h3{font-family:"Cormorant Garamond";font-size:1.55rem;color:var(--green-dark);margin-bottom:8px}
.feature p{font-size:.83rem;color:var(--muted)}

.types-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:22px}
.type-card{background:white;border-radius:24px;overflow:hidden;box-shadow:0 8px 28px rgba(36,70,56,.07);transition:.3s}
.type-card:hover{transform:translateY(-8px);box-shadow:var(--shadow)}
.type-card img{height:290px;object-fit:cover}
.type-content{padding:25px}
.type-content h3{font-family:"Cormorant Garamond";font-size:1.9rem;color:var(--green-dark)}
.type-content p{font-size:.84rem;color:var(--muted);margin:8px 0 15px}
.pill{display:inline-block;padding:5px 10px;border-radius:30px;background:var(--lilac);font-size:.68rem;font-weight:700;color:#625275}

.facts{background:var(--green-dark);color:white}
.facts .section-title{color:white}
.facts .section-intro{color:#d5e0d8}
.facts-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:17px}
.fact{
  padding:27px;background:rgba(255,255,255,.07);border:1px solid rgba(255,255,255,.1);
  border-radius:20px;transition:.3s
}
.fact:hover{background:rgba(255,255,255,.11)}
.fact-number{font-family:"Cormorant Garamond";font-size:2.5rem;color:#d7bd7d}
.fact h3{font-size:1rem;margin-bottom:5px}
.fact p{font-size:.82rem;color:#d4ddd7}

.care-grid{display:grid;grid-template-columns:1fr 1fr;gap:55px;align-items:center}
.care-list{display:grid;gap:14px}
.care-item{
  background:white;border-radius:18px;padding:18px 20px;display:flex;gap:15px;
  align-items:flex-start;box-shadow:0 6px 22px rgba(36,70,56,.06)
}
.care-item span{font-size:1.4rem}
.care-item h3{font-size:.95rem;color:var(--green-dark)}
.care-item p{font-size:.78rem;color:var(--muted)}
.care-image img{height:550px;object-fit:cover;border-radius:28px}

.meaning{background:linear-gradient(120deg,#f6e5e8,#e9e2f2)}
.meaning-box{text-align:center;max-width:800px;margin:auto}
.meaning-symbol{font-size:4rem;margin-bottom:10px}
.meaning-box .section-title{margin-bottom:25px}
.meaning-box p{color:var(--muted);font-size:1rem}
.meaning-tags{display:flex;justify-content:center;flex-wrap:wrap;gap:10px;margin-top:30px}
.meaning-tags span{background:white;padding:9px 16px;border-radius:50px;font-size:.75rem;font-weight:600;color:var(--green-dark)}

.gallery{padding-bottom:105px}
.gallery-grid{display:grid;grid-template-columns:1.2fr .8fr .8fr;grid-template-rows:260px 260px;gap:14px}
.gallery-item{overflow:hidden;border-radius:20px;position:relative}
.gallery-item:first-child{grid-row:span 2}
.gallery-item img{height:100%;object-fit:cover;transition:.5s}
.gallery-item:hover img{transform:scale(1.06)}
.gallery-item:after{
  content:"Ver imagen";position:absolute;bottom:14px;left:14px;background:rgba(255,255,255,.88);
  padding:6px 11px;border-radius:20px;font-size:.65rem;font-weight:700;color:var(--green-dark)
}

.cta{
  margin-top:30px;padding:55px;border-radius:30px;background:var(--green-light);
  display:flex;align-items:center;justify-content:space-between;gap:30px
}
.cta h2{font-family:"Cormorant Garamond";font-size:2.8rem;color:var(--green-dark);line-height:1}
.cta p{font-size:.8rem;color:var(--muted);margin-top:8px}

footer{background:#1b3429;color:#dbe5de;padding:35px 0}
.footer-inner{display:flex;justify-content:space-between;align-items:center;gap:20px}
footer strong{font-family:"Cormorant Garamond";font-size:1.5rem;color:white}
footer p{font-size:.7rem}

#topBtn{
  position:fixed;right:22px;bottom:22px;width:45px;height:45px;border-radius:50%;
  border:0;background:var(--gold);color:white;font-size:1.2rem;cursor:pointer;
  opacity:0;pointer-events:none;transition:.3s;z-index:900
}
#topBtn.show{opacity:1;pointer-events:auto}

.reveal{opacity:0;transform:translateY(25px);transition:.8s ease}
.reveal.visible{opacity:1;transform:none}
@keyframes fadeUp{from{opacity:0;transform:translateY(25px)}to{opacity:1;transform:none}}
@keyframes fadeIn{from{opacity:0;transform:scale(.96)}to{opacity:1;transform:scale(1)}}

@media(max-width:900px){
  .nav-links{
    position:absolute;top:76px;left:0;width:100%;background:var(--cream);
    flex-direction:column;padding:25px;gap:18px;transform:translateY(-130%);
    transition:.35s;box-shadow:0 12px 25px rgba(0,0,0,.06)
  }
  .nav-links.open{transform:translateY(0)}
  .menu-btn{display:block}
  .hero-grid,.about-grid,.care-grid{grid-template-columns:1fr}
  .hero{padding-top:115px;padding-bottom:70px}
  .hero-image img{height:500px}
  .feature-grid{grid-template-columns:repeat(2,1fr)}
  .types-grid{grid-template-columns:1fr 1fr}
  .facts-grid{grid-template-columns:1fr}
  .about-image{max-width:600px}
  .care-image{order:-1}
}
@media(max-width:600px){
  section{padding:70px 0}
  .hero h1{font-size:4rem}
  .hero-image img{height:420px}
  .float-note{left:10px;bottom:20px}
  .feature-grid,.types-grid{grid-template-columns:1fr}
  .gallery-grid{grid-template-columns:1fr 1fr;grid-template-rows:220px 220px 220px}
  .gallery-item:first-child{grid-row:span 1;grid-column:span 2}
  .cta{padding:35px 25px;flex-direction:column;align-items:flex-start}
  .footer-inner{flex-direction:column;text-align:center}
}
</style>
</head>

<body>

<nav class="navbar">
  <div class="container nav-inner">
    <a href="#inicio" class="logo">Lilium<span>✿</span></a>
    <button class="menu-btn" aria-label="Abrir menú">☰</button>
    <div class="nav-links">
      <a href="#inicio">Inicio</a>
      <a href="#que-son">¿Qué son?</a>
      <a href="#tipos">Tipos</a>
      <a href="#datos">Datos interesantes</a>
      <a href="#cuidados">Cuidados</a>
      <a href="#significado">Significado</a>
      <a href="#galeria">Galería</a>
    </div>
  </div>
</nav>

<main>
<section class="hero" id="inicio">
  <div class="container hero-grid">
    <div class="hero-text">
      <div class="hero-kicker">Guía botánica · Lilium</div>
      <h1>Lirios:<br><em>belleza</em> que florece</h1>
      <p>Descubre la historia, diversidad y curiosidades de una de las flores más fascinantes de la naturaleza.</p>
      <a class="btn" href="#que-son">Descubrir más <span>↓</span></a>
    </div>
    <div class="hero-image">
      <img src="https://i.pinimg.com/736x/05/ac/12/05ac12cde84b30f6b5c6435f39e378bb.jpg" alt="Lirio blanco en flor">
      <div class="float-note"><strong>Lilium</strong>Una flor llena de historia y simbolismo.</div>
    </div>
  </div>
</section>

<section id="que-son">
  <div class="container about-grid">
    <div class="about-image reveal">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQg22v9H1TJJDJVjj9RREKkpNRfJDHYR8oAkuQCitGvmw&s=10" alt="Flores en un jardín">
      <div class="about-card"><b>100+</b><small>especies reconocidas dentro del género Lilium</small></div>
    </div>
    <div class="reveal">
      <div class="section-tag">01 · Conociendo al lirio</div>
      <h2 class="section-title">¿Qué son los lirios?</h2>
      <div class="info-box">
        <p>Los lirios verdaderos pertenecen al género <strong>Lilium</strong>, un grupo de plantas con flores de la familia <strong>Liliaceae</strong>.</p>
        <p>Son plantas herbáceas perennes que crecen a partir de <strong>bulbos</strong>. Sus flores pueden presentar una gran variedad de formas y colores, desde blancos y amarillos hasta rosas, naranjas y tonos rojizos.</p>
        <p>Las especies de <strong>Lilium</strong> son originarias principalmente del hemisferio norte y se encuentran en distintas regiones de Asia, Europa y América del Norte.</p>
      </div>
    </div>
  </div>
</section>

<section class="features" id="caracteristicas">
  <div class="container">
    <div class="section-tag">02 · A simple vista</div>
    <h2 class="section-title">Características principales</h2>
    <p class="section-intro">Aunque existen muchas especies y variedades, los lirios comparten varias características que los hacen fáciles de reconocer.</p>
    <div class="feature-grid">
      <article class="feature reveal"><div class="feature-icon">🌱</div><h3>Tipo de planta</h3><p>Son plantas herbáceas perennes que desarrollan un bulbo subterráneo.</p></article>
      <article class="feature reveal"><div class="feature-icon">🌸</div><h3>Floración</h3><p>Producen flores grandes y llamativas, generalmente con seis tépalos.</p></article>
      <article class="feature reveal"><div class="feature-icon">🎨</div><h3>Colores</h3><p>Existen flores blancas, amarillas, rosadas, naranjas, rojas y combinadas.</p></article>
      <article class="feature reveal"><div class="feature-icon">🌿</div><h3>Hojas</h3><p>Sus hojas suelen ser alargadas y se distribuyen a lo largo del tallo.</p></article>
    </div>
  </div>
</section>

<section id="tipos">
  <div class="container">
    <div class="section-tag">03 · Diversidad</div>
    <h2 class="section-title">Tipos de lirios</h2>
    <p class="section-intro">Dentro del género <em>Lilium</em> encontramos especies y grupos con formas, colores y aromas muy diferentes.</p>
    <div class="types-grid">
      <article class="type-card reveal">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSUg5fa7sVVEZAh8yq3qN2rFwM7xbpQ-G7MMRyvD5vHVA&s=10" alt="Lirio asiático">
        <div class="type-content"><h3>Lirios asiáticos</h3><p>Destacan por sus colores intensos y gran variedad de formas. Muchas variedades no tienen un aroma fuerte.</p><span class="pill">Coloridos</span></div>
      </article>
      <article class="type-card reveal">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQFJrzdHEZwZwUWIGldkksGsmPNTAJg70RKyVeMuzvmVQ&s=10" alt="Flores de jardín">
        <div class="type-content"><h3>Lirios orientales</h3><p>Suelen tener flores grandes y fragantes, con tonos blancos, rosados y combinaciones llamativas.</p><span class="pill">Aromáticos</span></div>
      </article>
      <article class="type-card reveal">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRFrR6a3ySgbSN0PUhvJ0vI1hQfankd9g9RcTm8tDMYHg&s=10" alt="Flores rosadas">
        <div class="type-content"><h3>Lirios trompeta</h3><p>Sus flores tienen forma alargada y tubular, y muchas variedades desprenden una fragancia notable.</p><span class="pill">Elegantes</span></div>
      </article>
    </div>
  </div>
</section>

<section class="facts" id="datos">
  <div class="container">
    <div class="section-tag">04 · ¿Sabías que...?</div>
    <h2 class="section-title">Datos interesantes</h2>
    <p class="section-intro">Pequeños detalles que hacen todavía más interesante conocer a estas flores.</p>
    <div class="facts-grid">
      <article class="fact reveal"><div class="fact-number">01</div><h3>No todos los “lirios” son Lilium</h3><p>En el lenguaje común, muchas plantas reciben el nombre de lirio, aunque no pertenezcan al género botánico Lilium.</p></article>
      <article class="fact reveal"><div class="fact-number">02</div><h3>Crecen desde un bulbo</h3><p>El bulbo almacena nutrientes y permite que la planta vuelva a crecer en la siguiente temporada.</p></article>
      <article class="fact reveal"><div class="fact-number">03</div><h3>Son importantes para polinizadores</h3><p>Sus flores pueden ofrecer recursos a distintos visitantes, especialmente insectos que buscan néctar o polen.</p></article>
      <article class="fact reveal"><div class="fact-number">04</div><h3>Una flor con mucha historia</h3><p>Los lirios han aparecido durante siglos en arte, jardines, literatura y tradiciones de distintas culturas.</p></article>
    </div>
  </div>
</section>

<section id="cuidados">
  <div class="container care-grid">
    <div class="care-image reveal">
      <img src="https://lafloreria.ec/img/cms/arreglo%20con%20lirios%20blancos.jpg" alt="Flores en un jardín">
    </div>
    <div class="reveal">
      <div class="section-tag">05 · Jardinería</div>
      <h2 class="section-title">Cuidados básicos</h2>
      <p class="section-intro">Con algunas condiciones adecuadas, los lirios pueden convertirse en protagonistas del jardín.</p>
      <div class="care-list">
        <div class="care-item"><span>☀️</span><div><h3>Luz</h3><p>Prefieren buena iluminación. Algunas variedades toleran sol directo y otras agradecen cierta protección.</p></div></div>
        <div class="care-item"><span>💧</span><div><h3>Riego</h3><p>Mantén el suelo ligeramente húmedo, evitando el exceso de agua y el encharcamiento.</p></div></div>
        <div class="care-item"><span>🌿</span><div><h3>Suelo</h3><p>Un suelo fértil y con buen drenaje ayuda a mantener raíces y bulbos en buenas condiciones.</p></div></div>
        <div class="care-item"><span>✂️</span><div><h3>Mantenimiento</h3><p>Retira flores marchitas y deja que el follaje se conserve hasta que complete su ciclo natural.</p></div></div>
      </div>
    </div>
  </div>
</section>

<section class="meaning" id="significado">
  <div class="container meaning-box reveal">
    <div class="meaning-symbol">✿</div>
    <div class="section-tag">06 · Simbolismo</div>
    <h2 class="section-title">¿Qué significan los lirios?</h2>
    <p>El significado de los lirios cambia según la cultura, la época y el color. De manera tradicional, se han asociado con ideas como pureza, belleza, renovación y elegancia.</p>
    <div class="meaning-tags">
      <span>Pureza</span><span>Elegancia</span><span>Renovación</span><span>Belleza</span><span>Esperanza</span>
    </div>
  </div>
</section>

<section class="gallery" id="galeria">
  <div class="container">
    <div class="section-tag">07 · Galería</div>
    <h2 class="section-title">Un vistazo a su belleza</h2>
    <p class="section-intro">La diversidad de formas y colores convierte a los lirios en una de las flores más atractivas para jardines y arreglos florales.</p>
    <div class="gallery-grid">
      <div class="gallery-item"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTK2Cb0kX67dtwYvQ035VwLGRH3DSuAoTOMfXUatx7_-Q&s=10" alt="Lirio blanco"></div>
      <div class="gallery-item"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRSt6aHB5Sp8n12GlJEfR0Hkc6NSClEa0HbQ-t9KsTfTA&s=10" alt="Flores coloridas"></div>
      <div class="gallery-item"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQymaZomuXpBavCBBqfy-UYl9bFHvrzXrahL2LaWSlcfg&s=10" alt="Flores de jardín"></div>
      <div class="gallery-item"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTXQUZxab_3rKfmEWwlMF9rQyYERBDIQkCVtZoqCd4rTQ&s=10" alt="Flores rosadas"></div>
      <div class="gallery-item"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRrA59zVw-qDlCo39uhWeb6Yj7zq1-ZEo5JHv-buhgmWQ&s=10" alt="Flores naturales"></div>
    </div>
    <div class="cta">
      <div><h2>La naturaleza también cuenta historias.</h2><p>Cada lirio guarda una combinación distinta de forma, color, aroma y significado.</p></div>
      <a href="#inicio" class="btn">Volver al inicio ↑</a>
    </div>
  </div>
</section>
</main>

<footer>
  <div class="container footer-inner">
    <strong>Lilium ✿</strong>
    <p>Guía interactiva sobre los lirios · Diseño educativo y natural</p>
  </div>
</footer>

<button id="topBtn" aria-label="Volver arriba">↑</button>

<script>
const menuBtn = document.querySelector('.menu-btn');
const navLinks = document.querySelector('.nav-links');

menuBtn.addEventListener('click', () => {
  navLinks.classList.toggle('open');
  menuBtn.textContent = navLinks.classList.contains('open') ? '✕' : '☰';
});

document.querySelectorAll('.nav-links a').forEach(link => {
  link.addEventListener('click', () => {
    navLinks.classList.remove('open');
    menuBtn.textContent = '☰';
  });
});

const revealObserver = new IntersectionObserver((entries) => {
  entries.forEach(entry => {
    if(entry.isIntersecting){
      entry.target.classList.add('visible');
      revealObserver.unobserve(entry.target);
    }
  });
}, {threshold:0.12});

document.querySelectorAll('.reveal').forEach(el => revealObserver.observe(el));

const topBtn = document.getElementById('topBtn');
window.addEventListener('scroll', () => {
  topBtn.classList.toggle('show', window.scrollY > 500);
});
topBtn.addEventListener('click', () => window.scrollTo({top:0, behavior:'smooth'}));
</script>

</body>
</html>
