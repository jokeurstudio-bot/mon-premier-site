<!doctype html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mon Site Vitrine</title>
  <link rel="stylesheet" href="assets/css/style.css" />
</head>
<body>
  <header class="header">
    <div class="container header__inner">
      <a class="brand" href="index.html">MonSite</a>

      <button class="menu-btn" aria-label="Ouvrir le menu" aria-expanded="false" type="button">
        ☰
      </button>

      <nav class="nav" aria-label="Navigation principale">
        <a class="nav__link" href="index.html">Accueil</a>
        <a class="nav__link" href="about.html">À propos</a>
        <a class="nav__link" href="contact.html">Contact</a>
      </nav>
    </div>
  </header>

  <main>
    <section class="hero">
      <div class="container hero__grid">
        <div>
          <p class="tag">Vitrine • Simple • Rapide</p>
          <h1>Présentez votre activité, clairement.</h1>
          <p class="lead">
            Un site vitrine moderne et responsive : pages essentielles, design propre,
            et navigation fluide.
          </p>
          <div class="hero__actions">
            <a class="btn btn--primary" href="contact.html">Demander un devis</a>
            <a class="btn btn--ghost" href="about.html">En savoir plus</a>
          </div>
        </div>

        <div class="card card--accent">
          <h2 class="card__title">Ce que vous obtenez</h2>
          <ul class="checks">
            <li>Design responsive (mobile/desktop)</li>
            <li>Sections prêtes à remplir</li>
            <li>Menu mobile</li>
            <li>Hébergement via GitHub Pages</li>
          </ul>
        </div>
      </div>
    </section>

    <section class="container section">
      <h2 class="section__title">Pourquoi choisir votre entreprise ?</h2>

      <div class="features">
        <article class="feature">
          <h3>Clarté</h3>
          <p>Des messages courts pour convaincre vite.</p>
        </article>
        <article class="feature">
          <h3>Confiance</h3>
          <p>Une page À propos structurée et crédible.</p>
        </article>
        <article class="feature">
          <h3>Contact</h3>
          <p>Un formulaire simple (sans backend) + info claire.</p>
        </article>
      </div>
    </section>
  </main>

  <footer class="footer">
    <div class="container footer__inner">
      <p>© <span id="year"></span> MonSite. Tous droits réservés.</p>
      <p class="muted">Fait pour GitHub Pages.</p>
    </div>
  </footer>

  <script src="assets/js/main.js"></script>
</body>
</html>
