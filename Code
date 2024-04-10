#include<iostream>
#include<cstdlib>
#include<ctime>
using namespace std;



class guesso{
int guess;
int integ;

public:
    guesso(){
srand((unsigned int)time(NULL));


int integ=(rand() % 100) + 1;

int guess = 0;


do{

 cout<<"ENTER THE GUESS(1-100)"<<endl;
        cin>>guess;

        if(guess>integ)
        cout<<"GUESS LOWER"<<endl;
        else if(guess<integ)
        cout<<"GUESS HIGHER"<<endl;
        else
        cout<<"YOU HAVE WON THE GAME"<<endl;

}while(guess!=integ);
    }
};
int main(){

guesso g1;

return 0;
}
