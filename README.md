#include <iostream>
using namespace std;

int main() {
    int temp1, temp2, temp3;

    // Input
    cout << "Enter the first temperature reading: ";
    cin >> temp1;
    cout << "Enter the second temperature reading: ";
    cin >> temp2;

    // Check second reading conditions
    if (temp2 - temp1 > 50) {
