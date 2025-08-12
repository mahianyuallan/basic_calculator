# Basic Calculator

A simple and responsive calculator built with **HTML**, **CSS**, and **JavaScript**.  
This project allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.

---

## 📸 Screenshot

![Calculator Screenshot](https://github.com/mahianyuallan/basic_calculator/blob/master/basic-calculator.png?raw=true)


---

## 🚀 Features
- Perform basic arithmetic operations: **+**, **-**, **×**, **÷**
- Clear the display with a **C** button
- Handle decimal values
- Responsive and clean user interface
- Built with plain HTML, CSS, and JavaScript (no frameworks)

---

## 📂 Project Structure
basic_calculator/
│
├── index.html # HTML structure of the calculator
├── style.css # Styling for the calculator
├── index.js # JavaScript logic and event handling
└── README.md # Project documentation


---

## 💻 Usage
1. Clone or download the repository.
2. Open `index.html` in any modern web browser.
3. Use the buttons to perform calculations.

---

## 🛠 How It Works
- **index.html**: Defines the calculator's layout, including display and buttons.
- **style.css**: Styles the calculator with a grid layout and button effects.
- **index.js**:  
  - Detects button clicks.
  - Appends numbers/operators to the display.
  - Evaluates the expression using `eval()` when `=` is pressed.
  - Clears the display when `C` is pressed.

---

## ⚠️ Note
This project uses **`eval()`** for simplicity.  
In production environments, it’s recommended to avoid `eval()` for security and use a safe math parser library.

---

## 📜 License
This project is open-source and available under the **MIT License**.

---
