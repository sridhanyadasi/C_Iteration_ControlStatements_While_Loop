*Introduction

In C programming, iteration control statements are used to execute a block of code repeatedly until a specific condition becomes false.
One of the most commonly used iteration statements is the while loop.

The while loop checks the condition before executing the loop body. If the condition is true, the statements inside the loop will execute. This process continues until the condition becomes false.

*What is a While Loop?

A while loop is an iteration control statement in C that repeatedly executes a block of code as long as the specified condition is true.

It is also called a pre-test loop because the condition is checked before executing the loop body.

*Why We Use While Loop

The while loop is used when:

The number of iterations is not known in advance

We need to repeat a task until a condition becomes false

We want to control execution based on a condition

*Example situations:

Reading input until a user enters a specific value

Printing numbers until a limit is reached

Menu-driven programs

*Syntax of While Loop

while(condition)
{
    // statements to be executed
}
Execution Steps

Initialize the variable before the loop.

The condition is checked.

If the condition is true, the loop body executes.

The variable is updated inside the loop.

The program goes back and checks the condition again.

If the condition becomes false, the loop terminates and control moves to the next statement.

Example Program
#include <stdio.h>

int main()
{
    int i = 1;

  while(i <= 5)
    {
        printf("%d\n", i);
        i++;
    }

  return 0;
}
Output
1
2
3
4
5

**Purpose of this Repository

The purpose of this repository is to:

Understand the concept of iteration control statements

Learn how the while loop works in C

Practice simple C programs using while loops

Build a strong foundation in looping concepts

*Author*

~Sri Dhanya
