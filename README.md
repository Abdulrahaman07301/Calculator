🧮 Simple Web Calculator

This project is a basic calculator web application built using HTML, CSS, and JavaScript. It provides a clean UI and supports standard arithmetic operations such as addition, subtraction, multiplication, division, and modulus.
The interface features a gradient-themed background and a grid layout for calculator buttons, making it visually appealing and easy to use.



🚀 Features

Responsive calculator layout using CSS Grid

Supports:

➕ Addition

➖ Subtraction

✖️ Multiplication

➗ Division

% Modulus

“Clear” button to reset the input

“=” button to evaluate expressions using JavaScript’s eval()

Styled input and buttons for a clean user experience



📁 Project Structure
index.html        # Main calculator interface


🧩 How It Works


HTML

-> Contains a title, an input display, and a grid of calculator buttons.

-> Each button triggers a JavaScript function like appendNo(), clr(), or res() to update the input or calculate results.



CSS

-> Adds styling to inputs and buttons (rounded corners, large text, golden buttons).

-> Creates a modern gradient background.

-> Uses CSS Grid to position calculator buttons evenly.



JavaScript

-> Main functions:

-> appendNo(n) → Appends digits/operators to the input

-> res() → Uses eval() to compute the expression

-> clr() → Clears the input field



🖥️ Usage

-> Open the index.html file in any modern web browser.

-> Click the buttons to build a mathematical expression.

-> Press “=” to evaluate the result.

-> Press “Clear” to reset.

⚠️ Important Note

This project uses JavaScript’s eval(), which is convenient but not recommended for production applications because it can execute arbitrary code.
For learning and simple calculator demonstrations, it is acceptable.
