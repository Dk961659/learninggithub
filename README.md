# learninggithub this is my first git hub code
# for the front and back function
#include <stdio.h>
#include<iostream>
#include<array>
using namespace std;

int main()
{
    std::array<int,5> arr={11,22,33,44,55};
    cout<<arr.front();
    return 0;

}

--- at function for the position ---
int main()
{
    std::array<int,5> arr={11,22,33,44,55};
    cout<<arr.at(2);
    return 0;

}
output-- 33
--- [] operator ---
int main()
{
    std::array<int,5> arr={11,22,33,44,55};
    cout<<arr[3];
    return 0;

}
output- 44
--- fill function ---
#include <stdio.h>
#include<iostream>
#include<array>
using namespace std;

int main()
{
    std::array<int,8> arr={11,22,33,44,55};
    arr.fill(10);
    for(int i=0;i<=7;i++)
    cout<<" "<<arr[i];
    return 0;

}
output- 10 10 10 10 10 10 10 10
--- swap function ---
#include <stdio.h>
#include<iostream>
#include<array>
using namespace std;

int main()
{
    std::array<int,5> arr1={11,22,33,44,55};
    std::array<int,5> arr2={1,2,3,4,5};
    arr1.swap(arr2);

    
    for(int i=0;i<=4;i++)
    cout<<" "<<arr1[i];
    cout<<endl;
    
    for(int i=0;i<=4;i++)
    cout<<" "<<arr2[i];
    return 0;

}
 output-- 1 2 3 4 5
          11 22 33 44 55 
--- size function ---
#include <stdio.h>
#include<iostream>
#include<array>
using namespace std;

int main()
{
    std::array<int,5> arr={11,22,33,44,55};
    cout<<"size is "<<arr.size();
    return 0;

}
output-- size is 5

