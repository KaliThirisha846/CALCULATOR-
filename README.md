

1. Project Overview

Create a basic calculator with HTML for structure, CSS for styling, and JavaScript for functionality. The calculator should handle basic operations like addition, subtraction, multiplication, and division.

2. Technologies Used

HTML: Structure of the calculator (buttons, display)

CSS: Styling for a modern look

JavaScript: Functionality for calculations


3. Key Features

A display screen to show input and results.

Buttons for numbers (0-9) and operators (+, -, *, /).

A clear button to reset the calculator.

A functional "=" button to evaluate expressions.


4. Basic HTML Structure

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Calculator</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="calculator">
        <input type="text" id="display" disabled>
        <div class="buttons">
            <button onclick="clearDisplay()">C</button>
            <button onclick="appendCharacter('/')">/</button>
            <button onclick="appendCharacter('*')">*</button>
            <button onclick="appendCharacter('-')">-</button>
            
            <button onclick="appendCharacter('7')">7</button>
            <button onclick="appendCharacter('8')">8</button>
            <button onclick="appendCharacter('9')">9</button>
            <button onclick="appendCharacter('+')">+</button>

            <button onclick="appendCharacter('4')">4</button>
            <button onclick="appendCharacter('5')">5</button>
            <button onclick="appendCharacter('6')">6</button>
            <button onclick="calculateResult()">=</button>

            <button onclick="appendCharacter('1')">1</button>
            <button onclick="appendCharacter('2')">2</button>
            <button onclick="appendCharacter('3')">3</button>
            <button onclick="appendCharacter('0')" class="zero">0</button>
            <button onclick="appendCharacter('.')">.</button>
        </div>
    </div>
    <script src="script.js"></script>
</body>
    
7. Summary

HTML creates the structure of the calculator.

CSS styles the buttons and display.

JavaScript adds functionality to handle calculations.


Would you like to add any extra features, such as dark mode or advanced operations (square root, percentage, etc.)?

