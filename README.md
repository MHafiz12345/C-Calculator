# 🧮 Scientific Calculator in C++

A console-based scientific calculator written in C++. Capable of performing a variety of mathematical operations, from basic arithmetic to advanced trigonometry and expression evaluation. Includes a history tracking feature for storing past calculations.

---

## 📌 Features

- **Basic Operations**
  - Addition
  - Subtraction
  - Multiplication
  - Division
- **Advanced Functions**
  - Square Root
  - Powers and Exponents
  - Logarithms (Base 10, Natural Logarithm, Custom Base)
- **Trigonometric Functions**
  - sin, cos, tan (in degrees)
  - arcsin, arccos, arctan (results in radians and degrees)
- **Custom Expression Evaluation**
  - Input expressions like `5+3`, `2^4`, `2r16`, `s30`, `n5`, etc.
- **History Feature**
  - View and delete calculation history

---

## 📂 Project Structure

. ├── main.cpp # Program entry point ├── addition.* # Addition logic ├── substraction.* # Subtraction logic ├── multiplication.* # Multiplication logic ├── division.* # Division logic ├── sqrt.* # Square root logic ├── powerclass.* # Power/exponentiation logic ├── log10.* # Log base 10 ├── naturallogarithm.* # Natural log (ln) ├── LogCustomBase.* # Log with custom base ├── Trigonometry.* # Basic trig functions ├── advance_trig.* # Inverse trig functions ├── History.* # Linked list-based history tracking


---

## 💡 Custom Expression Guide

| Symbol | Operation             | Example     |
|--------|------------------------|-------------|
| `+`    | Addition               | `5+3`       |
| `-`    | Subtraction            | `10-4`      |
| `*`    | Multiplication         | `7*2`       |
| `/`    | Division               | `8/2`       |
| `^`    | Power                  | `2^3`       |
| `r`    | Root                   | `2r16` (√16) |
| `s`    | sin (degrees)          | `s30`       |
| `c`    | cos (degrees)          | `c60`       |
| `t`    | tan (degrees)          | `t45`       |
| `a`    | arcsin → degrees       | `a1`        |
| `q`    | arccos → degrees       | `q1`        |
| `e`    | arctan → degrees       | `e1`        |
| `l`    | log base 10            | `l100`      |
| `n`    | natural log (ln)       | `n5`        |

> ⚠️ No spaces are allowed in expressions.

---

## 🧠 How It Works

1. A menu interface guides function selection.
2. Each feature is implemented via a dedicated class.
3. Results are shown immediately and stored in memory.
4. A built-in parser handles typed expressions in the custom calculator mode.

---

## 🛠️ Build & Run

### ✅ Requirements
- C++ compiler (e.g., `g++`)

### 🔧 Build Instructions

```bash
git clone https://github.com/yourusername/scientific-calculator.git
cd scientific-calculator
g++ *.cpp -o calculator

# ▶️ Run
./calculator

# 🖥️ Sample Output
==== Welcome to our Scientific Calculator! ====
Press 1 for addition
Press 2 for subtraction
...
Press 14 for custom calculation

Enter your expression (NO SPACE):
2r16
Final answer: 4

# 📜 History Options
- View History → Option 12
- Clear History → Option 13
