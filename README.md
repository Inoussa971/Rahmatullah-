<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site Web Basique</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#">Accueil</a></li>
                <li><a href="#">À propos</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="hero">
            <h1>Bienvenue sur notre site web</h1>
            <p>Votre satisfaction est notre priorité.</p>
            <button id="ctaButton">En savoir plus</button>
        </section>

        <section class="content">
            <h2>Nos Services</h2>
            <p>Nous offrons une variété de services adaptés à vos besoins.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Site Web Basique. Tous droits réservés.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

/* Styles pour la page web */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    padding: 15px 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

.hero {
    background-color: #00aaff;
    color: white;
    text-align: center;
    padding: 100px 20px;
}

.content {
    padding: 20px;
    text-align: center;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: absolute;
    bottom: 0;
    width: 100%;
}

button {
    background-color: #ff6600;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #ff8533;
}

document.getElementById('ctaButton').addEventListener('click', function() {
    alert('Merci de votre intérêt. Plus d\'informations à venir !');
});