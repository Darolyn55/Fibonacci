Fibonacci Sequence Generator
A simple Java console application that prints the Fibonacci sequence up to a user-specified number of terms.

Features
Prompts the user to input the number of terms.

Calculates and displays the Fibonacci sequence up to the given number.

How to Run
Make sure Java is installed.
Check with:

bash
Copy
Edit
java -version
If needed, download Java or install it via your system’s package manager.

Compile the program:

bash
Copy
Edit
javac day6/Fibonacci.java
Run the program:

bash
Copy
Edit
java day6.Fibonacci
Example Usage
text
Copy
Edit
Enter the number of terms:
7
Fibonacci Sequence:
0 
1 
1 
2 
3 
5 
8 
Project Structure
mathematica
Copy
Edit
day6/
└── Fibonacci.java
How It Works
Starts with the first two Fibonacci numbers: 0 and 1.

Each subsequent number is the sum of the previous two.

Uses a simple for loop to generate the sequence.

Notes
The program expects an integer input for the number of terms.

Basic input validation is not implemented; entering a non-integer will cause an error.

