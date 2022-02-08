# To-print-Armstrong-Numbers

#include <stdio.h>
#include <iostream.h>
#include <math.h>
#include <conio.h>
int main()
{
int n,s=0,r,t,copy;
cout<<"Enter number: ";
cin>>n;
t=printf("%d",n);
copy=n;
clrscr();
cout<<"Your no = "<<n<<endl;
while(n)
{
r = n%10;
s = s + pow(r,t);
n = n/10;
}
if (copy==s)
{
cout<<"Armstrong . . .";
}
else
{
cout<<"Not Armstrong. . .";
}
return 0;
}
