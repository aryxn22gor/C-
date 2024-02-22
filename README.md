#include<iostream>
#include<iomanip>
using namespace std;
int main()
{
 float km, m, cm, feet, inch;
 cout<<"Enter any value in kilometer: ";
 cin>>km;
 m = km * 1000;
 cm = m * 100;
 feet = cm / 30;
 inch = cm / 2.54;
 cout<<setw(10)<<setfill('*')<<setprecision(3)<<"kilometres"<<km<<endl;
 cout<<setw(10)<<setfill('*')<<setprecision(6)<<"meter"<<m<<endl;
 cout<<setw(10)<<setfill('*')<<setprecision(6)<<"centimeters"<<cm<<endl;
 cout<<setw(10)<<setfill('*')<<setprecision(6)<<"feet"<<feet<<endl;
 cout<<setw(10)<<setfill('*')<<setprecision(6)<<"inch"<<inch<<endl;
 return 0;
}
