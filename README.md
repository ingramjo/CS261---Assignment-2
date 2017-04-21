# CS261---Assignment-2
Files for Assignment 2

Part 1: Implementation of Dynamic Array, Stack, and Bag
First, complete the Worksheets 14 (Dynamic Array), 15 (Dynamic Array Amortized Execution Time Analysis), 16 (Dynamic Array Stack),
and 21 (Dynamic Array Bag). These worksheets will get you started on the implementations, but you will NOT turn them in.
Next, complete the dynamic array and the dynamic array-based implementation of a stack and a bag in dynamicArray.c. The
comments for each function will help you understand what each function should do.
We have provided the header file for this assignment, DO NOT change the provided header file (dynArray.h).
You can test your implementation by using the code in testDynArray.c. This file contains several test cases for the functions in
dynamicArray.c. Try to get all the test cases to pass. You should also write more test cases on your own, but do not submit testDynArray.c.

Part 3: Application of the Stack - 

As discussed in the lecture notes, stacks are a very commonly used abstract data type. Applications of stacks include implementation of reverse Polish notation expression evaluation and undo buffers. Stacks can also be used to check whether an expression has balanced paretheses, braces, and brackets (,{,[ or not. For example, expressions with balanced parentheses are (x+y), (x+(y+z)) and with unbalanced are (x+y,(x+(y+z).
For this part of the assignment, you are to write a function that solves this problem using a stack (no counter integers or string functions allowed). If you use a counter or a string opertation of any kind, you will not recieve credit for completing this part of the assignment.
The file stackapp.c contains two functions -
char nextChar(char*s) - returns the next character or '\0' if at the end of the string.
int isBalanced(char*s) - returns 1 if the string is balanced and 0 if it is not balanced.
You have to implement int isBalanced(char*s) - which should read through the string using 'nextChar' and use a stack to do the test. It should return either 1(true) or 0(false)

Grading
Compile without warnings = 15
Implementation of the Dynamic Array, Stack, and Bag:
   void _dynArrSetCapacity(DynArr *v, int newCap) = 10 void
   addDynArr(DynArr *v, TYPE val) = 5
   TYPE getDynArr(DynArr *v, int pos) = 5
   void putDynArr(DynArr *v, int pos, TYPE val) = 5 void
   swapDynArr(DynArr *v, int i, int j) = 2
   void removeAtDynArr(DynArr *v, int idx) = 5
   int isEmptyDynArr(DynArr *v) = 2
   void pushDynArr(DynArr *v, TYPE val) = 2
   TYPE topDynArr(DynArr *v)= 2
   void popDynArr(DynArr *v)= 2
   int containsDynArr(DynArr *v, TYPE val) = 5
   void removeDynArr(DynArr *v, TYPE val) = 5
Amortized Analysis = 20
Stack application
   int isBalanced(char*s)= 15

