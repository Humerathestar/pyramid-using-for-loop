include <stdio.h>

int main()
{
    int i,j;
    printf("enter the value of i and j");
    scanf("%d%d",&i,&j);
    
   for(i=1;i<=4;i++)
   {
       for(j=1;j<=i;j++)
       {
           printf("*");
           
       }
       printf("\n");
   }
   

    return 0;
}
