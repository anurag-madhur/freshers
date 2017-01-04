#include<stdio.h>

int add(int x,int y)
{
	int z;
	z=x+y;
	return z;	

}
int swap(int x, int y)
{
x=x+y;
y=x-y;
x=x-y;
printf("after swapping the value of x is %d and y is %d", x,y);
}

void main()
{
	int a,b,c;
	
	scanf("%d%d",&a,&b);
	
	c=add(a,b);
	swap(a,b);
	printf("Sum of the two no.s is %d",c);

}
