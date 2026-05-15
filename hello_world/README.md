# hello_world

This folder contains beginner C and shell tasks that introduce the C toolchain and basic output programs.

## Files

- `0-preprocessor`: Script that runs a C file through the preprocessor and saves the result into `c`.
- `1-compiler`: Script that compiles a C file without linking.
- ` 2-assembler`: Script that generates the assembly code of a C file.
- `3-name`: Script that compiles a C file and outputs an executable named `cisfun`.
- `4-puts.c`: C program that prints a string using `puts`.
- `5-printf.c`: C program that prints text using `printf`.
- `6-size.c`: C program that prints the size of various types on the local architecture.
- `100-intel`: Script that generates Intel syntax assembly output.
- `101-quote.c`: C program that prints text to standard error with a specific return code.

## Usage

Run scripts:

```sh
./0-preprocessor
./1-compiler
./3-name
```

Compile and run C files:

```sh
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 4-puts.c -o 4-puts
./4-puts
```

## Permissions

All files in this directory have user executable permission (`u+x`).
