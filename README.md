<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GENKA LOGISTICS</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #008000;
            color: white;
            padding: 1.5em 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #006400;
        }
        nav a {
            color: white;
            padding: 1em;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #004d00;
        }
        section {
            padding: 2em;
        }
        .services, .testimonials, .tracking {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .service, .testimonial {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 1em;
            padding: 1em;
            width: 30%;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .tracking-item {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 1em;
            padding: 2em;
            width: 45%;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .tracking-item img {
            max-width: 100%;
            border-radius: 5px;
            margin-bottom: 1em;
        }
        footer {
            background-color: #006400;
            color: white;
            text-align: center;
            padding: 1em 0;
            position: relative;
            width: 100%;
            bottom: 0;
        }
        form {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 1em;
            width: 50%;
            margin: 0 auto;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        form input, form textarea {
            width: 100%;
            padding: 0.5em;
            margin: 0.5em 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        form button {
            background-color: #008000;
            color: white;
            border: none;
            padding: 0.5em 1em;
            border-radius: 5px;
            cursor: pointer;
        }
        form button:hover {
            background-color: #006400;
        }
        .tracking-item h3 {
            color: #008000;
        }
        .tracking-item p {
            margin: 0.5em 0;
        }
        .tracking-item ul {
            list-style-type: none;
            padding: 0;
        }
        .tracking-item li {
            display: flex;
            align-items: center;
            margin-bottom: 0.5em;
        }
        .tracking-item li i {
            margin-right: 0.5em;
            color: #008000;
        }
    </style>
</head>
<body>
    <header>
        <h1>GENKA LOGISTICS</h1>
        <p>Rastreo de Embarques Maritimos y Terrestres</p>
    </header>
    <nav>
        
        <a href="#testimonios">Testimonios</a>
        <a href="#seguimiento">Seguimiento</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <section id="testimonios" class="testimonials">
        <h2>Testimonios</h2>
        <div class="testimonial">
            <p>"Excelente servicio y puntualidad. Muy recomendable."</p>
            <p>- Juan Pérez</p>
        </div>
        <div class="testimonial">
            <p>"La mejor opción para el transporte de carga en México."</p>
            <p>- María López</p>
        </div>
        <div class="testimonial">
            <p>"Siempre cumplen con los tiempos de entrega. Muy satisfecho."</p>
            <p>- Carlos Rodríguez</p>
        </div>
    </section>
    <section id="seguimiento" class="tracking">
        <h2>Seguimiento de Embarques</h2>
        <div class="tracking-item">
            <img src="https://via.placeholder.com/300x200?text=Embarque+1" alt="Embarque 1">
            <h3>Embarque 1</h3>
            <p><strong>Estado:</strong> En tránsito</p>
            <p><strong>Historial:</strong></p>
            <ul>
                <li><i class="fas fa-box-open"></i> 2023-10-01: Recogido en origen</li>
                <li><i class="fas fa-warehouse"></i> 2023-10-02: En almacén de distribución</li>
                <li><i class="fas fa-truck"></i> 2023-10-03: En ruta hacia destino</li>
            </ul>
        </div>
        <div class="tracking-item">
            <img src="https://via.placeholder.com/300x200?text=Embarque+2" alt="Embarque 2">
            <h3>Embarque 2</h3>
            <p><strong>Estado:</strong> Entregado</p>
            <p><strong>Historial:</strong></p>
            <ul>
                <li><i class="fas fa-box-open"></i> 2023-09-28: Recogido en origen</li>
                <li><i class="fas fa-warehouse"></i> 2023-09-29: En almacén de distribución</li>
                <li><i class="fas fa-check-circle"></i> 2023-09-30: Entregado en destino</li>
            </ul>
        </div>
        <!-- Repite para los demás embarques -->
    </section>
    <section id="contacto">
        <h2>Contacto</h2>
        <form>
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="mensaje">Mensaje:</label>
            <textarea id="mensaje" name="mensaje" rows="4" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2023 GENKA LOGISTICS. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
