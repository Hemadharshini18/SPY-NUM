# SPY-NUM
CHECKING SPY NUMBER OR NOT
#include <stdio.h>
int main()
{
 int n;
   scanf("%d",&n);
 int sum=0,p=1;
   while(n!=0)
 {
       sum=sum+n%10;
 p=p*n%10;
       n=n/10;
}
   if(sum==p)
   {
       printf("SPY NUMBER");
}
   else{
printf("NOT A SPY NUMBER");
}
    }







