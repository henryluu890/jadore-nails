<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>J'adore Nails & Massages</title>
  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@400;600&display=swap" rel="stylesheet" />
  <!-- Feather Icons for SVG icons -->
  <script src="https://unpkg.com/feather-icons"></script>
  <style>
    :root {
      --green: #2ecc71;
      --blue: #3498db;
      --light: #f4fefe;
      --white: #ffffff;
      --shadow: 0 8px 20px rgba(0, 0, 0, 0.08);
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: "Quicksand", sans-serif;
      background: var(--light);
      color: #333;
      scroll-behavior: smooth;
    }

    /* ======= LOGO + NAV ======= */
    nav {
      position: sticky;
      top: 0;
      width: 100%;
      background: rgba(52, 152, 219, 0.9);
      backdrop-filter: blur(6px);
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 10px 30px;
      z-index: 999;
      box-shadow: var(--shadow);
    }

    nav .brand {
      display: flex;
      align-items: center;
      gap: 12px;
      color: var(--white);
      font-size: 1.3rem;
      font-weight: 600;
      text-decoration: none;
    }

    nav .brand img {
      width: 50px;
      height: 50px;
      object-fit: contain;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
    }

    nav ul li a {
      color: var(--white);
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s;
    }

    nav ul li a:hover {
      color: var(--green);
    }

    /* ======= HEADER / HERO ======= */
    header {
      height: 90vh;
      background: linear-gradient(135deg, rgba(52, 152, 219, 0.5), rgba(46, 204, 113, 0.5)),
        url("https://images.unsplash.com/photo-1602126046951-0af5ca97a7e8?auto=format&fit=crop&w=1600&q=80") center/cover
          no-repeat;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: var(--white);
      padding: 0 20px;
    }

    header h1 {
      font-size: 2.8rem;
      text-shadow: 0 3px 6px rgba(0, 0, 0, 0.25);
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.1rem;
      text-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
    }

    /* ======= SECTIONS ======= */
    section {
      max-width: 1100px;
      margin: 60px auto;
      background: var(--white);
      border-radius: 18px;
      padding: 60px 30px;
      box-shadow: var(--shadow);
    }

    section:nth-of-type(odd) {
      background: linear-gradient(135deg, rgba(46, 204, 113, 0.08), rgba(52, 152, 219, 0.08));
    }

    section h2 {
      font-size: 1.9rem;
      color: var(--blue);
      margin-bottom: 25px;
      position: relative;
    }

    section h2::after {
      content: "";
      position: absolute;
      bottom: -8px;
      left: 0;
      width: 60px;
      height: 4px;
      background: linear-gradient(90deg, var(--green), var(--blue));
      border-radius: 4px;
    }

    /* ======= SLIDER ======= */
    .slider {
      display: flex;
      overflow-x: auto;
      scroll-snap-type: x mandatory;
      gap: 18px;
      scroll-behavior: smooth;
    }

    .slider img {
      scroll-snap-align: start;
      border-radius: 14px;
      width: 100%;
      max-width: 380px;
      height: 260px;
      object-fit: cover;
      box-shadow: var(--shadow);
      transition: transform 0.4s;
    }

    .slider img:hover {
      transform: scale(1.05);
    }

    /* ======= CTA BOX ======= */
    .cta {
      padding: 24px;
      border-left: 6px solid var(--blue);
      background: var(--light);
      border-radius: 10px;
      box-shadow: var(--shadow);
    }

    /* ======= FORMULAIRE CONTACT ======= */
    form {
      margin-top: 25px;
    }

    form input,
    form textarea {
      width: 100%;
      padding: 10px 14px;
      border: 2px solid rgba(0, 0, 0, 0.05);
      border-radius: 8px;
      margin-bottom: 14px;
      font-family: inherit;
      font-size: 1rem;
    }

    form button {
      background: var(--green);
      color: var(--white);
      padding: 12px 28px;
      border: none;
      border-radius: 8px;
      font-weight: 600;
      cursor: pointer;
      transition: background 0.3s;
    }

    form button:hover {
      background: var(--blue);
    }

    /* ======= FOOTER ======= */
    footer {
      background: var(--blue);
      color: var(--white);
      text-align: center;
      padding: 25px 10px;
    }

    /* ======= INSTAGRAM FLOAT BUTTON ======= */
    #insta-float {
      position: fixed;
      bottom: 25px;
      right: 25px;
      background: var(--green);
      border-radius: 50%;
      width: 52px;
      height: 52px;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: var(--shadow);
      cursor: pointer;
      transition: background 0.3s;
      z-index: 1000;
    }

    #insta-float:hover {
      background: var(--blue);
    }

    #insta-float svg {
      width: 26px;
      height: 26px;
      color: var(--white);
    }

    /* ======= RESPONSIVE ======= */
    @media (max-width: 768px) {
      nav ul {
        display: none; /* Simple mobile nav placeholder */
      }
      nav .brand span {
        font-size: 1rem;
      }
      header h1 {
        font-size: 2.2rem;
      }
      section {
        margin: 40px 14px;
        padding: 40px 20px;
      }
    }
  </style>
</head>
<body>
  <!-- ===== NAVBAR ===== -->
  <nav>
    <a href="#" class="brand">
      <img src="https://raw.githubusercontent.com/feathericons/feather/master/icons/smile.svg" alt="Logo" />
      <span>J'adore Nails</span>
    </a>
    <ul>
      <li><a href="#ongles">Ongles</a></li>
      <li><a href="#spa">Massages</a></li>
      <li><a href="#galerie">Galerie</a></li>
      <li><a href="#horaires">Horaires</a></li>
      <li><a href="#tarifs">Tarifs</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- ===== HERO ===== -->
  <header>
    <div>
      <h1>J'adore Nails & Massages</h1>
      <p>Pour des ongles impeccables et des instants de pure détente</p>
      <p>📍 Av de l’église Saint-Julien 2 – 📞 (32) 470 94 87 07</p>
    </div>
  </header>

  <!-- ===== SECTIONS ===== -->
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
      <img src="https://images.unsplash.com/photo-1585238341972-17ec9eef1ef5?auto=format&fit=crop&w=600&q=80" alt="Ongles décorés" />
      <img src="https://images.unsplash.com/photo-1601109739360-968b9d8ee7a1?auto=format&fit=crop&w=600&q=80" alt="Salon spa" />
      <img src="https://images.unsplash.com/photo-1603349206294-08f98961453e?auto=format&fit=crop&w=600&q=80" alt="Massage relaxant" />
    </div>
  </section>

  <section id="horaires">
    <h2>Horaires d'ouverture</
