# epi-truck
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ÉPI-TRUCK - Roulons Solidaires</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background: #ffcc00;
            padding: 20px;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: black;
            font-weight: bold;
        }
        .hero {
            background: url('truck.jpg') no-repeat center center/cover;
            color: white;
            padding: 50px 20px;
        }
        .cta {
            margin: 20px;
            padding: 15px 25px;
            background: #007BFF;
            color: white;
            border: none;
            cursor: pointer;
            font-size: 18px;
        }
        .section {
            padding: 50px 20px;
        }
        .donate, .volunteer, .partners, .solidarity-truck, .guestbook {
            background: #f4f4f4;
            margin: 20px;
            padding: 30px;
        }
        footer {
            background: black;
            color: white;
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>ÉPI-TRUCK - Roulons Solidaires</h1>
        <nav>
            <a href="#mission">Notre Mission</a>
            <a href="#aider">Comment Aider ?</a>
            <a href="#solidarity-truck">Camion Solidaire</a>
            <a href="#guestbook">Livre de Doléance</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="hero">
        <h2>Un camion, mille solidarités : aidons là où le besoin est urgent !</h2>
        <button class="cta">Faire un don</button>
        <button class="cta">Rejoindre l’aventure</button>
    </section>

    <section class="section" id="mission">
        <h2>Notre Mission</h2>
        <p>Des milliers de personnes vivent dans la précarité. ÉPI-TRUCK va à leur rencontre avec un camion solidaire apportant repas et aide.</p>
    </section>

    <section class="section" id="aider">
        <h2>Comment Vous Pouvez Aider ?</h2>
        <div class="donate">
            <h3>Faire un Don 💙</h3>
            <p>Chaque euro compte et permet d’aider directement.</p>
            <button class="cta">Je fais un don maintenant</button>
        </div>
        <div class="volunteer">
            <h3>Devenir Bénévole 🤝</h3>
            <p>Donnez de votre temps pour une grande différence.</p>
            <button class="cta">Je m’inscris</button>
        </div>
        <div class="partners">
            <h3>Entreprises & Partenaires 🏢</h3>
            <p>Impliquez votre entreprise dans un projet solidaire.</p>
            <button class="cta">Proposer un partenariat</button>
        </div>
    </section>

    <section class="section" id="solidarity-truck">
        <h2>Notre Camion Solidaire 🚛</h2>
        <p>Le camion ÉPI-TRUCK sillonne les routes pour apporter une aide essentielle aux plus démunis.</p>
        <img src="solidarity_truck.jpg" alt="Camion solidaire en action" width="80%">
    </section>

    <section class="section" id="guestbook">
        <h2>Livre de Doléance 📖</h2>
        <p>Laissez un message, un témoignage ou une suggestion pour améliorer nos actions.</p>
        <textarea rows="5" cols="50" placeholder="Votre message ici..."></textarea>
        <br>
        <button class="cta">Envoyer</button>
    </section>

    <footer id="contact">
        <p>Retrouvez-nous sur les réseaux sociaux : Facebook | Instagram | LinkedIn</p>
        <p>Contactez-nous : contact@epi-truck.org</p>
    </footer>
</body>
</html>
