#include <iostream> 
using namespace std; 
class Krab { 
 int chislo; 
public: 
 void res() 
 { 
  cin >> chislo; 
   cout << "Вы ввели число: " << chislo << endl; 
 
 } 
}; 
int main() 
{ 
 setlocale(LC_ALL, "Russian"); 
 Krab k; 
 k.res(); 
  
}
