# Basic-NUM-calculator-by-using-c++
Here's the README with instructions for your program:

---

# Num Calculator

## Overview

The **Num Calculator** is a simple command-line calculator that provides various mathematical operations and conversions. It can perform addition, subtraction, multiplication, division, exponentiation, and multiplication tables. Additionally, it supports converting temperatures between Celsius and Fahrenheit.

## Features

1. **Addition**: Add two numbers.
2. **Subtraction**: Subtract one number from another.
3. **Multiplication**: Multiply two numbers.
4. **Division**: Divide one number by another.
5. **Exponentiation**: Raise a number to a power.
6. **Multiplication Table**: Display the multiplication table for a chosen number up to a specified range.
7. **Celsius to Fahrenheit**: Convert a temperature from Celsius to Fahrenheit.
8. **Fahrenheit to Celsius**: Convert a temperature from Fahrenheit to Celsius.

## Instructions

### 1. Compile the Program
To compile the program, ensure you have a C++ compiler like GCC, Clang, or MSVC.

- **Using GCC/Clang**: Open the terminal/command prompt and run:
  ```bash
  g++ -o num_calculator num_calculator.cpp
  ```
  This will compile the code into an executable file called `num_calculator`.

### 2. Run the Program
To run the compiled program, use the following command in the terminal:
- **On Windows**:
  ```bash
  num_calculator.exe
  ```
- **On Linux/macOS**:
  ```bash
  ./num_calculator
  ```

### 3. Navigate the Menu
Upon launching the program, you will be presented with the main menu:

```
Welcome to Num Calculator

1.Enter
0.Quit
```

- **Enter (1)**: Select this option to open the control panel and choose an operation.
- **Quit (0)**: Select this option to exit the program.

### 4. Use the Control Panel
Once you select **Enter (1)**, the control panel will display a menu of operations:

```
Control Panel

Operators:

1. Addition
2. Subtraction
3. Multiplication
4. Division
5. Exponent
6. Multiplication Table
7. Celsius to Fahrenheit
8. Fahrenheit to Celsius

0. Back
```

### 5. Select an Operation
You can now choose any of the following options by entering the corresponding number:

- **Addition (1)**: Adds two numbers.
- **Subtraction (2)**: Subtracts one number from another.
- **Multiplication (3)**: Multiplies two numbers.
- **Division (4)**: Divides one number by another.
- **Exponentiation (5)**: Raises a number to a power (exponentiation).
- **Multiplication Table (6)**: Displays the multiplication table for a chosen number.
- **Celsius to Fahrenheit (7)**: Converts a temperature in Celsius to Fahrenheit.
- **Fahrenheit to Celsius (8)**: Converts a temperature in Fahrenheit to Celsius.
- **Back (0)**: Return to the main menu.

### 6. Enter Values
When prompted by the program, you will need to input the required values:

- For arithmetic operations like addition, subtraction, multiplication, and division, the program will ask for two numbers.
- For exponentiation, you will be asked for a base and an exponent.
- For the multiplication table, you will input a number and a range.
- For temperature conversions, you will input the temperature in either Celsius or Fahrenheit.

### 7. Example Usage

If you select **1. Addition**, you will be prompted:

```
Addition
First Number: 10
Second Number: 5
```

The program will display:
```
15
```

For **7. Celsius to Fahrenheit**, you will be prompted:

```
Celsius to Fahrenheit
Temperature: 25
```

The program will display:
```
77°F
```

## Troubleshooting

- **Invalid Input**: If you enter a non-numeric value when prompted for numbers, the program may ask for input again. Make sure to enter valid numerical values.
- **Division by Zero**: If you attempt to divide by zero, the program will handle the error gracefully and display a result for that case.

