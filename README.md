Lab1.Algorythm
Завдання 6:
#include <iostream>
using namespace std;
int main() {
    double length, width;
    cout << "Введіть довжину прямокутника: ";
    cin >> length;
    
    cout << "Введіть ширину прямокутника: ";
    cin >> width;
    
    double area = length * width;
    double perimeter = 2 * (length + width);
    
    cout << "Площа прямокутника: " << area << endl;
    cout << "Периметр прямокутника: " << perimeter << endl;
    
    return 0;
}
