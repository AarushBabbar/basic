Code as described/written in the video
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript Tutorial</title>
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        .container {
            border: 2px solid red;
            margin: 3px 0;
            background: cyan;
            padding: 9px;
        }

        .bg-primary {
            background-color: blueviolet;
        }

        .text-success {
            color: white;
        }
    </style>
</head>
<body>
    <h1>Welcome to this JavaScript Tutorial</h1>
    <div id="firstContainer" class="container">
        <button id="click" onclick="clicked()">Click Me</button>
        <p>This is a paragraph which is the best para of this universe</p>
    </div>
    <div class="container">
        <p>This is a paragraph</p>
    </div>
    <script src="index.js"></script>
</body>
</html>
