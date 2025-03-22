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

/* Estilos generales */
body {
    font-family: 'Orbitron', sans-serif;
    margin: 0;
    padding: 0;
    background: url('ruta/del/archivo.png') no-repeat center center fixed;
    background-size: cover;
    color: #fff;
}

/* Encabezado */
header {
    background: rgba(0, 0, 0, 0.8);
    padding: 20px;
    text-align: center;
    box-shadow: 0px 4px 20px rgba(0, 255, 255, 0.7);
    border-bottom: 2px solid #00ffff;
}

header h1 {
    margin: 0;
    font-size: 3em;
    text-transform: uppercase;
    color: #00ffff;
    text-shadow: 0 0 15px #00ffff, 0 0 30px #0088ff;
}

/* Menú de navegación */
nav ul {
    list-style: none;
    padding: 0;
    margin-top: 10px;
}

nav ul li {
    display: inline;
    margin: 0 20px;
}

nav ul li a {
    text-decoration: none;
    color: #00ffff;
    font-size: 1.3em;
    transition: 0.3s ease-in-out;
    padding: 10px 15px;
    border-radius: 5px;
    border: 2px solid #00ffff;
    box-shadow: 0px 0px 15px rgba(0, 255, 255, 0.5);
    background: rgba(0, 0, 0, 0.5);
}

nav ul li a:hover {
    color: #ff00ff;
    border-color: #ff00ff;
    box-shadow: 0px 0px 20px rgba(255, 0, 255, 0.7);
    text-shadow: 0 0 10px #ff00ff;
}

/* Secciones */
section {
    padding: 50px;
    text-align: center;
    background: rgba(0, 0, 0, 0.8);
    margin: 20px;
    border-radius: 10px;
    box-shadow: 0px 4px 20px rgba(0, 255, 255, 0.7);
    border: 1px solid #00ffff;
}

h2 {
    font-size: 2.5em;
    text-shadow: 0 0 15px #00ffff, 0 0 30px #0088ff;
}

/* Servicios */
.service {
    background: rgba(0, 0, 0, 0.7);
    padding: 20px;
    margin: 20px auto;
    width: 80%;
    border-radius: 10px;
    box-shadow: 0px 0px 20px rgba(0, 255, 255, 0.7);
    border: 1px solid #00ffff;
    transition: 0.3s ease-in-out;
}

.service:hover {
    transform: scale(1.05);
    box-shadow: 0px 0px 30px rgba(0, 255, 255, 0.9);
}

.service h3 {
    color: #00ffff;
    text-shadow: 0 0 10px #00ffff;
}

/* Formulario */
form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

label {
    font-size: 1.3em;
    margin-top: 10px;
}

input, textarea {
    width: 80%;
    padding: 12px;
    margin: 8px 0;
    border: none;
    border-radius: 5px;
    background: rgba(255, 255, 255, 0.1);
    color: #fff;
    font-size: 1.1em;
    text-align: center;
    outline: none;
    border-bottom: 2px solid #00ffff;
    transition: 0.3s ease-in-out;
}

input:focus, textarea:focus {
    border-bottom: 2px solid #ff00ff;
    box-shadow: 0 0 15px rgba(255, 0, 255, 0.7);
}

/* Botón futurista */
button {
    background: linear-gradient(90deg, #00ffff, #0088ff);
    color: #000;
    border: none;
    padding: 12px 25px;
    margin-top: 10px;
    font-size: 1.3em;
    cursor: pointer;
    border-radius: 5px;
    box-shadow: 0 0 15px #00ffff;
    transition: 0.3s ease-in-out;
    text-transform: uppercase;
    font-weight: bold;
    position: relative;
    overflow: hidden;
}

button::before {
    content: "";
    position: absolute;
    top: 50%;
    left: 50%;
    width: 300%;
    height: 300%;
    background: rgba(255, 255, 255, 0.1);
    transition: 0.5s ease-in-out;
    border-radius: 50%;
    transform: translate(-50%, -50%) scale(0);
}

button:hover::before {
    transform: translate(-50%, -50%) scale(1);
}

button:hover {
    background: linear-gradient(90deg, #ff00ff, #8800ff);
    box-shadow: 0 0 25px #ff00ff;
}

/* Pie de página */
footer {
    text-align: center;
    padding: 15px;
    background: rgba(0, 0, 0, 0.8);
    border-top: 2px solid #00ffff;
    box-shadow: 0px -4px 20px rgba(0, 255, 255, 0.7);
    font-size: 1.2em;
}


// Validación del formulario de contacto
document.getElementById('contact-form').addEventListener('submit', function(event) {
    event.preventDefault(); // Evita que el formulario se envíe de forma predeterminada

    // Obtener los valores del formulario
    const name = document.getElementById('name').value;
    const email = document.getElementById('email').value;
    const message = document.getElementById('message').value;

    // Validar que todos los campos estén completos
    if (name === '' || email === '' || message === '') {
        alert('Por favor, completa todos los campos.');
    } else {
        alert('¡Gracias por contactarnos! Nos pondremos en contacto pronto.');
        // Aquí se puede agregar lógica para enviar el formulario a un servidor
    }
});
