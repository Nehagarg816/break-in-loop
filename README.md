# break-in-loop
This is a program for syntax of break statement in while loop.
#include<stdio.h>
#include<conio.h>
void main()
{
	int i=1,a,b;
	printf("Enter value of a:");
	scanf("%d",&a);
	while(i<=a)
	{
		printf("Enter value of b:");
	    scanf("%d",&b);
	    if(b%2==0)
	    break;
	    i++;
	}
	i==a+1?printf("Loop ends normally"):printf("break applied");
}
