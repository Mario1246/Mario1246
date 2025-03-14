- 👋 Hi, I’m @Mario1246
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Proyecto Ayuda a Desvalidos</title>
  <style>
    /* Estilos generales */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: #00539C;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }
    nav {
      background: #003f7d;
      padding: 10px 0;
    }
    nav ul {
      list-style: none;
      text-align: center;
      margin: 0;
      padding: 0;
    }
    nav ul li {
      display: inline;
      margin: 0 15px;
    }
    nav ul li a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }
    .container {
      width: 90%;
      max-width: 1000px;
      margin: auto;
      overflow: hidden;
      padding: 20px;
      background: #fff;
    }
    section {
      padding: 20px 0;
      border-bottom: 1px solid #ccc;
    }
    footer {
      background: #00539C;
      color: #fff;
      text-align: center;
      padding: 15px 0;
    }
    form {
      display: flex;
      flex-direction: column;
    }
    form input, form textarea {
      margin-bottom: 10px;
      padding: 10px;
      font-size: 1rem;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    form button {
      padding: 10px;
      background: #00539C;
      color: #fff;
      border: none;
      cursor: pointer;
      font-size: 1rem;
      border-radius: 4px;
    }
    form button:hover {
      background: #003f7d;
    }
    /* Estilos responsivos */
    @media(max-width: 768px) {
      nav ul li {
        display: block;
        margin: 10px 0;
      }
    }
  </style>
</head>
<body>
  <!-- Encabezado -->
  <header>
    <h1>Proyecto Ayuda a Desvalidos</h1>
    <p>Telemedicina y atención integral para los más vulnerables</p>
  </header>

  <!-- Menú de navegación -->
  <nav>
    <ul>
      <li><a href="#inicio">Inicio</a></li>
      <li><a href="#proyecto">El Proyecto</a></li>
      <li><a href="#telemedicina">Telemedicina</a></li>
      <li><a href="#atencion-mental">Salud Mental</a></li>
      <li><a href="#contacto">Contacto</a></li>
    </ul>
  </nav>

  <!-- Contenedor principal -->
  <div class="container">
    <!-- Sección de inicio -->
    <section id="inicio">
      <h2>Bienvenidos</h2>
      <p>En El Salvador, nuestro compromiso es transformar la salud y calidad de vida de las poblaciones más vulnerables. Con una red de atención integral y telemedicina, ofrecemos servicios que garantizan dignidad y bienestar para todos.</p>
    </section>

    <!-- Sección del proyecto -->
    <section id="proyecto">
      <h2>El Proyecto</h2>
      <p>El Proyecto Ayuda a Desvalidos se centra en la creación de una red de atención médica que abarca:</p>
      <ul>
        <li><strong>Identificación y Registro:</strong> Un censo digital para identificar y seguir a pacientes en situación de abandono.</li>
        <li><strong>Unidades Móviles:</strong> Equipos especializados que brindan atención psiquiátrica y médica directamente en las calles.</li>
        <li><strong>Centros de Acogida:</strong> Espacios de estabilización y rehabilitación integral.</li>
      </ul>
    </section>

    <!-- Sección de telemedicina -->
    <section id="telemedicina">
      <h2>Telemedicina Integral</h2>
      <p>La telemedicina es el pilar de nuestro sistema de salud, permitiendo:</p>
      <ul>
        <li>Acceso a una plataforma nacional de historia clínica electrónica.</li>
        <li>Consultas remotas y seguimiento continuo de tratamientos.</li>
        <li>Monitoreo a distancia y equipos móviles de diagnóstico.</li>
      </ul>
    </section>

    <!-- Sección de atención a salud mental -->
    <section id="atencion-mental">
      <h2>Atención a la Salud Mental</h2>
      <p>Especialmente dedicada a los pacientes con enfermedades mentales en situación de calle, nuestra propuesta incluye:</p>
      <ul>
        <li>Unidades móviles de atención psiquiátrica y psicológica.</li>
        <li>Teleconsultas para seguimiento y derivación a tratamientos especializados.</li>
        <li>Centros de acogida y programas de rehabilitación integral.</li>
      </ul>
    </section>

    <!-- Sección de contacto -->
    <section id="contacto">
      <h2>Contacto</h2>
      <p>¿Te interesa colaborar o deseas más información? Completa el siguiente formulario para ponerte en contacto:</p>
      <form action="https://formspree.io/f/yourFormID" method="POST">
        <input type="text" id="nombre" name="nombre" placeholder="Tu nombre" required>
        <input type="email" id="email" name="email" placeholder="Tu email" required>
        <textarea id="mensaje" name="mensaje" rows="5" placeholder="Tu mensaje" required></textarea>
        <button type="submit">Enviar Mensaje</button>
      </form>
      <p>También puedes escribirnos a: <a href="mailto:contacto@proyectoayuda.org">contacto@proyectoayuda.org</a> o llamarnos al +503 1234-5678.</p>
    </section>
  </div>

  <!-- Pie de página -->
  <footer>
    <p>&copy; 2025 Proyecto Ayuda a Desvalidos. Todos los derechos reservados.</p>
  </footer>
  
  <!-- Scripts adicionales (opcional) -->
  <script>
    // Aquí puedes agregar scripts de JavaScript para mayor interactividad
    // Ejemplo: Mostrar un mensaje al enviar el formulario
    document.querySelector('form').addEventListener('submit', function(e) {
      // e.preventDefault(); // Descomentar para pruebas sin enviar el formulario
      alert('Gracias por contactarnos. Nos pondremos en contacto contigo pronto.');
    });
  </script>
</body>
</html>
<!---
Mario1246/Mario1246 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
