//# harsh-kumar-nagar
//project for finding out the largest number in the given list
#include<stdio.h>
int main(void)
{
	int age[10];
	int i ;
	int agemax =0;
	for(i=0;i<10;i++)
	{
		scanf("%d",&age[i]);
		if(age[i]>agemax)
		{
			agemax=age[i];
		}
	}
	printf("%d",agemax);
	return 0;
}
