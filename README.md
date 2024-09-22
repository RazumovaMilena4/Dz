#include <windows.h>
#include <iostream>
#include <string>
using namespace std;
int main()
{
    SetConsoleCP(1251);
    SetConsoleOutputCP(1251);
    cout << boolalpha;
    int i1=0, i2=10, i3=10;
    while (i1<i2 && i3 !=4)
    {
        i1++;
        cout << i2 << "<" << i1 << i3 << "!= 4" << endl;
        i3--;
    }
    
    int k1=1, k2=6, k3=8;
    while (k2<k3 || k1==4)
     {
        k2++;
        cout << k2 << "<" << k3 << " или " << k1 << " == 4" << endl;
        k3--;
    }
    
    int m1=14, m2=10, m3=5;
    while (m1>=m2 && m3<10)
     {
        m1--;
        cout << m1 << " >= " << m2 << " и " << m3 << " < 10" << endl;
        m3++;
    }
}
