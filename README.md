# GCD_OF_TWO_NUMBERS
     code is implemented in c++;
     #include<iostream>
#include<limits.h>
using namespace std;
int gcd(int a, int b)
{
    if(b==0)
        return a;
    return gcd(b,a%b);
}

int main()
{
    int a,b;
    cin>>a>>b;
    cout<<gcd(a, b);
    return 0;
}
// code with brdcoder007
