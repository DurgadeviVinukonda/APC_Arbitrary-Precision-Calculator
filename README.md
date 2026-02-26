# 🧮 Arbitrary Precision Calculator

An **Arbitrary Precision Calculator** is a C-based command-line application that performs arithmetic operations on **very large numbers** which exceed the limits of standard data types like `int`, `long`, or `long long`.

This project implements big number arithmetic **without using any external libraries**, relying instead on **dynamic data structures** and custom algorithms.

---

## 📌 Features

- Supports **very large integers** (hundreds or thousands of digits)
- Arithmetic operations:
  - ➕ Addition
  - ➖ Subtraction
  - ✖️ Multiplication
  - ➗ Division
- Accurate and efficient computation
- No dependency on built-in big number libraries
- Modular and beginner-friendly code

---

## 🛠️ Technologies Used

- **Language:** C  
- **Concepts:**  
  - Linked Lists  
  - Dynamic Memory Allocation  
  - Pointers  
  - Custom Arithmetic Algorithms  

---

## ⚙️ How It Works

- Numbers are stored digit-by-digit using dynamic data structures.
- Arithmetic operations are performed manually using algorithms similar to paper-based calculations.
- The result is displayed with complete accuracy, regardless of number size.

---

## ▶️ How to Compile and Run

### Compile
```bash
gcc *.c -o apc
