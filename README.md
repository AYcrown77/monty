0x19. C - Stacks, Queues - LIFO, FIFO

Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General
What do LIFO and FIFO mean
What is a stack, and when to use it
What is a queue, and when to use it
What are the common implementations of stacks and queues
What are the most common use cases of stacks and queues
What is the proper way to use global variables

Compilation & Output
Your code will be compiled this way:
$ gcc -Wall -Werror -Wextra -pedantic -std=c89 *.c -o monty

Any output must be printed on stdout
Any error message must be printed on stderr

The Monty language
Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project is to create an interpreter for Monty ByteCodes files.

The opcode push pushes an element to the stack.

The opcode pall prints all the values on the stack, starting from the top of the stack.

The opcode pint prints the value at the top of the stack, followed by a new line.

The opcode pop removes the top element of the stack.

The opcode swap swaps the top two elements of the stack.

The opcode add adds the top two elements of the stack.

The opcode nop doesn’t do anything.

The opcode sub subtracts the top element of the stack from the second top element of the stack.

The opcode div divides the second top element of the stack by the top element of the stack.

The opcode mul multiplies the second top element of the stack with the top element of the stack.

The opcode mod computes the rest of the division of the second top element of the stack by the top element of the stack.

The opcode pchar prints the char at the top of the stack, followed by a new line.

The opcode pstr prints the string starting at the top of the stack, followed by a new line.

The opcode rotl rotates the stack to the top.

The opcode rotr rotates the stack to the bottom.

The opcode stack sets the format of the data to a stack (LIFO). This is the default behavior of the program.


