// This is the code by Akshat Nayal
// To convert decimal to binary number



    #include<iostream>
    #include<math.h>
    using namespace std;


    void function(){
    int n;
    int answer=0;
    int i=0;
    cout<<"Enter the value of n :";
    cin>>n;

    while( n !=0 ){
        int bit = n & 1;
        answer=(bit*pow(10,i)) + answer;
        n= n>>1;
        i++;


    }
    
    cout<<"Answer of this decimal no . is "<< answer<<endl;
    }

    int main(){

    function();
    
    return 0;
    }

//This is the program to convert binary to the decimal number :

    #include<iostream>
    #include<math.h>
    using namespace std;
    
    void function(){
        int n;
        cout<<"Enter the value of n :";
        cin>>n;
        int ans=0, i=0;
        while(n!=0){
            int digit = n%10;
            if(digit == 1 ){
                ans = ans + pow(2,i);
            }
            n=n/10;
            i++;
            
            
        }
    
        cout<<"The answer is "<< ans ;
    
    }
// Function to buid basic algo :
    #include <iostream>
    using namespace std;
    
    void function()
    {
        // sum from 1 to n ;
        int n;
        int sum = 0;
        cout << "enter the value of n to start counting :";
        cin >> n;
        cout << "Here you go ! :";
        for (int i = 1; i <= n; i++)
        {
            sum = sum + i;
        }
        cout << sum;
    }







    void function1()
    {
        // function for fab series
        int n;
        int a = 0, b = 1;
        int nextnumber;
        cout << "Enter the value of n :";
        cin >> n;
        cout << a << " , " << b << " , ";
        for (int i = 0; i < n; i++)
        {
            nextnumber = a + b;
    
            a = b;
            b = nextnumber;
            cout << nextnumber << " , ";
        }
    }







    void function2()
    {
        // function to check the no. is prime or not :
        int n;
        int result;
        int sum = 0;
        cout << "Enter the number to check its a prime number or not :";
        cin >> n;
         if (n % 2 == 0)
            {
                cout << " Its not a prime number :";
            }
            else
                cout << " Its a prime number boii !!";
    }


    
    int main()
    {
        function1();
        return 0;
    }
