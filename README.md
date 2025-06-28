<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>J'adore Nails & Massages</title>
  <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@400;600&display=swap" rel="stylesheet" />
  <style>
    :root {
      --green: #2ecc71;
      --blue: #3498db;
      --light: #d6f5ff;
      --white: #ffffff;
      --shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: "Quicksand", sans-serif;
      background: var(--blue);
      color: #333;
    }

    nav {
      background: var(--green);
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 10px 20px;
      box-shadow: var(--shadow);
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav .brand {
      display: flex;
      align-items: center;
      color: var(--white);
      font-size: 1.5rem;
      text-decoration: none;
      font-weight: 600;
    }

    nav .brand img {
      width: 40px;
      height: 40px;
      margin-right: 10px;
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
    }

    header {
      height: 90vh;
      background: url('https://images.unsplash.com/photo-1600423115360-b1fe70c2e98d') center/cover no-repeat;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: var(--white);
      padding: 0 20px;
    }

    header h1 {
      font-size: 3rem;
    }

    section {
      padding: 60px 20px;
      background: var(--white);
      margin: 40px auto;
      max-width: 1000px;
      border-radius: 10px;
      box-shadow: var(--shadow);
    }

    section h2 {
      color: var(--green);
      font-size: 2rem;
      margin-bottom: 20px;
    }

    .slider {
      display: flex;
      overflow-x: auto;
      gap: 20px;
    }

    .slider img {
      border-radius: 10px;
      width: 300px;
      height: 200px;
      object-fit: cover;
      box-shadow: var(--shadow);
    }

    .tarifs ul {
      list-style: none;
      padding: 0;
    }

    .tarifs li {
      margin-bottom: 10px;
      font-size: 1.1rem;
    }

    footer {
      text-align: center;
      background: var(--green);
      color: var(--white);
      padding: 20px;
    }
  </style>
</head>
<body>
  <nav>
    <a href="#" class="brand">
      <img src="https://cdn-icons-png.flaticon.com/512/3135/3135715.png" alt="Logo Nails">
      <span>J'adore Nails</span>
    </a>
    <ul>
      <li><a href="#ongles">Ongles</a></li>
      <li><a href="#spa">Massages</a></li>
      <li><a href="#galerie">Galerie</a></li>
      <li><a href="#tarifs">Tarifs</a></li>
    </ul>
  </nav>

  <header>
    <div>
      <h1>J'adore Nails & Massages</h1>
      <p>Pour des ongles impeccables et un moment de détente absolue.</p>
    </div>
  </header>

  <section id="ongles">
    <h2>Soins des Ongles</h2>
    <p>Manucure, gel, vernis semi-permanent, décoration d'ongles et plus encore !</p>
  </section>

  <section id="spa">
    <h2>Massages et Bien-être</h2>
    <p>Des massages relaxants, shiatsu, pierres chaudes et bien plus pour vous détendre.</p>
  </section>

  <section id="galerie">
    <h2>Galerie</h2>
    <div class="slider">
      <img src="https://images.unsplash.com/photo-1611078489935-0cb9649e5c48" alt="Ongles artistiques">
      <img src="https://images.unsplash.com/photo-1603395095293-65460494b1ae" alt="Soin Spa">
      <img src="https://images.unsplash.com/photo-1618517351616-5ceea7b771ae" alt="Massage relaxant">
    </div>
  </section>

  <section id="tarifs" class="tarifs">
    <h2>Tarifs</h2>
    <ul>
      <li>Manucure - 19€</li>
      <li>Pose Vernis Simple - 19€</li>
      <li>Manucure + Pose Vernis Simple - 32€</li>
      <li>Pose Vernis Semi-Permanent - 29€</li>
      <li>Manucure + Vernis Semi-Permanent - 37€</li>
      <li>Dépôt Vernis Semi-Permanent - 12€</li>
      <li>Gel - 46€/50€</li>
      <li>Gel + Manucure - 56€/60€</li>
      <li>French/Babyboomer/Ombré - 55€/59€</li>
      <li>Dépôt Gel - 15€</li>
      <li>Dépôt Acrylique - 18€</li>
      <li>Pédicure/Massage (10min) - 35€/40€/45€</li>
      <li>Pédicure + Vernis Simple - 42€</li>
      <li>Nettoyage + Vernis Semi-Permanent - 36€</li>
      <li>Pédicure + Semi-Permanent + Massage (5/15min) - 46€/50€/60€</li>
      <li>Dépôt Vernis Pieds Semi-Permanent - 12€</li>
      <li>Décorations : Diamants (0,5€/pièce), Couleur (2€/couleur), Design (2€-5€/doigt), Réparation Ongle Cassé (7€/doigt)</li>
      <li>Massage Pieds (30min) - 35€, Tui Na (45/60min) - 50€/65€</li>
      <li>Massage Corps : Dos & Bras (30min) - 35€, Relaxant (60/90/120min) - 58€/85€/110€, Thaï (60min) - 76€, Shiatsu + Pierres Chaudes (60/90min) - 70€/104€, Relaxant + Pierres Chaudes (60/90/120min) - 65€/99€/128€</li>
    </ul>
  </section>

  <footer>
    <p>&copy; 2025 J'adore Nails. Tous droits réservés.</p>
  </footer>
</body>
</html>
