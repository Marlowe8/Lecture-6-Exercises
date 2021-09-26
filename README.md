# Lecture-6-Exercises

//Slide 24 (odd or even)
#include <iostream>
using namespace std;


bool Checker(int num) {	
	bool check = false;
	if (num > 0) {
		if ((num % 2) == 0) {
			check = true;
		}
	}
	return check;
}
void NumChecker(int num) {

	if (Checker(num)) {
		cout << "the number is even" << endl;
	}
	else
		cout << "the number is odd" << endl;
}
int main() {

	int num;
	cout << "Enter a number: "; cin >> num;

	NumChecker(num);

	return 0;
}
  
  
