# ranju-kumari-lab-4

#include<iostream>
#include<conio.h>
using namespace std;
void multiplication(int,int);            //function declaration with two argument
void multiplication(int,int,int);       //function declaration with three arguments
int main()
{
    multiplication(23,14);           //taking input for one two arguments function
    multiplication(34,12,13);         //taking input for one three arguments function
    return 0;
    getchar();
}
//driver code:
void multiplication(int x, int y)
{
cout<<"the multiplication of x*y= "<<(x*y)<<endl;
}
void multiplication(int x, int y, int z)
{
cout<<"the multiplication of x*y*z= "<<(x*y*z)<<endl;
}
