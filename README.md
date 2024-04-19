#include <bits/stdc++.h>
using namespace std;

class Programmer{
 private: 
 string Name="Vivek Kumar";
 long int ContactNo=9310460643;
 string Profession="Full Stack Developer";

 public:
  void summary(){
  cout<<"Hello This side is : "<<Name<<"\n I am a "<<Profession<<"since 2020";
  cout<<"If you want to connect me, you can directly call on : "<<ContactNo;
  cout<<"I just like to learn new Programming Language"<<"\n Thank You for reading my read me.....";
  }

  ~ Programmer(){
  cout<<"\n Destructor Executed";
  }
};

int main(){
   Programmer Vivek_Kumar;
   Vivek_Kumar.summary();
   return 0; 
}
