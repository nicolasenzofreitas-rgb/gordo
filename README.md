<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lista de Filmes Infantis</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            margin: 0;
            padding: 0;
        }
        h1 {
            text-align: center;
            color: #2c3e50;
            padding: 20px;
        }
        .movie-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            padding: 20px;
        }
        .movie {
            text-align: center;
            width: 150px;
            cursor: pointer;
            transition: transform 0.2s ease;
        }
        .movie img {
            width: 150px;
            height: 225px;
            border-radius: 10px;
        }
        .movie:hover {
            transform: scale(1.05);
        }
        .movie-title {
            margin-top: 10px;
            color: #34495e;
            font-size: 14px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <h1>Filmes Infantis</h1>
    <div class="movie-container">
        <div class="movie" onclick="window.location.href='https://www.youtube.com/watch?v=1lGFqEox1E4'">
            <img src="https://upload.wikimedia.org/wikipedia/pt/3/35/Frozen_II.jpg" alt="Frozen II">
            <div class="movie-title">Frozen II</div>
        </div>
        <div class="movie" onclick="window.location.href='https://www.youtube.com/watch?v=9ePrYlZjPfs'">
            <img src="https://upload.wikimedia.org/wikipedia/pt/5/58/Coco_-_Cartaz.png" alt="Coco">
            <div class="movie-title">Coco</div>
        </div>
        <div class="movie" onclick="window.location.href='https://www.youtube.com/watch?v=hpKhI-ya8JI'">
            <img src="https://upload.wikimedia.org/wikipedia/pt/3/3c/Minions_2.jpg" alt="Minions 2">
            <div class="movie-title">Minions 2</div>
        </div>
        <div class="movie" onclick="window.location.href='https://www.youtube.com/watch?v=VVpD47C1W3Y'">
            <img src="https://upload.wikimedia.org/wikipedia/pt/a/af/Uma_Aventura_Epica.jpg" alt="Uma Aventura Épica">
            <div class="movie-title">Uma Aventura Épica</div>
        </div>
        <div class="movie" onclick="window.location.href='https://www.youtube.com/watch?v=tr0HZmGOF6g'">
            <img src="https://upload.wikimedia.org/wikipedia/pt/6/6a/Carros_2_cartaz.jpg" alt="Carros 2">
            <div class="movie-title">Carros 2</div>
        </div>
        <div class="movie" onclick="window.location.href='https://www.youtube.com/watch?v=4h3eKkQGvzc'">
            <img src="https://upload.wikimedia.org/wikipedia/pt/d/d5/O_Rei_Le%C3%A3o_%282019%29_cartaz.jpg" alt="O Rei Leão">
            <div class="movie-title">O Rei Leão</div>
        </div>
    </div>
</body>
</html>
