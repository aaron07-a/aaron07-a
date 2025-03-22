<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>QuickBuy - Tienda Online</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
</head>
<body>
    <header>
        <h1>QuickBuy</h1>
        <nav>
            <ul>
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Productos</a></li>
                <li><a href="#">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="productos">
            <h2>Nuestros Productos</h2>
            <div class="producto">
                <img src="producto1.jpg" alt="Producto 1">
                <h3>Producto 1</h3>
                <p>$19.99</p>
                <button onclick="agregarAlCarrito('Producto 1', 19.99)">Añadir al carrito</button>
            </div>
            <div class="producto">
                <img src="producto2.jpg" alt="Producto 2">
                <h3>Producto 2</h3>
                <p>$24.99</p>
                <button onclick="agregarAlCarrito('Producto 2', 24.99)">Añadir al carrito</button>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 QuickBuy - Todos los derechos reservados.</p>
    </footer>
</body>
</html>
