# ranju-kumari-lab-4

#include <iostream>
#include<math.h>
using namespace std;
class Power{
  public:
      double power(double x,int y){
           int i,ans=1;
          for( i=0;i<y;i++){
              ans=ans*x; 
          }
          return ans;
      }
      double power(double x)
      {
          int y = 2;
          double a;
          a = pow(x,y);
          return a;
      }
};

int main()
{
    int result = 0;
    Power pow;
    result = pow.power(8,6);
    cout<<"the  result is:"<<result;
    return 0;
}
