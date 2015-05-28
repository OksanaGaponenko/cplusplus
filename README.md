program in C plus plus

#include <iostream>
using namespace std;
void main()
{
	const int b = 15;
	int array[b];

	cout << "vvedite elementi massiva" << endl;
	for (int i = 0; i < b; i++)
	{
		cin >> array[i];
	}
	cout << "kratnoe 3 : " << endl;
for (int i = 0; i < b; i++)
	{
		if (array[i] % 3 == 0)
			cout << "array[" << i << "] = " << array[i] << endl;
	}
	system("pause");
}