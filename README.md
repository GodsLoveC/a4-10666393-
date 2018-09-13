# a4-10666393-
assignment
#include<iostream>
using namespace std;
int gcd (int n1, int n2);
int main()
{
int n1,n2;
cout<<"Enter two positive integers:";
cin>>n1>>n2;
cout<<"G.C.D of"<<n1<<"&"<<n2<<gcd(n1,n2);
return 0;
}
if (n2!=0)
return gcd(n2,n1 % n2); 
else
return n1;
}
