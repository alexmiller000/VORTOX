<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Vorlox</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto+Condensed:wght@300;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            overflow: hidden;
            font-family: 'Roboto Condensed', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(45deg, #1e3c72, #2a5298, #3b5998, #8a3ab9);
            background-size: 400% 400%;
            animation: gradient 15s ease infinite;
        }

        @keyframes gradient {
            0% { background-position: 0% 0%; }
            50% { background-position: 100% 100%; }
            100% { background-position: 0% 0%; }
        }

        .content {
            text-align: center;
            color: white;
            text-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }

        h1 {
            font-size: 3.5em;
            margin: 0;
            font-weight: 700;
            letter-spacing: 3px;
            text-transform: uppercase;
        }

        p {
            font-size: 1.3em;
            margin: 10px 0;
            font-weight: 300;
            opacity: 0.9;
        }

        .contact {
            font-size: 1.1em;
            margin-top: 20px;
            opacity: 0.8;
            transition: opacity 0.3s ease;
        }

        .contact:hover {
            opacity: 1;
        }

        a {
            color: white;
            text-decoration: none;
        }

        @media (max-width: 600px) {
            h1 {
                font-size: 2.5em;
            }
            p {
                font-size: 1em;
            }
            .contact {
                font-size: 0.9em;
            }
        }
    </style>
</head>
<body>
    <div class="content">
        <h1>Vorlox</h1>
        <p>Financial Technology of the Future</p>
        <div class="contact">
            <a href="mailto:gazam609@gmail.com">gazam609@gmail.com</a>
        </div>
    </div>
</body>
</html>