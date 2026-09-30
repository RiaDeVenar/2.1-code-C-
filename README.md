# 2.1-code-C-
Крутой калькулятор
#include <iostream>
using namespace std;

int main()
{
    int x;
    int y;
    cout << "Enter x: ";
    cin >> x;
    cout << "Enter y: ";
    cin >> y;
    cout << "x: " << x << endl;
    cout << "y: " << y << endl;
    int result = x / y; 
    cout << "x : y = " << result << endl;
    return 0;
}
