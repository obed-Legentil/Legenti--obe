<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Expert Virtuel | Obed</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        :root {
            --primary: #003366; /* Bleu Profond */
            --accent: #007bff;  /* Bleu Éclatant */
            --white: #ffffff;
            --light: #f8f9fa;
            --text: #212529;
        }

        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            margin: 0;
            line-height: 1.6;
            color: var(--text);
            background-color: var(--white);
        }

        header {
            background: var(--white);
            padding: 1.2rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .logo { font-weight: bold; color: var(--primary); font-size: 1.5rem; text-transform: uppercase; letter-spacing: 1px; }

        .hero {
            background: linear-gradient(rgba(0, 51, 102, 0.8), rgba(0, 123, 255, 0.8)), url('https://images.unsplash.com/photo-1484417894907-623942c8ee29?auto=format&fit=crop&q=80&w=2000');
            background-size: cover;
            background-position: center;
            color: var(--white);
            padding: 100px 5%;
            text-align: center;
        }

        .hero h1 { font-size: 2.8rem; margin-bottom: 15px; text-shadow: 2px 2px 4px rgba(0,0,0,0.3); }
        .hero p { font-size: 1.3rem; opacity: 0.9; margin-bottom: 30px; }

        .container { padding: 60px 5%; max-width: 1200px; margin: auto; }

        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }

        .card {
            background: var(--light);
            padding: 40px;
            border-radius: 15px;
            text-align: center;
            border-bottom: 5px solid transparent;
            transition: all 0.3s ease;
        }

        .card:hover { 
            transform: translateY(-10px); 
            background: var(--white);
            box-shadow: 0 15px 30px rgba(0,0,0,0.1);
            border-bottom: 5px solid var(--accent);
        }

        .card i { font-size: 3rem; color: var(--accent); margin-bottom: 25px; }
        .card h3 { color: var(--primary); margin-bottom: 15px; }

        .lang-tag {
            display: inline-block;
            background: var(--primary);
            color: white;
            padding: 6px 18px;
            border-radius: 50px;
            margin: 5px;
            font-size: 0.9rem;
            font-weight: bold;
        }

        .cta-btn {
            background: var(--accent);
            color: white;
            padding: 18px 35px;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            transition: background 0.3s;
            box-shadow: 0 4px 15px rgba(0,123,255,0.3);
        }

        .cta-btn:hover { background: var(--primary); }

        #contact { background: var(--primary); color: white; padding: 80px 5%; text-align: center; }
        #contact h2 { font-size: 2.2rem; margin-bottom: 20px; }

        footer { text-align: center; padding: 40px; background: #001a33; color: white; font-size: 0.9rem; }

        @media (max-width: 768px) {
            .hero h1 { font-size: 2rem; }
        }
    </style>
</head>
<body>

<header>
    <div class="logo">Expert Virtuel</div>
</header>

<section class="hero">
    <h1>Votre allié quotidien pour une productivité sans frontières</h1>
    <p>Solutions d'assistance et de traduction multilingue</p>
    <a href="mailto:legentil.ob@gmail.com" class="cta-btn">Démarrer un projet</a>
</section>

<div class="container">
    <h2 style="text-align:center; color: var(--primary);">Mes Services</h2>
    <div class="services">
        <div class="card">
            <i class="fas fa-tasks"></i>
            <h3>Assistance Virtuelle</h3>
            <p>Organisation, gestion d'emails et support administratif rigoureux pour optimiser votre temps.</p>
        </div>
        <div class="card">
            <i class="fas fa-headset"></i>
            <h3>Support Client</h3>
            <p>Une présence professionnelle et chaleureuse pour répondre aux besoins de vos utilisateurs.</p>
        </div>
        <div class="card">
            <i class="fas fa-globe"></i>
            <h3>Traductions</h3>
            <p>Traduction fluide et fidèle de vos documents professionnels en trois langues :</p>
            <div style="margin-top:20px">
                <span class="lang-tag">FRANÇAIS</span>
                <span class="lang-tag">ANGLAIS</span>
                <span class="lang-tag">ESPAGNOL</span>
            </div>
        </div>
    </div>
</div>

<section id="contact">
    <h2>Prêt à passer au niveau supérieur ?</h2>
    <p style="margin-bottom: 30px; font-size: 1.1rem; opacity: 0.8;">Réponse garantie sous 24 heures.</p>
    <a href="mailto:legentil.ob@gmail.com" class="cta-btn" style="background: var(--white); color: var(--primary);">
        <i class="fas fa-envelope"></i> legentil.ob@gmail.com
    </a>
</section>

<footer>
    <p>&copy; 2026 - Obed Legentil. Expert Assistant Virtuel & Traducteur.</p>
</footer>

</body>
</html>
