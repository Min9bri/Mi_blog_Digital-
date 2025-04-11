# Mi_blog_Digital-
<!DOCTYPE html><html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Blog Personal</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@400;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Roboto Slab', serif;
            background-color: #fdf6f0;
            color: #333;
            line-height: 1.6;
        }
        header {
            background-color: #f4a261;
            color: white;
            padding: 1rem;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        nav {
            margin-top: 1rem;
        }
        nav a {
            background-color: #264653;
            color: white;
            padding: 0.5rem 1rem;
            text-decoration: none;
            border-radius: 5px;
            margin: 0 0.5rem;
            transition: background 0.3s;
        }
        nav a:hover {
            background-color: #2a9d8f;
        }
        section {
            padding: 2rem;
            max-width: 800px;
            margin: auto;
        }
        .volver-arriba {
            display: block;
            margin: 2rem auto;
            text-align: center;
        }
        .volver-arriba a {
            background-color: #e76f51;
            color: white;
            padding: 0.7rem 1.2rem;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
        }
        .volver-arriba a:hover {
            background-color: #d35400;
        }
        img {
            max-width: 100%;
            border-radius: 10px;
            margin-bottom: 1rem;
        }
        video {
            width: 100%;
            border-radius: 10px;
            margin-top: 1rem;
        }
    </style>
</head>
<body id="inicio">
    <header>
        <h1>Mi Blog Personal</h1>
        <nav>
            <a href="#inicio">Inicio</a>
        </nav>
    </header><section>
    <h2>Biografía</h2>
    <p>
        Bienvenidos a mi página web, donde les mostraré lo que he hecho en mis clases de Cultura Digital en mi segundo trimestre.
        Aquí podrán ver desde fotos hasta videos.
    </p>
</section>

<section>
    <h2>Galería de fotos</h2>
    <p>Aquí hay algunas imágenes representando mis clases de Cultura Digital:</p>
    <img src="https://static.canva.com/web/images/35ab2b40073ffb8b3c24cf84767b0d11.jpg" alt="Clase de Cultura Digital 1">
    <p>En esta imagen se ve cuando trabajamos en Canva para crear presentaciones interactivas.</p>

    <img src="https://static.canva.com/web/images/17b97a7c0c5393c7e88ad80ad3be8b64.jpg" alt="Clase de Cultura Digital 2">
    <p>Este fue el día que exploramos herramientas de diseño para redes sociales.</p>
</section>

<section>
    <h2>Video del trimestre</h2>
    <p>Este es uno de los videos que representa lo trabajado en clase:</p>
    <video controls>
        <source src="VID-20250331-WA0013(1).mp4" type="video/mp4">
        Tu navegador no soporta la reproducción de videos.
    </video>
</section>

<div class="volver-arriba">
    <a href="#inicio">Volver al inicio</a>
</div>

</body>
</html>
