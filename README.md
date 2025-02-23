
<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>你愿意让我当你的父亲吗</title>
    <style>
        body {
            background: url('assets/images/史迪仔.jpg') no-repeat center center fixed;
            background-size: cover;
            font-family: 'Comic Sans MS', sans-serif;
            text-align: center;
            color: white;
        }
        h1 {
            font-size: 3em;
            margin-top: 20%;
        }
        .btn {
            background-color: #FF6347;
            color: white;
            padding: 15px 30px;
            font-size: 1.5em;
            border: none;
            cursor: pointer;
            margin: 20px;
            border-radius: 10px;
            transition: background-color 0.3s;
        }
        .btn:hover {
            background-color: #FF4500;
        }
    </style>
</head>
<body>
    <h1>你愿意让我当你的父亲吗</h1>
    <button class="btn" onclick="playMusic()">愿意</button>
    <button class="btn" onclick="playMusic()">不愿意</button>

    <!-- 使用相对路径 -->
    <audio id="fatherMusic" src="assets/audios/father.mp3" preload="auto"></audio>

    <script>
        function playMusic() {
            var music = document.getElementById('fatherMusic');
            music.play();
        }
    </script>
</body>
</html>
