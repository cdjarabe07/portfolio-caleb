<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio – Caleb Djarabé</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    body {
      font-family: "Times New Roman", Times, serif;
      margin:0; padding:0;
      background-image: url('design.jpg');
      background-size: cover;
      background-attachment: fixed;
      background-position: center;
      color:#fff;
    }
    header {
      background: rgba(0,0,0,0.6);
      color:white; 
      padding:80px 20px; 
      text-align:center;
      border-bottom: 2px solid #1e90ff;
    }
    header img {
      width:160px; height:160px; 
      border-radius:50%; 
      object-fit:cover; 
      margin-bottom:20px;
      border:3px solid #fff;
    }
    header h1 {margin:0; font-size:3em;}
    header p {margin:10px 0; font-size:1.2em;}
    nav {
      background:#111; 
      padding:15px; 
      text-align:center;
      position: sticky;
      top:0;
      z-index: 100;
    }
    nav a {
      color:white; margin:0 15px; text-decoration:none; font-weight:bold;
      transition: color 0.3s;
    }
    nav a:hover { color: #1e90ff; }
    section {padding:60px 20px; max-width:1000px; margin:auto; background: rgba(0,0,0,0.5); border-radius:10px; margin-bottom:40px;}
    h2 {color:#1e90ff; margin-bottom:20px;}
    .skills, .projects, .experience, .education {display:grid; grid-template-columns:1fr 1fr; gap:20px;}
    .card {
      background: rgba(255,255,255,0.05); 
      padding:20px; 
      border-radius:10px; 
      box-shadow:0 2px 6px rgba(0,0,0,0.5);
      transition: all 0.3s ease;
    }
    .card:hover {transform: translateY(-5px); box-shadow:0 4px 12px rgba(0,0,0,0.7);}
    footer {background:#111; color:white; text-align:center; padding:20px; margin-top:40px;}
    .contact-info p, .contact-info ul {margin:5px 0;}
    .contact-info a {color:#1e90ff; text-decoration:none;}
    .contact-info a:hover {text-decoration:underline;}
    @media(max-width:768px){
      .skills, .projects, .experience, .education {grid-template-columns:1fr;}
      header h1 {font-size:2em;}
      header p {font-size:1em;}
    }
    .project-img {width:100%; height:200px; object-fit:cover; border-radius:10px; margin-bottom:10px;}
  </style>
</head>
<body>

<header>
  <img src="photo_profil.jpg" alt="Photo de Caleb Djarabé">
  <h1>Caleb Djarabé</h1>
  <p>MBA Ingénierie Financière | Data Science & Fintech</p>
  <p><em>Allier économie, finance et data science pour bâtir des solutions inclusives et innovantes en Afrique.</em></p>
</header>

<nav>
  <a href="#about">À propos</a>
  <a href="#skills">Compétences</a>
  <a href="#projects">Projets</a>
  <a href="#experience">Expérience</a>
  <a href="#education">Formation</a>
  <a href="#contact">Contact</a>
</nav>

<section id="about">
  <h2>À propos</h2>
  <img class="project-img" src="apropos.jpg" alt="À propos">
  <p>Je suis Caleb Djarabé, étudiant en MBA Ingénierie Financière à ISM Dakar et en formation Data Science. Passionné par la finance inclusive et l’innovation numérique, je développe des compétences pour créer des solutions fintech adaptées aux besoins des marchés africains. Mon objectif : concilier analyse économique et technologies data-driven pour un impact durable.</p>
  <p>Actuellement en MBA 2 Ingénierie Financière à ISM Dakar et en formation Data Science chez GoMyCode, j’explore l’intersection entre finance, économie et technologies numériques. Mon parcours en économie appliquée m’a permis de comprendre les enjeux de développement, tandis que mes apprentissages en data science m’ouvrent la voie vers la modélisation, la prédiction et la détection de fraudes financières. Mon ambition est de contribuer à la création d’infrastructures financières inclusives, notamment via des solutions mobiles et des institutions de microfinance, afin de renforcer l’accès aux services financiers et accélérer la croissance économique en Afrique de l’Ouest.</p>
</section>

<section id="skills">
  <h2>Compétences</h2>
  <div class="skills">
    <div class="card">
      <h3><i class="fas fa-chart-line"></i> Finance & Économie</h3>
      <ul>
        <li>Analyse économique & financière</li>
        <li>Ingénierie financière</li>
        <li>Gestion des risques bancaires et prudentiels (Bâle I, II, III – UEMOA)</li>
        <li>Microfinance & inclusion financière</li>
      </ul>
    </div>
    <div class="card">
      <h3><i class="fas fa-robot"></i> Data Science & Machine Learning</h3>
      <ul>
        <li>Analyse de données (Excel, Stata, Eviews, Google Data Analytics)</li>
        <li>Python (Pandas, NumPy, Scikit-learn)</li>
        <li>Visualisation (Power BI, Tableau)</li>
        <li>Détection de fraudes financières</li>
        <li>Analyse prédictive des risques climatiques</li>
      </ul>
    </div>
    <div class="card">
      <h3><i class="fas fa-laptop-code"></i> Outils & Tech</h3>
      <ul>
        <li>Microsoft Excel & Word</li>
        <li>SQL</li>
        <li>GitHub</li>
        <li>ERP / CRM</li>
      </ul>
    </div>
    <div class="card">
      <h3><i class="fas fa-users"></i> Compétences transversales</h3>
      <ul>
        <li>Gestion administrative & de projet</li>
        <li>Vente et relation client</li>
        <li>Organisation & capacité d’adaptation</li>
        <li>Travail en équipe & sens de l’innovation</li>
      </ul>
    </div>
  </div>
</section>

<section id="projects">
  <h2>Projets</h2>
  <div class="projects">
    <div class="card">
      <img class="project-img" src="microfinance.jpg" alt="Microfinance Digitale">
      <h3>Institution de Microfinance Digitale</h3>
      <p><strong>Contexte :</strong> Besoin urgent d’accès au financement inclusif dans les zones peu bancarisées.</p>
      <p><strong>Solution :</strong> Application mobile pour des transactions rapides et sécurisées.</p>
      <p><strong>Impact :</strong> Amélioration de l’accès au financement pour micro-entrepreneurs.</p>
    </div>
    <div class="card">
      <img class="project-img" src="fraudes.jpg" alt="Détection de Fraudes Financières">
      <h3>Détection de Fraudes Financières par Machine Learning</h3>
      <p><strong>Contexte :</strong> Lutte contre les fraudes bancaires.</p>
      <p><strong>Solution :</strong> Pipeline de données et modèles ML.</p>
      <p><strong>Impact :</strong> Réduction des faux positifs et système plus robuste.</p>
    </div>
    <div class="card">
      <img class="project-img" src="industrialisation.jpg" alt="Industrialisation biens courants">
      <h3>Industrialisation de biens de consommation courante</h3>
      <p><strong>Contexte :</strong> Forte dépendance aux importations.</p>
      <p><strong>Solution :</strong> Développement d’une industrie locale (mobilier, emballages, ustensiles, etc.).</p>
      <p><strong>Impact :</strong> Réduction des importations, création d’emplois, souveraineté industrielle.</p>
    </div>
  </div>
</section>

<section id="experience">
  <h2>Expérience professionnelle</h2>
  <div class="experience">
    <div class="card">
      <ul>
        <li>Contrôleur de Gestion — Agence Nationale des Investissements et des Exportations (2024)</li>
        <li>Stage en Gestion Bancaire — Commercial Bank Tchad, N’Djaména (2024)</li>
      </ul>
    </div>
  </div>
</section>

<section id="education">
  <h2>Formation</h2>
  <div class="education">
    <div class="card">
      <ul>
        <li>MBA 2 Ingénierie Financière — ISM Dakar (en cours)</li>
        <li>Formation Data Science — GoMyCode Dakar (en cours)</li>
        <li>Licence en Sciences économiques & gestion (Éco appliquée) — Univ. Saint Charles Lwanga, Tchad (2023)</li>
        <li>Certificat Google Data Analytics — Coursera (2024)</li>
        <li>Certificat « Intelligence économique » — ITC e-learning (2024)</li>
        <li>Attestation « Management logistique des projets humanitaires » — CREDI, Tchad (2024)</li>
        <li>Formation CRM & techniques de vente — A.S Consulting (2025)</li>
      </ul>
    </div>
  </div>
</section>

<section id="contact">
  <h2>Contact</h2>
  <div class="contact-info">
    <p>📧 Email : cdjarabe07@gmail.com</p>
    <p>📱 Téléphone : (+221) 77 437 55 22</p>
    <p>🔗 LinkedIn : <a href="https://www.linkedin.com/in/caleb-djarabé-230477234" target="_blank">Mon Profil</a></p><br><a href="CV_Caleb.pdf" download>
  <button style="padding:10px 20px; background:#1e3a8a; color:white; border:none; border-radius:5px; cursor:pointer;">
    Télécharger mon CV
  </button>
</a>

    <p>Références académiques :</p>
    <ul>
      <li>Mantobaye MOUNDIGBAYE, Ph.D — mantobaye@yahoo.fr</li>
      <li>Mbatina NODJI, Ph.D — <a href="https://www.linkedin.com/in/mbatina-nodji-ph-d-7524ab96" target="_blank">Profil LinkedIn</a></li>
    </ul>
  </div>
</section>

<footer>
  <p>© 2025 Caleb Djarabé – Tous droits réservés</p>
</footer>

</body>
</html>
