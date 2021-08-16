#include <iostream>

using namespace std;

int main()
{
   cout<<" plese enter the total miles driven per day \n";
float miles;
cin>>miles;
cout<<" plese enter the cost of each mile \n" ;
float cost_mile ;
double cost , cost2 ;
cost =(miles*1.609344) ;
double num_of_litres ;
num_of_litres = cost / 6.5 ;
cost2= num_of_litres *8 ;
cin>>cost_mile ;
int number ;
cout<<" please enter number of litres of gasoline \n";
cin>> number ;
cout<<" please enter the cost per gallon of gasoline \n" ;
float  fuel;
cin>>fuel;
cout<<"please enter Parking fees per day. \n " ;
float  fees;
cin>>fees;
float average ;
average =(float) miles / fuel ;
cout<<"Average miles per gallion IS : "<<average<<"\n" ;

cout<<"total cost per day "<<(number*fuel)+fees<<"\n" ;
cout<<" another solution yo calculate cost of gasoline is : " << (cost2) <<"\n";


    return 0;
}
