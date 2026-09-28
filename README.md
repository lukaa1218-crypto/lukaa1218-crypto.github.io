<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>My Website</title>

    <style>
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            background: #000;
        }

        body {
            display: flex;
            justify-content: center;
            align-items: center;

            color: red;
            font-family: monospace;
        }

        .blink {
            font-size: 40px;
            font-weight: bold;

            animation: blink 1s infinite;
        }

        @keyframes blink {
            0%, 49% {
                opacity: 1;
            }

            50%, 100% {
                opacity: 0;
            }
        }
    </style>
</head>

<body>

    <div class="blink">
        DEIN TEXT HIER
    </div>

</body>
</html>
