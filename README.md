<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pikselowany Kot</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #E2E8E1;
        }
        .pixel-cat {
            display: grid;
            grid-template-columns: repeat(16, 20px);
            grid-template-rows: repeat(16, 20px);
            gap: 1px;
        }
        .pixel {
            width: 20px;
            height: 20px;
        }
        .pixel.orange { background-color: #FFA500; }
        .pixel.black { background-color: #000000; }
        .pixel.white { background-color: #FFFFFF; }
        .pixel.pink { background-color: #FFC0CB; }
        .pixel.yellow { background-color: #FFFF00; }
        .pixel.green { background-color: #00FF00; }
        .pixel.blue { background-color: #0000FF; }
    </style>
</head>
<body>

<div class="pixel-cat">
    <!-- 16x16 pixel art grid for the cat and flowers -->
    <div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.green"></div>
    <div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.black"></div><div class="pixel.black"></div><div class="pixel.black"></div><div class="pixel.black"></div><div class="pixel.orange"></div><div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.green"></div>
    <div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.black"></div><div class="pixel.white"></div><div class="pixel.white"></div><div class="pixel.white"></div><div class="pixel.white"></div><div class="pixel.black"></div><div class="pixel.orange"></div><div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.green"></div>
    <div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.black"></div><div class="pixel.white"></div><div class="pixel.black"></div><div class="pixel.white"></div><div class="pixel.black"></div><div class="pixel.white"></div><div class="pixel.black"></div><div class="pixel.orange"></div><div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.green"></div>
    <div class="pixel.green"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.black"></div><div class="pixel.white"></div><div class="pixel.black"></div><div class="pixel.white"></div><div class="pixel.white"></div><div class="pixel.white"></div><div class="pixel.black"></div><div class="pixel.white"></div><div class="pixel.black"></div><div class="pixel.orange"></div><div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.green"></div>
    <div class="pixel.green"></div><div class="pixel.orange"></div><div class="pixel.black"></div><div class="pixel.white"></div><div class="pixel.black"></div><div class="pixel.white"></div><div class="pixel.black"></div><div class="pixel.black"></div><div class="pixel.black"></div><div class="pixel.white"></div><div class="pixel.black"></div><div class="pixel.white"></div><div class="pixel.black"></div><div class="pixel.orange"></div><div class="pixel.green"></div><div class="pixel.green"></div>
    <div class="pixel.green"></div><div class="pixel.orange"></div><div class="pixel.black"></div><div class="pixel.white"></div><div class="pixel.white"></div><div class="pixel.white"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.white"></div><div class="pixel.white"></div><div class="pixel.white"></div><div class="pixel.black"></div><div class="pixel.orange"></div><div class="pixel.green"></div><div class="pixel.green"></div>
    <div class="pixel.green"></div><div class="pixel.black"></div><div class="pixel.orange"></div><div class="pixel.black"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.black"></div><div class="pixel.orange"></div><div class="pixel.black"></div><div class="pixel.orange"></div><div class="pixel.green"></div><div class="pixel.green"></div>
    <div class="pixel.green"></div><div class="pixel.black"></div><div class="pixel.orange"></div><div class="pixel.black"></div><div class="pixel.orange"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.orange"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.orange"></div><div class="pixel.black"></div><div class="pixel.orange"></div><div class="pixel.black"></div><div class="pixel.orange"></div><div class="pixel.green"></div><div class="pixel.green"></div>
    <div class="pixel.green"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.orange"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.green"></div><div class="pixel.green"></div>
    <div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.green"></div><div class="pixel.green"></div>
    <div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.orange"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.orange"></div><div class="pixel.green"></div><div class="pixel.green"></div>
    <div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.pink"></div><div class="pixel.orange"></div><div class="pixel.green"></div><div class="pixel.green"></div>
    <div class="pixel.green"></div><div class="pixel.green"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.orange"></div><div class="pixel.green"></div><div class="pixel.green"></div>
</div>

</body>
</html>
