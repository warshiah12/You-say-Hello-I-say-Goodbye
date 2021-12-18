# You-say-Hello-I-say-Goodbye
#displays message welcome to my program and end of program
#include <iostream>
using namespace std;
void welcome();
void goodbye();   //function declaration
int main()
{
	welcome();   //function call
	goodbye();
	return 0;
}

void welcome()
{
	cout << "\n\t\t\tWelcome to my program " << endl;
}
void goodbye()  //function definition
{
	cout << "\n \t\t\tEnd of program " << endl;
}
