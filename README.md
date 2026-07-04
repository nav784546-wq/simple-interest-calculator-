# Simple Interest Calculator

## Introduction

The Simple Interest Calculator is a Bash shell script that calculates the simple interest earned or payable on a principal amount over a specified period of time. This project is intended to demonstrate basic shell scripting concepts, including user input, arithmetic calculations, variables, and output formatting. It is designed to be simple, lightweight, and easy to understand for beginners who are learning Bash scripting and GitHub project management.

The script accepts three values from the user:
- Principal Amount
- Annual Rate of Interest
- Time Period (in years)

Using these values, it calculates the simple interest using the standard mathematical formula and displays the result on the screen.

---

## Objective

The objective of this project is to provide a simple command-line utility that performs simple interest calculations accurately and efficiently. It also serves as an educational example for users who want to learn:
- Basic Bash scripting
- User input handling
- Arithmetic operations in shell scripts
- Git and GitHub project management
- Open-source project structure

---

## Features

- Calculates simple interest accurately.
- Accepts user input from the terminal.
- Uses a standard mathematical formula.
- Easy to execute on any system with Bash installed.
- Lightweight and requires no external libraries.
- Beginner-friendly source code.
- Well-documented project structure.
- Suitable for educational and demonstration purposes.

---

## Formula Used

The calculator uses the following formula:

```
Simple Interest = (Principal × Rate × Time) / 100
```

Where:

- **Principal (P)** = Original amount invested or borrowed
- **Rate (R)** = Annual rate of interest (percentage)
- **Time (T)** = Duration in years

---

## Requirements

Before running the project, ensure that you have:

- Linux operating system, macOS, or Windows with Git Bash
- Bash Shell
- Git (optional, for cloning the repository)

---

## Project Structure

```
github-final-project/
│
├── LICENSE
├── README.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── simple-interest.sh
└── .gitignore
```

---

## Installation

### Step 1: Clone the repository

```bash
git clone https://github.com/<your-username>/github-final-project.git
```

### Step 2: Navigate to the project directory

```bash
cd github-final-project
```

### Step 3: Make the script executable

```bash
chmod +x simple-interest.sh
```

---

## Usage

Run the script using:

```bash
./simple-interest.sh
```

The program will ask for the following information:

```
Enter Principal Amount:
```

```
Enter Rate of Interest:
```

```
Enter Time Period:
```

After entering the required values, the script calculates the simple interest and displays the result.

---

## Example

### Input

```
Enter Principal Amount: 10000
Enter Rate of Interest: 5
Enter Time Period: 2
```

### Calculation

```
Simple Interest = (10000 × 5 × 2) / 100
                = 1000
```

### Output

```
The Simple Interest is: 1000
```

---

## Benefits

This calculator provides several advantages:

- Saves time by automating calculations.
- Eliminates manual calculation errors.
- Easy to understand and modify.
- Suitable for students learning shell scripting.
- Demonstrates the use of variables and arithmetic expressions in Bash.
- Can be extended with additional financial calculations.

---

## Future Enhancements

The project can be extended to include:

- Compound Interest Calculator
- Interest payable with monthly calculations
- Currency formatting
- Input validation
- Decimal value support
- Error handling for invalid inputs
- Menu-driven interface
- Logging calculation history

---

## Learning Outcomes

By studying this project, users will learn:

- Bash scripting fundamentals
- Reading user input
- Performing arithmetic calculations
- Displaying formatted output
- Creating executable shell scripts
- Managing Git repositories
- Writing project documentation
- Using GitHub for version control

---

## Contributing

Contributions are welcome. Feel free to improve the project by fixing bugs, enhancing the code, improving documentation, or suggesting new features. Please read the `CONTRIBUTING.md` file before submitting pull requests.

---

## License

This project is licensed under the Apache License 2.0. See the `LICENSE` file for more information.

---

## Author

Created as part of the GitHub Final Project assignment to demonstrate Bash scripting and GitHub repository management.
