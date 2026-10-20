Name: NG LING NA

Student ID: AI240142

Course: BIC21203 Web Development



This repository contains solutions for Lab #4a: Client-Side Scripting (JavaScript). The lab focuses on modern client-side JavaScript techniques, including DOM selection, event handling using addEventListener(), input validation with conditional logic, dynamic element creation using loops, and safe text updates via textContent.



**How to Run?**

Prerequisites

1. Any modern web browser (Google Chrome, Microsoft Edge)

2. No external libraries or node modules are required.



**Instructions**

1. Clone or download this repository:

https://github.com/lingnaa/bic21203-lab4a-javascript.git

2. Open any question file (q1.html, q2.html, or q3.html)

3. Double-click the HTML file (or open it with VS Code Live Server) to run the code in your web browser.



**Implementation Details and Output Evidence**

### Q1. Interactive Text Changer

Changes paragraph text from "Welcome to my website!" to "Hello there!" upon clicking a button.

**JS Features Used:** `document.getElementById()`, `textContent`, `addEventListener("click", ...)`.

**Output Evidence:**
* **q1 1.jpeg** (Initial State)
  
  ![q1 1.jpeg](q1%201.jpeg)

* **q1 2.jpeg** (After Click - Message Changed)
  
  ![q1 2.jpeg](q1%202.jpeg)



### Q2. Smart Number Validator

Reads user input, validates against empty string or non-numeric values, and displays whether the number is lower than, higher than, or equal to 10.

**JS Features Used:** `if...else`, `isNaN()`, `trim()`, `textContent`.

**Test Cases & Outputs:**

1. Input: 5 Output: "The number is lower than 10"
2. Input: 10 Output: "The number is equal to 10"
3. Input: 15 Output: "The number is higher than 10"
4. Input: abc Output: "Please enter a valid number!"
5. Input: [empty] Output: "Please enter a valid number!"

**Output Evidence:**
* **q2 1.jpeg** (Initial State)
  
  ![q2 1.jpeg](q2%201.jpeg)

* **q2 2.jpeg** (Input: 1 -> "The number is lower than 10")
  
  ![q2 2.jpeg](q2%202.jpeg)

* **q2 3.jpeg** (Input: 10 -> "The number is equal to 10")
  
  ![q2 3.jpeg](q2%203.jpeg)

* **q2 4.jpeg** (Input: 50 -> "The number is higher than 10")
  
  ![q2 4.jpeg](q2%204.jpeg)



### Q3. Dynamic Number Generator

Generates an ordered list numbered from 1 to 5 dynamically. Clears previous list items before each generation to prevent duplicate outputs on repeated clicks.

**JS Features Used:** `for` loop, `document.createElement('li')`, `textContent = ""`, `.appendChild()`.

**Output Evidence:**
* **q3 1.jpeg** (Initial State)
  
  ![q3 1.jpeg](q3%201.jpeg)

* **q3 2.jpeg** (After Click - Generated Number List 1 to 5)
  
  ![q3 2.jpeg](q3%202.jpeg)
