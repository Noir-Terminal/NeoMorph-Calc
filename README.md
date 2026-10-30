# 🧮 Neumorphism Calculator — Dark & Light

A compact, browser-based calculator with a soft **neumorphic** design, a frosted-glass display, and an animated light/dark theme switch. Built with **HTML, CSS, and vanilla JavaScript**—no framework or installation required.

## ✨ Features

- Basic arithmetic: addition, subtraction, multiplication, and division
- Decimal input, sign toggle (`+/-`), percentage conversion, and clear
- Backspace support for deleting the last entered character
- Keyboard input for digits, decimal point, and arithmetic operators
- Comma separators for large displayed numbers
- Light and dark themes with animated transitions and glowing background orbs

## 🚀 Run it

### Quick start

Open `index.html` in a modern web browser.

### Run from a local server

If Python is installed, open a terminal in this project folder and run:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## 🎮 Controls

| Action | Mouse / touch | Keyboard |
| --- | --- | --- |
| Enter a number or decimal | Click the number or `.` button | `0`–`9`, `.` |
| Choose an operation | Click `+`, `−`, `×`, or `÷` | `+`, `-`, `*`, `/` |
| Calculate | Click `=` | `Enter` or `=` |
| Delete last character | Not shown as a button | `Backspace` |
| Clear the calculation | Click `AC` or `C` | `Escape` |
| Convert current number to a percentage | Click `%` | `%` |
| Change sign | Click `+/-` | Not mapped |
| Switch appearance | Use the theme toggle | — |

The `%` button divides the currently entered number by 100. Calculations are carried out as operations are entered; this is a basic four-function calculator rather than an expression parser with parentheses or operator precedence.

## 🧩 How it works

The calculator keeps the current value, previous value, and selected operation in JavaScript. Button presses and supported key presses update this state and refresh the display. Arithmetic runs locally in your browser; no calculation data is sent to a server.

## 📁 Project files

| File | Purpose |
| --- | --- |
| `index.html` | Calculator display, buttons, and theme toggle |
| `style.css` | Neumorphic controls, light/dark color themes, and animations |
| `script.js` | Calculation state, input handling, formatting, and keyboard mapping |

## ℹ️ Notes

The design loads **Orbitron** and **Poppins** from Google Fonts. An internet connection is needed for those fonts; the calculator itself works locally without a backend.
