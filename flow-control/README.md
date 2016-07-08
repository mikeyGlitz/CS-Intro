[Back To Index](../README.md)

# Introduction

Flow control is the name that is given to structures in computer science which
control the flow of the execution. These flow control structures exist in most
languages as condiditional statements (typically referred to as if-then statements),
and loops.

This module will focus on logical flow control statements. In C++ as well as
a lot of other computer languages, conditional statements exist in two forms:
* switch-case blocks
* if-then-else blocks

## Example of an if-then-else block
```cpp
// Arbitrary number for the sake of example
int numberOfCars = 3;

//Set up an if block
if(numberOfCars == 3){
    // If we're in here, that means the number of cars was 3. == tests equality,
    // DO NOT confuse with assignment!!!
    
    // Do stuff
}

// Else if basically will only run if the previous if block did not run
// and the condition in the if proceeding the else is met
else if (numberOfCars == 4){
    // Will only run if numberOfCars was not equal to 3, but equal to 4
    
    // Do stuff
}
else{
    // Will only run if numberOfCars was not equal to 3 or equal to 4
    
    // Do stuff
}

```

### Assignment 1

For this assignement, you are going to write a program which categorizes animals
by the amount of legs they have. The following conditions need to be met:
* If the animal has 4 legs, then it's a dog
* If the animal has 6 legs, then it's a ladybug
* If the animal has 8 legs, then it's an octopus
* If the animal has 2 legs, then it's an ostrich
* If the animal has 0 legs, then it's a fish
* If the animal has 1,000,000 legs, then it's a milipede and it's amazing!!!
* Otherwise, the you output that it is not an animal

## Switch

Switch-case blocks are a lot like if-then-else blocks, but with a catch. Switch-
case blocks can only be used with a limited set of datatypes:
* numerical datatypes
* enumerations
* characters (but not strings)

The logical flow of a switch-case block will start with accepting a variable and
then going through each case block until it finds a matching case. If a matching
case isn't found, the next lines after the switch case block will be run.
From the previous example:

```cpp
int numberOfCars = 3;

switch(numberOfCars){
    case 3:
        // If we're in here, that means that the number of cars was 3.
        break;
    case 4:
        // If we're in here, that means the number of cars was 4.
        break;
    default:
        // This will run if any of the above conditions were not met.
        break;
}

```

Break statements are used to break out of the switch block and continue with the
code after the switch block.

It is possible to have a case which accepts more than one condition.

### Example of multi-condition case
```cpp
// ...
case 4:
case 5:
    // Do stuff if the number is 4 or 5
    break;
// ...
```

### Assignment 2

For this assignment, take the code for example 1 and replace the if else blocks
with switch case statements

[Back To Index](../README.md)