<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Ropa</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>Tienda de Ropa</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Productos</a></li>
                <li><a href="#">Carrito</a></li>
                <li><a href="#">Feedback</a></li>
                <li><a href="#">Iniciar Sesión</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="hero">
            <h2>Bienvenido a nuestra tienda de ropa</h2>
            <p>Encuentra las mejores ofertas y la última moda aquí</p>
            <a href="#" class="btn">Comprar Ahora</a>
        </section>

        <section class="destacados">
            <h2>Productos Destacados</h2>
            <div class="productos">
                <div class="producto">
                    <img src="img/producto1.jpg" alt="Producto 1">
                    <h3>Producto 1</h3>
                    <p>$20.00</p>
                </div>
                <div class="producto">
                    <img src="img/producto2.jpg" alt="Producto 2">
                    <h3>Producto 2</h3>
                    <p>$25.00</p>
                </div>
                <div class="producto">
                    <img src="img/producto3.jpg" alt="Producto 3">
                    <h3>Producto 3</h3>
                    <p>$30.00</p>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Tienda de Ropa. Todos los derechos reservados.</p>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>




/* Reset de márgenes y padding */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

header .logo h1 {
    margin: 0;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    margin-top: 0.5rem;
}

nav ul li {
    margin: 0 1rem;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.hero {
    background: url('../img/hero.jpg') no-repeat center center/cover;
    color: #fff;
    height: 400px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 1rem;
}

.hero h2 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 1.5rem;
}

.hero .btn {
    background: #333;
    color: #fff;
    padding: 0.5rem 1rem;
    text-decoration: none;
    border-radius: 5px;
}

.destacados {
    padding: 2rem;
    text-align: center;
}

.destacados h2 {
    margin-bottom: 2rem;
}

.destacados .productos {
    display: flex;
    justify-content: center;
    gap: 2rem;
}

.destacados .producto {
    border: 1px solid #ddd;
    padding: 1rem;
    border-radius: 5px;
    text-align: center;
}

.destacados .producto img {
    width: 100%;
    height: auto;
    border-radius: 5px;
    margin-bottom: 1rem;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    margin-top: 2rem;
}
