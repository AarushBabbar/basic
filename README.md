    <!DOCTYPE html>
<html>
    <head>
        <title>Understanding Properties and their values</title>
        <link href="style.css" rel="stylesheet">
    <style>
        .division{
            border: 2px black solid;
            height: 100px;
            width: 100px;
            background: blue;
            border-radius: 50% ;
            position: absolute;
            animation: animation-1 5s infinite;
        }
        /*Animation*/
        @keyframes animation-1{
            0% {top: 0px; left: 0px;}
            25% {top: 0px; left: 200px;}
         50% {top: 200px; left: 200px; background: red;}
         75% { top: 200px; left: 0px;}
         100% {top: 0px; left:0px;}
        }
    </style>
</head>
    <body>
        <div class="division"></div>
    </body>
</html>
