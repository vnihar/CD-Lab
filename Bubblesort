#include <stdio.h>

int main()
{
    int i,j,temp,size;
	int arr[10];
   	printf("\nEnter the size of array:");
	scanf("%d",&size);
	printf("\nEnter the array------");
	for(i=0;i<size; i++)
	{
		printf("\nEnter the element%d=",i+1);
		scanf("%d",&arr[i]);
			}
	      for(i=0;i<size; i++)
	{
		for(j=0;j<size-i;j++)
		{
			if(arr[j]>arr[j+1])
			{
				temp=arr[j+1];
				arr[j+1]=arr[j];
				arr[j]=temp;
			}
		}
		printf("\nAfter %d Iteration array is:",i+1);
		for(j=0;j<size;j++)
		printf("\t%d",arr[j]);
	}
	printf("\nsorted array is----\n");
	for(i=0;i<size;i++)
	printf("\t%d",arr[i]);	
	
}
