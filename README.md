# <!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Prénom Nom — Mathématicien·ne</title>
  <meta name="description" content="Page personnelle de Prénom Nom — chercheur·se en mathématiques">

  <link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Serif:ital,wght@0,400;0,600;1,400&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
  <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

  <style>
    :root{
      --bg: #fbfbfb;
      --card: #ffffff;
      --text: #111214;
      --muted: #5b6166;
      --accent: #0b6e99;
      --accent-2: #8a2be2;
      --glass: rgba(11,110,153,0.06);
      --radius: 12px;
      font-family: 'Inter', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    body{
      margin:0; background:linear-gradient(180deg,var(--bg),#f3f6f8 60%);
      color:var(--text); line-height:1.5; padding:48px; display:flex; justify-content:center;
    }
    .wrap{width:min(1100px,96%);}
    header{display:flex; gap:24px; align-items:center; margin-bottom:28px;}
    .avatar{width:84px; height:84px; border-radius:12px; background:linear-gradient(135deg,var(--accent),var(--accent-2)); display:flex; align-items:center; justify-content:center; color:white; font-weight:700; font-family:'IBM Plex Serif'; font-size:28px;}
    .meta h1{margin:0; font-family:'IBM Plex Serif'; font-weight:600; font-size:22px}
    .meta p.role{margin:6px 0 0; color:var(--muted);}
    nav{margin-left:auto;}
    nav a{color:var(--muted); text-decoration:none; margin-left:18px; font-weight:600}
    nav a:hover{color:var(--text);}
    main{display:grid; grid-template-columns: 2fr 1fr; gap:22px; align-items:start}
    .card{background:var(--card); border-radius:var(--radius); padding:20px; box-shadow:0 6px 20px rgba(16,24,40,0.04)}
    .section-title{font-family:'IBM Plex Serif'; margin:0 0 10px; font-size:18px}
    footer{margin-top:26px; color:var(--muted); font-size:13px; text-align:center}
    @media (max-width:900px){main{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="avatar">PN</div>
      <div class="meta">
        <h1>Prénom Nom</h1>
        <p class="role">Titre / Fonction</p>
      </div>
      <nav>
        <!-- Exemple : <a href="#recherche">Recherche</a> -->
      </nav>
    </header>

    <main>
      <section class="card">
        <h2 class="section-title">Section principale</h2>
        <!-- Ici, vous pouvez ajouter vos paragraphes de présentation, vos formules (ex: \(x^2+y^2=z^2\)), ou vos projets. -->
      </section>

      <aside class="card">
        <h3 class="section-title">Encadré latéral</h3>
        <!-- Exemple : informations de contact, liens externes, CV, etc. -->
      </aside>
    </main>

    <footer>
      <p>© Prénom Nom — dernière mise à jour : octobre 2025</p>
    </footer>
  </div>
</body>
</html>
