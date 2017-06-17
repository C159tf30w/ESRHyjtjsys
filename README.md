# ESRHyjtjsys
#include <stdio.h> /* */
#include <iostream> /* 
#include <locale.h> /*
#include <windows.h> /* 
using namespace std;
 
int main(int argc, char* argv[])
{
    setlocale(LC_CTYPE,"Russian");
    double plus, minus, pow, div; //
    double a1; // 
    double a2; // 
    cout << 
    cin >> a1;
    cout << 
    cin >> a2;
    plus  = a1 + a2;  //
    minus = a1 - a2;  //
    pow  = a1 * a2;  // 
    div  = a1 / a2;  //
    cout << a1 << "+" << a2 << "=" << plus  << endl;
    cout << a1 << "-" << a2 << "=" << minus << endl;
    cout << a1 << "*" << a2 << "=" << pow  << endl;
    cout << a1 << "/" << a2 << "=" << div  << endl;
    system("pause");
    return 0;
}
