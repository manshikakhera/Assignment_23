#include<iostream>
using namespace std;

int main() {
    cout << "Hello MySirG" << endl;
    return 0;
}
2. Print "Hello" on the first line and "MySirG" on the second line using endl:

#include<iostream>
using namespace std;

int main() {
    cout << "Hello" << endl;
    cout << "MySirG" << endl;
    return 0;
}
3. Calculate the sum of two numbers:

#include<iostream>
using namespace std;

int main() {
    int num1, num2;
    cout << "Enter the first number: ";
    cin >> num1;
    cout << "Enter the second number: ";
    cin >> num2;
    int sum = num1 + num2;
    cout << "Sum: " << sum << endl;
    return 0;
}
4. Calculate the area of a circle:

#include<iostream>
using namespace std;

int main() {
    double radius;
    cout << "Enter the radius of the circle: ";
    cin >> radius;
    double area = 3.14159 * radius * radius;
    cout << "Area of the circle: " << area << endl;
    return 0;
}
5. Calculate the volume of a cuboid:

#include<iostream>
using namespace std;

int main() {
    double length, width, height;
    cout << "Enter length, width, and height of the cuboid: ";
    cin >> length >> width >> height;
    double volume = length * width * height;
    cout << "Volume of the cuboid: " << volume << endl;
    return 0;
}
6. Calculate the average of 3 numbers:

#include<iostream>
using namespace std;

int main() {
    double num1, num2, num3;
    cout << "Enter three numbers: ";
    cin >> num1 >> num2 >> num3;
    double average = (num1 + num2 + num3) / 3.0;
    cout << "Average: " << average << endl;
    return 0;
}
7. Calculate the square of a number:


#include<iostream>
using namespace std;

int main() {
    int num;
    cout << "Enter a number: ";
    cin >> num;
    int square = num * num;
    cout << "Square of the number: " << square << endl;
    return 0;
}
8. Swap values of two int variables without using a third variable:


#include<iostream>
using namespace std;

int main() {
    int a, b;
    cout << "Enter two numbers: ";
    cin >> a >> b;
    a = a + b;
    b = a - b;
    a = a - b;
    cout << "After swapping: a = " << a << ", b = " << b << endl;
    return 0;
}
9. Find the maximum of two numbers:


#include<iostream>
using namespace std;

int main() {
    int num1, num2;
    cout << "Enter two numbers: ";
    cin >> num1 >> num2;
    int maxNum = (num1 > num2) ? num1 : num2;
    cout << "Maximum number: " << maxNum << endl;
    return 0;
}
