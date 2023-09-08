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





Program to find the complimentary 
    
    #include<iostream>  
    using namespace std;
    
    void compliment(){
    
    // program to find the compliment of the no. 
        int n;
        cout<<"Enter the value of n to print compliment of the no. ";
        cin>> n ;
        int ans;
        int m=n;
        int mask = 0 ;
        while (m!=0)
        {
            mask = (mask << 1)| 1; // we are just doing 0000...111 this intension 
            m = m >> 1;

    }
    ans = (~n) & mask; // the 5 is 000...00101 so doing and with mask ie = 0000111 gives you 2 hence that's all we needed
    cout<<ans;
    }

    
    void function (){

    int n ;
    cout<<"Enter the value of n to reverse the number :";
    cin>>n ;
    int digit = 0;
    int ans = 0 ;
    while (n!=0)
    {
        digit = n % 10 ;
        
        ans = (ans*10) + digit ;
        n = n / 10 ;
    

    }
    cout<<ans ;
    }





Basic Calculator 

    
    #include<iostream>
    using namespace std;
    
    int main(){
        int  a ;
        int b ;
        cout<< "Enter the value of a ";
        cin>>a;
        cout<< "Enter the value of b ";
        cin>>b;
        char operation ;
        cout<< "Enter the operator : ";
        cin>>operation;

    switch (operation)
    {
        case '+': cout<< a+b ;
        break;
        case '-': cout<< a-b ;
        break;
        case '*': cout<< a*b ;
        break;
        case '/': cout<< a/b;
        break;
        case '%'; cout<< a%b;
        default : cout<<"Calculation finished successfully : ";
    }
    return 0;
    }    



Some functions 
   
    
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
        cout << "Enter the number to check its a prime number or not :";
        cin >> n;
        if (n % 2 == 0)
        {
            cout << " Its not a prime number :";
        }
        else
            cout << " Its a prime number boii !!";
    }
    
    void functionP()
    {
        int n;
        cout << "enter the req value of n :";
        cin >> n;
        int ans = 0;
        int i = 0;
        while (n != 0)
        {
            int bit = n & 1;
            ans = (bit * pow(10, i)) + ans;
            n = n >> 1;
            i++;
        }
        cout << ans;
    }
    
    int main()
    {
        // functionP();

    int num = 5;

    switch (num)
    {
    case 1:
        cout << " hello world ";
        break;
    case 5:
        cout << " hello this is akhsat " << endl;
    default:
        cout << " this is the default value ";
    }
    return 0;
}


 

