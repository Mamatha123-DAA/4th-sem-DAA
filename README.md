# 4th-sem-DAA
Selection sort
#include<stdio.h>
void swap(int *a, int *b)
{
    int temp = *a;
    *a = *b;
    *b = temp;
}
void selectionsort(int a[],int size)
for(int i=0;i<n-1;i++)
{
 int min=i;
 for(int j=i+1;j<n;j++)
 {
  if(a[j]<a[mid])
  {
   min=j;
   }
  }
 if(min!=i)
 {
  swap(a[i],a[min])
  }
 }
 int main()
 {
 int a[];
 int n;
 printf("Enter the size of the array:");
 scanf("%d",&n);
 printf("Array elements are:");
 for(int i=0;i<n;i++)
 {
  scanf("%d",&a[i]);
 }
 selectionsort(a[],n);
 printf("After sorting");
 for(int i=0;i<n;i++)
 {
  scanf("%d",a[i]);
 }
 }
 
 
