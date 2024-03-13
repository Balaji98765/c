# c
//sum of diagonals
#include <stdio.h>
int main()
{
   int m,n,b=0,rev=0,rem,l,o;
   scanf("%d %d",&m,&n);
   int a[n][m];
   for (int i= 0;i<n;i++){
   for(int j=0;j<m;j++)
   {
     scanf("%d",&a[i][j]);
    }}
    
    for(int i=0;i<n;i++){int c=0;
    for(int j=0;j<m;j++)
    {
      if(c<a[i][j])
      c=a[i][j];}
      b=b+c;
    printf("%d",c);}
    printf("\n%d",b);
    int i=0;
    while(i<b)
    {
      rev=b%10;
      rem=rem+rev;
      b=b/10;
    }
    printf("\n%d",rem);
    int j=0;
    while(j<rem)
    {
      l=rem%10;
      o=o+l;
      rem=rem/10;
    }
    printf("%d",o);
}

