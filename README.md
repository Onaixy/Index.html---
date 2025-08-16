# Index.html---

html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Onaixy.com - AI Future Platform</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0f172a;
      color: #f8fafc;
      text-align: center;
    }
    header {
      background: linear-gradient(90deg, #3b82f6, #06b6d4);
      padding: 20px;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
      color: #fff;
    }
    nav {
      margin-top: 10px;
    }
    nav a {
      margin: 0 15px;
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      padding: 60px 20px;
    }
    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 15px;
    }
    .hero p {
      font-size: 1.2rem;
      color: #cbd5e1;
    }
    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 24px;
      border-radius: 8px;
      background: #3b82f6;
      color: #fff;
      text-decoration: none;
      font-size: 1rem;
      transition: 0.3s;
    }
    .btn:hover {
      background: #2563eb;
    }
    footer {
      margin-top: 50px;
      padding: 20px;
      background: #1e293b;
      color: #94a3b8;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>🚀 Onaixy.com</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Features</a>
      <a href="#">Membership</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Welcome to the Future of AI 🌍</h2>
    <p>
      Onaixy.com is your all-in-one AI ecosystem with security, innovation, and future-proof tools.
    </p>
    <a href="#" class="btn">Get Started</a>
  </section>

  <footer>
    <p>© 2025 Onaixy.com | Powered by AI & Innovation</p>
  </footer>
</body>
</html>
/ (repo root)
├─ index.html
└─ assets/
   ├─ style.css
   └─ script.js
   <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Onaixy — AI Tools Ecosystem</title>
  <meta name="description" content="Onaixy: World-class AI ecosystem — secure, future-ready." />
  <link rel="stylesheet" href="assets/style.css" />
</head>
<body>
  <!-- NAV -->
  <header class="nav-wrap">
    <nav class="nav">
      <a class="logo" href="./" aria-label="Onaixy home">Onaixy</a>

      <button class="burger" aria-label="Open menu" aria-expanded="false" aria-controls="mobileMenu">☰</button>

      <ul class="menu">
        <li><a href="index.html" data-nav="home">Home</a></li>
        <li><a href="tools.html" data-nav="tools">Tools</a></li>
        <li><a href="about.html" data-nav="about">About</a></li>
        <li><a href="contact.html" data-nav="contact">Contact</a></li>
        <li><a href="pro.html" data-nav="pro">Pro</a></li>
        <li><a class="btn" href="login.html" data-nav="login">Login</a></li>
      </ul>
    </nav>

    <!-- Mobile dropdown -->
    <div id="mobileMenu" class="mobile">
      <a href="index.html" data-nav="home">Home</a>
      <a href="tools.html" data-nav="tools">Tools</a>
      <a href="about.html" data-nav="about">About</a>
      <a href="contact.html" data-nav="contact">Contact</a>
      <a href="pro.html" data-nav="pro">Pro</a>
      <a class="btn" href="login.html" data-nav="login">Login</a>
    </div>
  </header>

  <!-- HERO -->
  <main class="container">
    <section class="hero">
      <p class="badge">Budget-friendly Launch · ₹12,000 Ready</p>
      <h1>Welcome to <span class="grad">Onaixy</span></h1>
      <p class="sub">World-class AI ecosystem — Secure · Future-Ready · Global</p>
      <div class="actions">
        <a class="btn" href="tools.html">Explore Tools</a>
        <a class="ghost" href="pro.html">Go Pro</a>
      </div>
    </section>

    <!-- FEATURES -->
    <section class="grid">
      <article class="card">
        <h3>⚡ AI Tools</h3>
        <p>EmotionToon™, TheaterFusion™ और और भी smart utilities—ready to expand.</p>
      </article>
      <article class="card">
        <h3>🛡️ Security</h3>
        <p>Onaixy Shield™, Quantum Safety Net™, Invisible Threat Cloak™ (roadmap).</p>
      </article>
      <article class="card">
        <h3>🌍 Multilingual</h3>
        <p>Hindi + English UI; i18n JSON से आगे scale करना आसान.</p>
      </article>
      <article class="card">
        <h3>🚀 Growth</h3>
        <p>Turning Points — Knowledge Hub, learn → build → grow.</p>
      </article>
    </section>
  </main>

  <!-- FOOTER -->
  <footer class="footer">
    <p>© <span id="year"></span> Onaixy · Built for the Future</p>
    <p><a href="privacy.html">Privacy</a> · <a href="terms.html">Terms</a></p>
  </footer>

  <script src="assets/script.js"></script>
</body>
</html>
:root{
  --bg:#0f172a; --panel:#111827; --card:#0b1222;
  --text:#e5e7eb; --muted:#9ca3af;
  --brand:#5b7cfa; --brand2:#22d3ee;
}

*{box-sizing:border-box}
html,body{margin:0}
body{
  font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  color:var(--text);
  background:
    radial-gradient(1200px 600px at 10% -10%, rgba(91,124,250,.25), transparent 40%),
    radial-gradient(900px 400px at 110% 0%, rgba(34,211,238,.25), transparent 30%),
    var(--bg);
}

/* NAV */
.nav-wrap{position:sticky; top:0; z-index:10; backdrop-filter: blur(8px); background: rgba(15,23,42,.6); border-bottom:1px solid rgba(255,255,255,.06)}
.nav{max-width:1100px; margin:auto; padding:12px 16px; display:flex; align-items:center; justify-content:space-between; gap:12px}
.logo{font-weight:800; color:#fff; text-decoration:none; font-size:1.25rem; letter-spacing:.3px}
.menu{list-style:none; display:flex; align-items:center; gap:12px; margin:0; padding:0}
.menu a{color:var(--text); text-decoration:none; padding:8px 12px; border-radius:10px}
.menu a:hover, .menu a.active{background: rgba(255,255,255,.08)}
.btn{background: linear-gradient(135deg, var(--brand), var(--brand2)); color:#fff !important; border-radius:10px}
.burger{display:none; background:transparent; color:var(--text); border:1px solid rgba(255,255,255,.18); padding:8px 10px; border-radius:10px}
.mobile{display:none; border-top:1px solid rgba(255,255,255,.06); background: rgba(15,23,42,.95)}
.mobile a{display:block; padding:12px 16px; color:var(--text); text-decoration:none}
.mobile a + a{border-top:1px solid rgba(255,255,255,.06)}

/* HERO */
.container{max-width:1100px; margin:0 auto; padding:22px 16px}
.hero{text-align:center; padding:36px 8px}
.badge{display:inline-block; padding:6px 10px; border-radius:999px; background:rgba(91,124,250,.12); color:#cdd6ff; border:1px solid rgba(91,124,250,.35); font-size:.85rem}
.hero h1{font-size:clamp(28px,6vw,44px); margin:12px 0 6px}
.grad{background: linear-gradient(90deg, var(--brand), var(--brand2)); -webkit-background-clip:text; color:transparent}
.sub{color:var(--muted)}
.actions{display:flex; gap:10px; justify-content:center; margin-top:14px}
.ghost{border:1px solid rgba(255,255,255,.18); border-radius:10px; padding:8px 12px; color:var(--text); text-decoration:none}

/* GRID */
.grid{display:grid; grid-template-columns: repeat(12, 1fr); gap:14px; margin-top:26px}
.card{grid-column: span 6; background:linear-gradient(180deg, rgba(255,255,255,.04), rgba(255,255,255,.02)); border:1px solid rgba(255,255,255,.06); padding:18px; border-radius:16px}
.card h3{margin:0 0 6px}

/* FOOTER */
.footer{border-top:1px solid rgba(255,255,255,.08); padding:18px; text-align:center; color:var(--muted); margin-top:26px}

/* Responsive */
@media (max-width: 840px){
  .menu{display:none}
  .burger{display:inline-flex}
  .mobile.show{display:block}
  .card{grid-column: span 12}
}
// active link highlight (both desktop & mobile menus)
(function(){
  const path = (location.pathname.split('/').pop() || 'index.html').toLowerCase();
  const links = document.querySelectorAll('[data-nav]');
  links.forEach(a=>{
    const href = (a.getAttribute('href') || '').toLowerCase();
    if(href.endsWith(path)) a.classList.add('active');
  });
})();

// mobile menu toggle
(function(){
  const btn = document.querySelector('.burger');
  const menu = document.getElementById('mobileMenu');
  if(!btn || !menu) return;
  btn.addEventListener('click', ()=>{
    const open = menu.classList.toggle('show');
    btn.setAttribute('aria-expanded', open ? 'true' : 'false');
  });
})();

// footer year
document.getElementById('year') && (document.getElementById('year').textContent = new Date().getFullYear());
