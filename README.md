# codes
#include <iostream>
using namespace std;
int main()
{ 
int n;
n=2;
int i = 0;
while (i < 120)
   {
    if (n==2 or n==3 or n==5 or n==7)
    cout <<n<<'\n';
    else
    if (n%2!=0)
    if (n%3!=0)
    if (n%5!=0)
    if (n%7!=0)
    {
    cout << n<<'\n';
    i++;
    }
    n++;
   }
}
//first 120 Sieve of Eratosthenes
