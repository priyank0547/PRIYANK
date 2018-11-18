#include<stdio.h>
#include<stdlib.h>
int main()
{
  int i,n;
  printf("enter the number of elements:");
  scanf("%d",&n);
  int a[n];
  printf("enter the elements in an array:");
  for(i=0;i<n;i++)
  {
     scanf("%d",&a[i]);
  }
  printf("the entered array is:");
  for(i=0;i<n;i++)
  {
    printf("%d",a[i]);
  }
  
}
