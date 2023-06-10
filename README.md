# 4th
#include<iostream>
using namespace std;

// Loops in C++

// 1. While Loop - syntax
// int main(){
//     int i = 1;
//     while(i<=5){
//         cout<<i<<endl;
//         i++;
//     }
//     return 0;
// }


// Q1. Print the sum of first n natural numbers where n is the input
// int main(){
//     int n,i=1,sum = 0;
//     cout<<"Enter the numbers you want to Add : ";
//     cin>>n;
//     while(i<=n){
//         sum+=i;
//         i++;
//     }
//     cout<<"The sum of natural numbers is : "<<sum<<endl;
//     return 0;
// }



// 2. For Loop - syntax

// int main(){
//     int i;
//     for(i=1;i<=5;i++){
//         cout<<i<<endl;
//     }
//     return 0;
// }



//Q2. Print the sum of first n natural numbers where n is the input but now with a for loop

// int main(){
//     int i,sum=0,n;
//     cout<<"Enter the any natural number : ";
//     cin>>n;
//     for(i=1;i<=n;i++){
//         sum+=i;
//     }
//     cout<<"The Sum of the natural number is : "<<sum<<endl;
//     return 0;
// }



// this is the same code for the above problem but with INIT condition ommitted 
// int main(){
//     int i=1,sum=0,n;
//     cout<<"Enter the any natural number : ";
//     cin>>n;
//     for(;i<=n;i++){
//         sum+=i;
//     }
//     cout<<"The Sum of the natural number is : "<<sum<<endl;
//     return 0;
// }

//this is the same code for the above problem but with final condition ommitted 
// int main(){
//     int i,sum=0,n;
//     cout<<"Enter the any natural number : ";
//     cin>>n;
//     for(i=1;i<=n;){
//         sum+=i;
//         i++;
//     }
//     cout<<"The Sum of the natural number is : "<<sum<<endl;
//     return 0;
// }

// Q.3 Print the first multiple of 5 which is also a multiple of 7

int main(){
    int i=5;
    while (true){
        if(i%7 == 0){
            cout<<i<<endl;
            break;
        }
        i+=5;  
    }
    return 0;
}
