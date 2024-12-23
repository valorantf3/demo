<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lời cảm ơn </title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f8ff;
            margin: 0;
            font-family: 'Courier New', Courier, monospace;
            overflow: hidden;
        }
        .container {
            text-align: center;
            padding: 20px;
            border: 2px solid #ff69b4;
            border-radius: 15px;
            background-color: #fff0f5;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
            animation: fadeIn 2s ease-in-out;
        }
        h1 {
            color: #ff1493;
            animation: textGlow 1.5s infinite alternate;
        }
        p {
            font-size: 1.2em;
            color: #4b0082;
        }
        button {
            padding: 10px 20px;
            background-color: #ff69b4;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
            transition: background-color 0.3s ease;
        }
        button:hover {
            background-color: #ff1493;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes textGlow {
            from { text-shadow: 0 0 10px #ff69b4, 0 0 20px #ff69b4, 0 0 30px #ff69b4; }
            to { text-shadow: 0 0 20px #ff1493, 0 0 30px #ff1493, 0 0 40px #ff1493; }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Cảm ơn </h1>
        <p>nhấn vào cái nút bên dưới để nhận được sự bất ngờ nhé:3 😊</p>
        <button onclick="showMessage()">Nhấn vào đây</button>
        <p id="message" style="display: none;">Cảm ơn đã xem và chúc cậu một ngày mới thật vui nhé  ❤️</p>
    </div>

    <script>
        function showMessage() {
            document.getElementById("message").style.display = "block";
        }
    </script>
</body>
</html>