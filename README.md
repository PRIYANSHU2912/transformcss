<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            margin: 0;
            padding: 0;
        }
        .container{
            border: 2px solid black;
            background-color: beige;
            height: 100vh;
           display: flex;
           justify-content: center;
           align-items: center;
        }
        .box{
            border: 2px solid black;
            background-color: aquamarine;
            width: 200px;
            height: 200px;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 15px;
            transition: all 6s 0s linear;
        }
        .box:hover{
            background-color: blue;
            transform: skew(30deg);
            text-shadow: 3px 3px 4px white;
            box-shadow: 3px 3px 10px brown;
            font-size: 25px;
        }
    </style>
</head>
<body>
    <div class="container">
    <div class="box">
        <p>WELCOME</p>
    </div>
</div>
</body>
</html>
