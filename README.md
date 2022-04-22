<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HIPNOCLASS</title>
    <style>
        body{
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container{
            width: 100%;
            height: 300px;
            position: relative;
        }
       .tiles{
            display: flex;
            width: 100%;
            height: 300px;
        }
        .tiles [class*="tile"] {
            height: 300px;
            width: 5%;
            background: #2962ff;
        }
        .tile1{
            transition: all 0.1s;
        }
        .tile2{
            transition: all 0.2s;
        }
        .tile3{
            transition: all 0.3s;
        }
        .tile4{
            transition: all 0.4s;
        }
        .tile5{
            transition: all 0.5s;
        }
        .tile6{
            transition: all 0.6s;
        }
        .tile7{
            transition: all 0.7s;
        }
        .tile8{
            transition: all 0.8s;
        }
        .tile9{
            transition: all 0.9s;
        }
        .tile10{
            transition: all 1s;
        }
        .content{
            position: absolute;
            top: 0;
            z-index: -1;
            color: white;
            background: #0088cc;
            height: 300px;
            width: 100%;
            display: flex;
            justify-content: center;
            align-content: center;
            flex-direction: column;
            font-family: Arial, Helvetica, sans-serif;
        }
        .container:hover .tiles [class*="tile"]{
            background: white;
            /* opacity: 0; */
            transform: scaleY(0)
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="tiles">
            <div class="tile10"></div>
            <div class="tile9"></div>
            <div class="tile8"></div>
            <div class="tile7"></div>
            <div class="tile6"></div>
            <div class="tile5"></div>
            <div class="tile4"></div>
            <div class="tile3"></div>
            <div class="tile2"></div>
            <div class="tile1"></div>
            <div class="tile1"></div>
            <div class="tile2"></div>
            <div class="tile3"></div>
            <div class="tile4"></div>
            <div class="tile5"></div>
            <div class="tile6"></div>
            <div class="tile7"></div>
            <div class="tile8"></div>
            <div class="tile9"></div>
            <div class="tile10"></div>
        </div>
        <div class="content">
            <h1>HIPNOCLASS</h1>
            <h2>    Hipnose científica é coisa séria!</h2>
        </div>
    </div>
</body>
</html>
