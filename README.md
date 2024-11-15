# HTML-
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ITSEC SUCRE</title>
    <style>
        /* Estilos básicos para diseño */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #003366;
            color: white;
            padding: 10px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #0059b3;
            padding: 10px 0;
        }
        nav a {
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            background-color: #004080;
        }
        .section {
            padding: 20px;
        }
        .section img {
            width: 100%;
            max-width: 400px;
        }
        footer {
            background-color: #003366;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <!-- Encabezado Principal -->
    <header>
        <h1>ITSEC SUCRE</h1>
    </header>

    <!-- Barra de Navegación -->
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#sistemas-informaticos">Sistemas Informáticos</a>
        <a href="#motivo-eleccion">Motivo de Elección</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <!-- Sección de Inicio -->
    <section id="inicio" class="section">
        <h2>Inicio</h2>
        <p><strong>Misión:</strong> [Descripción de la misión del ITSEC SUCRE]</p>
        <p><strong>Visión:</strong> [Descripción de la visión del ITSEC SUCRE]</p>
        <p><strong>Ubicación:</strong> [Dirección física y enlaces a mapas]</p>
        <img src="ruta-a-imagen-mision-vision.jpg" alt="Imagen de misión y visión">
    </section>

    <!-- Sección de Sistemas Informáticos -->
    <section id="sistemas-informaticos" class="section">
        <h2>Sistemas Informáticos</h2>
        <p>Información sobre la carrera de Sistemas Informáticos en el ITSEC SUCRE.</p>
        <img src="ruta-a-imagen-sistemas-informaticos.jpg" alt="Imagen de Sistemas Informáticos">
    </section>

    <!-- Sección de Motivo de Elección -->
    <section id="motivo-eleccion" class="section">
        <h2>Motivo de Elección de la Carrera</h2>
        <p>Razones personales para elegir la carrera de Sistemas Informáticos y cómo contribuye a los objetivos personales y profesionales.</p>
        <p><strong>¿Cómo me enteré del ITSEC SUCRE?:</strong> [Descripción breve]</p>
        <img src="ruta-a-imagen-motivo-eleccion.jpg" alt="Imagen sobre motivo de elección">
    </section>

    <!-- Sección de Contacto -->
    <section id="contacto" class="section">
        <h2>Contacto</h2>
        <p>Información de contacto del estudiante o enlaces relevantes.</p>
        <ul>
            <li>Email: <a href="mailto:estudiante@itsecsucre.edu.bo">estudiante@itsecsucre.edu.bo</a></li>
            <li>Teléfono: [Número de contacto]</li>
            <li>Redes Sociales: 
                <a href="https://www.facebook.com/ITSECSucre" target="_blank">Facebook</a>,
                <a href="https://twitter.com/ITSECSucre" target="_blank">Twitter</a>
            </li>
        </ul>
        <!-- Formulario de Contacto -->
        <form action="/enviar-mensaje" method="post">
            <label for="nombre">Nombre:</label><br>
            <input type="text" id="nombre" name="nombre" required><br>
            
            <label for="email">Correo Electrónico:</label><br>
            <input type="email" id="email" name="email" required><br>
            
            <label for="mensaje">Mensaje:</label><br>
            <textarea id="mensaje" name="mensaje" rows="4" required></textarea><br>
            
            <button type="submit">Enviar</button>
        </form>
    </section>

    <!-- Pie de Página -->
    <footer>
        <p>&copy; 2023 ITSEC SUCRE. Todos los derechos reservados.</p>
    </footer>

</body>
</html>
