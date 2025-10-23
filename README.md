                # ICS-QUADRATIC-GRADER--MUTALE-MICHAEL-
# ICS-Quadratic-Grader-<Surname-Firstname>
# ICT251 Quadratic Solver & Grading System

## Project Title
**ICT251: Quadratic Solver & Grading System**  

A single-page web application built using **HTML** and **JavaScript** to solve quadratic equations and convert numeric scores to letter grades.  

---

## Project Description
This project provides two main tools in one file (`index.html`), making it easy for users to perform calculations offline:

1. **Quadratic Solver**  
   - Solves equations in the standard form: `ax² + bx + c = 0`.  
   - Automatically calculates the **discriminant (Δ = b² - 4ac)**.  
   - Determines the **nature of roots**:
     - Two distinct real roots (Δ > 0)  
     - One repeated real root (Δ = 0)  
     - Two complex conjugate roots (Δ < 0)  
   - Displays the **equation and roots** clearly, formatted for readability.  
   - Includes **input validation** to prevent invalid calculations (e.g., `a = 0` is not allowed).  

2. **Grading System**  
   - Converts a numeric score (0–100) into a **letter grade**.  
   - Follows the specified grading scale:
     - A+: 85–100  
     - A: 75–84  
     - B+: 65–74  
     - B: 60–64  
     - C+: 55–59  
     - C: 50–54  
     - D: 0–49  
   - Validates inputs to ensure the score is a number within the allowed range.  
   - Provides **immediate feedback** with a highlighted grade.  

This project is **designed for students and learners** to quickly solve equations and convert scores without requiring additional software.

---

## How to Run

1. **Download or clone** the repository from GitHub.  
2. **Open the `index.html` file** in any modern web browser such as:
   - Google Chrome  
   - Mozilla Firefox  
   - Microsoft Edge  
   - Safari  

3. **Using the Quadratic Solver**:
   - Enter values for `a`, `b`, and `c`.  
   - Click **Compute** to see the equation, discriminant, nature of roots, and the actual roots.  
   - Click **Clear** to reset the input fields and result area.  

4. **Using the Grading System**:
   - Enter a score from 0 to 100.  
   - Click **Compute** to see the corresponding letter grade.  
   - Click **Clear** to reset the input field and result area.

> The page is **fully offline** and does not require an internet connection.

---

## Test Cases

### Quadratic Solver

| a   | b   | c   | Expected Output |
|-----|-----|-----|----------------|
| 1   | -3  | 2   | Equation: 1x² - 3x + 2 = 0<br>Discriminant: 1<br>Two distinct real roots: x₁ = 2, x₂ = 1 |
| 1   | 2   | 1   | Equation: 1x² + 2x + 1 = 0<br>Discriminant: 0<br>One repeated real root: x = -1 |
| 1   | 2   | 5   | Equation: 1x² + 2x + 5 = 0<br>Discriminant: -16<br>Two complex roots: x₁ = -1 + 2i, x₂ = -1 - 2i |
| 2   | 5   | -3  | Equation: 2x² + 5x - 3 = 0<br>Discriminant: 49<br>Two distinct real roots: x₁ = 0.5, x₂ = -3 |
| 1   | 0   | -4  | Equation: 1x² - 4 = 0<br>Discriminant: 16<br>Two distinct real roots: x₁ = 2, x₂ = -2 |
| 1   | 0   | 4   | Equation: 1x² + 4 = 0<br>Discriminant: -16<br>Two complex roots: x₁ = 0 + 2i, x₂ = 0 - 2i |
| 0   | 2   | 3   | Error: a cannot be zero (not a quadratic equation) |
| -1  | 4   | -4  | Equation: -1x² + 4x - 4 = 0<br>Discriminant: 0<br>One repeated real root: x = 2 |

---

## Features
- **Single-page web app**: Everything is contained in `index.html`.  
- **User-friendly interface**: Clearly labeled inputs, instructions, and result display.  
- **Input validation**: Prevents invalid entries such as non-numbers or `a = 0`.  
- **Real-time feedback**: Immediately shows results after clicking **Compute**.  
- **Stylish and responsive design**: Attractive layout with hover effects.  
- **Offline functionality**: Runs locally without any server or internet connection.  

---

## Author
**Michael Mutale**  
ICT251 – Web Technologies 2025

