# Java-Console-Calculator

🧮 Project Report: Java Console Calculator
Developer: [Kousalya C]
Technical Stack: Java SE, JDK 17+, Terminal/CLI

**📌 Project Overview**
The Java Console Calculator is a command-line application designed to perform basic arithmetic operations. The primary objective was to implement a robust input-handling system that remains stable even when faced with invalid user data.

**🛠️ Key Technical Features**
**1. Robust Input Validation**
     To prevent the program from crashing due to InputMismatchException (e.g., a user entering "abc" instead of a number I implemented custom helper methods:
getIntInput(): Validates menu selections.
getDoubleInput(): Ensures numeric values for calculations.
Buffer Clearing: Uses scanner.next() to clear invalid tokens from the input stream.

**2. Functional Decomposition**
The logic is separated into distinct methods for better readability and maintenance:
add(double a, double b)
subtract(double a, double b)
multiply(double a, double b)
divide(double a, double b)

**3. Logic & Control Flow**
Looping: A while(running) loop allows users to perform multiple calculations without restarting the app.
Switch Case: Efficiently maps user menu choices to the appropriate mathematical function.
Precision Formatting: Used System.out.printf with %.2f to ensure output is rounded to two decimal places for professional display.

**🚀 Technical Implementation (Source Code)**
// Include your corrected Calculator_Task1.java code here

**Scenario,Input,Expected Result,Status**
Basic Addition---> 10 + 5.5 ---> 15.50✅ 
Division by Zero ---> 10/0 --->Error:Cannot divide by zero!-->✅ 
Invalid String Input ---> hello---> Please enter a valid number:✅ 
Exit Logic---> Choice 5 ---> Program terminates with "Goodbye!!✅ 

📈 Learning Outcomes
 **Mastered the use of the Scanner class for interactive CLI tools.
 **Implemented Error Handling without using try-catch blocks by leveraging hasNext methods.
 **Practiced Method Overloading logic and formatting floating-point numbers.
