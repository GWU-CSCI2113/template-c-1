# C Module 1: Pointers, arrays, malloc

## Exercise 1.1
>Write your program in `pointer.c`.
Can two pointers point to the same thing?

## Exercise 1.2
>Write your program in `pointer2.c`.
Fill in the memory table below to represent just after the line `sum = (*intPtr) + (*intPtr2);`
In your memory diagram, use the actual addresses printed to the screen. You might need to add extra print statements to find them out.

**Globals:**

| Address  | Name | Contents |
| :---     |:---  |:---      |
|          | i        |         |
|          | j        |         |
|          | sum      |         |

**Stack:**

| Address  | Name | Contents |
| :---     |:---  |:---      |
|          | intPtr        |         |
|          | intPtr2       |         |
|          | intPtr3       |         |

(For markdown table formatting help, see: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#tables)

## Exercise 1.3
> Write your program in `charpointer.c`.


## Exercise 1.4
>Write your program in `pointertopointer.c`. Fill in the memory diagram below
just after the printf. Use the
actual addresses from your program.

**Stack:**

| Address  | Name | Contents |
| :--- |:---  |:--- |
|          | i       |         |
|          | p       |         |
|          | p2      |         |

## Exercise 1.5
>Write your program in `string.c`.

## Exercise 1.6
>Write your program in `string2.c`. Explain what these lines are trying to achieve.

```
Paste your output here
```

## Exercise 1.7
>Write your programs in `array.c` and `array2.c`.
>What is the output for each program?

## Exercise 1.8
>Write your program in `array3.c`


## Exercise 1.9
>You do not need to submit your diagram.
>Explain where `B[1][3]` is located in your diagram and how the calculation
for its address works.

## Exercise 1.10
>Write your code in `sizeof.c`.
What is printed out by the program?  Fill in the memory diagram below for
the point right before the calls to free. You may need to modify the program
to print more addresses.

**Stack:**

| Address  | Name | Contents |
| :--- |:---  |:--- |
|          | doublePtr       |         |
|          | charPtr         |         |


**Heap:**

| Address  |  Contents |
| :--- |:--- |
|          |        |
|          |        |
|          |        |

## Exercise 1.11
>Write your code in `pointerArith.c`.

```
Paste your output here

```

## Exercise 1.12
>Write your code in `pointerArith2.c`.


## Exercise 1.13
>Write your code in `pascal.c`
What is your program's output when `size=10`?

```
Paste your output here

```

## Exercise 1.14
>Write your code in `pascal2.c`

## Exercise 1.15
> What is the decimal value of the number 1ABE?


> Convert the decimal number 8384 into hexadecimal.


> Use the hex version of 8384 to write that as a binary number,
leaving spacing between every four bits.

## Exercise 1.16
> Without writing the program, can you predict what it will print? Confirm your
answers with the program's output.

## Exercise 1.17 (Bonus)
>Write your code in `endian.c`


## Exercise 1.18 (Bonus)
>Modify `endian.c`.
to print the addresses of all the variables. Then draw
a detailed memory diagram like the one we've shown above,
but using the actual memory addresses from the execution
of your program.
Look up the terms little- and big-endian and explain their origin.
