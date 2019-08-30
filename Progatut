#include <iostream>

int vvod()
{
	std::cout<< "Please enter an integer: ";
	int value;
	std::cin >> value;
	return value;
}

int matematicvibor()
{
	std::cout << "Please enter which operator you want (1 = +, 2 = -, 3 = *, 4 = /): ";

	int op;
	std::cin >> op;
	return op;
}

int matematicreshenie(int x, int op, int y)
{
	if (op == 1)
		return x + y;
	if (op == 2)
		return x - y;
	if (op == 3)
		return x * y;
	if (op == 4)
		return x / y;

	return -1;
}

void printresult(int result)
{
	std::cout << "Your result is: " << result << std::endl;
}

int main()
{

	int input1 = vvod();

	int y = matematicvibor();

	int input2 = vvod();

	int result = matematicreshenie(input1, y, input2);

	printresult(result);
}
