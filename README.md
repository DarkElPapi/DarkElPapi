<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feliz Día</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #f0e68c;
            font-family: Arial, sans-serif;
        }
        #sunflower {
            width: 100px;
            animation: spin 5s linear infinite;
        }
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        #message {
            text-align: center;
            font-size: 24px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <img id="sunflower" src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2b/Yellow_flower.svg/512px-Yellow_flower.svg.png" alt="Girasol">
    
    <div id="message">
        ¡Feliz 21 de septiembre!<br>
        ¡Feliz día, mi niñita hermosa! ❤️<br>
        Te Amo, Mika ❤️
    </div>

</body>
</html>
