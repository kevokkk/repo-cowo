# repo-cowo
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8">
    <title>Mi sitio web</title>
    <link rel="stylesheet" href="css/estilos.css">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/5.0.0-alpha2/css/bootstrap.min.css" integrity="sha384-IlR13UaYolYvd6SLzI3mIVDslW2PFdRO+jP6Zozp6eI1MnRr6rY1XEWTjG/vzN+" crossorigin="anonymous">
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/5.0.0-alpha2/js/bootstrap.min.js" integrity="sha384-TvXPoljl77z9+a39BxpCpG8OrOxRSwK8BiI2QblqzqfITzX9yW1TISdE6UZw6UZj" crossorigin="anonymous"></script>
  </head>
  <body>
    <header>
      <h1 class="navbar-logo"><a href="#">Mi sitio web</a></h1>
      <button class="navbar-toggle">
        <span></span>
        <span></span>
        <span></span>
      </button>
      <ul class="navbar-menu">
        <li><a href="#about">Sobre nosotros</a></li>
        <li><a href="#activities">Actividades</a></li>
        <li><a href="#pricing">Precios</a></li>
        <li><a href="#staff">Nuestro equipo</a></li>
        <li><a href="#contact">Contáctanos</a></li>
      </ul>
    </header>
    <main>
      <section id="about">
        <div class="intro-text">
          <h2>Sobre nosotros</h2>
          <p>¡Bienvenido a nuestro sitio web! Somos una empresa dedicada a brindar experiencias únicas e inolvidables a nuestros clientes.</p>
        </div>
        <img class="intro-image" src="imagen-intro.jpg" alt="Imagen de introducción">
      </section>
      <section id="activities">
        <h2>Actividades</h2>
        <div class="card">
          <h3>Actividad 1</h3>
          <p>Descripción de la actividad 1.</p>
          <a href="#">Más información</a>
        </div>
        <div class="card">
          <h3>Actividad 2</h3>
          <p>Descripción de la actividad 2.</p>
          <a href="#">Más información</a>
        </div>
        <div class="card">
          <h3>Actividad 3</h3>
          <p>Descripción de la actividad 3.</p>
          <a href="#">Más información</a>
        </div>
      </section>
      <section id="pricing">
        <h2>Precios</h2>
        <div class="card">
          <h3>Plan básico</h3>
          <p>Descripción del plan básico.</p>
          <a href="#">Más información</a>
        </div>
        <div class="card">
          <h3>Plan premium</h3>
          <p>Descripción del plan premium.</p>
          <a href="#">Más información</a>
        </div>
        <div class="card">
          <h3>Plan deluxe</h3>
          <p>Descripción del plan deluxe.</p>
          <a href="#">Más información</a>
        </div>
      </section>
      <section id="staff">
        <h2>Nuestro equipo</h2>
        <div class="card">
          <h3>Nombre del miembro del equipo 1</h3>
          <p>Cargo del miembro del equipo 1.</p>
          <a href="#">Más información</a>
        </div>
        <div class="card">
          <h3>Nombre del miembro del equipo 2</h3>
          <section id="contact">
            <div class="container">
              <h2>Contacto</h2>
              <p>Por favor complete el formulario para ponerse en contacto con nosotros.</p>
              <form>
                <label for="name">Nombre:</label>
                <input type="text" id="name" name="name" required>
          
                <label for="email">Correo Electrónico:</label>
                <input type="email" id="email" name="email" required>
          
                <label for="subject">Asunto:</label>
                <input type="text" id="subject" name="subject" required>
          
                <label for="message">Mensaje:</label>
                <textarea id="message" name="message" required></textarea>
          
                <button type="submit">Enviar</button>
              </form>
            </div>
          </section>
          
          <footer>
            <div class="container">
              <div class="footer-info">
                <p><strong>Gimnasio XYZ</strong></p>
                <p>Dirección: Calle Falsa 123, Ciudad Imaginaria</p>
                <p>Teléfono: +54 11 1234 5678</p>
              </div>
              <div class="footer-social">
                <a href="https://www.instagram.com"><i class="fab fa-instagram"></i></a>
                <a href="https://www.facebook.com"><i class="fab fa-facebook-f"></i></a>
                <a href="https://twitter.com"><i class="fab fa-twitter"></i></a>
                <a href="https://www.linkedin.com"><i class="fab fa-linkedin-in"></i></a>
              </div>
            </div>
          </footer>
          