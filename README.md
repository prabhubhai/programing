#include<stdio.h>
using namespace std;
int main()
{
  int a;
  cout<<"Enter the age";
  cin>>a;
  
  if(a>0)
  {
    cout<<"Please Enter the valide number";
   }
   else if(a<=18)
   {
    cout<<" You are a kid";
   }
   else
   {
      cout<<"You are not kid";
   }
}
