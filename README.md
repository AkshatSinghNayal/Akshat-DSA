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

    void function1()

{
    int n;
    cout << "enter the value of n for the pattern :";
    cin >> n;

    for (int i = 0; i < n; i++)
    {
        for (int j = 0; j <= i; j++)
        {
            cout << " *";
        }
        cout << endl;
    }
}

    void function2()

{
    int n;
    cout << "enter the value of n :";
    cin >> n;
    for (int i = 1; i <= n; i++)
    {
        for (int j = 1; j <= i; j++)
        {
            cout << j;
        }
        cout << endl;
    }
}

    void function3()

{

    int n;
    cout << "enter the value of n to help in the following code :";
    cin >> n;
    for (int i = 1; i < n; i++)
    {
        for (int j = 1; j <= n - i + 1; j++)
        {
            cout << j;
        }
        cout << endl;
    }
}

    void function4()

{
    int n;
    cout << "enter the value of n to help in printing the pattern :";
    cin >> n;
    for (int i = 0; i < n; i++)
    {
        for (int j = 0; j < n - i - 1; j++)
        {
            cout << " ";
        }
        for (int j = 0; j < 2 * i + 1; j++)
        {
            cout << "*";
        }
        for (int j = 0; j < n - i - 1; j++)
        {
            cout << " ";
        }
        cout << endl;
    }
}

    void function5()

{

    int n;
    cout << " Enter the value of n for pattern implimentaion :";
    cin >> n;
    for (int i = 0; i < n; i++)
    {
        for (int j = 0; j < i; j++)
        {
            // this is for space
            cout << " ";
        }

        for (int j = 0; j < 2 * n - (2 * i + 1); j++)
        {
            // this is for stars
            cout << "*";
        }

        for (int j = 0; j < i; j++)
        {
            // this is again for space
            cout << " ";
        }
        cout << endl;
    }
    }
    
    void function6()

{
    int n;
    cout << "enter the value of n so that the pattern works :";
    cin >> n;
    for (int i = 0; i < n; i++)
    {
        for (int j = 0; j <= i; j++)
        {
            cout << "*";
        }
        cout << endl;
    }
    for (int i = 1; i < 5; i++)
    {
        for (int j = 0; j < n - i; j++)
        {
            cout << "*";
        }
        cout << endl;
    }
}

    void function7()

{
    int start = 1212;
    int n;
        cout << "Enter the value of n ";
    cin >> n;

    for (int i = 0; i < n; i++)
    {
        if (i % 2 == 0)
            start = 1;

        else
            start = 0;
        for (int j = 0; j <= i; j++)
        {
            cout << start;
            start = 1 - start;
        }
        cout << endl;
 }
}

    void function8()

{

    int n;
    cout << "Enter the value of n to move forward :";
    cin >> n;
    for (int i = 1; i < n; i++)
    {
        for (int j = 1; j <= i; j++)
        {
            cout << j;
        }
        for (int j = 2; j < 2 * (n - i); j++)
        {
            cout << " ";
        }

        for (int j = i; j >= 1; j--)
        {
            cout << j;
        }
     }
}

    void function9()

{
    int num = 1;
    int n;
    cout << "enter the value of n to print the pattern :";
    cin >> n;
    for (int i = 1; i < n; i++)
    {
        for (int j = 1; j <= i; j++)
        {
            cout << num << " ";
            num++;
        }
  }
}

    void function10()

{
    int n;
    cout << "enter the value of n so that the pattern prints :";
    cin >> n;
    for (int i = 0; i < n; i++)
    {
        for (char ch = 'A'; ch <= 'A' + i; ch++)
        {
            cout << ch;
        }
 }
}

    void function11()

{
    int n;
    cout << "enter the value of n so that the pattern prints :";
    cin >> n;
    for (int i = 1; i <= n; i++)
    {
        for (char ch = 'A'; ch <= 'A' + (n - i); ch++)
        {
            cout << ch << " ";
        }
        cout << endl;
}
}

    void function12()

{
    int num = 1;
    int n;
    cout << "enter the value of n to print the pattern :";
    cin >> n;
    for (int i = 0; i < n; i++)
    {
        char ch = 'A' + i;
        for (int j = 0; j <= i; j++)
        {
            cout << ch << " ";
        }
        cout << endl;
 }
}



    void function13(){
    

 int n;
    cout << "Enter the value of n to move forward :";
    cin >> n;
    for (int  i = 0; i <n; i++)
    {
        for (char ch = 'E'-i; ch <='E' ; ch++)
        {
            cout<<ch<<" ";
        }
        cout<<endl;
 }
 
}


    void function14(){
    

    int n;
    cout << "Enter the value of n to move forward :";
    cin >> n;
        int inis= 0;
    for (int i = 1; i <= n; i++)
    {
        for (int j = 0; j <= n-i; j++)
        {
            cout<< "*";
        }

        for (int j = 1; j <= inis; j++)
        {//Loop for space 
            cout<<" ";
        }
        for (int j = 0; j <=n-i; j++)
        {
            cout<<"*";
        }
        inis = inis + 2;
        cout<<endl;
    }   
        int ins=8;
        for (int i = 1; i <= n; i++)
        {
            for (int  j = 1; j <=i; j++)
            {
                // for star
                cout<<"*";
            }
            for (int j =0 ; j <ins; j++)
            {
                // for space
                cout<< " ";
            }
            for (int  j = 1; j <=i; j++)
            {
                // for star
                cout<<"*";
                
            }
            ins=ins-2;
            cout<<endl;
            
             
}

    void function15(){
    
    int n;
    int space = 8;
    cout<<"enter the value of n for printing the pattern :";
    cin>>n;
    for (int  i = 0; i <= n; i++)
    {
        for (int  j = 0; j <i; j++)
        {
            cout<<"*";
        }
        for (int  j = 0; j < space; j++)
        {
            // space
            cout<<" ";
        }
        for (int  j=i; j >1; j--)
        {
            cout<<"*";
        }
        space+=2;
        cout<<endl;
        
        
    }
}

    void function16(){

    int n;
    cout << "Enter the value of n to move forward :";
    cin >> n;
    for (int i = 0; i < n; i++)
    {
        for (int j = 0; j < n; j++)
        {
            if(i==0|| i==n-1|| j==0|| j==n-1){
                cout<<"*";
            }
            else cout<<" ";
        }
        cout<<endl;
    }

}
    

int main()
{

    function7();

    return 0;
}
