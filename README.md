#include<stdio.h>
#include<string.h>
int main() 
{
    char x[100];
    int n,i,j,k,l;
    scanf("%s",x);
    scanf("%d",&n);
    l=strlen(x);
    for(i=n;i<l;i++)
       {
       printf("%c",x[i]);
       }
    for(i=0;i<n;i++)
       {
       printf("%c",x[i]);
       }
}
