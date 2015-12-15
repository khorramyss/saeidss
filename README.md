# saeidss

#include <fstream>
#include <iostream>
#include <iomanip>
#include <cmath>
Class Clr{
private:
      const long long unsigned;
      static long long unsigned;  
      const unsigned int;
      long double R;
public:
      Clr ():m(1844073709551615ul),x(9),a(9),c(3){;}
      long double Rand(){		   
      X = (a*X + c)%m;
      R = double(X) / m;
      return (R);
int main()
{
   Clr ob;
   std::of stream out;
   out open("mirik",std::ios::out);
   for (int i =0;i<1000;i++)
{
    long double R=ob.Rand()
    out<<std::set w(10)<<i<<std::set w(20)<<R<<std::endl;
}
}
