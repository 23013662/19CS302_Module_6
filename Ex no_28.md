# EX 28 C program that demonstrates the use of enum (enumeration) type to define and use named integer constants.
## DATE:
## AIM:
To write a C program that demonstrates the use of enum (enumeration) type to define and use named integer constants.

## Algorithm
1.Start

2.Define an enumeration weekdays with values: Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday.

3.Declare a variable today of type weekdays and assign it the value Wednesday.

4.Check condition: If today == Wednesday:

5.Print "Today is Wednesday."

6.End 

## Program:
```
/*
C program that demonstrates the use of enum (enumeration) type to define and use named integer constants.
Developed by: santhiya c
RegisterNumber: 212223060247
*/
#include <stdio.h>
enum weekdays{ Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday};
int main()
{
 enum weekdays today = Wednesday;
 if (today == Wednesday)
 {
    printf("Today is Wednesday.\n");
 }
}

```

## Output:
![image](https://github.com/user-attachments/assets/4414e93a-790d-4b55-9af7-3075c037c3e9)



## Result:
Thus the program was executed and the output was verified successfully.
