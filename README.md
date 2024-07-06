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
    // Obtener secciones
    const inicioSection = document.getElementById('inicio');
    const productosSection = document.getElementById('productos');
    // Aquí puedes obtener las secciones de Carrito y Feedback
    // const carritoSection = document.getElementById('carrito');
    // const feedbackSection = document.getElementById('feedback');

    // Función para ocultar todas las secciones
    function hideAllSections() {
        inicioSection.style.display = 'none';
        productosSection.style.display = 'none';
        // Ocultar otras secciones
        // carritoSection.style.display = 'none';
        // feedbackSection.style.display = 'none';
    }

    // Función para mostrar una sección específica
    function showSection(section) {
        hideAllSections();
        section.style.display = 'block';
    }

    // Agregar eventos a los enlaces de navegación
    inicioLink.addEventListener('click', () => {
        showSection(inicioSection);
    });

    productosLink.addEventListener('click', () => {
        showSection(productosSection);
    });

    // Aquí puedes agregar eventos para Carrito y Feedback
    // carritoLink.addEventListener('click', () => {
    //     showSection(carritoSection);
    // });

    // feedbackLink.addEventListener('click', () => {
    //     showSection(feedbackSection);
    // });

    // Mostrar la sección de inicio por defecto
    showSection(inicioSection);
});
