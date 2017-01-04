#include<stdio.h>

int add(int x,int y,int a)
{
	int z;
	z=x+y+a;
	return z;	

}

void main()
{
	int a,b,c;
	int d;
	scanf("%d%d",&a,&b,&d);
	
	c=add(a,b,d);
	printf("Sum of the two no.s is %d",c);

}
