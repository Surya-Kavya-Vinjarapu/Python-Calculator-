# Simple Python Calculator

This is a basic command-line calculator built with Python. It allows users to perform fundamental arithmetic operations: addition, subtraction, multiplication, and division.

## Features

* **Addition:** Adds two numbers.
* **Subtraction:** Subtracts two numbers.
* **Multiplication:** Multiplies two numbers.
* **Division:** Divides two numbers, with robust error handling for division by zero.
* **User-Friendly Interface:** Simple text-based menu for easy interaction.
* **Input Validation:** Catches non-numeric inputs to prevent crashes.

## How to Run

1.  **Clone the repository (or download the files):**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/simple-calculator.git](https://github.com/YOUR_USERNAME/simple-calculator.git)
    cd simple-calculator
    ```

2.  **(Optional) Create a virtual environment:**
    It's good practice to use a virtual environment to manage dependencies.
    ```bash
    python -m venv venv
    ```
    * On Windows:
        ```bash
        .\venv\Scripts\activate
        ```
    * On macOS/Linux:
        ```bash
        source venv/bin/activate
        ```

3.  **Install dependencies (if any, though this project has none beyond standard Python):**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the calculator:**
    ```bash
    python main.py
    ```

## Usage

Follow the on-screen prompts:

1.  Select an operation by entering its corresponding number (1 for Add, 2 for Subtract, etc.).
2.  Enter the first number when prompted.
3.  Enter the second number when prompted.
4.  The result will be displayed.
5.  You can continue performing operations until you choose option `5` to exit.

