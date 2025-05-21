# EX 29 C program to create two float variables using calloc() and find minimum among them.
## DATE:
## AIM:
To write a C program to create two float variables using calloc() and find minimum among them.

## Algorithm
1.Start

2.Allocate memory for num1 and num2 using calloc().

3.Assign values and compare using a ternary operator.

4.Print the minimum value.

5.Free allocated memory and End 

## Program:
```
/*
C program to create two float variables using calloc() and find minimum among them.
Developed by: 
RegisterNumber:  
*/
#include <stdio.h>
#include <stdlib.h>
int main() {
 int *num1, *num2, minimum;
 num1 = (int *)calloc(1, sizeof(int));
 num2 = (int *)calloc(1, sizeof(int));
 num1= 5.8 , num2 = 6.5;
 minimum = (*num1 < *num2) ? *num1 : *num2;
 printf("%d\n", minimum);
 free(num1);
 free(num2);
```

## Output:
![image](https://github.com/user-attachments/assets/24f0cc84-9aa9-4205-b7af-157c3a5614af)



## Result:
Thus the program was executed and the output was verified successfully.
