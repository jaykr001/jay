#include <stdio.h>

int main() 
{
	int a1[1000],i,j,k;
	for(i=0;i<1000;i++)
	scanf("%d" &a1[i]);
	
	for(i=0;i<1000;i++){
	if (a1[i]>a1[i+1])
	printf("%d"a1[i+1]);
	else
	printf("-1");
	}
	printf("-1");

	
}
