# web-01

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Imagen de Fondo</title>
    <style>
        body {
            background-image: url('fondo n1.jpg'); /* Imagen de fondo */
            background-size: cover; /* Ajusta la imagen para cubrir toda la pantalla */
            background-position: center; /* Centra la imagen */
            background-repeat: no-repeat; /* Evita que la imagen se repita */
            margin: 0;
            font-family: Arial, sans-serif;
        }
        h1, p {
            color: white; /* Color del texto para contrastar con el fondo */
            text-align: center; /* Centra el texto */
        }
    </style>
</head>
<body>
    <h1>¡Hola Mundo!</h1>
    <p>Este es un ejemplo de una página con una imagen de fondo.</p>
</body>
</html>










<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dividir Página en Secciones</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            height: 100vh;
        }
        .section {
            flex: 1;
            padding: 20px;
            box-sizing: border-box;
        }
        .section-1 {
            background-color: #f8b400; /* Color de fondo para la primera sección */
        }
        .section-2 {
            background-color: #34ace0; /* Color de fondo para la segunda sección */
        }
        .section-3 {
            background-color: #2ed573; /* Color de fondo para la tercera sección */
        }
        /* Opcional: para ajustar los tamaños de las secciones */
        .section-1 {
            flex: 2; /* La primera sección ocupa el doble de espacio */
        }
        .section-2, .section-3 {
            flex: 1;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="section section-1">
            <h1>Sección 1</h1>
            <p>Contenido de la primera sección.</p>
        </div>
        <div class="section section-2">
            <h1>Sección 2</h1>
            <p>Contenido de la segunda sección.</p>
        </div>
        <div class="section section-3">
            <h1>Sección 3</h1>
            <p>Contenido de la tercera sección.</p>
        </div>
    </div>
</body>
</html>



















<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sección de Texto Distinta</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .main-section {
            padding: 20px;
            background-color: #f0f0f0;
        }
        .distinct-section {
            padding: 20px;
            background-color: #007BFF; /* Color de fondo diferente */
            color: white; /* Color del texto diferente */
            text-align: center; /* Centrar el texto */
            margin: 20px 0; /* Espaciado arriba y abajo */
        }
        h1 {
            margin-top: 0;
        }
    </style>
</head>
<body>
    <div class="main-section">
        <h1>Sección Principal</h1>
        <p>Este es el contenido de la sección principal.</p>
    </div>
    <div class="distinct-section">
        <h1>Sección Distinta</h1>
        <p>Este es el contenido de la sección con un estilo diferente.</p>
    </div>
    <div class="main-section">
        <h1>Otra Sección Principal</h1>
        <p>Este es el contenido de otra sección principal.</p>
    </div>
</body>
</html>
