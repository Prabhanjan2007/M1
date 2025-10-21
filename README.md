
# EX-01-Datatypes-Operators
## AIM:
Write a C program to initialize the value as 5.800000 & display the same value as 5.8.

## ALGORITHM:
1.	Declare a float variable a and initialize the value 5.8000000
2.	Use the printf satement with ".1f" to restrict the decimal places
3.	End the program.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    float a=5.800000;
    printf("%.1f",a);
    return 0;
}
```
## OUTPUT:
![alt text](<Downloads - File Explorer 19-10-2025 17_32_17.png>)


## RESULT:
Thus the program to initialize the value as 5.800000 & display the same value as 5.8 has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C program to read N value and check that value is equal to 10 or not using if-else.

# ALGORITHM:
1.	Declare a variable to store the input value N.
2.	Use the scanf function to read the value of N from the user.
3.	Check if the value of N is equal to 10.
4.	If N is equal to 10, print a message indicating that it is ten. 
5.	Otherwise, print a message indicating that it is not ten.
6.  End the program.

# PROGRAM:
```
#include<stdio.h>
int main()
{
    int N;
    scanf("%d",&N);
    if(N!=10)
    {
        printf("Given number is NOT TEN.");
    }
    else
    {
        printf("Given number is TEN.");
    }
    return 0;
}
```
# OUTPUT:

![alt text](<M1-D1-L1-Datatypes & Operators-Automata Coding-(Weekly Challenge)-SEB_ Attempt review - Google Chrome 19-10-2025 17_26_39.png>)

# RESULT:
Thus the program to read N value and check that value is equal to 10 or not using if-else has been executed successfully.
 
 
 


# EX-03- Operators-Expressions
## AIM:
Write a C program to calculate the diameter and circumference of circle.

## ALGORITHM:
1.	Declare variables to store radius as a fraction number 'a'.
2.	Use scanf to get the value from the user.
3.  Print area and perimeter using respective formulas on 'a'.
4.  End of program.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    float a;
    scanf("%f",&a);
    printf("Diameter of circle=%.2f units\nCircumference of circle=%.2f units",2*a,2*3.14*a);
    return 0;
}
```

## OUTPUT:

![alt text](<M1-D3-L2-Operators & Expressions -Automata Coding-(Weekly Challenge)-SEB_ Attempt review - Google Chrome 19-10-2025 17_57_43.png>)

## RESULT:
Thus the program to calculate the diameter and circumference of circle has been executed successfully.




# EX-04- Using Conditional Statements

## AIM:

Raju and Ramu purchased a product and they made a self analysis that if cost price and selling price of a product are input through the keyboard,Help them out to write a C program to determine whether the seller has made profit or incurred loss using IF-ELSE.

## ALGORITHM:
1.	Declare two variable to store the input value.
2.	Use the scanf function to read the input values from the user.
3.	Use an if statement to check if the difference in cost price and selling price greater than 0 or not.
4.	If the condition in the if difference is greater than 0, print the profit as the difference.
5.	Otherwise, print the difference as loss.
6.	End the program.

## PROGRAM:
```
#include<stdio.h>
int main()
{
    int a,b;
    scanf("%d\n%d",&a,&b);
    if((b-a)>0)
    {
        printf("Profit = %d",b-a);
    }
    else
    {
        printf("Loss = %d",a-b);
    }
    return 0;
}
```

## OUTPUT:
![alt text](<M1-D1-L1-Datatypes & Operators-Automata Coding-(Weekly Challenge)-SEB_ Attempt review - Google Chrome 19-10-2025 17_28_48.png>)

## RESULT:
Thus the program to determine whether the seller has made profit or incurred loss using IF-ELSE has been executed successfully



# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 
## AIM:
Write a C program to check whether number is even number and divisible by 3 or not using nested if.
## ALGORITHM:
1.	Declare a float variable 'a' to store the value.
2.  Use scanf to get the input value from user.
3.  Using if statement and modulus(%) check whether the given value is even or not.
4.  If even,print value is even and using nested if check whether the input is divisible by 3.
    a.  If divisible by 3,print number is divisible is divisible by 3.
    b.  Else print number is not divisible by 3.
5.  Else, print number is not an even number.
6.  End of program.    
## PROGRAM:
```#include<stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    if(a%2==0)
    {
        printf("The number is even\n");
        if(a%3==0)
        {
            printf("The number is divisible by %d",3);
        }
        else
        {
            printf("The number Not divisible by %d",3);
        }
    }
    else
    {
        printf("The number is NOT an even number");
    }
    return 0;
    
}
```
## OUTPUT:
![alt text](<M1-D1-L1-Datatypes & Operators-Automata Coding-(Weekly Challenge)-SEB_ Attempt review - Google Chrome 19-10-2025 17_30_22.png>)

## RESULT:
Thus the program to check whether number is even number and divisible by 3 or not using nested if has been executed successfully
