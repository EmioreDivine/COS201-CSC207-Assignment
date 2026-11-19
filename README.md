# COS201-CSC207-Assignment
++ program to check whether a number is odd or even. 

#include <iostream>
using namespace std;

int main() {
    int number;

    cout << "Enter a number: ";
    cin >> number;

    if (number % 2 == 0) {
        cout << "The number is Even";
    }
    else {
        cout << "The number is Odd";
    }

    return 0;
}
