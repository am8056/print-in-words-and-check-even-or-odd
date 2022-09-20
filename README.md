# print-in-words-and-check-even-or-odd
Using c++ print the number in words and check that the number is even or odd


#include <iostream>
#include <cstdio>
using namespace std;

int main() {
    string numToString[10] = {"one","two","three","four","five","six","seven","eight","nine"};
 
    int i,j;
    cin>>i>>j;
    for(i=i;i<=j;i++){
        cout << (i<10 ? numToString[i-1] : (i%2==0 ? "even" : "odd")) <<endl;
    }
    return 0;
}
