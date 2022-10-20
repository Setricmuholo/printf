This repo is about the recreation of the printf function as part of the collaboration project issued by ALX Software Engineer curriculum 

# C - printf
### Authors
- [Setric Muholo](https://github.com/Setricmuholo)
- [Lynn Ekalaji](https://github.com/lynnagidza)

## Task 0.
Write a function that produces output according to a format.
- Prototype: int _printf(const char *format, ...);
- Returns: the number of characters printed (excluding the null byte used to end output to strings)
- write output to stdout, the standard output stream

## Task 1.
Handle the following conversion specifiers:
- d
- i

## Task 2.
Handle the following custom conversion specifiers:
- b: the unsigned int argument is converted to binary

## Task 3.
Handle the following conversion specifiers:
- u
- o
- x
- X

## Task 4.
Use a local buffer of 1024 chars in order to call write as little as possible.

## Task 5.
Handle the following custom conversion specifier:
- S : prints the string.
- Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (upper case - always 2 characters)

## Task 6.
Handle the following conversion specifier: p.

## Task 7.
Handle the following flag characters for non-custom conversion specifiers:
- +
- space
- #

## Task 8.
Handle the following length modifiers for non-custom conversion specifiers:
- l
- h
Conversion specifiers to handle: d, i, u, o, x, X

## Task 9.
Handle the field width for non-custom conversion specifiers.

## Task 10.
Handle the precision for non-custom conversion specifiers.

## Task 11.
Handle the 0 flag character for non-custom conversion specifiers.

## Task 12.
Handle the - flag character for non-custom conversion specifiers.

## Task 13.
Handle the following custom conversion specifier:
- r : prints the reversed string

## Task 14.
Handle the following custom conversion specifier:
- R: prints the rot13'ed string

## Task 15.
All the above options work well together.
