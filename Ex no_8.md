EX NO 2E : C PROGRAM TO FIND FACTORIAL OF THE GIVEN NUMBER.

AIM:

To write a program to find factorial of the given number.

ALGORITHM:

1. Start.
2. Declare the variables.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Enter factorial of the number.
6. End.

PROGRAM:

#include <stdio.h>

int main() {

 int n, i;
 
 unsigned long long factorial = 1;
 
 scanf("%d", &n);
 
 if (n < 0) {
 
 printf("Factorial is not defined for negative numbers.\n");
 
 } else {
 
 for (i = 1; i <= n; i++) {
 
 factorial *= i;
 
 }
 
 printf("Factorial of %d = %llu\n", n, factorial);
 
 }
 
 return 0;

}

OUTPUT:

![Screenshot 2025-05-15 153016](https://github.com/user-attachments/assets/d823fe64-849a-41eb-baf4-d13f7a62d863)

RESULT:

Thus, the program is executed and verified successfully
