# Scientific & Graphing Calculator - User Manual

## Table of Contents
1. [Overview](#overview)
2. [Mode Switching](#mode-switching)
3. [Scientific Mode](#scientific-mode)
4. [Graphing Mode](#graphing-mode)
5. [Variables](#variables)
6. [Keyboard Shortcuts](#keyboard-shortcuts)
7. [Examples](#examples)
8. [Troubleshooting](#troubleshooting)

---

## Overview

This calculator has **two distinct modes**:
- **Scientific Mode**: Full-featured scientific calculator with variables and calculus
- **Graphing Mode**: Dedicated graphing calculator with live plot, table, and statistics

Switch between modes instantly using the mode buttons at the top.

---

## Mode Switching

Click **"Scientific Mode"** or **"Graphing Mode"** buttons at the top to switch.

**Seamless Integration**: In Scientific Mode, click **"TO GRAPH"** to instantly send your current equation to Graphing Mode and plot it.

---

## Scientific Mode

### Display
- **Top line (history)**: Shows previous calculations
- **Bottom line (current)**: Shows current input/result in blue monospace font

### Angle Modes
| Button | Mode | Description |
|--------|------|-------------|
| DEG | Degrees | 0-360 circle |
| RAD | Radians | 0-2π circle |
| GRAD | Gradians | 0-400 circle |

### Variables
Press variable buttons to insert into your expression:
- **x, y, z, a, b** - Use in any expression

Example: `2*x + 3` or `sin(x) + cos(y)`

### Memory Operations
| Button | Function |
|--------|----------|
| MC | Memory Clear |
| MR | Memory Recall |
| M+ | Add to memory |
| M- | Subtract from memory |
| MS | Store in memory |

### Trigonometric Functions
All trig functions respect the current angle mode (DEG/RAD/GRAD).

| Button | Function | Example (DEG) |
|--------|----------|---------------|
| sin | Sine | sin(30) = 0.5 |
| cos | Cosine | cos(60) = 0.5 |
| tan | Tangent | tan(45) = 1 |
| asin | Arcsine | asin(0.5) = 30 |
| acos | Arccosine | acos(0.5) = 60 |
| atan | Arctangent | atan(1) = 45 |
| sinh | Hyperbolic sine | sinh(1) ≈ 1.175 |
| cosh | Hyperbolic cosine | cosh(0) = 1 |
| tanh | Hyperbolic tangent | tanh(1) ≈ 0.762 |

### Logarithms & Powers
| Button | Function | Example |
|--------|----------|---------|
| log | Base-10 log | log(100) = 2 |
| ln | Natural log | ln(e) = 1 |
| log2 | Base-2 log | log2(8) = 3 |
| sqrt | Square root | sqrt(16) = 4 |
| cbrt | Cube root | cbrt(27) = 3 |
| x^2 | Square | 5^2 = 25 |
| x^3 | Cube | 2^3 = 8 |
| x^y | Power | 2^3 = 8 |
| e^x | Exponential | e^2 ≈ 7.389 |
| 10^x | Power of 10 | 10^3 = 1000 |

### Calculus Functions
| Button | Function | Description |
|--------|----------|-------------|
| d/dx | Derivative | Numerical derivative at current x value |
| integral | Integral | Definite integral from 0 to current value |
| lim | Limit | Evaluate limit |
| sum | Summation | Sum from n=1 to current value |
| prod | Product | Product from n=1 to current value |

**Note**: For calculus functions, enter an expression with variable x first, then press the calculus button.

Example:
1. Enter: `x^2`
2. Enter value: `3`
3. Press **d/dx** → calculates derivative of x² at x=3 = 6

### Constants
| Button | Value |
|--------|-------|
| pi | π ≈ 3.14159... |
| e | e ≈ 2.71828... |
| phi | φ ≈ 1.61803... (golden ratio) |

### Other Functions
| Button | Function | Example |
|--------|----------|---------|
| abs | Absolute value | abs(-5) = 5 |
| n! | Factorial | 5! = 120 |
| 1/x | Reciprocal | 1/5 = 0.2 |
| +/- | Negate | -(5) = -5 |

### Display Modes
| Button | Effect |
|--------|--------|
| FIX | Fixed decimal places |
| SCI | Scientific notation |

---

## Graphing Mode

### Layout
- **Left side**: Graphing keypad with display
- **Right side**: Graph canvas with tabs (Graph/Table/Stats)

### Variables
| Button | Use |
|--------|-----|
| x | Independent variable for f(x) |
| y | For implicit equations |
| z | Additional variable |
| t | Parametric variable |
| theta | Polar coordinates |

### Entering Equations

**Method 1: Type directly**
Click the input field and type: `sin(x)`, `x^2`, `e^x`, `log(x)`

**Method 2: Use keypad**
Use the graphing keypad buttons to build your equation

**Method 3: Send from Scientific Mode**
In Scientific Mode, click **"TO GRAPH"** to transfer your equation

### Supported Functions
- **Trigonometric**: sin(x), cos(x), tan(x)
- **Roots**: sqrt(x), cbrt(x)
- **Logs**: log(x), ln(x)
- **Exponential**: exp(x), e^x
- **Other**: abs(x)
- **Powers**: x^2, x^y (use ^ operator)

### Graph Controls

#### Viewing Window
Adjust range inputs to zoom/pan:
- **Xmin/Xmax**: Horizontal range
- **Ymin/Ymax**: Vertical range

Common windows:
- Standard: X[-10, 10], Y[-10, 10]
- Zoom in: X[-5, 5], Y[-5, 5]
- Zoom out: X[-50, 50], Y[-50, 50]

#### Multiple Functions
- Add multiple functions (each gets different color)
- Up to 8 simultaneous functions
- Click **x** to remove a function
- Click **CLR ALL** to clear all

### Tabs

#### Graph Tab
- Live plot with grid and axes
- Color-coded function lines
- Auto-scaled labels

#### Table Tab
- Numerical values for first function
- x and f(x) columns
- Updates when switching to tab

#### Stats Tab
- Domain and range
- Minimum and maximum values
- Approximate roots (where f(x) = 0)

---

## Keyboard Shortcuts

### Scientific Mode
| Key | Action |
|-----|--------|
| 0-9 | Enter numbers |
| . | Decimal point |
| + - * / | Operators |
| ( ) | Parentheses |
| ^ | Power |
| Enter / = | Calculate |
| Escape | Clear all |
| Backspace | Delete last |

### Graphing Mode
| Key | Action |
|-----|--------|
| 0-9 | Enter numbers |
| . | Decimal point |
| + - * / | Operators |
| ( ) | Parentheses |
| ^ | Power |
| Enter | Plot equation |
| Escape | Clear input |
| Backspace | Delete last |

---

## Examples

### Basic Calculations
```
2 + 3 * 4 = 14
(2 + 3) * 4 = 20
sin(30) = 0.5
cos(pi) = -1
ln(e^2) = 2
sqrt(144) = 12
5! = 120
```

### Using Variables
```
x = 5
2*x + 3 = 13
x^2 = 25
sin(x) + cos(x) ≈ -0.675
```

### Calculus
```
Expression: x^2
Value: 3
d/dx → 6 (derivative of x² at x=3)

Expression: x^2
Value: 3
integral → 9 (integral of x² from 0 to 3)

Expression: x
Value: 5
sum → 15 (1+2+3+4+5)
```

### Graphing
```
sin(x)        - Sine wave
x^2           - Parabola
x^3 - 3*x     - Cubic
e^x           - Exponential growth
exp(-x/5)*sin(x)  - Damped oscillation
log(x)        - Logarithmic
abs(x)        - Absolute value
```

### Multi-Function Graphs
Add multiple functions to compare:
```
sin(x) vs cos(x)
x^2 vs x^3
exp(x) vs ln(x)
```

---

## Troubleshooting

### "Error" Display
- Check for division by zero
- Verify function domain (e.g., sqrt of negative)
- Check parentheses are balanced
- Ensure variables are properly used

### Graph Not Showing
- Verify equation uses x as variable
- Check viewing window includes the function
- Try zooming out
- Ensure function is valid (no "Error")

### Trig Results Wrong
- Check angle mode (DEG/RAD/GRAD)
- sin(30°) = 0.5, but sin(30 rad) ≈ -0.988

### Variable Issues
- Use x, y, z, a, b buttons or type directly
- Variables must be separate from numbers (use 2*x not 2x)

### Tips
- Use parentheses liberally for correct order of operations
- Press "TO GRAPH" to quickly plot scientific calculations
- The calculator handles implicit multiplication for constants (2pi = 2*pi)
- Use ^ for powers in both modes

---

*Happy Calculating!* 🧮📈
