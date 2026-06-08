
# EX 21 Write a program to calculate area of a circle using pointer.
## AIM:
To write a program to calculate area of a circle using pointer.
## Algorithm
1. Start.
2. Declare three variable value of type float.
3. Prompt the user to enter values.
4. Read the values using scanf.
5. Find the area of triangle using formula
6. End  

## Program:
```
#include <stdio.h>
#define PI 3.14

int main() {
    float radius, area;
    float *ptrRadius, *ptrArea;
    ptrRadius = &radius;
    ptrArea = &area;
    scanf("%f", ptrRadius);
    *ptrArea = PI * (*ptrRadius) * (*ptrRadius);
    printf("Area of Circle : %f\n", *ptrArea);
    return 0;
}

```

## Output:

<img width="1133" height="202" alt="image" src="https://github.com/user-attachments/assets/8c5b6cfc-26ef-470e-8229-153bbac88aa3" />


## Result:
Thus the program was executed and the output was verified successfully.
