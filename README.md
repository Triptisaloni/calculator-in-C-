# calculator-in-C++
#include<iostream>
using namespace std;

int sum(int a, int b)
{
    cout<<"Sum = ";
    return a+b;
}

int sub(int a, int b)
{
    cout<<"Sub = ";
    return a-b;
}

int mul(int a, int b)
{
    cout<<"Multiply = ";
    return a*b;
}

int divi(int a, int b)
{
    cout<<"Division = ";
    return a/b;
}

int main()
{
    int a, b;
    char o;
    cout<<"Enter the first number "<<endl;
    cin>>a;
    cout<<"Enter the second number"<<endl;
    cin>>b;
    cout<<"Enter the operation "<<endl;
    cin>>o;
   
    
  if(o=='+')
    cout<<sum(a,b);
  else if(o=='-')   
    cout<<sub(a,b);
    else if(o=='*')   
    cout<<mul(a,b);
   else if(o=='/')
   cout<<divi(a,b);
   
   else
   cout<<"Error";
    
}
