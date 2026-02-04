README for calculator.html - Basic Calculator

Overview:
This is a simple interactive calculator (calculator.html) built using HTML, CSS, and JavaScript. It provides basic arithmetic operations and serves as a demonstration of front-end web development skills.

Features:
- Display screen for showing input and results
- Number buttons (0-9) and decimal point
- Operator buttons for addition (+), subtraction (-), multiplication (*), and division (/)
- Clear button (C) to reset the display
- Equals button (=) to calculate the result
- Error handling for invalid expressions
- Responsive design with centered layout
- Button hover effects for better user experience

Technologies Used:
- HTML5 (structure and buttons)
- CSS3 (styling, grid layout for buttons, colors, and transitions)
- JavaScript (event listeners, calculation logic using eval(), display updates)

How to Use:
1. Open calculator.html in a web browser
2. Click number buttons to input digits
3. Click operator buttons to select operations
4. Click equals (=) to compute the result
5. Click clear (C) to reset the calculator
6. The display shows the current input and final result

Implementation Notes:
- Uses CSS Grid for button alignment
- JavaScript eval() function for calculation (simple but not recommended for production due to security)
- Event listeners attached to buttons for interactivity
- Basic error handling with try-catch for invalid inputs
- Accessible with aria-label on the display input

Limitations:
- No advanced functions (square root, etc.)
- No memory functions
- Simple error handling (shows "Error" for invalid expressions)
- eval() can be a security risk in real applications

Future Improvements:
- Add more mathematical functions
- Implement proper expression parsing instead of eval()
- Add keyboard support
- Include calculation history
- Enhance styling and animations

