<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eventos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-image: url('IMAGEN-ARTESANO.jpg'); /* Ruta de la imagen de fondo */
            background-size: cover; /* Ajusta la imagen para cubrir todo el fondo */
            background-position: center; /* Centra la imagen */
            background-repeat: no-repeat; /* Evita que la imagen se repita */
            margin: 0;
            padding: 0;
            color: white; /* Cambia el color del texto si es necesario */
        }
        header {
            background: rgba(53, 66, 74, 0.8);
            padding: 20px;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
            background: rgba(0, 0, 0, 0.5); /* Fondo semi-transparente para el contenedor */
            border-radius: 8px; /* Bordes redondeados */
        }
        footer {
            text-align: center;
            padding: 10px;
            background: rgba(53, 66, 74, 0.8);
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .media {
            text-align: center; 
        }
        .media img, .media video {
            display: inline-block;
            max-width: 300px; /* Ajusta el tamaño de las imágenes y videos */
            margin: 10px;
            vertical-align: top;
        }
        .videos {
            text-align: center;
            margin-top: 20px; /* Ajusta el margen superior del segundo video */
        }
        .video-with-images {
            display: flex;
            justify-content: space-between;
            align-items: center; /* Alinea verticalmente en el centro */
            margin-top: 20px;
        }
        .video-with-images img, .video-with-images video {
            width: 30%; /* Ajusta el ancho de las imágenes y video */
        }
    </style>
</head>
<body>

<header>
    <h1>ARTESANO FEST 🎃</h1>
</header>

<div class="container">
    <h2>Próximos Eventos</h2>
    <p>Aquí encontrarás información sobre los próximos eventos de música en ICA.</p>
    <ul>
        <li>ARTESANO FEST HALLOWEEN 🎃 🎃 🎃🎸.</li>
        <li>DISFRUTA DE ESTE GRAN EVENTO DE ROCK POR HALLOWEEN ESTE 26 DE OCTUBRE</li>
        <li>CONCURSOS DE DISFRACES CON GRANDES PREMIOS</li>
        <li>Como bandas y artistas invitados:</li>
        <li>This fools - 6:00PM</li>
        <li>Quédate en Illinois - 6:30PM</li>
        <li>Bucle Perpetuo - 7:00PM</li>
        <li>ADSEX - 7:40PM</li>
        <li>The Nygma's - 8:20PM</li>
        <li>Piña Xpress - 9:00PM</li>
        <li>Brayan ak7 - 9:40PM</li>
        <li>COMPONEEX - 10:20PM</li>
        <li>Sebastián Aarón - 11:00PM</li>
        <li>*****ENTRADA FREE*****</li>
        <li>Nos ubicamos en Parque Campo Alegre (frente a la universidad UTP), en la tienda "Artesano".</li>
    </ul>
    
    <h2>¿QUÉ ES EL ARTESANO FEST?</h2>
    <p>El Artesano Fest es un evento que se celebra cada dos meses, donde diferentes bandas se presentan para compartir su talento y ofrecer una experiencia única a los asistentes. Es un espacio para disfrutar, celebrar y fomentar el arte y la cultura en ICA.</p>

    <!-- Sección de imágenes y video -->
    <h2>MÁS SOBRE ESTE EVENTO</h2>
    <div class="media">
        <img src="IMAGENES-ARTESANO1.jpeg" alt="Foto 1 del Artesano Fest">
        <img src="IMAGENES-ARTESANO2.jpeg" alt="Foto 2 del Artesano Fest">
        <video width="240" controls>
            <source src="VIDEO-ARTESANO1.mp4" type="video/mp4">
            Tu navegador no soporta la reproducción de videos.
        </video>
    </div>

    <!-- Sección del segundo video con imágenes alineadas a los lados del video -->
    <div class="video-with-images">
        <img src="IMAGENES-ARTESANO3.jpeg" alt="Imagen izquierda">
        <video controls>
            <source src="VIDEO-ARTESANO2.mp4" type="video/mp4">
            Tu navegador no soporta la reproducción de videos.
        </video>
        <img src="IMAGENES-ARTESANO4.jpeg" alt="Imagen derecha">
    </div>

</div>

<footer>
    <p>&copy; 2024 EN MI MUSICA IQUEÑA. Todos los derechos reservados.</p>
</footer>

</body>
</html>
