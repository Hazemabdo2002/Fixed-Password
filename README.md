# Fixed-Password
Fixed password code with C++
#include <iostream>
#include <cstdio>
using namespace std;
void check()
{
    int pass = 1999;
    long long ent;
    cin>>ent;
    if ( ent == pass )
    {
        cout<<"Correct";
    }
    else
    {
        cout<<"Wrong"<<endl;
        check();
    }
}
int main()
{
    int pass = 1999;
    long long ent;
    cin>>ent;
    if ( ent == pass )
    {
        cout<<"Correct";
    }
    else
    {
        cout<<"Wrong"<<endl;
        check();
        
    }

    return 0;
}
