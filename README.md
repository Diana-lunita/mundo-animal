<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Paseos para Perritos - Diana Landa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }

        header {
            background-color: #9C27B0;
            color: white;
            padding: 20px;
            text-align: center;
            font-size: 2em;
        }

        nav {
            background-color: #7B1FA2;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2em;
        }

        .hero {
            background: url('C:/Users/diana/Pictures/perritos.jpg') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }

        .hero h1, .hero p {
            color: #9C27B0;
        }

        .hero h1 {
            font-size: 3em;
            margin-bottom: 10px;
        }

        .hero p {
            font-size: 1.5em;
        }

        .content {
            padding: 40px 20px;
            text-align: center;
        }

        .content h2 {
            color: #9C27B0;
            font-size: 2em;
        }

        .zones, .experience, .contact {
            margin: 20px 0;
        }

        .zones ul {
            list-style: none;
            padding: 0;
        }

        .zones li {
            font-size: 1.2em;
            margin: 5px 0;
        }

        .footer {
            background-color: #9C27B0;
            color: white;
            text-align: center;
            padding: 15px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>Paseos para Perritos en CDMX</header>

    <nav>
        <a href="#servicios">Servicios</a>
        <a href="#zonas">Zonas</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <section class="hero">
        <h1>¡Cuidado y Paseos para tu Mejor Amigo!</h1>
        <p>Servicios profesionales para perros de todas las razas en Ciudad de México.</p>
    </section>

    <div class="content">
        <section id="servicios">
            <h2>¿Por qué Elegirme?</h2>
            <p>Soy <strong>Diana Landa</strong> y tengo <strong>5 años de experiencia</strong> cuidando y paseando mascotas. Me especializo en brindar un servicio cariñoso y seguro para perros de todas las razas.</p>
            <p>¡Tu perrito estará feliz y saludable con mis paseos diarios!</p>
        </section>

        <section id="zonas" class="zones">
            <h2>Zonas de Servicio</h2>
            <ul>
                <li>Condesa</li>
                <li>Escandón</li>
                <li>Roma Sur</li>
                <li>Roma Norte</li>
                <li>Del Valle</li>
            </ul>
        </section>

        <section id="contacto" class="contact">
            <h2>¡Contáctame!</h2>
            <p><strong>Nombre:</strong> Diana Landa</p>
            <p><strong>Celular:</strong> <a href="tel:5541007956">5541007956</a></p>
            <p>¡Estoy lista para conocer a tu perrito!</p>
        </section>
    </div>

    <div class="footer">
        &copy; 2024 Paseos para Perritos - Diana Landa
    </div>
</body>
</html>

