#include <iostream>
#include <string>
using namespace std;

int main()
{
	for (int i = 1; i <= 100; i++)
	{
   
		string test = ""; // every time the test string will be initialized to an empty string 
		if ((i % 3) == 0)
			test += "fizz";
		else
			test += "";

		if ((i % 5) == 0)
			test += "buzz";
		else
			test += "";


		if (!test.empty())
			cout << test;
		else
			cout << i;

		cout << " ";
	}
}

int main()
{
	for (int i = 1; i < 101; i++)
	{
		if (i % 3 == 0 && i % 5 == 0)
		{
			cout << "fizzbuzz ";
			continue;
		}
		else if (i % 5 == 0)
		{
			cout << "buzz ";
			continue;
		}
		else if (i % 3 == 0)
		{
			cout << "fizz ";
			continue;
		}
		cout << i << " ";
	}
}
