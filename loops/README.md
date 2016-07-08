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
Make product equal to sum added to itself and make it so that the loop goes for
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