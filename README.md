#include <iostream>
#include <string>
using namespace std;

int main (){
  string fullName;
  int age, currentYr, birthYr, yearAt_60;
  
     cout << "Enter your Full Name: ";
     cin >> fullName;

     cout <<"Enter your Age: ";
     cin >> age;

     cout <<"Enter Current Year: ";
     cin >> currentYr;

  yearAt_60 = (currentYr - age) + 60;
  
     cout <<"Your name is " << fullName << " you are " << age << " years old,";
     cout <<" You will turn 60 years old in the year of << yearAt_60 << endl;
}
     
