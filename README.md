# cplus2.0-do_while_loops
printing asteris in stair form

#include <iostream>
using namespace std;

int main()
{
     int i=1, j;
     do
     {
          j=1;
          do
          {
               cout<<"*";
               j++;
     }while(j<=i);
     i++;
    cout<<endl;
    }while (i<=5);
    return 0;
}
