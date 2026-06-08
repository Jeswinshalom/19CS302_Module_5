
# EX 25 C program to find character 'V' is vowel or consonant using pointer.
## DATE: 
## AIM:
To write a C program to check whether a given character is a vowel or consonant using pointer

## Algorithm
1. Start.
2. Declare a variable value of type char.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Find vowel and consonants
6. End.

## Program:
```
#include<stdio.h>
int main()
{
  char c, *pc;
  pc= &c;
  scanf("%c", pc);

  if( (*pc=='A'||*pc=='E'||*pc=='I'||*pc=='O'||*pc=='U') ||
      (*pc=='a'||*pc=='e'||*pc=='i'||*pc=='o'||*pc=='u') )
    printf("%c is Vowel.\n", *pc);

  else
    printf("%c is consonant.\n", *pc);

  return 0;
}
```

## Output:

<img width="1140" height="200" alt="image" src="https://github.com/user-attachments/assets/e2c30ff7-a2d2-4abe-852e-f8fdb50dbd5c" />


## Result:
Thus the program was executed and the output was verified successfully.
