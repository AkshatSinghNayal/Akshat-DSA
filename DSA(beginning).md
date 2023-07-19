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
