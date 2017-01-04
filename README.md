#include<stdio.h>
#include<conio.h>

int add(int a,int b);
void main()
{
int a,b,c;
printf("enter the value of a and b");
scanf("%d %d",&a,&b);
c=add(a,b);
getch();
}
int add(int a,int b)
{
int sum;
sum=a+b;
return sum;
}
