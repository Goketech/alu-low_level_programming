# malloc_free

This directory contains C functions that practice dynamic memory allocation
with `malloc` and releasing memory with `free`.

## Files

- `0-create_array.c`
	- Implements `create_array(unsigned int size, char c)`.
	- Allocates an array of `size` chars and initializes each element with `c`.
	- Returns `NULL` if `size` is `0` or allocation fails.

- `1-strdup.c`
	- Implements `_strdup(char *str)`.
	- Allocates memory for a copy of `str`, including the null terminator.
	- Returns `NULL` if `str` is `NULL` or allocation fails.

- `2-str_concat.c`
	- Implements `str_concat(char *s1, char *s2)`.
	- Allocates a new string containing `s1` followed by `s2`.
	- Treats `NULL` inputs as empty strings.
	- Returns `NULL` if allocation fails.

- `3-alloc_grid.c`
	- Implements `alloc_grid(int width, int height)`.
	- Allocates a 2D array of integers (`height` rows by `width` columns).
	- Initializes all elements to `0`.
	- Returns `NULL` on invalid dimensions or allocation failure.

- `4-free_grid.c`
	- Implements `free_grid(int **grid, int height)`.
	- Frees memory previously allocated by `alloc_grid`.
	- Releases each row, then the row-pointer array.

- `100-argstostr.c`
	- Implements `argstostr(int ac, char **av)`.
	- Concatenates all program arguments into one string.
	- Inserts a newline (`\n`) after each argument.
	- Returns `NULL` for invalid input or allocation failure.

- `101-strtow.c`
	- Implements `strtow(char *str)`.
	- Splits a string into words separated by spaces.
	- Allocates memory for an array of words and each word.
	- Returns `NULL` if input is empty/invalid or allocation fails.

- `main.h`
	- Header file containing function prototypes used in this directory.

## Compilation

Compile any task file with:

```sh
gcc -Wall -Werror -Wextra -pedantic *.c -o output
```

Replace `output` with your preferred executable name.
