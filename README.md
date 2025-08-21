<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Cristiano Ronaldo | Fan Site</title>
  <meta name="description" content="Sitio de fans de Cristiano Ronaldo. Biografía, logros, galería y cronología. Hecho por Dilan Geovanny Romero." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0b0f17; --card:#111827; --muted:#94a3b8; --text:#e5e7eb; --accent:#22d3ee; --accent2:#60a5fa; --ring: rgba(34,211,238,.4);
    }
    *{box-sizing:border-box}
    html,body{margin:0; padding:0; background: radial-gradient(1200px 600px at 10% 0%, #0f172a 0%, #0b0f17 60%), #0b0f17; color:var(--text); font-family:Poppins, system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, Cantarell, 'Helvetica Neue', Arial, 'Noto Sans', 'Apple Color Emoji','Segoe UI Emoji', 'Segoe UI Symbol';}
    a{color:var(--accent); text-decoration:none}
    header{
      position:relative; overflow:hidden; isolation:isolate;
      background:linear-gradient(120deg, rgba(34,211,238,.15), transparent 40%),
                 linear-gradient(320deg, rgba(96,165,250,.15), transparent 50%);
      border-bottom:1px solid rgba(148,163,184,.15);
    }
    .container{max-width:1100px; margin:0 auto; padding:24px}
    .nav{display:flex; align-items:center; justify-content:space-between; gap:16px}
    .brand{display:flex; align-items:center; gap:10px; font-weight:800; letter-spacing:.5px}
    .brand .ball{width:32px; height:32px; border-radius:50%; background:conic-gradient(from 0deg, var(--accent), var(--accent2)); box-shadow:0 0 0 6px rgba(34,211,238,.12), 0 8px 30px rgba(96,165,250,.25)}
    .nav a{padding:8px 12px; border-radius:12px;}
    .nav a:hover{background:rgba(148,163,184,.08)}

    .hero{display:grid; grid-template-columns:1.2fr .8fr; gap:28px; padding:56px 24px 64px}
    .hero h1{font-size:clamp(28px, 6vw, 56px); line-height:1.05; margin:0 0 12px}
    .hero p{color:var(--muted); margin:0 0 24px}
    .cta{display:flex; gap:12px; flex-wrap:wrap}
    .btn{padding:12px 16px; border-radius:14px; font-weight:600; border:1px solid rgba(148,163,184,.25); cursor:pointer; background:#0b1220; color:var(--text)}
    .btn.primary{background:linear-gradient(90deg, var(--accent), var(--accent2)); color:#0b0f17; border:0}
    .btn:focus{outline:3px solid var(--ring)}

    .card{background:linear-gradient(180deg, rgba(255,255,255,.02), rgba(255,255,255,.0)); border:1px solid rgba(148,163,184,.16); border-radius:22px; padding:20px; box-shadow:0 8px 30px rgba(2,8,23,.35)}
    .grid{display:grid; gap:16px}
    .stats{grid-template-columns:repeat(4,1fr)}
    .stat{display:flex; flex-direction:column; align-items:flex-start}
    .stat .n{font-size:28px; font-weight:800}
    .stat .l{color:var(--muted); font-size:13px}

    .section{padding:40px 24px}
    h2{font-size:28px; margin:0 0 16px}
    h3{margin:8px 0 6px}

    .timeline{position:relative}
    .timeline:before{content:""; position:absolute; left:10px; top:0; bottom:0; width:2px; background:linear-gradient(180deg, var(--accent), transparent)}
    .titem{position:relative; padding-left:36px; margin:16px 0}
    .titem:before{content:""; position:absolute; left:4px; top:4px; width:12px; height:12px; border-radius:50%; background:var(--accent)}
    .titem small{color:var(--muted)}

    .gallery{display:grid; grid-template-columns:repeat(3,1fr); gap:10px}
    .gallery img{width:100%; height:180px; object-fit:cover; border-radius:16px; border:1px solid rgba(148,163,184,.2); cursor:pointer}

    .achievements{display:grid; grid-template-columns:repeat(3,1fr); gap:16px}
    .achievements .card{min-height:120px}

    footer{border-top:1px solid rgba(148,163,184,.15); padding:24px}
    .made{color:var(--muted)}

    /* Responsive */
    @media (max-width: 900px){
      .hero{grid-template-columns:1fr; padding-top:36px}
      .stats{grid-template-columns:repeat(2,1fr)}
      .achievements{grid-template-columns:1fr 1fr}
      .gallery{grid-template-columns:1fr 1fr}
    }
    @media (max-width: 520px){
      .stats{grid-template-columns:1fr 1fr}
      .achievements{grid-template-columns:1fr}
      .gallery{grid-template-columns:1fr}
    }
  </style>
</head>
<body>
  <header>
    <div class="container nav">
      <div class="brand"><div class="ball"></div> <span>CR7 • Fan Site</span></div>
      <nav>
        <a href="#bio">Biografía</a>
        <a href="#logros">Logros</a>
        <a href="#galeria">Galería</a>
      </nav>
    </div>
    <div class="container hero">
      <div>
        <h1>Cristiano Ronaldo</h1>
        <p>
          Atleta de élite, profesional ejemplar y una leyenda del fútbol moderno. Con una ética de trabajo
          incomparable, Cristiano ha redefinido los límites del rendimiento, la longevidad y la mentalidad ganadora.
        </p>
        <div class="cta">
          <a class="btn primary" href="#bio">Conocer su historia</a>
          <a class="btn" href="#galeria">Ver galería</a>
        </div>
        <div class="grid stats" style="margin-top:22px">
          <div class="card stat"><span class="n">5</span><span class="l">Balones de Oro</span></div>
          <div class="card stat"><span class="n">5</span><span class="l">UEFA Champions League</span></div>
          <div class="card stat"><span class="n">+800</span><span class="l">Goles oficiales</span></div>
          <div class="card stat"><span class="n">200+</span><span class="l">Partidos con Portugal</span></div>
        </div>
      </div>
      <div class="card" aria-hidden="true" style="display:grid; place-items:center; min-height:280px; background:radial-gradient(120px 120px at 30% 30%, rgba(34,211,238,.25), transparent 60%), radial-gradient(160px 140px at 70% 60%, rgba(96,165,250,.25), transparent 60%)">
        <svg width="220" height="220" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" aria-label="Balón de fútbol">
          <circle cx="12" cy="12" r="10" stroke="currentColor" opacity=".5" />
          <polygon points="12,7 9,9 10,12 14,12 15,9" fill="currentColor" opacity=".4"></polygon>
          <path d="M12 2v5M12 17v5M2 12h5M17 12h5M5 5l3 4M19 5l-3 4M5 19l3-4M19 19l-3-4" stroke="currentColor" opacity=".4" />
        </svg>
      </div>
    </div>
  </header>

  <main>
    <section id="bio" class="section container">
      <h2>Biografía</h2>
      <div class="grid" style="grid-template-columns:1.1fr .9fr; gap:18px">
        <div class="card">
          <h3>Origen y primeros años</h3>
          <p>
            Cristiano Ronaldo dos Santos Aveiro nació el 5 de febrero de 1985 en Funchal, Madeira, Portugal.
            Inició su carrera en el <strong>Sporting CP</strong>, donde su talento llamó la atención del
            <strong>Manchester United</strong>, club con el que conquistó sus primeros títulos europeos.
          </p>
          <h3>Consagración</h3>
          <p>
            En el <strong>Real Madrid</strong> se convirtió en una superestrella global, rompiendo récords de goles
            y levantando múltiples <em>UEFA Champions League</em>. Posteriormente jugó en la <strong>Juventus</strong>,
            regresó al <strong>Manchester United</strong> y actualmente compite al más alto nivel en <strong>Al Nassr</strong>.
          </p>
          <h3>Selección de Portugal</h3>
          <p>
            Capitán y máximo referente de su país, lideró a Portugal para ganar la <strong>Eurocopa 2016</strong>
            y la <strong>UEFA Nations League 2019</strong>.
          </p>
        </div>
        <aside class="card">
          <h3>Perfil rápido</h3>
          <ul style="list-style:none; padding-left:0; margin:0">
            <li>🇵🇹 Nacionalidad: Portuguesa</li>
            <li>🎂 Nacimiento: 5/02/1985</li>
            <li>📍 Lugar: Funchal, Madeira</li>
            <li>🦵 Posición: Delantero</li>
            <li>⚡ Fortalezas: definición, salto, tiro, mentalidad</li>
          </ul>
        </aside>
      </div>
    </section>

    <section id="logros" class="section container">
      <h2>Logros destacados</h2>
      <div class="achievements">
        <div class="card"><h3>5× Balón de Oro</h3><p>Reconocido entre los mejores futbolistas del mundo durante más de una década.</p></div>
        <div class="card"><h3>5× UEFA Champions League</h3><p>Protagonista en la competición de clubes más exigente del planeta.</p></div>
        <div class="card"><h3>Campeón de Europa (2016)</h3><p>Título histórico con la selección de Portugal.</p></div>
        <div class="card"><h3>Máximo goleador en UCL</h3><p>Referente de eficacia en noches europeas.</p></div>
        <div class="card"><h3>Máximo con selecciones</h3><p>Centenas de goles y partidos internacionales.</p></div>
        <div class="card"><h3>UEFA Nations League (2019)</h3><p>Primer campeón del nuevo torneo europeo de selecciones.</p></div>
      </div>
    </section>

    <section class="section container">
      <h2>Cronología</h2>
      <div class="card timeline">
        <div class="titem"><small>2002–2003</small><div><strong>Sporting CP</strong> • Debut profesional</div></div>
        <div class="titem"><small>2003–2009</small><div><strong>Manchester United</strong> • 3× Premier League, 1× UCL</div></div>
        <div class="titem"><small>2009–2018</small><div><strong>Real Madrid</strong> • Era dorada, 4× UCL</div></div>
        <div class="titem"><small>2018–2021</small><div><strong>Juventus</strong> • Serie A y récords</div></div>
        <div class="titem"><small>2021–2022</small><div><strong>Manchester United</strong> • Regreso</div></div>
        <div class="titem"><small>2023–Actualidad</small><div><strong>Al Nassr</strong> • Goles y liderazgo</div></div>
      </div>
    </section>

    <section id="galeria" class="section container">
      <h2>Galería</h2>
      <p class="made" style="margin-top:-6px">Imágenes de ejemplo libres: reemplázalas por tus fotos favoritas de CR7 pegando URLs en el código.</p>
      <div class="gallery">
        <img src="https://images.unsplash.com/photo-1517927033932-b3d18e61fb3a?q=80&w=1200&auto=format&fit=crop" alt="Balón en cancha" />
        <img src="https://images.unsplash.com/photo-1508098682722-e99c43a406b2?q=80&w=1200&auto=format&fit=crop" alt="Estadio iluminado" />
        <img src="https://images.unsplash.com/photo-1471295253337-3ceaaedca402?q=80&w=1200&auto=format&fit=crop" alt="Botas de fútbol" />
      </div>
    </section>
  </main>

  <footer class="container">
    <div class="made">Hecho por <strong>Dilan Geovanny Romero</strong> • Sitio de fans sin afiliación oficial.</div>
  </footer>

  <script>
    // Scroll suave para los enlaces del header
    document.querySelectorAll('a[href^="#"]').forEach(a=>{
      a.addEventListener('click', e=>{
        const target = document.querySelector(a.getAttribute('href'));
        if(target){ e.preventDefault(); target.scrollIntoView({behavior:'smooth', block:'start'}); }
      });
    });

    // Ampliar imágenes simples (modal minimalista)
    const images = document.querySelectorAll('.gallery img');
    const modal = document.createElement('div');
    modal.style.cssText = 'position:fixed; inset:0; background:rgba(0,0,0,.8); display:none; align-items:center; justify-content:center; padding:16px; z-index:50';
    const big = document.createElement('img');
    big.style.cssText = 'max-width:90vw; max-height:85vh; border-radius:16px; border:1px solid rgba(148,163,184,.25)';
    modal.appendChild(big);
    modal.addEventListener('click', ()=> modal.style.display='none');
    document.body.appendChild(modal);
    images.forEach(img=> img.addEventListener('click', ()=>{ big.src = img.src; big.alt = img.alt; modal.style.display='flex'; }));
  </script>
</body>
</html>


