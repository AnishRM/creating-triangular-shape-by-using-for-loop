# creating-triangular-shape-by-using-for-loop
Beginner level

#include <stdio.h> 
int main() 
{ 
 int i,j,n; 
 printf("enter the number of row: "); 
 scanf("%d", &n); 

 for(i=0;i<n;i++) 
  { 
    for(j=0;j<=i;j++); 
      {
        printf("01"); 
      } 
    printf("\n"); 
  } 
return 0; 
} 
 
 
 
