<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kymh Mosakoani</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            color: #fff;
            text-decoration: none;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        article {
            background: #fff;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px #ccc;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .gallery img {
            width: 30%;
            border-radius: 5px;
            box-shadow: 0 0 10px #ccc;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background: #333;
            color: #fff;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        form {
            background: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px #ccc;
        }
    </style>
</head>
<body>

<header>
    <h1>Kymh Mosakoani</h1>
    <nav>
        <a href="#articles">Articles</a>
        <a href="#gallery">Galerie</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<div class="container">
    <section id="articles">
        <article>
            <h2>Titre de l'Article 1</h2>
            <p>Contenu de l'article 1. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </article>
        <article>
            <h2>Titre de l'Article 2</h2>
            <p>Contenu de l'article 2. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </article>
    </section>

    <section id="gallery">
        <h2>Galerie</h2>
        <div class="gallery">
            <img src="https://via.placeholder.com/300" alt="Image 1">
            <img src="https://via.placeholder.com/300" alt="Image 2">
            <img src="https://via.placeholder.com/300" alt="Image 3">
            <img src="https://via.placeholder.com/300" alt="Image 4">
            <img src="https://via.placeholder.com/300" alt="Image 5">
            <img src="https://via.placeholder.com/300" alt="Image 6">
        </div>
    </section>

    <section id="contact">
        <h2>Suivez-moi sur les réseaux sociaux</h2>
        <p>
            <a href="https://www.youtube.com/@Kymh_mosakoani" target="_blank">YouTube</a> |
            <a href="https://tiktok.com/@kymh_mosakoani" target="_blank">TikTok</a> |
            <a href="https://www.instagram.com/kymh_mosakoani?igsh=a2gybXJuZXQ2OWZs" target="_blank">Instagram</a> |
            <a href="https://www.facebook.com/kymh.mosakoani" target="_blank">Facebook</a>
        </p>
        <form>
            <h3>Contactez-moi</h3>
            <label for="name">Nom :</label><br>
            <input type="text" id="name" name="name" required><br><br>
            <label for="email">Email :</label><br>
            <input type="email" id="email" name="email" required><br><br>
            <label for="message">Message :</label><br>
            <textarea id="message" name="message" required></textarea><br><br>
            <button type="submit">Envoyer</button>
        </form>
    </section>
</div>

<footer>
    <p>&copy; 2023 Kymh Mosakoani. Tous droits réservés.</p>
</footer>

</body>
</html>
