EX NO 6: C PROGRAM TO PRINT A RIGHT TRIANGLE STAR PATTERN USING NESTED FOR LOOP

AIM:

To write a c program to print a right triangle star pattern using nested for loop.

ALGORITHM:

1. Start.
2. Declare the variables i,j,k,n.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Enter number of rows and columns.
6. End.

PROGRAM:

#include <stdio.h>

int main() {

 int i, j, rows;
 
 scanf("%d", &rows);
 
 for (i = 1; i <= rows; i++) {
 
 for (j = 1; j <= i; j++) {
 
 printf("*");
 
 }
 
 printf("\n");
 
 } return 0;

}

OUTPUT:

![Screenshot 2025-05-15 152118](https://github.com/user-attachments/assets/13646b69-7f00-4aa3-bda6-85d2dc1f8c20)


RESULT:

Thus, the program is executed and verified successfully
