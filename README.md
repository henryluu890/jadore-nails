<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>J'adore Nails & Massages</title>
  <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@400;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --green: #2ecc71;
      --blue: #3498db;
      --white: #ffffff;
      --light: #f4fefe;
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      font-family: 'Quicksand', sans-serif;
      background: var(--light);
      color: #333;
    }

    /* === HERO HEADER === */
    header {
      height: 75vh;
      background: linear-gradient(rgba(52,152,219,0.45), rgba(46,204,113,0.45)), url('https://images.unsplash.com/photo-1602126046951-0af5ca97a7e8?auto=format&fit=crop&w=1600&q=80') center/cover no-repeat fixed;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: var(--white);
      padding: 0 20px;
    }

    header h1 {
      font-size: 2.5rem;
      margin: 0 0 10px;
      font-weight: 600;
      text-shadow: 0 2px 4px rgba(0,0,0,0.25);
    }

    header p {
      font-size: 1.1rem;
      margin: 5px 0;
      text-shadow: 0 1px 3px rgba(0,0,0,0.2);
    }

    /* === NAVIGATION === */
    nav {
      position: sticky;
      top: 0;
      z-index: 100;
      background: rgba(52,152,219,0.9);
      padding: 12px 0;
      text-align: center;
      backdrop-filter: blur(4px);
    }

    nav a {
      color: var(--white);
      margin: 0 18px;
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s;
    }

    nav a:hover {
      color: var(--green);
    }

    /* === SECTIONS === */
    section {
      padding: 60px 20px;
      max-width: 1100px;
      margin: auto;
      background: var(--white);
      border-radius: 16px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.05);
      margin-bottom: 40px;
    }

    section h2 {
      color: var(--blue);
      margin-top: 0;
      font-size: 1.8rem;
    }

    .cta {
      background: linear-gradient(135deg, rgba(46,204,113,0.15), rgba(52,152,219,0.15));
      border: 1px solid rgba(52,152,219,0.25);
      padding: 24px;
      border-radius: 12px;
    }

    /* === FOOTER === */
    footer {
      background: var(--blue);
      color: var(--white);
      text-align: center;
      padding: 25px 10px;
    }

    /* === INSTAGRAM LINK === */
    .insta {
      text-align: center;
      margin: 30px 0 10px;
    }

    .insta a {
      color: var(--green);
      font-weight: 600;
      transition: color 0.3s;
    }

    .insta a:hover {
      color: var(--blue);
      text-decoration: underline;
    }

    /* === RESPONSIVE === */
    @media (max-width: 600px) {
      header h1 {font-size: 1.8rem;}
      nav a {margin: 0 10px;}
      section {padding: 40px 16px;}
    }
  </style>
</head>
<body>
  <!-- HERO HEADER -->
  <header>
    <h1>J'adore Nails & Massages <span style="color:#ff66b2;">❤</span></h1>
    <p>Pour des ongles impeccables et des instants de pure détente</p>
    <p>📍 Av de l’église Saint-Julien 2 – 📞 (32) 470 94 87 07</p>
  </header>

  <!-- NAVIGATION -->
  <nav>
    <a href="#ongles">Ongles</a>
    <a href="#spa">Massages</a>
    <a href="#horaires">Horaires</a>
    <a href="#tarifs">Tarifs</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- CONTENT SECTIONS -->
  <section id="ongles">
    <h2>Nail Art & Soins</h2>
    <p>Vous retrouverez à J’adore Nails une multitude de couleurs laissant place à vos envies. Laissez s’exprimer votre créativité et optez pour le nail art digne des plus grands nails artistes.</p>
  </section>

  <section id="spa">
    <h2>Spa & Massages</h2>
    <p>Embarquez pour un voyage vers la zen-attitude ! En solo, en duo ou entre ami·es, découvrez nos soins des mains et massages dans un cadre apaisant.</p>
  </section>

  <section id="horaires">
    <h2>Horaires d'ouverture</h2>
    <ul>
      <li>Lundi - Samedi : 10h - 18h</li>
      <li>Dimanche : fermé</li>
    </ul>
    <div class="cta">
      <strong>Jours fériés :</strong> Nous sommes exceptionnellement fermés certains jours fériés. <br>
      <em>Vous pouvez ajouter les dates ici manuellement :</em><br>
      <ul>
        <li>15 août – Assomption</li>
        <!-- Ajoutez ou modifiez ici -->
      </ul>
    </div>
  </section>

  <section id="tarifs">
    <h2>Services & Tarifs</h2>
    <p>Consultez notre grille tarifaire complète sur notre page dédiée. Vous pouvez modifier ce contenu à tout moment.</p>
    <ul>
      <li>Nail Art – À partir de 30€</li>
      <li>Soin des mains – À partir de 25€</li>
      <li>Massage relaxant – À partir de 40€</li>
      <!-- Vous pouvez ajouter vos propres lignes ici -->
    </ul>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>📍 Adresse : Av de l’église Saint-Julien 2, 1160 Auderghem</p>
    <p>📞 Téléphone : (32) 470 94 87 07 (Appels et messages)</p>
  </section>

  <div class="insta">
    <p>📸 Suivez-nous sur Instagram : <a href="https://www.instagram.com/jadoreauderghem" target="_blank">@jadoreauderghem</a></p>
  </div>

  <footer>
    <p>© 2025 J'adore Nails & Massages – Tous droits réservés</p>
  </footer>
</body>
</html>
