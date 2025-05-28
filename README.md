
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página de Juegos</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Mi Página de Juegos</h1>
            <nav>
                <ul>
                    <li><a href="#">Inicio</a></li>
                    <li><a href="#">Juegos</a></li>
                    <li><a href="#">Categorías</a></li>
                    <li><a href="#">Contacto</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main class="container">
        <section class="game-listing">
            <h2>Juegos Populares</h2>
            <div class="game-grid">
                <div class="game-card">
                    <img src="https://via.placeholder.com/200x150" alt="Imagen del Juego 1">
                    <h3>Juego de Aventura 1</h3>
                    <p>¡Explora mundos increíbles y derrota enemigos épicos!</p>
                    <a href="#" class="btn">Jugar Ahora</a>
                </div>
                <div class="game-card">
                    <img src="https://via.placeholder.com/200x150" alt="Imagen del Juego 2">
                    <h3>Juego de Estrategia 2</h3>
                    <p>Pon a prueba tu mente con desafiantes puzzles.</p>
                    <a href="#" class="btn">Jugar Ahora</a>
                </div>
                <div class="game-card">
                    <img src="https://via.placeholder.com/200x150" alt="Imagen del Juego 3">
                    <h3>Juego de Carreras 3</h3>
                    <p>Siente la velocidad y compite por el primer lugar.</p>
                    <a href="#" class="btn">Jugar Ahora</a>
                </div>
                </div>
        </section>

        <section class="categories">
            <h2>Explorar Categorías</h2>
            <ul>
                <li><a href="#">Acción</a></li>
                <li><a href="#">Aventura</a></li>
                <li><a href="#">Estrategia</a></li>
                <li><a href="#">Deportes</a></li>
                <li><a href="#">Puzzle</a></li>
            </ul>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2025 Mi Página de Juegos. Todos los derechos reservados.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>

CSS Styling (style.css)
This CSS provides basic styling to make your page look presentable.
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: #f0f2f5;
    color: #333;
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px 0;
}

header {
    background-color: #28a745; /* Color similar a Optijuegos */
    color: white;
    padding: 10px 0;
    box-shadow: 0 2px 5px rgba(0,0,0,0.2);
}

header h1 {
    margin: 0;
    float: left;
}

header nav {
    float: right;
}

header nav ul {
    margin: 0;
    padding: 0;
    list-style: none;
}

header nav ul li {
    display: inline-block;
    margin-left: 20px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

header nav ul li a:hover {
    text-decoration: underline;
}

/* Clearfix for header */
header .container::after {
    content: "";
    display: table;
    clear: both;
}

main {
    padding: 20px 0;
}

.game-listing {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    margin-bottom: 30px;
}

.game-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.game-card {
    border: 1px solid #ddd;
    border-radius: 8px;
    overflow: hidden;
    text-align: center;
    padding-bottom: 15px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
}

.game-card img {
    width: 100%;
    height: 150px;
    object-fit: cover;
    display: block;
    margin-bottom: 10px;
}

.game-card h3 {
    margin: 10px 0;
    color: #28a745;
}

.game-card p {
    padding: 0 15px;
    font-size: 0.9em;
    color: #555;
    margin-bottom: 15px;
}

.btn {
    display: inline-block;
    background-color: #007bff;
    color: white;
    padding: 8px 15px;
    border-radius: 5px;
    text-decoration: none;
    transition: background-color 0.3s ease;
}

.btn:hover {
    background-color: #0056b3;
}

.categories {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.categories ul {
    list-style: none;
    padding: 0;
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
}

.categories ul li a {
    background-color: #e2e6ea;
    color: #333;
    padding: 8px 15px;
    border-radius: 20px;
    text-decoration: none;
    transition: background-color 0.3s ease;
}

.categories ul li a:hover {
    background-color: #d1d5da;


