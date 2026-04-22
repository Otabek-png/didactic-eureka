# didactic-eureka
;             
<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>siz</title>
    <style>
        /* Sahifa */
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh; /* E */
            background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%); /* Chiroyli ranglar */
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: white;
            overflow: hidden;
        }

        /* Yozuvning ko'rinishi va animatsiyasi */
        h1 {
            font-size: 5rem;
            text-shadow: 2px 4px 10px rgba(0, 0, 0, 0.3);
            animation: paydoBolish 2s ease-in-out infinite alternate;
            text-align: center;
        }

        /* Yozuv sekin o'sib-kichrayishi uchun animatsiya */
        @keyframes paydoBolish {
            from {
                transform: scale(1);
                opacity: 0.8;
            }
            to {
                transform: scale(1.1);
                opacity: 1;
            }
        }

        /* Mobil telefonlar uchun moslashtirish */
        @media (max-width: 600px) {
            h1 {
                font-size: 2.5rem;
            }
        }
    </style>
</head>
<body>

    <h1>Yozib turinglo</h1>

</body>
</html>
