# HackerRank solution
//fizz buzz question code using functions

#include <bits/stdc++.h>

using namespace std;

string ltrim(const string &);
string rtrim(const string &);


using namespace std;
/*
 * Complete the 'fizzBuzz' function below.
 *
 * The function accepts INTEGER n as parameter.
 */

void fizzBuzz(int n){
    cin>>n;
    int i;
    for(i=1; i<=n; i++){
        if(i%3==0 && i%5==0){
            cout<<"FizzBuzz"<<endl;
        }
    
        else if(i%3==0 && i%5!=0){
        cout<<"Fizz"<<endl;
        }
        else if(i%3!=0 && i%5==0){
            cout<<"Buzz"<<endl;
        }
        else{
            cout<<i<<endl;
        }
    }
}
        

int main(){
    int n;
    fizzBuzz(n);
    return 0;
    
}
