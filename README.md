# Delicias-Chic
Una página web de repostería artesanal
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Delicias Chic - Proyecto Escolar</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #fff8f0;
    }
    header {
      background-color: #f28ab2;
      color: white;
      padding: 15px;
      text-align: center;
    }
    header h1 {
      margin: 0;
    }
    nav {
      background-color: #ffcad4;
      display: flex;
      justify-content: center;
      padding: 10px;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    nav a:hover {
      color: #f28ab2;
    }
    section {
      padding: 20px;
    }
    .producto {
      display: flex;
      align-items: center;
      margin-bottom: 20px;
    }
    .producto img {
      width: 150px;
      height: auto;
      margin-right: 15px;
      border-radius: 8px;
    }
    footer {
      background-color: #f28ab2;
      color: white;
      text-align: center;
      padding: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Delicias Chic <small>- Proyecto Escolar</small></h1>
    <img src="logo.png" alt="Logo Delicias Chic" width="80">
  </header>

  <nav>
    <a href="#productos">Productos</a>
    <a href="#servicios">Servicios</a>
    <a href="#promociones">Promociones</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="productos">
    <h2>Productos</h2>
    <div class="producto">
      <img src="pastel.jpg" alt="Pastel de chocolate">
      <div>
        <h3>Pastel de Chocolate</h3>
        <p>Suave y esponjoso, con cobertura de ganache.</p>
        <p><strong>Precio:</strong> $250 MXN</p>
      </div>
    </div>
    <div class="producto">
      <img src="cupcake.jpg" alt="Cupcake de vainilla">
      <div>
        <h3>Cupcake de Vainilla</h3>
        <p>Decorado con crema de mantequilla y chispas.</p>
        <p><strong>Precio:</strong> $35 MXN</p>
      </div>
    </div>
  </section>

  <section id="servicios">
    <h2>Servicios</h2>
    <p>Ofrecemos repostería personalizada para cumpleaños, bodas y eventos especiales. También damos talleres de decoración de postres.</p>
  </section>

  <section id="promociones">
    <h2>Promociones</h2>
    <p>¡Compra 5 cupcakes y el sexto es gratis!</p>
    <p>10% de descuento en pedidos mayores a $500 MXN.</p>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <p>Teléfono: <a href="tel:9843113566">984 311 3566</a></p>
    <p>Correo: deliciaschic@ejemplo.com</p>
  </section>

  <footer>
    <p>&copy; 2026 Delicias Chic - Proyecto Escolar</p>
  </footer>
</body>
</html>
