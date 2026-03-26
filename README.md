# program-4e
C module 4
EX NO:4e) Count the number of blank spaces in a given string. 

Date: 26/03/26
Name: JADEN SAMUEL ABRAHAM
Ref no: 25003451

AiM:
To write a C program to count the number of blank spaces in the given string.

ALGORITHM:
1) Get a string as input from the user.
2) Count the number of blank spaces in the string using for loop and if else statements.
3) Print the result using printf() function.

PROGRAM:
```
#include<stdio.h>
#include<ctype.h>
#include<string.h>
int main()
{
    char str[100];
    fgets(str,sizeof(str),stdin);
    int count=0;
    for(int i=0;str[i]!='\0';i++)
    {
        if(str[i]==' ')
        count++;
    }
    printf("%d",count);
}
```
OUTPUT:

<img width="531" height="147" alt="Screenshot 2025-10-20 140509" src="https://github.com/user-attachments/assets/7e50380a-f8d6-4464-be3b-4f2712ce847e" />

RESULT:
Thus the C program to count the number of blank spaces in the given string is successfully executed.















