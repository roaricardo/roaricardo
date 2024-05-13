<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Compartiendo Información</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #333;
      color: #fff;
      padding: 10px 0;
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
      color: #fff;
      text-decoration: none;
    }
    .container {
      width: 80%;
      margin: auto;
      padding: 20px 0;
    }
    .welcome {
      text-align: center;
      margin-bottom: 20px;
    }
    .about, .services, .information, .contact {
      margin-bottom: 40px;
    }
    footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 10px 0;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <h1>Compartiendo Información</h1>
    <nav>
      <ul>
        <li><a href="#about">Acerca de</a></li>
        <li><a href="#services">Servicios</a></li>
        <li><a href="#information">Información</a></li>
        <li><a href="#contact">Contacto</a></li>
      </ul>
    </nav>
  </header>

  <div class="container">
    <section id="about" class="about">
      <h2>Acerca de</h2>
      <p>Inserta aquí la información sobre tu empresa o proyecto.</p>
    </section>

    <section id="services" class="services">
      <h2>Servicios</h2>
      <p>Descripción de los servicios ofrecidos.</p>
    </section>

    <section id="information" class="information">
      <h2>Información</h2>
      <p>Artículos o publicaciones informativas.</p>
    </section>

    <section id="contact" class="contact">
      <h2>Contacto</h2>
      <form action="#" method="post">
        <label for="name">Nombre:</label><br>
        <input type="text" id="name" name="name" required><br>
        <label for="email">Correo electrónico:</label><br>
        <input type="email" id="email" name="email" required><br>
        <label for="message">Mensaje:</label><br>
        <textarea id="message" name="message" required></textarea><br>
        <input type="submit" value="Enviar">
      </form>
    </section>
  </div>

  <footer>
    <p>&copy; 2024 Compartiendo Información</p>
  </footer>
</body>
</html>
