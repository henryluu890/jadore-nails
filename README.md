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

    header {
      height: 90vh;
      position: relative;
      background: linear-gradient(rgba(52,152,219,0.45), rgba(46,204,113,0.45)), url('https://images.unsplash.com/photo-1602126046951-0af5ca97a7e8?auto=format&fit=crop&w=1600&q=80') center/cover no-repeat;
      color: var(--white);
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }

    header h1 {
      font-size: 2.8rem;
      margin: 0;
      text-shadow: 0 2px 4px rgba(0,0,0,0.25);
    }

    header p {
      font-size: 1.2rem;
      margin: 8px 0;
      text-shadow: 0 1px 3px rgba(0,0,0,0.2);
    }

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

    .slider {
      display: flex;
      overflow-x: auto;
      scroll-snap-type: x mandatory;
      gap: 16px;
      padding: 16px;
    }

    .slider img {
      width: 100%;
      max-width: 400px;
      height: auto;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.15);
      scroll-snap-align: start;
    }

    footer {
      background: var(--blue);
      color: var(--white);
      text-align: center;
      padding: 25px 10px;
    }

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

    @media (max-width: 600px) {
      header h1 {font-size: 2rem;}
      nav a {margin: 0 10px;}
      section {padding: 40px 16px;}
      .slider {flex-direction: column; align-items: center;}
    }
  </style>
</head>
<body>
  <header>
    <div>
      <h1>J'adore Nails & Massages <span style="color:#ff66b2;">❤</span></h1>
      <p>Pour des ongles impeccables et des instants de pure détente</p>
      <p>📍 Av de l’église Saint-Julien 2 – 📞 (32) 470 94 87 07</p>
    </div>
  </header>

  <nav>
    <a href="#ongles">Ongles</a>
    <a href="#spa">Massages</a>
    <a href="#galerie">Galerie</a>
    <a href="#horaires">Horaires</a>
    <a href="#tarifs">Tarifs</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="ongles">
    <h2>Nail Art & Soins</h2>
    <p>Vous retrouverez à J’adore Nails une multitude de couleurs laissant place à vos envies. Laissez s’exprimer votre créativité et optez pour le nail art digne des plus grands nails artistes.</p>
  </section>

  <section id="spa">
    <h2>Spa & Massages</h2>
    <p>Embarquez pour un voyage vers la zen-attitude ! En solo, en duo ou entre ami·es, découvrez nos soins des mains et massages dans un cadre apaisant.</p>
  </section>

  <section id="galerie">
    <h2>Galerie</h2>
    <div class="slider">
      <img src="https://images.unsplash.com/photo-1585238341972-17ec9eef1ef5?auto=format&fit=crop&w=600&q=80" alt="Ongles décorés">
      <img src="https://images.unsplash.com/photo-1601109739360-968b9d8ee7a1?auto=format&fit=crop&w=600&q=80" alt="Salon spa">
      <img src="https://images.unsplash.com/photo-1603349206294-08f98961453e?auto=format&fit=crop&w=600&q=80" alt="Massage relaxant">
    </div>
  </section>

  <section id="horaires">
    <h2>Horaires d'ouverture</h2>
    <ul>
      <li>Lundi - Samedi : 10h - 18h</li>
      <li>Dimanche : fermé</li>
    </ul>
    <div class="cta">
      <strong>Jours fériés :</strong> Nous sommes exceptionnellement fermés certains jours fériés. <br>
      <ul>
        <li>1er janvier – Nouvel An</li>
        <li>Lundi de Pâques</li>
        <li>1er mai – Fête du Travail</li>
        <li>15 août – Assomption</li>
        <li>1er novembre – Toussaint</li>
        <li>11 novembre – Armistice</li>
        <li>25 décembre – Noël</li>
      </ul>
    </div>
  </section>

  <section id="tarifs">
    <h2>Services & Tarifs</h2>
    <ul>
      <li>Manucure simple : 19€</li>
      <li>Pose vernis simple : 19€</li>
      <li>Manucure + vernis simple : 32€</li>
      <li>Vernis semi-permanent : 29€</li>
      <li>Manucure + vernis semi-permanent : 37€</li>
      <li>Dépose vernis semi-permanent : 12€</li>
      <li>Gel : 46€/50€</li>
      <li>Gel + manucure : 56€/60€</li>
      <li>French/Babyboomer/Ombré : 55€/59€</li>
      <li>Dépose gel : 15€</li>
      <li>Dépose acrylique : 18€</li>
      <li>Pédicure + massage : 35€–45€</li>
      <li>Pédicure + vernis simple : 42€</li>
      <li>Pédicure + vernis semi-permanent : 36€</li>
      <li>Pédicure complète : 46€–60€</li>
      <li>Dépose vernis pieds semi-permanent : 12€</li>
      <li>Diamants (0,5€/pièce), Couleurs supplémentaires (2€), Design (2€–5€/doigt), Réparation ongle cassé (7€/doigt)</li>
      <li>Massage pieds simple (30min) : 35€</li>
      <li>Massage Tui Na (45min/60min) : 50€/65€</li>
      <li>Massage dos & bras (30min) : 35€</li>
      <li>Massage relaxant (60/90/120min) : 58€/85€/110€</li>
      <li>Massage Thaï (60min) : 76€</li>
      <li>Shiatsu et pierres chaudes (60/90min) : 70€/104€</li>
      <li>Massage relaxant et pierres chaudes (60/90/120min) : 65€/99€/128€</li>
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
