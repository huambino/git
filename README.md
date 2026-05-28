<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Mi Página Sencilla</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 15px;
            text-align: center;
        }
        main {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .boton {
            display: inline-block;
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
        .boton:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenido a mi página</h1>
    </header>
    <main>
        <h2>Sobre mí</h2>
        <p>Esta es una página sencilla creada en Visual Studio Code.</p>
        <a href="https://www.uss.edu.pe/uss/Inicio" class="boton">Visitar USS</a>
    </main>
    <footer>
        <p>© 2026 Mi Página</p>
    </footer>
</body>
</html>
