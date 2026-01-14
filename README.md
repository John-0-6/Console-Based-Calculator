# Console-Based Calculator (Java)

A simple **console-based calculator** built in **Java**. This program allows users to perform basic arithmetic operations while handling invalid inputs safely using exception handling.

---

## Features

- Supports basic arithmetic operations:
  - Addition (`+`)
  - Subtraction (`-`)
  - Multiplication (`*`)
  - Division (`/`)
- Input validation using `try-catch`
- Prevents division by zero
- Accepts only valid operators
- Displays results formatted to **2 decimal places**

---

## Technologies Used

- Java  
- `Scanner` for user input  
- Exception handling with `InputMismatchException`  
- Control flow using loops and `switch` expressions  

---

## How It Works

1. The user enters the **first number**.
   - Invalid inputs are rejected until a valid number is provided.
2. The user enters a **valid operator** (`+`, `-`, `*`, `/`).
3. The user enters the **second number**.
   - Division by zero is prevented.
4. The program calculates and displays the result.

---

## Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/John-0-6/Calculator-Console-Based.git
