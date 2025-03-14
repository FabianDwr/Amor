<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pedido Fofo</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            background-color: #ffe6f2;
            color: #ff4d88;
        }
        .container {
            margin-top: 100px;
        }
        h1 {
            font-size: 28px;
        }
        .btn {
            background-color: #ff4d88;
            color: white;
            padding: 10px 20px;
            font-size: 18px;
            border: none;
            cursor: pointer;
            margin: 10px;
            border-radius: 10px;
            transition: 0.3s;
        }
        .btn:hover {
            background-color: #ff1a66;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Você quer namorar comigo? 💖</h1>
        <button class="btn" onclick="aceitou()">Sim 💞</button>
        <button class="btn" onclick="negou()">Não 💔</button>
    </div>

    <script>
        function aceitou() {
            alert("Aaaahhh! Você é a pessoa mais linda e maravilhosa do mundo! 💖🥰");
        }

        function negou() {
            window.open("implorando.html", "_blank");
        }
    </script>
</body>
</html>
