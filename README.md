-<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clone Netflix</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #141414;
            color: #fff;
        }

        .navbar {
            background-color: #111;
            padding: 10px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .navbar a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
        }

        .hero {
            position: relative;
            height: 60vh;
            background: url('https://via.placeholder.com/1500x600') no-repeat center center/cover;
            color: #fff;
            text-align: center;
            padding: 50px 20px;
        }

        .hero h1 {
            font-size: 3em;
            margin: 0;
        }

        .section {
            padding: 20px;
        }

        .section h2 {
            font-size: 2em;
            margin-bottom: 20px;
        }

        .movie-list {
            display: flex;
            overflow-x: auto;
        }

        .movie-list img {
            width: 150px;
            height: 225px;
            margin-right: 10px;
            border-radius: 8px;
        }

        footer {
            background-color: #111;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>

    <nav class="navbar">
        <div class="logo">
            <a href="#">Logo</a>
        </div>
        <div class="links">
            <a href="#">Home</a>
            <a href="#">Séries</a>
            <a href="#">Filmes</a>
            <a href="#">Minha Lista</a>
        </div>
    </nav>

    <header class="hero">
        <h1>Assista a Seus Filmes Favoritos</h1>
    </header>

    <section class="section">
        <h2>Em Alta</h2>
        <div class="movie-list">
            <img src="https://via.placeholder.com/150x225" alt="Filme 1">
            <img src="https://via.placeholder.com/150x225" alt="Filme 2">
            <img src="https://via.placeholder.com/150x225" alt="Filme 3">
            <img src="https://via.placeholder.com/150x225" alt="Filme 4">
            <!-- Adicione mais imagens conforme necessário -->
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Clone Netflix. Todos os direitos reservados.</p>
    </footer>

</body>
</html>
