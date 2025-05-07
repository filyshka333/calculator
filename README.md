#include <iostream>			
using namespace std;
class Calculator 
{	public:
		int x1;
		int x2;
		int result;
	void calc_sum()
	{
		this->result=this->x1+this->x2;
	}
	void calc_multiply()
	{
		this->result=this->x1*this->x2;
	}
	void calc_subtract()
	{
		this->result=this->x1-this->x2;
	}
	void calc_divide()
	{
		this->result=this->x1/this->x2;
	}
};

int main(){
	Calculator calculator;
	calculator.x1 = 4;
	calculator.x2 = 9;
	calculator.calc_sum();
	cout << calculator.result << endl;
	
	calculator.calc_multiply();
	cout << calculator.result << endl;
	
	calculator.calc_subtract();
	cout << calculator.result << endl;
	
	calculator.calc_divide();
	cout << calculator.result << endl;
}
