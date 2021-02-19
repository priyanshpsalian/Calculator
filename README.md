# Calculator
#include<iostream.h>
#include<conio.h>
int main
{ 
    double num,den,result;
    char op;
    cout<<"Enter two no between whom you want to perform operations"<<endl;
    cin>>num>>den;
    cout<<"Enter what operation you want to perform from the following +,-,*,/"<<endl;
    cin>>op;
    if (op=='+') 
    {
        result=num+den;
    }  
    if (op=='-') 
    {
        result=num-den;
    }   
    if (op=='*') 
    {
        result=num*den;
    }   
    if (op=='/') 
    {
        result=num/den;
    }  
    cout<<"Your ans is" <<result;
 }   
    
