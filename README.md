# Calculator

This project implements a basic calculator with a clean user interface and responsive design.

## Features

- Basic arithmetic operations (addition, subtraction, multiplication, division)
- Decimal point support
- Clear screen functionality
- Backspace (DEL) button to remove last entered character
- Error handling for invalid calculations
- Responsive design with hover and active states
- Modern dark theme interface

## Project Structure

```
calculator/
│
├── index.html      # Main HTML structure
├── style.css       # Styling and layout
└── script.js       # Calculator functionality
```

## Technical Details

### HTML
- Semantic HTML5 markup
- Responsive viewport meta tag
- Calculator layout using div containers
- Buttons for numbers, operations, and control functions

### CSS
- Flexbox for centering the calculator
- CSS Grid for button layout
- Custom styling including:
  - Dark theme with RGB colors
  - Circular buttons with hover effects
  - Distinctive styling for operation buttons
  - Responsive text sizing
  - Custom font family

### JavaScript
- Event-driven functionality
- Core functions:
  - `appendToDisplay()`: Adds numbers and operators to display
  - `clearScreen()`: Resets the calculator
  - `calculate()`: Processes and evaluates the mathematical expression
  - `backSpace()`: Removes the last entered character
- Error handling for invalid calculations

## Usage

1. Visit https://calculate7289.netlify.app/ 
2. Use the calculator by clicking the buttons:
   - Numbers 0-9 for input
   - Operators (+, -, *, /) for calculations
   - '=' to evaluate expressions
   - 'C' to clear the display
   - 'DEL' to remove the last character

## Styling

The calculator features a dark theme with:
- Main background: RGB(19, 31, 31)
- Calculator background: Black
- Button background: RGB(43, 56, 56)
- Operation buttons: RGB(231, 154, 12)
- White text for contrast
- Interactive hover and active states for better user feedback

## Future Improvements

Potential enhancements could include:
- Scientific calculator functions
- Keyboard input support
- History of calculations
- Memory functions (M+, M-, MR, MC)
- Parentheses support
- Percentage calculations

## License

This project is available for open use and modification. Feel free to customize it for your needs.