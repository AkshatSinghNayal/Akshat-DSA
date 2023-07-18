# Akshat-DSA
Here is the code for practise of DSA by (Akshat Nayal)
This is for Pattern Printing

#include <iostream>
using namespace std;

void function()
{
    int n;
    cout << "enter the value of n :";
    cin >> n;
    for (int i = 0; i < n; i++) // it is responsible for the number of rows in the pattern
    {
        for (int j = 0; j < n; j++) // it is responsible for the iteration in the rows in the pattern
        {
            cout << "*";
        }
        cout << endl;
    }
}
