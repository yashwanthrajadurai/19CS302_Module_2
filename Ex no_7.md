EX NO 7 : C PROGRAM TO PERFORM MULTIPLICATION AND DIVISION OF TWO NUMBERS USING FUNCTIONS (WITHOUT ARGUMENT AND WITHOUT RETURN TYPE).

AIM:

To write a program to perform multiplication and division of two numbers using functions (without argument and without return type).

ALGORITHM:

1. Start.
2. Declare the variables.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Enter number for multiplication and division.
6. End.

PROGRAM:

#include<stdio.h>

void multiply(int a,int b);

void div(int a,int b);

int main ()

{

int a,b;

scanf("%d%d",&a,&b);

multiply(a,b);

div(a,b);

}

void multiply(int a,int b)

{

int product;

product= a*b;

printf("Multiplication: %d",product);

}

void div(int a,int b)

{

int result;

result=a/b;

printf("\nDivision: %d",result);

}


OUTPUT:

![Screenshot 2025-05-15 152421](https://github.com/user-attachments/assets/47f42f97-71f0-4880-bbfd-c73c063f510a)

RESULT:

Thus, the program is executed and verified successfully.
