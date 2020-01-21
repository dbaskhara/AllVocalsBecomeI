#include <iostream>
#include <string.h>
using namespace std;

void checkup(char &a)
{
	if(a == 'a' || a == 'u' || a == 'e' || a == 'o')
	{
		a = 'i';
	}
	else if(a == 'A' || a == 'U' || a == 'E' || a == 'O')
	{
		a = 'I';
	}
}

main()
{
	int a;
	a = 0;
	string word;
	cout << "Please Insert Word : ";
	getline(cin,word);
	while(word[a] != NULL)
	{
		checkup(word[a]);
		a++;
	}
	cout << "Aftermath : " << word;
}
