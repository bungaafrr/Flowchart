# program flowchart untuk menghitung konversi suhu dari fahrenheit ke celcius dan reamur dengan nilai fahrenheit diinput
```C
#include <iostream>
using namespace std;

int main() 
{
	float F, C, R;
	cout << "Input Suhu (Fahrenheit) : ";
	cin >> F;
	C = (F-32)*0.555555556;
	cout << "Celcius : " << C <<endl;
	R = C*0.8;
	cout << "Reamur : " << R;
	
	return 0;
}
```
