#include <iostream>
using namespace std;

int main() {
  int n;

  //Declaring the number That you want to know is odd or even
  cout << "Please specify the integer in question:  ";
  cin >> n;

  // Based on the number chosen, a result will come back that your number is odd or even
  if ( n % 2 == 0)
    cout << n << " This integer is even. ";
    else
    cout << n << " This integer is odd. ";

    return 0;
    }
    
