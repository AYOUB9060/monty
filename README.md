# Monty

Monty is a program that interprets Monty Bytecode files. It executes commands stored in these files to manipulate data in a stack or queue data structure.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Command Descriptions](#command-descriptions)
- [Contributing](#contributing)
- [License](#license)

## Installation

To compile and run the Monty program, follow these steps:

1. Clone the repository:
git clone https://github.com/your-username/monty.git

2. Change to the project directory:
cd monty

3. Compile the source code:
gcc -Wall -Werror -Wextra -pedantic *.c -o monty

## Usage

To use Monty, provide a valid Monty Bytecode file as a command-line argument when running the program. The program will then execute the commands in the file and perform the specified operations on the stack or queue.

Example usage:

./monty test.m

## Command Descriptions

Here's a brief description of some of the commands supported by Monty:

- `push <int>`: Pushes an element to the stack.
- `pall`: Prints all the values on the stack, from top to bottom.
- `pop`: Removes the top element of the stack.
- `swap`: Swaps the top two elements of the stack.
- `add`: Adds the top two elements of the stack.
- `sub`: Subtracts the top element of the stack from the second top element.
- `mul`: Multiplies the top two elements of the stack.
- `div`: Divides the second top element of the stack by the top element.
- `mod`: Computes the modulus of the second top element of the stack divided by the top element.
- `pchar`: Prints the ASCII value of the top element of the stack as a character.
- `pstr`: Prints the string contained in the stack.

For a complete list of commands and their descriptions, please refer to the `monty.h` file.
