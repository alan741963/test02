# test02

#include<stdio.h>
int main(void)
{
	int a;
	scanf("%d",&a);
	if(a%3==2)
		printf("%d",a+1);
	else if(a%3==0)
		printf("%d",a);	
	else if(a%3==1)
		printf("%d",a-1);
			
	return 0;
}
