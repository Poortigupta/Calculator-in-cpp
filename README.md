# Calculator-in-cpp
Code of simple calculator in cpp
#include<iostream>
using namespace std;
int main(){
       int a,b;
       char op;
       cout<<"Enter the value of a and b and valid operator(+,-,*,/,%)"<<endl;
       cin>>a>>b>>op;
       switch( op ){

        case '+': cout<<"Add of a and b is:"<<a+b<<endl;
                  break;
        case '-': cout<<"Subtraction of a and b is:"<<a-b<<endl;
                 break;
      case '*': cout<<"Multiplication of a and b is:"<<a*b<<endl;
                 break;
     case '/': cout<<"Division of a and b is"<<a/b<<endl;
                 break;
     case '%': cout<<"Modulo of a and b is"<<a%b<<endl;
                 break;
     default : cout<<"Not an valid operator"<<endl;  

       }
}
