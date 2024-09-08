# Calculator Web Application

## Project Description:

This project is a simple calculator built using **HTML**, **CSS**, and **JavaScript**. It supports basic arithmetic operations such as addition, subtraction, multiplication, division, percentage, and also provides functionalities like reset (`AC`) and delete (`DEL`).

## Project Structure:

The project consists of three main files:

1. **`calculator.html`** - Defines the structure of the calculator and its interface.
2. **`calculator.css`** - Provides the styling for the calculator, including layout, buttons, input field, and responsiveness for smaller screens.
3. **`calculator.js`** - Contains the logic for performing the calculations and handling user interactions.

## Features:

- Basic arithmetic operations (addition, subtraction, multiplication, division, percentage).
- Special functions:
  - **AC**: Clears all input.
  - **DEL**: Deletes the last entered character.
  - **=**: Evaluates the mathematical expression.
- Responsive design for smaller screens.
- Minimalistic design with a dark theme.

## Technologies Used

- **HTML5**: For structuring the calculator layout.
- **CSS3**: For styling the calculator (including a gradient background and neumorphism button styles).
- **JavaScript**: For handling the calculation logic and user interactions.

## How to Use

1. Download or clone the repository.
2. Open `index.html` in a browser to run the calculator.
3. Use the buttons to input numbers and perform calculations.

## Code Overview

### 1. HTML (`calculator.html`)
Defines the structure of the calculator. It includes:
- An input field (`<input>`) to display the numbers and results.
- Buttons for digits, operators, and special functions (AC, DEL, =).

### 2. CSS (`calculator.css`)
- Provides styling for the calculator layout, buttons, and input field.
- Uses a **neumorphism design** for buttons, giving them a raised appearance.
- The calculator is responsive for small screen sizes.

### 3. JavaScript (`calculator.js`)
- Handles the core logic for the calculator.
- Listens for button clicks and updates the input field accordingly.
- Uses the JavaScript `eval()` function to evaluate mathematical expressions.

### JavaScript Logic:
- **Equal (`=`)**: Calculates the result using `eval()`.
- **AC**: Clears the input.
- **DEL**: Deletes the last character in the input string.
  
## Responsive Design

The calculator is designed to be responsive. The buttons and input field resize appropriately on screens smaller than 600px.

## Future Improvements

- Add more advanced operations like square root, exponentiation, etc.
- Improve the UI/UX for a more interactive experience.

