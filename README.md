# TASK3
COMPANY CODETECH IT SOLUTIONS 
NAME : Rubika A 
INTERN ID : CT08HCQ 
**DOMAIN NAME ** : C Programming 
**BATCH DURATION **: December 30th, 2024 to January 30th, 2025 
MENTOR NAME : Neela Santhosh Kumar

Description of the Lexical Analyzer Program
This program implements a simple lexical analyzer in C to identify three major components of source code:

Keywords: Predefined words with special meaning (e.g., int, float).
Operators: Characters that represent operations (e.g., +, -, *, /).
Identifiers: User-defined names for variables, functions, etc.
Numeric Constants: Numbers used in the source code (e.g., 42, 3.14).
Special Characters: Non-alphanumeric characters other than operators or whitespace.
Features and Workflow
Input Source File: The program accepts the name of a source file as input, which it then analyzes.
Token Classification: It reads the content of the file character by character and classifies tokens using these checks:
If the token is composed of letters, it determines whether it is a keyword or identifier.
If numeric, it identifies it as a numeric constant.
If an operator, it directly classifies the character as such.
All other characters are classified as special characters.
Modular Functions:
isKeyword: Checks if a word is a keyword by comparing it to a predefined list.
isOperator: Identifies valid operator characters.
lexicalAnalysis: Main function for token extraction and classification.
How to Compile and Run
Save the code to a file named lexical_analyzer.c.
Compile the program:
bash
Copy
Edit
gcc lexical_analyzer.c -o lexical_analyzer
Run the program:
bash
Copy
Edit
./lexical_analyzer
Enter the name of an input file containing the source code to analyze:
plaintext
Copy
Edit
example.c

**THE OUTPUT OF THE FILE
![Image](https://github.com/user-attachments/assets/ab2003d8-1bf8-4fbb-8f55-bffa47cfb6e5)


