# amaiiii[baitap1.cpp](https://github.com/user-attachments/files/25084987/baitap1.cpp)
#include <stdio.h>
int main ()
{
	int a[50][50];
	int n,j;
	do
	{
		printf ("Nhap n=");
		scanf("%d",&n);
	}while(n<=0);
	
	for (int i = 0; i<n; i++)
	{
		for(int j=0; j<n; j++)
		{
			printf("a[%d][%d]",i,j);
			scanf("%d",&a[i][j]);
		}
	}
	//xuat ma tran
	printf("\nXuat ma tran : \n");
	for (int i=0; i<n; i++)
	{
		printf("\n");
		for(int j=0; j<n; j++)
		{
			printf("a[%d][%d]=",i,j);
			scanf("5%d",&a[i][j]);
			
		}
	}
		
printf("\nGia tri cua ma tran : ");
	
	return 0;
}
