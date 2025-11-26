#include <stdio.h>
int main()
{
    int num1, num2, temp;
    printf("enter number1 :");
    scanf("%d", &num1);
    printf("enter number2 :");
    scanf("%d", &num2);
    printf("before swapoing, num1=%d, num2=%d",num1,num2);
    temp=num1;
    num1=num2;
    num2=temp;
    printf("after swapping num1 =%d,num2=%d", num1,num2);
    return 0;
}# c-7
write a program to perform swapping
