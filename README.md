
#include<stdio.h>
int main()
{
    /*
&x[0] =x,x[0]= *x
&x[1]= x+1, x[1]=*x+1
&x[i]=x+i, x[i]=*x+1
*/

    int x[4],i,sum=0;
    printf("Enter 4 num ");
    scanf("%d",x+i);

   for(i=0;i<4;i++)
   {
        scanf("%d",x+i);
        sum+=*(x+i); //sum=sum+ *(x+i)
   }

   printf("sum= %d",sum);

return 0;
}

