#0x01. C - Variables, if, else, while
C
 By: Julien Barbier
 Weight: 1
 Project will start Oct 6, 2023 5:00 AM, must end by Oct 7, 2023 5:00 AM
 Checker was released at Oct 6, 2023 11:00 AM
 An auto review will be launched at the deadline
Resources
Read or watch:

Everything you need to know to start with C.pdf (You do not have to learn everything in there yet, but make sure you read it entirely first and make sure you understand the slides: “comments”, “Data types | Integer types”, “Declaration”, “Characters”, “Arithmetic operators”, “Variables assignments”, “Comparisons”, “Logical operators”, “if, if…else”, “while loops”.)
Keywords and identifiers
integers
Arithmetic Operators in C
If statements in C
if…else statement
Relational operators
Logical operators
while loop in C
While loop
man or help:

ascii (You do not need to learn about scanf, getc, getchar, EOF, EXIT_SUCCESS, time, rand, srand, RAND_MAX, for loops, do...while loops, functions.)
Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General
What are the arithmetic operators and how to use them
What are the logical operators (sometimes called boolean operators) and how to use them
What the the relational operators and how to use them
What values are considered TRUE and FALSE in C
What are the boolean operators and how to use them
How to use the if, if ... else statements
How to use comments
How to declare variables of types char, int, unsigned int
How to assign values to variables
How to print the values of variables of type char, int, unsigned int with printf
How to use the while loop
How to use variables with the while loop
How to print variables using printf
What is the ASCII character set
What are the purpose of the gcc flags -m32 and -m64
Copyright - Plagiarism
You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
You are not allowed to publish any content of this project.
Any form of plagiarism is strictly forbidden and will result in removal from the program.
Requirements
General
Allowed editors: vi, vim, emacs
All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
All your files should end with a new line
A README.md file, at the root of the folder of the project
There should be no errors and no warnings during compilation
You are not allowed to use system
Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
Quiz questions
Question #0
Which of the following are valid for statements in ANSI C and Betty-compliant? (Considering a and b two variables of type int)

Please select all correct answers


for (int a = 0; a < b; a++)
{
    printf("%d\n", a);
}

a = 0;
for (a < b;;)
{
    printf("%d\n", a++);
}

for (a = 0; a < b; a++)
    printf("%d\n", a);

a = 0;
for (; a < b;)
{
    printf("%d\n", a++);
}

for (a = 0; a < b; a++)
{
    printf("%d\n", a);
}
Question #1
What is the size of the char data type?


4 bytes


2 bytes


8 bytes


1 byte

Question #2
What is the size of the unsigned int data type?


4 bytes


2 bytes


8 bytes


1 byte

Question #3
What is the size of the float data type?


4 bytes


2 bytes


8 bytes


1 byte

Question #4
Which of the following are valid while or do/while statements in ANSI C and Betty-compliant? (Considering a and b two variables of type int)

Please select all correct answers


a = 0;
do {
    printf("%d\n", a);
    a++;
} while (a < b);

a = 0;
do while (a < b)
{
    printf("%d\n", a);
    a++;
}

a = 0;
while (a < b)
{
    printf("%d\n", a);
    a++;
}

a = 0;
while (a < b)
    printf("%d\n", a++);

a = 0;
while (a < b)
(
    printf("%d\n", a);
    a++;
)

while (a = 0; a < b; a++)
{
    printf("%d\n", a);
}
Question #5
Which of the following are valid if statements in ANSI C and Betty-compliant? (Considering a and b two variables of type int)

Please select all correct answers


if {a > b}
(
  return {a};
)

if ((((((a > b))))))
{
  return (a);
}

if (a > b)
{
  return (a);
}

if (a > b)
  return (a);

if a > b
{
  return (a);
}
Please make sure to validate all quiz questions before moving on to project tasks
Copyright © 2023 ALX, All rights reserved.
