# include<stdio.h>
void main()
{
int m=0,l,n=99,t;
scanf(%d,&t);
while(n>0)
{
l=n%10;
m=m+l;
n=n/10;
}
if(n==t)
{
printf("it is palindrome");
}
else
{
printf("not a palindrome");
}
}
