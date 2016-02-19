# Tech_Writing2_Calculate
Program Descrption
===========================
This is a basic program created in C++ that will calculate the area, diameter, and circumference based on the information given by the user. The user begins by entering A for area, C for curcumference, or D for diameter after this information is entered they input the amount they want to be used for the calculation. 
The program then takes the input given, calculates it accordingly, and outputs the answer.

Functions
===========================
Since this program is very basic it doesn't have very many functions that are needed aside from the initial main() function and a switch statement that makes up the majority of the program code.

Our main() function starts off the program and opens up the opportunity for other functions to be used. The main() functions comes directly after the directives:

```
#define _USE_MATH_DEFINES //computer may not be required to compile
#include <iostream>
#include <cmath>

using namespace std;

int main() { 
```

Key Statements
==================================
In the body of the program a switch function is used to help the program respond to the user's input. In essence, it is a very useful selection statment that responds to the user's input.

```
switch (circle) {
	case 'A':
		cout << "The area of a circle with radius " << radius << " is " << (M_PI * pow(radius, 2)) << '\n';
		break;
	case 'C':
		cout << "The circumference of a circle with radius " << radius << " is " << (2 * M_PI * radius) << '\n';
		break;
	case 'D':
		cout << "The diameter of a circle with radius " << radius << " is " << (2 * radius) << '\n';
		break;
	default:
		cout << "Error: Wrong input!" << '\n';
```

