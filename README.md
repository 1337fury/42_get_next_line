# 42get_next_line
The "42 get next line" project is a programming exercise that involves writing a function in the C programming language that reads a line from a file descriptor. The goal of the project is to create a function that reads a line from a file descriptor, including the newline character at the end of the line, and stores the result in a buffer.

### Here is a high-level overview of how the function might work:

 - The function takes as input a file descriptor and a buffer to store the line.
 - The function reads one character at a time from the file descriptor and stores it in the buffer.
 - If the character is a newline, the function stops reading and stores the newline character in the buffer.
 - If the character is not a newline, the function continues reading until it reaches the end of the line or the end of the file.
 - The function returns the number of characters that were read and stored in the buffer, including the newline character.
 
There are a few additional requirements and constraints that are often part of the "42 get next line" project. For example, the function may be required to handle multiple file descriptors simultaneously, to handle errors and edge cases, and to use a certain number of bytes of memory.
