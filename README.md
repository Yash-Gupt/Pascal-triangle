#include<stdio.h>
#include<conio.h>
int main()
{
    int i,j,k,n;
    for(i=0;i<5;i++)
    {
        for(j=4;j>i;j--)
        {
            printf(" ");
        }
        for(k=0;k<=i;k++)
        {
            if(k==0||i==0)
            {
                n=1;
            }
            else 
            {
                n=n*(i-k+1)/k;    
            }
            printf("%d ",n);
        }
        printf("\n");
    }
    return 0;
}
