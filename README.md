
# Custom _printf Function Project

Welcome to the Custom _printf Function Project! This project aims to create a simplified version of the printf function that supports basic format specifiers ('c', 's', '%') without handling complex formatting features. This implementation allows you to print characters and strings to the standard output while adhering to the specified format.

## Table of Contents
- [Introduction](#introduction)
- [Usage](#usage)
- [Implementation Details](#implementation-details)
- [How to Compile](#how-to-compile)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project provides a custom _printf function that mimics the functionality of the standard printf function. It can print characters, strings, and the '%' character while handling basic formatting.

## Usage
To use the custom _printf function in your C program, you can follow these steps:

1. Include the "main.h" header file in your code:
   ```c
   #include "main.h"

## Implementation Details
The custom _printf function is implemented as follows:

It loops through the format string character by character.
When a '%' is encountered, it processes the format specifier using helper functions to extract flags, width, precision, and size.
The appropriate handler function is called to handle printing based on the format specifier.
The helper functions for flags, width, precision, and size should be implemented separately.
The print_buffer function is used to efficiently manage and print characters.

## How to Compile
To compile your program, follow these steps:

1. Ensure all source files (_printf.c, print_buffer.c, print_char.c, print_string.c, main.c, etc.) are in the same directory.
2. Open your terminal or command prompt.
3. Navigate to the directory containing your source files.
4. Run the following command to compile your program (replace "your_program" with the desired output file name):
```
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c