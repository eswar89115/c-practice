# c-practice
#include<sdio.h>
void main()
{
int i,j,k,t=1,x;
printf("enter the no. of rows : ");
scanf("%d"&x);
for(i=1;i<=x;i++)
{
for(j=1;j<=x-i;j++)
{
prnf(" ");
}
for(k=1;k<=i;k++)
{
printf(" %d",t++);
}
printf("\n");
}
}
