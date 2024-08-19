#include<iostream>
using namespace std;
  
int main(){
int n;
cout<<"Enter the number no:"<<endl;
cin>>n;
int a=1;
int b=1;
int sum=1;
for(int i=1;i<=n-2;i++){
    sum=a+b;
    a=b;
    b=sum;
}
cout<< "fibo of n is"<<sum ;
}
