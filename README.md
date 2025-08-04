
# 🧮 Java Console Calculator

## 📘 Overview

The **Java Console Calculator** is a simple command-line calculator application written in Java. It allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division using console input and output. The calculator runs in a loop, enabling multiple calculations until the user chooses to exit.

## ✨ Features

* ➕ **Addition**: Calculate the sum of two numbers.
* ➖ **Subtraction**: Find the difference between two numbers.
* ✖️ **Multiplication**: Multiply two numbers.
* ➗ **Division**: Divide one number by another (with division-by-zero protection).
* 🚪 **Exit Option**: Safely exit the calculator when finished.

## ⚙️ How It Works

1. **🔔 Start the Program**
   The calculator displays a welcome message and a menu of operations.

2. **⌨️ User Input**

   * The user selects an operation by entering a number (1-5).
   * If an arithmetic operation is chosen (1-4), the user is prompted to enter two numbers.

3. **🧠 Perform Calculation**

   * The program calls the corresponding method (`add`, `subtract`, `multiply`, or `divide`) to compute the result.
   * The result is displayed on the console.

4. **🔁 Repeat or 🚫 Exit**

   * After each calculation, the menu is shown again.
   * If the user chooses option 5, the program exits.

## 🗂️ Code Structure

* **🔧 Methods for Operations**
  Each arithmetic operation is implemented as a static method:

  ```java
  public static double add(double a, double b)
  public static double subtract(double a, double b)
  public static double multiply(double a, double b)
  public static double divide(double a, double b)
  ```

  🔒 The `divide` method checks for division by zero and returns `Double.NaN` if attempted.

* **🧵 Main Loop**
  The main method uses a `Scanner` for user input and a loop to continuously prompt the user until exit.

## 💻 Example Usage

```
=== Java Console Calculator ===
Choose operation: 
1. Addition (+)
2. Subtraction (-)
3. Multiplication (*)
4. Division (/)
5. Exit
Enter your choice (1-5): 1
Enter first number: 10
Enter second number: 20
Result: 30.0
```

## 🧰 Requirements

* ☕ **Java JDK** (8 or above)
* 🖥️ **VS Code**, **IntelliJ CE**, or any Java IDE
* 💬 **Terminal/Command Prompt**

## ▶️ Running the Calculator

1. 💾 Save the code in a file named `ConsoleCalculator.java`.
2. 🔨 Compile the code:

   ```
   javac ConsoleCalculator.java
   ```
3. 🚀 Run the program:

   ```
   java ConsoleCalculator
   ```

## 📚 Learning Outcomes

* ✍️ Practice in using Java syntax and logical flow
* 🔁 Experience with console I/O in Java using `Scanner`
* 🧩 Understanding of methods, loops, conditionals, and basic error handling

## 📄 License

This project is for **educational purposes**.
