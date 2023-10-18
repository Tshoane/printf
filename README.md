0x11. C - printf
Overview
The "0x11. C - printf" project is a comprehensive C programming project that focuses on implementing a custom version of the printf function. The printf function is a standard output formatting function in C, widely used for displaying formatted text. This project delves into the inner workings of printf and aims to replicate its functionality.

Project Goals
Implement a custom version of the printf function, adhering to the standard format specifiers and behavior.
Understand the complexities and intricacies of string formatting and output in C.
Learn about variadic arguments and how they are handled in C functions.
Explore memory management and efficient code implementation.
Key Features
Format Specifiers: Support a wide range of format specifiers for various data types like integers, floats, characters, and strings.
Precision and Width: Handle precision and width formatting for precise and well-structured output.
Variadic Arguments: Accommodate a variable number of arguments using variadic functions.
Error Handling: Implement robust error handling to manage unexpected inputs and edge cases.
Modular Design: Organize the codebase into modular and manageable components for enhanced maintainability and readability.
Compliance with Standards: Ensure the custom printf function follows the standard behavior and format specifiers as specified in the C programming language.

How to Use
Clone the repository and navigate to the project directory.
Compile the code using a C compiler (e.g., gcc -Wall -Wextra -Werror -pedantic *.c -o printf).
Include the custom printf function in your C programs to utilize the enhanced formatting capabilities.

#include "holberton.h"

int main(void) {
    _printf("Hello, %s! You are %d years old.\n", "John", 30);
    return 0;
}

c

#include "holberton.h"

int main(void) {
    _printf("Hello, %s! You are %d years old.\n", "John", 30);
    return 0;
}
Contributors

Masehla Tshoane Respect and Rufaro Wayne.

License

This project is licensed under the MIT License
