# Postfix-Expression-Evaluator
A C++ program created for my Data Structures class. It simply uses a stack to store numbers, and once you add or multiply it pops the top 2 numbers and pushes the result back to the stack.

## Technologies
* C++
* Stack
* Visual Studios

## Features
What the program includes is
* **Input for numbers**: Has an uncapped stack size and number limit
* **Can do mathematics like multiply or add**: Can add the numbers or multiply them
* **Includes fail safes**: Inputs that aren't numbers or symbols (+, *) won't work

## The Process
The process was split between 3 steps with the functions: isNumber, toNumber, and main.

isNumber checks to make sure what's being inputted is a number. It does this by checking if each character in the string isn't outside of 0 and 9.

toNumber converts the string number into a value. This is done after making sure that it is a number with isNumber.

Main runs everything together. Creating the stack, as well as checking the inputs. Running a loop to add everything into the stack until '=' is inputed. Can also input 'q' to quit.

## What I Learned
During this project, I got to mess with some data structures and hone my skills on problem solving

## Overall Growth
Overall, I feel proud of what I created, utilizing a new data structure with stack and C++. I hope I can apply this knowledge with what's next.

## How can it be Improved?
* Add '-' and '/' to it
* Allow a single negative number to be added
