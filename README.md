<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kobard & Mögle Services</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                <img src="Km.png" alt="Kobard & Mögle Logo" style="height: 80px;">
            </div>
            <ul>
                <li><a href="#about">Sobre Nosotros</a></li>
                <li><a href="#services">Servicios</a></li>
                <li><a href="#team">Equipo</a></li>
                <li><a href="#contact">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="hero">
        <h1>Bienvenidos a Kobard & Mögle Services</h1>
        <p>Ofrecemos soluciones personalizadas en asistencia, restauración, eventos y más.</p>
        <a href="#services" class="cta-button">Descubre nuestros servicios</a>
    </section>

    <section id="about">
        <h2>Sobre Nosotros</h2>
        <p>Somos Ariadna Kobard, abogada con experiencia internacional, y Stefanie Mögle, experta en marketing y desarrollo de negocios. Nuestro objetivo es brindar servicios de alta calidad adaptados a las necesidades de nuestros clientes, con un enfoque multilingüe y profesional.</p>
    </section>

    <section id="services">
        <h2>Servicios</h2>
        <div class="service">
            <h3>Ayuda a Personas Mayores</h3>
            <p>Acompañamiento diario, gestión de documentación legal y organización de actividades sociales.</p>
        </div>
        <div class="service">
            <h3>Compra y Venta / Restauración de Muebles</h3>
            <p>Venta y restauración de muebles vintage, así como compra y reventa de piezas seleccionadas.</p>
        </div>
        <div class="service">
            <h3>Gestión de Eventos</h3>
            <p>Planificación integral de eventos corporativos y sociales, con un enfoque multilingüe.</p>
        </div>
    </section>

    <section id="team">
        <h2>Conoce al Equipo</h2>
        <div class="team-member">
            <h3>Ariadna Kobard</h3>
            <p>Abogada experta en derecho internacional, con fluidez en francés, inglés y español.</p>
        </div>
        <div class="team-member">
            <h3>Stefanie Mögle</h3>
            <p>Marketing Manager y Business Development Manager, con dominio de alemán, español e inglés.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contacto</h2>
        <p>¿Tienes preguntas o necesitas más información? Contáctanos:</p>
        <form action="/submit" method="post">
            <label for="name">Nombre:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Correo Electrónico:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Mensaje:</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Kobard & Mögle. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
