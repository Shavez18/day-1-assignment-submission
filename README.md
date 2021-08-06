# Day-1-assignment-submission

Question-1:
What is the time complexity T(n) for the following code snippet?
a = 1
b = 1
while(b <= n)
{
  a += 1
  b += 1
  cout<<"Hi";
}

Solution: T(n) = O(n)
Since it is increasing linearly

Question-2:
Write the output for the following recursive code snippet for n = 3:
void fun(int n)
{
  if(n > 0)
  {
     cout<<n:
     fun(n - 1);
     cout<<n;
  }
}

Solution:
//Program:-
#include <iostream>
using namespace std;
void fun(int n)
{
  if(n > 0)
  {
    fun(n - 1);
    cout<<n;
  }
}
int main()
{
    fun(3);
    return 0;
}

//Output:
123
