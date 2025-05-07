#include <iostream>
using namespace std;
class Calculator
{ public:
	int x1;
	int x2;
	int result;
	void cals_sum()
	{
		this->result=this->x1+this->x2;
	}
	void calc_subtract()
	{
		this->result=this->x1-this->x2;	
	}
	void calc_multiply()
	{
		this->result=this->x1*this->x2;	
	}
	void calc_divide()
	{
		this->result=this->x1/this->x2;	
	}
};

int main()
{
	Calculator calculator;
	calculator.x1 = 3;
	calculator.x2 = 1;
	calculator.cals_sum();
	cout << calculator.result << endl;
	
	calculator.x1 = 5;
	calculator.x2 = 7;
	calculator.calc_subtract();
	cout << calculator.result << endl;
	
	calculator.x1 = 5;
	calculator.x2 = 4;
	calculator.calc_multiply();
	cout << calculator.result << endl;
	
	calculator.x1 = 7;
	calculator.x2 = 1;
	calculator.calc_divide();
	cout << calculator.result << endl;
}
