#include <iostream>;
using namespace std;
void calculateLinearEquation(double a, double b)
{
     if(a==0 && b!=0)
     { cout<<"Корней нет";}
     else
     {  if(a==0 && b==0) { cout<<"Корень любое число"; }
     else { cout<<"Корень уравнения = "<< -b/a; }
     }
}

#include <iostream> 
#include "CalculateLinearEquation.h"; 
using namespace std; 
int main() 
{ 
    SetConsoleCP(1251);
    SetConsoleOutputCP(1251); 
    double a,b; 
    cout<<"Уравнение типа ax + b = 0\nНапример:\nКорень выражения 2,4x - 1 = 0: x = ";
    calculateLinearEquation(2.4,-1); 
    cout<<endl<<"Введите a и b: ";
    cin>>a>>b; 
    calculateLinearEquation(a,b); 
    return 0; 
}

#ifndef LABORATORNAYA_5_CALCULATELINEAREQUATION_H
#define LABORATORNAYA_5_CALCULATELINEAREQUATION_H
void calculateLinearEquation(double a, double b);
#endif //LABORATORNAYA_5_CALCULATELINEAREQUATION_H

