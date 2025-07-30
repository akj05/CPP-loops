🎯 AIM
To explore the use of for, while, and do while loops in C++ for automating repetitive tasks, implementing algorithms, and optimizing control flow in applications.

📚 THEORY
Loops in C++ are control flow structures that allow repeated execution of a block of code. They are fundamental in programming for:

Automating repetitive tasks
Iterating over data structures
Implementing algorithms efficiently
Enhancing code modularity and readability

🔐 Password Verification Algorithm
    Initialize Variables
        Set a fixed password (e.g., "BCD9QTTU").
        Create a variable to store user input.
        Set attempts to 0.
        Define a maximum number of attempts (e.g., 3).
    Loop While Attempts Are Less Than Maximum
        Prompt the user to enter the password.
        Hide the input characters (optional, depending on system).
        Capture each character typed until the Enter key is pressed.
            If the character is Backspace, remove the last character from the input.
            Otherwise, add the character to the input and show * on the screen.
    Validate the Password
        If the entered password matches the stored password:
            Display "System is Unlocked".
            Exit the program.
        If not:
            Increment the attempt counter.
            Display "Incorrect Password" and show remaining attempts.
    Lock the System if Attempts Exceed Limit
        After maximum attempts, display "System is locked".
        Exit the program.
        
🔄 Types of Loops in C++
1. For Loop
Used when the number of iterations is known beforehand.
Combines initialization, condition check, and increment or decrement in a single line.
Ideal for counting loops, array traversal, and fixed iteration tasks.

2. While Loop
Used when the number of iterations is unknown.
Condition is checked before each iteration.
Suitable for condition-driven logic such as waiting for user input or sensor data.

3. Do While Loop
Executes the loop body at least once before checking the condition.
Useful in scenarios like menu-driven programs or input validation where the loop must run at least once.

🧭 Loop Control Statements
Break
Terminates the loop immediately when a specific condition is met.
Commonly used in search operations or early exits.

Continue
Skips the current iteration and proceeds to the next.
Helps avoid deeply nested conditions and improves clarity.

🔁 Nested Loops
Nested loops are loops placed inside other loops. They are essential for:

Generating patterns such as triangles or grids
Traversing multi-dimensional arrays or matrices
Creating structured outputs like multiplication tables
In nested loops, the inner loop completes its full cycle for each iteration of the outer loop.

🧠 Common Loop-Based Algorithms
Factorial Calculation
Multiplies all positive integers up to a given number.
Used in combinatorics and mathematical computations.

Fibonacci Sequence
Each term is the sum of the two preceding ones.
Applied in algorithm design and modeling growth patterns.

Prime Number Check
Determines if a number has no divisors other than one and itself.
Crucial in cryptography and number theory.

Sum of Natural Numbers
Adds numbers sequentially from one to N.
Demonstrates basic iterative accumulation.

Pattern Generation
Uses nested loops to print visual structures.
Enhances understanding of loop flow and indexing.

📊 Comparative Overview of Loop Types
Feature	For Loop	While Loop	Do While Loop
Use Case	Known iteration count	Unknown iteration count	Must run at least once
Condition Check	Before loop starts	Before loop starts	After loop body
Initialization	Inside loop header	Outside loop	Outside loop
Iteration Control	Structured and concise	Manual control	Manual control
Readability	High for counting tasks	Good for condition-based logic	Best for menu or input-driven programs
Risk of Infinite Loop	Lower	Moderate	Moderate
⚙️ Loop Optimization Techniques
Minimize Work Inside the Loop
Avoid complex operations or function calls within the loop body.

Use Efficient Conditions
Keep loop conditions simple and fast to evaluate.

Reduce Memory Access
Store frequently accessed values in temporary variables.

Avoid Deep Nesting
Flatten logic where possible to reduce time complexity.

Short Circuiting with Break
Exit loops early when the goal is achieved.

Loop Unrolling
Combines multiple iterations into one to reduce overhead.
Used in performance-critical systems.

✅ CONCLUSION
Loops are a cornerstone of C++ programming, enabling efficient repetition, algorithmic logic, and structured control flow. Understanding the differences between for, while, and do while loops along with control statements and optimization techniques empowers developers to write clean, scalable, and high-performance code. Mastery of loops is essential for solving real-world problems, from pattern generation to complex algorithmic tasks.
