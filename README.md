# Boozy-Angel
Boozy Angel App

<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Boozy Angel — Politique de confidentialité</title>
  <style>
    :root {
      --bg-1: #1a0f2a;
      --bg-2: #2c123d;
      --panel: rgba(46, 25, 57, 0.94);
      --purple: #d57fe5;
      --pink: #ff5fa2;
      --gold: #f5d67a;
      --text: #f8edf1;
      --muted: #d9c7d8;
      --line: rgba(255,255,255,0.12);
      --accent: #e37fb4;
    }

    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background:
        radial-gradient(circle at top, rgba(255, 105, 180, 0.12), transparent 30%),
        linear-gradient(180deg, var(--bg-1), var(--bg-2));
      color: var(--text);
      line-height: 1.7;
    }

    .container {
      max-width: 980px;
      margin: 0 auto;
      padding: 40px 20px 80px;
    }

    .topbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 12px;
      padding: 18px 0 26px;
      border-bottom: 1px solid var(--line);
    }

    .brand {
      display: flex;
      align-items: center;
      gap: 10px;
      font-weight: 800;
      letter-spacing: 0.05em;
      font-size: 1.1rem;
      color: var(--text);
      text-decoration: none;
    }

    .brand-mark {
      width: 28px;
      height: 28px;
      border-radius: 50%;
      background: linear-gradient(135deg, var(--pink), var(--purple));
      position: relative;
      box-shadow: 0 0 16px rgba(255, 95, 162, 0.6);
    }

    .brand-mark::before {
      content: "";
      position: absolute;
      inset: 8px;
      border-radius: 50%;
      background: rgba(255,255,255,0.3);
    }

    .nav {
      display: flex;
      gap: 16px;
      flex-wrap: wrap;
    }

    .nav a {
      color: var(--muted);
      text-decoration: none;
      font-size: 0.95rem;
    }

    .nav a:hover { color: var(--text); }

    .page {
      background: rgba(25, 15, 31, 0.78);
      border: 1px solid var(--line);
      border-radius: 22px;
      padding: 30px 28px;
      box-shadow: 0 20px 50px rgba(0,0,0,0.18);
      margin-top: 28px;
    }

    h1 {
      font-size: clamp(2.2rem, 4vw, 3.3rem);
      margin: 0 0 12px;
      line-height: 1.1;
      letter-spacing: -0.04em;
    }

    .subtitle {
      color: var(--muted);
      margin: 0 0 30px;
      font-size: 1.02rem;
    }

    h2 {
      font-size: 1.4rem;
      margin-top: 32px;
      margin-bottom: 12px;
      color: #f9d8ef;
    }

    p, li {
      color: var(--text);
      font-size: 1rem;
    }

    ul {
      padding-left: 22px;
      margin: 10px 0 18px;
    }

    .muted {
      color: var(--muted);
    }

    .footer-note {
      margin-top: 30px;
      padding-top: 20px;
      border-top: 1px solid var(--line);
      color: var(--muted);
      font-size: 0.95rem;
    }

    @media (max-width: 700px) {
      .topbar {
        flex-direction: column;
        align-items: flex-start;
      }
      .page {
        padding: 22px 18px;
      }
      h1 {
        font-size: 2.2rem;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <header class="topbar">
      <a class="brand" href="index.html">
        <span class="brand-mark"></span>
        <span>BOOZY ANGEL</span>
      </a>

      <nav class="nav">
        <a href="privacy.html">Confidentialité</a>
        <a href="support.html">Assistance</a>
      </nav>
    </header>

    <main class="page">
      <h1>Politique de confidentialité</h1>
      <p class="subtitle">
        Dernière mise à jour : 11 octobre 2026
      </p>

      <p>
        Boozy Angel ("nous", "notre", "nos") s'engage à protéger la vie privée de ses utilisateurs.
        Cette politique de confidentialité explique quelles informations sont collectées, comment elles sont utilisées
        et quelles garanties sont mises en place pour les protéger.
      </p>

      <h2>1. Informations collectées</h2>
      <p>
        Nous pouvons collecter les informations suivantes lorsque vous utilisez notre application :
      </p>
      <ul>
        <li>Informations de compte (si vous créez un compte) : pseudo, adresse e-mail, identifiant d'appareil ;</li>
        <li>Informations de jeu : scores, questions répondues, sessions de jeu, résultats et statistiques ;</li>
        <li>Informations techniques : type d'appareil, système d'exploitation, langue, version de l'application, identifiants de session ;</li>
        <li>Informations de diagnostic : éventuelles erreurs, performances ou signalements de bugs ;</li>
        <li>Informations de disponibilité et d'activité dans l'application, si nécessaire au bon fonctionnement du service.</li>
      </ul>

      <h2>2. Utilisation des données</h2>
      <p>Nous utilisons vos informations pour :</p>
      <ul>
        <li>fournir et améliorer l'application ;</li>
        <li>gérer les parties, les scores et les résultats ;</li>
        <li>assurer la sécurité, la stabilité et la prévention des abus ;</li>
        <li>répondre aux demandes d'assistance ;</li>
        <li>améliorer nos services et développer de nouvelles fonctionnalités.</li>
      </ul>

      <h2>3. Partage des données</h2>
      <p>
        Nous ne vendons ni ne louons vos données personnelles. Nous pouvons partager certaines informations
        avec des prestataires techniques uniquement dans le cadre strict de la fourniture du service
        (hébergement, analyse, support technique, sécurité, etc.).
      </p>
      <p>
        Nous pouvons également divulguer des informations si la loi l'exige ou si cela est nécessaire pour
        protéger nos droits, la sécurité des utilisateurs ou la conformité réglementaire.
      </p>

      <h2>4. Données de jeu et vie privée</h2>
      <p>
        Les scores, résultats et créations de contenu généré dans l'application peuvent être utilisés dans le cadre du
        gameplay, des statistiques et des fonctionnalités sociales, selon les options activées dans l'application.
      </p>
      <p>
        Si vous choisissez de partager vos données avec d'autres utilisateurs, cela est soumis aux paramètres du service
        et à la configuration de votre compte.
      </p>

      <h2>5. Sécurité</h2>
      <p>
        Nous mettons en place des mesures raisonnables pour protéger vos informations contre l'accès non autorisé,
        la modification, la divulgation ou la destruction.
      </p>

      <h2>6. Conservation des données</h2>
      <p>
        Nous conservons vos données uniquement pendant la période nécessaire à l'utilisation du service, aux obligations
        légales, à la résolution de litiges et à l'amélioration de nos services.
      </p>

      <h2>7. Droits de l'utilisateur</h2>
      <p>
        Conformément aux lois applicables, vous pouvez demander :
      </p>
      <ul>
        <li>l'accès à vos données personnelles ;</li>
        <li>la correction de données inexactes ;</li>
        <li>la suppression de vos données ;</li>
        <li>la limitation ou l'opposition au traitement ;</li>
        <li>la portabilité de vos données.</li>
      </ul>
      <p>
        Pour exercer ces droits, veuillez nous contacter via la page d'assistance.
      </p>

      <h2>8. Enfants</h2>
      <p>
        Notre application n'est pas destinée à être utilisée par des enfants de moins de 13 ans, ou par des mineurs
        dans les juridictions où une restriction supplémentaire est requise. Nous ne collectons pas sciemment
        de données personnelles provenant d'enfants.
      </p>

      <h2>9. Modifications</h2>
      <p>
        Nous pouvons modifier cette politique de confidentialité à tout moment. Les changements importants seront
        communiqués dans l'application ou sur notre site web le cas échéant.
      </p>

      <h2>10. Contact</h2>
      <p>
        Si vous avez des questions concernant cette politique de confidentialité, veuillez nous contacter :
      </p>
      <p>
        <strong>Email :</strong> support@boozyangel.app<br />
        <strong>Nom de l'application :</strong> Boozy Angel
      </p>

      <div class="footer-note">
        En utilisant l'application, vous acceptez cette politique de confidentialité.
      </div>
    </main>
  </div>
</body>
</html>
