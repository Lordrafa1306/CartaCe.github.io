<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carta para Cesia</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #ffe4e1;
            font-family: Arial, sans-serif;
        }

        .card {
            background: #fff;
            width: 90%;
            max-width: 400px;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            text-align: center;
        }

        .card h1 {
            color: #e91e63;
            font-size: 24px;
            margin-bottom: 15px;
        }

        .card p {
            color: #333;
            font-size: 18px;
            line-height: 1.6;
        }

        .heart {
            margin: 20px auto;
            width: 50px;
            height: 50px;
            background: linear-gradient(45deg, #ff4081, #ff80ab);
            position: relative;
            transform: rotate(-45deg);
        }

        .heart:before,
        .heart:after {
            content: '';
            width: 50px;
            height: 50px;
            background: linear-gradient(45deg, #ff4081, #ff80ab);
            border-radius: 50%;
            position: absolute;
        }

        .heart:before {
            top: -25px;
            left: 0;
        }

        .heart:after {
            top: 0;
            left: 25px;
        }
    </style>
</head>
<body>
    <div class="card">
        <h1>Para Cesia, con todo mi corazón:</h1>
        <p>En este Día de San Valentín, quiero recordarte lo especial que eres para mí. Tu sonrisa ilumina mis días, y tu amor es el regalo más hermoso que la vida me ha dado. Cada momento contigo es un tesoro, y cada recuerdo que creamos juntamente.</p>
        <p>Cesia, gracias por ser mi refugio, mi fortaleza y mi alegría. Hoy quiero prometerte que haré todo lo posible por seguir siendo la razón detrás de tus sonrisas y el apoyo en tus días difíciles.</p>
        <p>Te amo con todo mi corazón y</p>
        <p><strong>Feliz Día de San Valentín, mi amor.</strong></p>
        <div class="heart"></div>
    </div>
</body>
</html>
