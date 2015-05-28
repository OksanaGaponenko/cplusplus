Программирование на языке С плюс плюс
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