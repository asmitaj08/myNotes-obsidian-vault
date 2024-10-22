## Strings
- Page 32 : ARR01-C : Do not apply sizeof operator to a pointer when taking the size of an array
- Loophole in UTF-8 decoder (page 33)
- If time permits, come back to page 32-34
- Page 36 : STR36-C -  Do not specify the bound of a character array initialized with a string literal
- In C, const char ('A')and multicharacter literals('ABCD') has type int (page 38-39), unsigned char - pure binary notation, non-bit-field objects of any type may be copied into array of unsigned char
- Page 39- STR31-C : Guarantee tahta storage for strings has sufficient space for character data and null terminator, 
- Size of wchar (page 40-41)
- Errors while manipulating strings (page 42..) : unbound string copies (*when data is cpoied from source to a fixed-length arr*) , of-by-one, null-termination, string truncation
- Page 43-44 : Command line arguments are passed to main() as pointers to null-terminated strings in the array members `argv[0]` through `argv[argc-1]` , we know `argv[0]` is program name, the pint is : Avoid assuming that element of `argv` including `argv[0` is not NULL, hence check before directly using `argv[n]`
- `snprintf()` is also susceptible to format string vulnerabilities (Page 45)
- Null-terminate byte strings as required (see how even `strncpy` can be tricked page 48-49)
- In some cases, sting truncation may lead to software vulnerabilities.
- Most functions defined in standard string handling library are susceptible to errors including strcpy(), strncpy(), strcat(), strncat(), strtok()





**To Read Later**

1. C locale & multibyte character set(page 32)
2. Page 65 buffer overflow exploit example (page 65-68)
3. ROP (returned oriented programming ) (page 71)
4. Turing complete set of gadgets (page 71)