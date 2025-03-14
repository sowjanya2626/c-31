//To Check Minimum two numbers using a function and ternary operator ,using return values while passing arguments also by using mirror values
#include<stdio.h>
int min(int a,int b)
{
    return (a<b)?a:b;
}
int main()
{
   int x,y;
   printf("enter the value of x");
   scanf("%d",&x);
   printf("enter the value of y");
   scanf("%d",&y);
   printf("minimum:%d \n",min(x,y));
    return 0;
}
