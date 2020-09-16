# Sum_of-_Digits
Created by Abdulrahim Mulla

//Sum_of_Digits
#include<stdio.h>
#include<stdlib.h>
int main()
{
	int num,sum=0,i=0,n;
	printf("Enter Total number of digits : \n");
	scanf("%d",&n);
	printf("Enter number for addition of individuals : \n");
	while(i<n)
	{	
		scanf("%d",&num);
		sum=sum+num;
		i++;		
	}
	printf("\n Sum of digits : %d \n",sum);
	return 0;
	
}

