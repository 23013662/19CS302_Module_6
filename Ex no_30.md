# EX 30 C program to add two integer elements in an array using realloc() and that array already has three elements.
## DATE:
## AIM:
To write a C program to add two integer elements in an array using realloc() and that array already has three elements.

## Algorithm
1.Start

2.Allocate and reallocate memory for list using malloc() and realloc().

3.Check memory allocation, then assign values.

4.Print list elements using a loop.

5.Free memory and End. 
  

## Program:
```
/*
C program to add two integer elements in an array using realloc() and that array already has three elements.
Developed by:santhiya c 
RegisterNumber:212223060247  
*/
#include <stdio.h>
#include <stdlib.h>
int main()
 {
    int i;
    float *list;
    list = (float *)malloc(3 * sizeof(float));
    if (list == NULL)
    {
        printf("Initial memory allocation failed.\n");
        return 1;
    }
    list[0] = 12.33;
    list[1] = 67.44;
    list[2] = 89.55;
    list = (float *)realloc(list, 5 * sizeof(float));
    if (list == NULL)
    {
        printf("Memory reallocation failed.\n");
        return 1;
    }
    list[3] = 20.21;
    list[4] = 32.67;
    printf("Result\n");
    for (i = 0; i < 5; i++)
    {
        printf("%.2f ", list[i]);
    }
    printf("\n");
    free(list);
    return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/f8d0976a-f2b3-4848-b47a-7e3facd1d8ee)



## Result:
Thus the program was executed and the output was verified successfully.
