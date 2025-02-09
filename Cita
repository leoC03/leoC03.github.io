<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¿Quieres ser mi cita?</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #ffe6e6;
            font-family: Arial, sans-serif;
        }
        .heart-button {
            position: relative;
            background-color: #ff4d4d;
            height: 60px;
            width: 60px;
            border: none;
            cursor: pointer;
            color: white;
            font-size: 16px;
            font-weight: bold;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            text-decoration: none;
            padding: 20px;
            transition: transform 0.2s, background-color 0.3s;
        }
        .heart-button:hover {
            background-color: #ff1a1a;
            transform: scale(1.1);
        }
        .heart-button::before,
        .heart-button::after {
            content: "";
            position: absolute;
            width: 60px;
            height: 100px;
            background-color: #ff4d4d;
            border-radius: 50px 50px 0 0;
            top: -50px;
        }
        .heart-button::before {
            left: -30px;
        }
        .heart-button::after {
            right: -30px;
        }
    </style>
</head>
<body>

<button class="heart-button" onclick="mostrarMensaje()">¿Sí?</button>

<script>
    function mostrarMensaje() {
        alert("¡Sabía que dirías que sí! ❤️");
    }
</script>

</body>
</html>
