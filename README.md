# Advanced-Swing-Calculator-U23CYS1017
Sa'ad Maryam Bala
U23CYS1017
Cyber Security
myrabeee
# Advanced Swing Calculator

## Description
The **Advanced Swing Calculator** is a Java-based GUI calculator built using the Swing framework. It provides basic arithmetic operations along with advanced functions such as logarithm, exponentiation, square root, and memory storage capabilities. The calculator also maintains a history of calculations.

## Features
- **Basic Arithmetic Operations**: Addition (+), Subtraction (-), Multiplication (*), Division (/)
- **Advanced Functions**: Logarithm (log), Exponential (exp), Square Root (√), Power (^)
- **Memory Functions**:
  - **MC**: Clear memory
  - **MR**: Recall stored memory value
  - **M+**: Add the current value to memory
- **Calculation History**: Keeps a record of past calculations
- **Clear Functions**:
  - **C**: Clears the entire input
  - **CE**: Clears only the current entry

## Installation & Usage
### Prerequisites
- Java Development Kit (JDK) 8 or later

### Running the Application
1. Clone or download the repository.
2. Compile the Java file:
   ```sh
   javac AdvancedSwingCalculator.java
   ```
3. Run the compiled program:
   ```sh
   java AdvancedSwingCalculator
   ```

## Code Structure
- **`AdvancedSwingCalculator`**: Main class extending `JFrame` that initializes the GUI and event handling.
- **GUI Components**:
  - `JTextField`: Display for input/output
  - `JTextArea`: History display
  - `JPanel`: Container for buttons
  - `JButton`: Number and function buttons
- **Event Handling**:
  - Implements `ActionListener` to process button clicks.
  - Calls appropriate mathematical functions based on user input.

## Possible Improvements
- Improve UI layout to better integrate the history section.
- Enhance exception handling for invalid operations.
- Add support for parentheses and more scientific functions.

