portfolio/
├── index.html
├── style.css
└── script.js
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <title>Abdelhak Ennabli | Chef de cuisine</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <header>
    <h1>Abdelhak Ennabli</h1>
    <p>Chef / Sous-chef de cuisine</p>
    <p>📞 +33 7 49 25 24 76 | ✉️ Ennabli141@gmail.com</p>
  </header>

  <section id="about">
    <h2>Profil</h2>
    <p>
      Chef de cuisine expérimenté avec plus de 10 ans d’expérience en restauration.
      Spécialisé dans la création de menus, l’ouverture de restaurants et la gestion d’équipes.
      Rigoureux, dynamique et doté d’un excellent esprit d’équipe.
    </p>
  </section>

  <section id="skills">
    <h2>Compétences</h2>
    <ul>
      <li>Création et élaboration de menus innovants</li>
      <li>Gestion, recrutement et formation d’équipes</li>
      <li>Optimisation des coûts et gestion des stocks</li>
      <li>Fiches techniques et sélection des fournisseurs</li>
      <li>Organisation du service et gestion du timing</li>
      <li>Adaptation aux régimes spécifiques (végétarien, sans gluten…)</li>
      <li>Hygiène et sécurité alimentaire (HACCP)</li>
    </ul>
  </section>

  <section id="experience">
    <h2>Expériences professionnelles</h2>

    <div class="job">
      <h3>Chef – Ouverture de restaurants</h3>
      <span>2023 – 2025 | Maroc</span>
      <p>Lancement de plusieurs enseignes, structuration des cuisines et formation des équipes.</p>
    </div>

    <div class="job">
      <h3>Chef & Commis de cuisine – ARENFIP</h3>
      <span>2019 – 2023</span>
    </div>

    <div class="job">
      <h3>Chef de cuisine – Taverna di Mezzo</h3>
      <span>2017 – 2019</span>
      <p>Cuisine italienne locale revisitée.</p>
    </div>

    <div class="job">
      <h3>Sous-chef – Pousada</h3>
      <span>2014 – 2017</span>
      <p>Cuisine sud-américaine.</p>
    </div>

    <div class="job">
      <h3>Sous-chef – Salino</h3>
      <span>2012 – 2014</span>
      <p>Cuisine de bistro saisonnière.</p>
    </div>

    <div class="job">
      <h3>Serveur en salle – Villa Prati</h3>
      <span>2010 – 2012</span>
    </div>
  </section>

  <section id="education">
    <h2>Formations</h2>
    <ul>
      <li><strong>2008 – 2012</strong> : École IAL – École hôtelière</li>
      <li><strong>2007 – 2008</strong> : ISS Roberto Ruffia – Diplôme professionnel en gestion d’entreprise</li>
    </ul>
  </section>

  <section id="languages">
    <h2>Langues</h2>
    <p>Français • Anglais • Italien • Arabe</p>
  </section>

  <footer>
    <p>© 2026 – Abdelhak Ennabli</p>
  </footer>
body {
  font-family: "Segoe UI", Arial, sans-serif;
  margin: 0;
  background-color: #f7f7f7;
  color: #333;
}

header {
  background-color: #1e1e1e;
  color: white;
  text-align: center;
  padding: 50px 20px;
}

section {
  max-width: 900px;
  margin: auto;
  padding: 40px 20px;
}

h2 {
  border-bottom: 2px solid #c59d5f;
  padding-bottom: 5px;
  margin-bottom: 20px;
}

ul {
  list-style: square;
  padding-left: 20px;
}

.job {
  background: white;
  padding: 20px;
  margin-bottom: 15px;
  border-left: 5px solid #c59d5f;
}

.job span {
  font-size: 0.9em;
  color: #666;
}

footer {
  background: #ddd;
  text-align: center;
  padding: 20px;
}
