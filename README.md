Name  : RAJ PATIL
compony : CODTECH IT SOLUTIONS
ID : CT4PP2843
Domain : Python Programming
Duration : JUNE to JULY 2024
Mentor : Neela kumar

Certainly! Here's an overview of the project:

### Project Overview: Simple Command-Line Calculator

**Objective:**
The objective of this project is to create a simple command-line calculator in Python that allows users to perform basic arithmetic operations (addition, subtraction, multiplication, division) on two numbers. The calculator also includes functionality to clear the screen and provides a user-friendly interface.

**Key Features:**

1. **Clear Screen Functionality:**
   - Uses `os.system` to clear the console screen. It detects the operating system (`os.name`) to choose the appropriate command (`'cls'` for Windows, `'clear'` for Unix-like systems).

2. **Menu-Driven Interface:**
   - Presents a menu of operations to the user:
     - Addition (+)
     - Subtraction (-)
     - Multiplication (*)
     - Division (/)
     - Exit (5)

3. **User Input and Validation:**
   - Prompts the user to enter their choice of operation and validates the input to ensure it matches one of the menu options.
   - Prompts the user to enter two numbers for the selected operation and validates these inputs as floating-point numbers.

4. **Arithmetic Operations:**
   - Performs the selected arithmetic operation based on the user's input (`+`, `-`, `*`, `/`).
   - Handles division by zero gracefully, displaying an error message when `num2` is zero.

5. **User Interaction:**
   - After displaying the result of the operation, prompts the user to press Enter to continue, maintaining an interactive user experience.

6. **Exit Functionality:**
   - Allows the user to exit the calculator by selecting option 5 from the menu, displaying a farewell message ("Thank you...") before terminating the program.

7. **Error Handling:**
   - Provides feedback for invalid choices or inputs, such as non-numeric inputs for numbers or unrecognized operator choices.

### Implementation Details:

- **Modules Used:** Uses the `os` module for clearing the screen (`os.system`) and the basic input/output functions (`input`, `print`) for user interaction.
  
- **Control Flow:** Utilizes a `while True:` loop to keep the calculator running until the user chooses to exit (`break` statement).

- **Function Definitions:**
  - `clear_screen()`: Clears the console screen based on the operating system.
  - `main()`: Contains the main logic for displaying the menu, performing operations, and handling user input.

- **Execution:** The script checks if it is being run as the main program (`if __name__ == "__main__":`) and then calls the `main()` function to start the calculator.

### Conclusion:

This simple command-line calculator project provides a foundational example of basic Python programming concepts such as functions, loops, conditional statements, and input/output operations. It demonstrates how to create an interactive application that performs useful calculations while maintaining a clear and responsive user interface.
