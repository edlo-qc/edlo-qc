
Edgar Loja Viri <lojed99@gmail.com>
8:30 AM (4 minutes ago)
to me

#include <iostream>

using namespace std;

int main(){
   
    int category;
    //Enter category of hurricane (1-5):> ;
    //category
    cin>>category;
    //if the category is 1, display windspeed of 74-95 mph.
    if (category==1)
    cout<<"the windpseed is 74-95 mph." ;
    //else if the category is 2, display windpseed of 96-110 mph.
    else if (category==2)
    cout<<"the windspeed is 96-110 mph." ;
    //else if the category is 3, display windspeed of 111-130 mph.
    else if (category==3)
    cout<<"the windpseed is 111-130 mph." ;
    //else if the category is 4, display the windpspeed of 131-155.
    else if (category==4)
    cout<<"the windspeed is 131-155 mph." ;
    //else if the category is 5, display the windspeed exceeds 155.
    else if (category==5)
    cout<<"the windspeed exceeds 155 mph" ;
    return 0;
}
