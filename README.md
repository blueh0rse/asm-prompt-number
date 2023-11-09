# Learning

## Assembly

### Prompt Number

This code prompt the user a number then display it.

To assemble the program:

````bash
nasm -f elf promptnumber.asm
````

To link the object file and create an executable file:

````bash
ld -m elf_i386 -s -o ./PromptNumber promptnumber.o
````

To execute it:

````bash
$ ./PrompNumber 
Please enter a number: 1
You have entered: 1
````
