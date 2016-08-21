[Back To Index](../README.md)

# Flow-Control Continued -- Loops

Having introduced flow-control with logical conditions (ifs and switches), it's
now time to progress into code reuse. There are times when writing code where
you'll need to repeat code. Re-writing the same code over and over again
is not only boring and time consuming, but also counter-productive from a code
reading and maintenance standpoint.

Having a block structure where you can state what you want repeated only once
and the computer will repeat it without having to re-write the code is easier to
read. Enter the *loop*.

A loop is a block of code which executes the same code again and again for a given
interval or condition. There are two kinds of loops: *for* loops and *while* loops

## For Loops

For loops are mostly used in situations where there is a finite number of times
you need to execute the code.

```cpp
// say hello 3 times
for( int i = 0; i < 3; i++){
    cout << "hello";
}
```

### Assignment 1
In this assignment, we are going to practice using for loops. Create a program
that declares three variables. One variable will be called *number* and the other
variable will be called *multipliler*. The third variable will be called product.
Make product equal to the product added to the number and make it so that the loop goes for
as many times as indicated by multipliler. (see the example above to structure
your for loop)

## While loops

While loops are mostly used in situations where there is not a finite number of
While loops will continue to repeat the code in the block unil the condition
in the while loop is no longer satisfied

```cpp
int counter = 0;
while(counter < 3){
    cout << "hello";
    counter ++;
}
```

### Assignment 2
In this assignment, we are going to practice using while loops. Create a program
that declaresa number variable called *counter*, and a string variable called *word*.
*word* will be an arbitrary string value (assign the string whatever you want).
*counter* must be initialized to 0. In C++ since a string is an array of char
(arrays will be covered in the next lesson), create a while loop that prints out
every letter in *word*.

#### Hints
```cpp
#include <cstdlib>
...
// You access a particular position in the string like below
char letter = myString[5];  //Accessess the 6th position of the string
// Arrays in C/C++ begin with index 0 (more on that in the next lesson)

// To do this exercise you need to check to see if the character exists
if(myString[counter])

// NULL is essentially the programmer's way of saying "nothing"
```

## Breaking out of loops
At any time you need to exit a loop, use the *break* keyword to exit the loop.
Please be aware that utilizing the *break* keyword is generally considered bad
practice and should really only be used in special circumstances.

[Back To Index](../README.md)