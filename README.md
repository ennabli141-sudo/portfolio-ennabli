<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>Abdelhak Ennabli | Chef de cuisine gastronomique</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Montserrat:wght@300;400;500&display=swap" rel="stylesheet">

<style>
:root {
  --gold: #c6a75e;
  --dark: #0f0f0f;
  --light: #f5f3ef;
}

* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: 'Montserrat', sans-serif;
  background-color: var(--dark);
  color: var(--light);
  line-height: 1.7;
}

/* HEADER */
header {
  text-align: center;
  padding: 120px 20px;
  background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.9));
}

header h1 {
  font-family: 'Playfair Display', serif;
  font-size: 3rem;
  letter-spacing: 2px;
  margin-bottom: 10px;
}

header p {
  color: var(--gold);
  font-size: 1.1rem;
  margin: 5px 0;
}

/* SECTIONS */
section {
  max-width: 900px;
  margin: auto;
  padding: 80px 20px;
}

h2 {
  font-family: 'Playfair Display', serif;
  font-size: 2rem;
  margin-bottom: 30px;
}

h2::after {
  content: "";
  width: 60px;
  height: 2px;
  background: var(--gold);
  display: block;
  margin-top: 10px;
}

/* LISTES */
ul {
  list-style: none;
  padding: 0;
}

ul li {
  padding: 10px 0;
  border-bottom: 1px solid rgba(255,255,255,0.08);
}

/* EXPERIENCES */
.job {
  margin-bottom: 40px;
  padding-left: 20px;
  border-left: 2px solid var(--gold);
}

.job h3 {
  margin: 0;
  color: var(--gold);
  font-weight: 500;
}

.job span {
  font-size: 0.9rem;
  opacity: 0.7;
}

/* FOOTER */
footer {
  background: #080808;
  text-align: center;
  padding: 30px;
  font-size: 0.9rem;
  opacity: 0.6;
}

/* RESPONSIVE */
@media (max-width: 600px) {
  header h1 {
    font-size: 2.2rem;
  }
}
</style>
</head>

<body>

<header>
  <h1>Abdelhak Ennabli</h1>
  <p>Chef de cuisine gastronomique</p>
  <p>France • International</p>
  <p>📞 +33 7 49 25 24 76 | ✉️ Ennabli141@gmail.com</p>
</header>

<section id="about">
  <h2>Profil</h2>
  <p>
    Chef de cuisine expérimenté avec plus de dix ans d’expérience en restauration
    gastronomique et traditionnelle. Spécialisé dans la création de menus,
    l’ouverture de restaurants et la gestion d’équipes multiculturelles.
    Rigoureux, passionné et orienté excellence.
  </p>
</section>

<section id="skills">
  <h2>Compétences</h2>
  <ul>
    <li>Création et élaboration de menus gastronomiques</li>
    <li>Gestion, recrutement et formation d’équipes</li>
    <li>Optimisation des coûts et gestion des stocks</li>
    <li>Fiches techniques et sélection des fournisseurs</li>
    <li>Organisation du service et gestion du timing</li>
    <li>Adaptation aux régimes spécifiques</li>
    <li>Hygiène et sécurité alimentaire (HACCP)</li>
  </ul>
</section>

<section id="experience">
  <h2>Expériences</h2>

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
  © 2026 – Abdelhak Ennabli | Chef de cuisine
</footer>

</body>
</html>
