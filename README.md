# Odd-or-even-using-Bitwise-Operator-in-C
#Print the Odd or Even using Bitwise Operator in Conditional Operator, Instead of using if-else statement. 
#include<stdio.h>
void main(){
    int a;
    printf("Enter the number:");
    scanf("%d",&a);
    ((a&1)==0) ? printf("Even Number") : printf("Odd Number");
}
