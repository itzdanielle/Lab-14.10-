# Lab-14.10-
#include <iostream>
using namespace std;

int main() {
  int number = 0;
  double average;
  cout << "Enter 10 when done" << endl;
  cout << "input the first number" << endl;
  cin >> number;
  
  for ( int number = 1; number <=10; number++ ) {
    cout << "Please input a number " << endl;
     cin >> number;
  }
 
 average = (number + number + number + number) /4;
cout << "The average of the numbers you entered is: " << average << endl;


}
