# My C++ Projects

This is my first repository for learning C++. It includes a simple program called `PrintName` that demonstrates passing strings by value to a function.

## PrintName Example
Here's the code:

#include <iostream>

using namespace std;

void PrintName(string Name)
{

	cout << " The Name is : " << Name << endl;

}

int main()
{
	
	PrintName("Adam");

}
