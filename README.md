# C2
Rectangular pattern  using nested loop 
#include<stdio.h>
int main()
{
	int i,j,n,m;
	printf("enter the row of matrix:");
	scanf("%d",&n);
	printf("enter the column of matrix:");
	scanf("%d",&m);
	for(i=1; i<=n; i++){
		for(j=1; j<=n; j++){
				printf(" @ ");
			}
				printf("\n");
			}
	return 0;
}
