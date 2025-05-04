Project Overview
The Arbitrary Precision Calculator (APC) is a command-line utility designed to perform arithmetic operations (addition, subtraction, multiplication, division) on extremely large numbers that exceed standard data type limits. By using a doubly linked list to store and manipulate individual digits, this calculator can handle numbers of arbitrary length with precise results.
Features

Unlimited Precision: Calculate with numbers of any length
Core Operations: Addition, subtraction, multiplication, and division
Command-Line Interface: Simple and straightforward usage
Flexible Input: Handles both positive and negative numbers
Memory Efficient: Uses dynamic memory allocation for digits storage

Technologies Used

C Programming Language
Doubly Linked Lists
Dynamic Memory Allocation
Command-Line Argument Processing
Pointer Manipulation and Memory Management
String Manipulation
Character-to-Integer Conversion

Implementation Details

The calculator represents numbers as doubly linked lists:
Each node in the list contains a single digit
Operations are performed digit by digit
Arithmetic is performed from right to left (least significant to most significant digit)
Carries and borrows are managed during calculations
Special handling for negative numbers and edge cases

Key Learnings

Implementing arithmetic operations (add, subtract, multiply, divide) digit by digit using doubly linked lists
Managing memory efficiently for large data structures
Solving edge cases in mathematical operations
Handling very large numbers beyond standard data type limits
