# C7
odd natural numbers
#include<stdio.h>
int main()
{
	int n,i;
	printf("enter the number:\n");
	scanf("%d ",&n);
	for(i=1;i<=n;i++)
	{
		if(i%2!=0)
		printf("%d",i);
    }
     printf("\n");
     return 0;
 }
