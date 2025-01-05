<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Farbauswahl</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        button {
            margin: 10px;
            padding: 15px 30px;
            font-size: 16px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .color1 {
            background-color: #ff5733;
            color: white;
        }
        .color2 {
            background-color: #33c4ff;
            color: white;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Wähle eine Farbe</h1>
        <button class="color1" onclick="alert('Farbe 1 gewählt!')">Farbe 1</button>
        <button class="color2" onclick="alert('Farbe 2 gewählt!')">Farbe 2</button>
    </div>
</body>
</html>
