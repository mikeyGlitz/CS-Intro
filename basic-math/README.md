[Back To Index](../README.md)

# Introduction

This module introduces the notion of basic types. In computer science, things
are described in terms of types. Types are like categories for which something
is part of. Basic types usually consist of numbers, phrases, individual letters,
or true or false.

In C++ these types exist as the following:
 
 * Like math numbers are complicated. Numbers are modeled similarly to their
   mathematic domains. C++ represents decimal numbers and whole numbers.
    * An *int* is a whole number. int types do not have a decimal point.
    * A *double* is a decimal number. double stands for double percision
    * A *float* is a decimal number. float stands for floating point number
* Phrases are represented as *strings*
* individual letters are represented as *char*
* Other languages have a type called *boolean* which represents a true/false value
  C++ uses int types 1 and 0 to represent booleans and they're aliased in the
  standard library as the Boolean type.

## Usage example
```cpp
// Creating a number
int myNum = 0;

// Adding the number to the number 2
myNum = myNum + 2;

// Declaring a string variable
string mystring;

// Assigning a string
mystring = "my value";

// Adding strings together
string mystring2;
mystring2 = "my second value";
string mystring3 = mystring + mystring2;
```

# Assignment

You are going to create a program which adds two numbers.

1. Declare two numbers and assign them to an integer value.
2. Use the addition operator to add the numbers together.
3. Output the two numbers and the result of when they're added together

**Update**: strings
4. Declare two string variables
5. Assign your first name to the first string variable
6. Assign your last name to the last string variable
7. Create a third string variable and assign it to the first string variable
   added to the second string variable
8. Output the third string variable

[Back To Index](../README.md)