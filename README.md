# Hello-World
just  text


#include<stdio.h>
int main()
{
	int n,i;
	double sum;
	for( n=1, i=2, sum=0;n<=1000000;n=n+2,i=i+1)
	{
		
		double a=pow(-1,i);
		sum=sum+a*1.0/n;
	}
	printf("%lf\n",sum);	
	return 0;	
}
