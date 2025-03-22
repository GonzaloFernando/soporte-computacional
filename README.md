<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Soporte Informático</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Soporte Informático</h1>
        <nav>
            <ul>
                <li><a href="#servicios" class="btn">Servicios</a></li>
                <li><a href="#contacto" class="btn">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="servicios">
        <h2>Servicios que ofrecemos</h2>
        <div class="service">
            <h3>Asistencia remota</h3>
            <p>Ayuda a distancia para resolver problemas informáticos sin necesidad de estar físicamente presentes.</p>
        </div>
        <div class="service">
            <h3>Reparación de Hardware</h3>
            <p>Reparamos y sustituimos componentes de tu ordenador, como discos duros, RAM, tarjetas gráficas, etc.</p>
        </div>
        <div class="service">
            <h3>Instalación de Software</h3>
            <p>Instalación de sistemas operativos, programas antivirus, y otras herramientas para optimizar tu equipo.</p>
        </div>
        <div class="service">
         <h3>Mantenimiento de equipos</h3>
            <p>Realizamos mantenimiento de hardware y Software para que puedas tener tu equipo en optimas condiciones.</p>
        </div>
    </section>

    <section id="contacto">
        <h2>Contacta con nosotros</h2>
        <form id="contact-form">
            <label for="name">Nombre:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Correo electrónico:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Mensaje:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit" class="btn">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Soporte Informático | Todos los derechos reservados</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
