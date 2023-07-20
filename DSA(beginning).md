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
    
    int main(){
        function();
        return 0;
    }
