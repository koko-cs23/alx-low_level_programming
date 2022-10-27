File 0-strcat.c contains a function that concatenates two strings. This function appends the src string to the dest string, overwriting the terminating null byte (\0) at the end of dest, and then adds a terminating null byte.
Returns a pointer to the resulting string dest. The standard library provides a similar function: strcat.

File 1-strncat.c contains a function that concatenates two strings. The _strncat function is similar to the _strcat function, except that itwill use at most n bytes from src and src does not need to be null-terminated if it contains n or more byte. Return a pointer to the resulting string dest. The standard library provides a similar function: strncat.

File 2-strncpy.c contains a function that copies a string. The standard library provides a similar function: strncpy.

File 3-strcmp.c contains a function that compares two strings. The standard library provides a similar function: strcmp.

File 4-rev_array.c contains a function that reverses the content of an array of integers where n is the number of elements of the array.

File 5-string_toupper.c contains a function that changes all lowercase letters of a string to uppercase.

File 6-cap_string.c contains a function that capitalizes all words of a string. 

File 7-leet.c contains a function that encodes a string into 1337. 
Letters a and A should be replaced by 4
Letters e and E should be replaced by 3
Letters o and O should be replaced by 0
Letters t and T should be replaced by 7
Letters l and L should be replaced by 1

File 100-rot13.c contains a function that encodes a string using rot13.

File 101-print_number.c contains a function that prints an integer.

File 102-magic.c contains a program that prints a[2] = 98 followed by a new line.

File 103-infinite_add.c contains a function that adds two numbers where n1 and n2 are the two numbers. r is the buffer that the function will use to store the result. size_r is the buffer size. The function returns a pointer to the result. 

File 104-print_buffer.c prints a buffer. 
The function must print the content of size bytes of the buffer pointed by b
The output is 10 bytes per line
Each line starts with the position of the first byte of the line in hexadecimal (8 chars), starting with 0
Each line shows the hexadecimal content (2 chars) of the buffer, 2 bytes at a time, separated by a space
Each line shows the content of the buffer. If the byte is a printable character, print the letter, if not, print .
Each line ends with a new line \n
If size is 0 or less, the output is a new line only \n

