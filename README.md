-<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Catálogo de Perfumes</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Encabezado -->
  <header>
    <h1>Catálogo de Perfumes</h1>
    <input type="text" id="busqueda" placeholder="Buscar perfumes..." />
    <button id="verCarrito" class="btnCarrito">Ver Carrito</button>
  </header>

  <!-- Contenedor de productos -->
  <section id="catalogo"></section>

  <!-- Carrito de compras -->
  <div id="carritoPanel" class="carritoPanel">
    <h2>Carrito de Compras</h2>
    <div id="listaCarrito"></div>
    <p>Total: <span id="totalCarrito">$0</span></p>
    <button id="cerrarCarrito" class="btnCerrarCarrito">Cerrar</button>
  </div>

  <footer>
    <h3>Opciones de pago:</h3>
    <p>Crédito, Débito, PayPal</p>
  </footer>

  <script src="app.js"></script>
</body>
</html>
