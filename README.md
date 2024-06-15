<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>iOS Style Calculator</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="calculator">
        <div class="display">
            <input type="text" id="display" placeholder="0" readonly>
        </div>
        <div class="buttons">
            <button class="button" onclick="clearDisplay()">AC</button>
            <button class="button" onclick="deleteChar()">DEL</button>
            <button class="button" onclick="appendOperator('/')">÷</button>
            <button class="button" onclick="appendOperator('*')">×</button>

            <button class="button" onclick="appendNumber('7')">7</button>
            <button class="button" onclick="appendNumber('8')">8</button>
            <button class="button" onclick="appendNumber('9')">9</button>
            <button class="button" onclick="appendOperator('-')">−</button>

            <button class="button" onclick="appendNumber('4')">4</button>
            <button class="button" onclick="appendNumber('5')">5</button>
            <button class="button" onclick="appendNumber('6')">6</button>
            <button class="button" onclick="appendOperator('+')">+</button>

            <button class="button" onclick="appendNumber('1')">1</button>
            <button class="button" onclick="appendNumber('2')">2</button>
            <button class="button" onclick="appendNumber('3')">3</button>
            <button class="button equal" onclick="calculate()">=</button>

            <button class="button zero" onclick="appendNumber('0')">0</button>
            <button class="button" onclick="appendNumber('.')">.</button>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
