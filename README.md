# C to read any Month Number in integer and display the number of days for this month.
## AIM:
To Write a program in C to read any Month Number in integer and display the number of days for this month.
## ALGORITHM:
1. Include the standard input-output header file.
2. Define the main function.
3. Declare a variable to store the month number.
4. Prompt the user to enter the month number and read the input.
5. Use a switch statement to handle different cases based on the month number:
   a. For months with 31 days (January, March, May, July, August, October, December), print "Number of days: 31".
   b. For months with 30 days (April, June, September, November), print "Number of days: 30".
   c. For February (month number 2), print "Number of days: 28 or 29 (leap year)" depending on whether it's a leap year.
   d. For any invalid month number, print "Invalid month number".
## PROGRAM:
```
#include <stdio.h>
int main()  
{
    int x;
    scanf("%d",&x);
    if (x==1||x==3||x==5||x==7||x==8||x==10||x==12)
    {
        printf("Month have 31 days.\n");
    }
    else if (x==4||x==6||x==9||x==11)
    {
        printf("Month have 30 days.\n");
    }
    else
    {
        printf("Month have 28 or 29 days.");
    }
    return 0;
}
```
## OUTPUT:

![image](https://github.com/VerginJenifer/c-programming-9/assets/136251012/7f25f666-171f-45e4-9ab9-6f70523c1fb6)

## RESULT:
Thus, a C to read any Month Number in integer and display the number of days for this month was executed successfully.
