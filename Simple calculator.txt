#include <iostream>
using namespace std;

int main()
{
 
 char operation;
 float x ,y ;
    cout<<"Enter the operation (+ or - or * or /) :  "<<endl;
    cin>>operation;
    cout<<"Enter the two numbers, taking into consideration that the order is important in some operations "<<endl;
    cin>>x>>y;
    switch(operation)
     {
         case'+':
         cout<<x<<"+"<<y<<"="<<x+y;
         break;
          case'-':
         cout<<x<<"-"<<y<<"="<<x-y;
         break;
          case'*':
         cout<<x<<"*"<<y<<"="<<x*y;
         break;
          case'/':
         cout<<x<<"/"<<y<<"="<<x/y;
         break;
         default:
         cout<<"ERROR! operation is not found  "<<endl;
         break;
     }
    
    return 0;
}