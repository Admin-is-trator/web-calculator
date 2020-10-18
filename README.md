<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" type="text/css" href="style.css">
    <link href="https://fonts.googleapis.com/css?family=Open+Sans:600,700" rel="stylesheet">
    <title>Simple Calculator</title>
</head>
<body>
    <div id="container">
        <div id="calculator">
            <div id="result">
                <div id="history">
                    <p id="history-value">9*9</p>
                </div>
                <div id="output">
                    <p id="output-value">81</p>
                </div>
            </div>
            <div id="keyboard">
                <button class="operator" id="clear">C</button>
                <button class="operator" id="backspace">CE</button>
                <button class="operator" id="%">%</button>
                <button class="operator" id="/">&#247;</button>
                <button class="number" id="7">7</button>
                <button class="number" id="8">8</button>
                <button class="number" id="9">9</button>
                <button class="operator" id="*">&times;</button>
                <button class="number" id="4">4</button>
                <button class="number" id="5">5</button>
                <button class="number" id="6">6</button>
                <button class="operator" id="-">-</button>
                <button class="number" id="1">1</button>
                <button class="number" id="2">2</button>
                <button class="number" id="3">3</button>
                <button class="operator" id="+">+</button>
                <button class="empty" id="empty"></button>
                <button class="number" id="0">0</button>
                <button class="empty" id="empty"></button>
                <button class="operator" id="=">=</button>
            </div>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
