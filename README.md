# Project ISGC

ISGC (Interactive Scientific and Graphing Calculator) is a robust application combining scientific computation with graphing functionality. Built using the SFML (Simple and Fast Multimedia Library) for interactive graphics and the exprtk library for mathematical expression parsing, ISGC enables users to perform advanced calculations and visualize equations in real time.

This project aims to simplify complex mathematical tasks with an intuitive interface for both computation and graphing.
 
![Project ISGC](https://raw.githubusercontent.com/SafalNarsingh/Project-ISGC/refs/heads/main/Images/ISGC.png)

## Table of Contents  

1. [Screenshots](#screenshots)  
2. [Features](#features)  
3. [Usage/Examples](#usageexamples) 
4. [Dependencies](#dependencies)  
5. [Troubleshooting](#troubleshooting)  
6. [Supported Operators](#supported-operators)  
7. [Contributors](#contributors)  
8. [To-Do List](#to-do-list)  


## Screenshots

![Screenshot 1 ](https://raw.githubusercontent.com/SafalNarsingh/Project-ISGC/refs/heads/main/Images/new_1.png)


![Screenshot 2 ](https://github.com/SafalNarsingh/Project-ISGC/blob/main/Images/new_4.png?raw=true)


![Screenshot 3](https://raw.githubusercontent.com/SafalNarsingh/Project-ISGC/refs/heads/main/Images/new_5.png)


![Screenshot 4](https://raw.githubusercontent.com/SafalNarsingh/Project-ISGC/refs/heads/main/Images/new_6.png)




## Features
- Scientific Calculations:
- Common operations: sine (`sin`), cosine (`cos`), tangent (`tan`), square root (`sqrt`), logarithms (`log`), etc.
- Support for constants like `π` (`Pi`).
- Expression evaluation using `exprtk`.
- Graphing Capabilities:
    - Plot functions like `sin(x)`, `cos(x)`, `x^2`, and more.
    -   Dynamic and interactive graph rendering.
- User-Friendly Interface:
    - Two distinct modes: Scientific Calculator and Graphing.
    - Intuitive input via buttons and visual feedback.
    - Cross-Platform: Runs on systems supported by `SFML`.
## Usage/Examples

- Launch the application from your terminal or file explorer.
- Switch between Scientific Calculator and Graphing modes via the UI.
- For scientific calculations:
    - Input expressions using the provided buttons.
    - Press = to calculate results.
- For graphing:
    - Enter functions in the graphing interface (e.g., y = sin(x)).
    - View the plotted graph dynamically on the graphing panel.
## Dependencies

- **SFML**: Used for graphics rendering, window management, and event handling.
- **exprtk**: Provides fast and reliable parsing and evaluation of mathematical expressions.

Ensure these dependencies are properly installed and configured before compiling the project.
## Troubleshooting

- No Display Output: Verify SFML is correctly installed and linked during compilation.
- Function Not Plotted: Ensure the input follows valid mathematical syntax as per exprtk.
- Application Crash: Check for missing library dependencies and ensure paths are set correctly.
## Supported Operators

The calculator supports the following operators with parentheses:

| Operator | Definition         | Type  |
|----------|--------------------|-------|
| +        | Addition            | Binary|
| -        | Subtraction         | Binary|
| *        | Multiplication      | Binary|
| /        | Division            | Binary|
| x^2      | Squared             | Binary|
| x^y      | Exponential         | Binary|
| ln()     | Natural Logarithm   | Unary |
| log()    | Logarithm (Base 10) | Unary |
| sqrt()   | Square Root         | Unary |
| sin()    | Sine                | Unary |
| cos()    | Cosine              | Unary |
| tan()    | Tangent             | Unary |

## To-Do List


- [ ] Panning Functionality 
- [ ] Zoom Out, Zoom In buttons
## Contributors

- Dinisha Uprety
- Safal Narshing Shrestha

> Last updated by Safal Narshing Shrestha on Nov 23, 2024, 18:54. </br> Copyright © 2024 Safal Narshing Shrestha, Dinisha Uprety. All rights reserved.
##
