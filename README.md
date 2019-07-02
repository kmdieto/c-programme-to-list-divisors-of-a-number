# c-programme-to-list-divisors-of-a-number
A programme that computes the divisors of a number in a particular range
#include <iostream>
# include <cmath>
using namespace std;
int range;


int num;
int main(){
    cout<<"PROGRAM TO LIST THE DIVISORS OF A NUMBER IN A GIVEN RANGE"<<endl<<endl<<"ENTER THE NUM"<<endl;
    cin>>num;
    cout<<"ENTER THE RANGE"<<endl;
    cin>>range;
    cout<<"------------------------------------------------------------"<<endl;

int x=1;
    while(x < range){
            int counter =x;

            if (num % x==0){cout<<num/x<<"   ______  divided by ......"<<x<<endl;}

            
x++;
}
    }
