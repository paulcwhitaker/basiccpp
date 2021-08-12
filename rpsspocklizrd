#include <iostream>
#include <stdlib.h>

int main(){

srand(time(NULL));
int computer = rand()%3+1;
int user=0;
int diff=0;

std::cout << "====================\n";
std::cout << "rock paper scissors!\n";
std::cout << "====================\n";
 
std::cout << "1) ✊\n";  //This particular ordering ensures symmetry in the relationships, ie the ordering is set so that each next entry beats the previous.
std::cout << "2) ✋\n";
std::cout << "3) ✌️\n";
std::cout<<"4) Spock\n";
std::cout<<"5) Lizard\n";
 
std::cout << "shoot! ";
std::cin>>user;

diff=computer-user;
std::cout<<diff<<"\n";
if(diff==0) std::cout<<"tie\n";
else if(diff==1 || diff==3 || diff==-2 || diff==-4) std::cout<<"computer wins\n";
else std::cout<<"user wins\n";
  




return(0);
}
