<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Bienvenido a TEMBA, donde nos comprometemos a ofrecer la mejor atención.">
    <title>Mi Página Gratis</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Bienvenido a TEMBA </h1>
        <p>Nuestro compromiso es ofrecerte la mejor atención para ti.</p>
    </header>

    <section>
        <h2>Servicios</h2>
        <p>Ofrecemos una variedad de servicios para satisfacer tus necesidades:</p>
        <ul>
            <li>Asesoría Personalizada</li>
            <li>Soporte Técnico 24/7</li>
            <li>Descuentos en Servicios Premium</li>
        </ul>
    </section>

    <section>
        <h2>Contáctanos</h2>
        <p>Si tienes preguntas, no dudes en contactarnos:</p>
        <form method="POST" action="enviar.php">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>
            <br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <br>
            <input type="submit" value="Enviar">
        </form>
    </section>

    <footer>
        <p>&copy; 2023 TEMBA. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
