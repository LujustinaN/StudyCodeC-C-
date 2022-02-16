#include<stdio.h>
#include<conio.h>
void xuatnhiphan(int n);
int main()
{
	int n;
	printf("Nhap n: ");
	scanf("%d",&n);
	printf("Co so 2 cua %d la: \n", n);
	xuatnhiphan(n);
	printf("\n");
	return 0;	
}
void xuatnhiphan(int n)
{
	if(n>=0)
	{
		if(n/2 > 0)
		{
			xuatnhiphan(n/2);
			printf("%d", n%2);
		}
	}
}
