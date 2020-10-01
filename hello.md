https://github.com/Humayun-glitch/Noob/tree/gh-pages

#include <iostream>

using namespace std;


int main() 
{
	
	int base_1,base_2,exp_1,exp_2,res1,res2;
	int sum;
	cout<<"Enter base for First Number: "<<endl;
	cin>>base_1;
	cout<<"Enter base for Second Number: "<<endl;
	cin>>base_2;
	cout<<"Enter exponent for First Number: "<<endl;
	cin>>exp_1;
	cout<<"Enter exponent for Second Number: "<<endl;
	cin>>exp_2;
	cout << base_1 << "^" << exp_1 << " = " <<res1<<endl;
	cout << base_2 << "^" << exp_2 << " = " <<res2<<endl;
	while (exp_1 != 0) {
        res1 *= base_1;
        --exp_1;
    }
    while (exp_2 != 0) {
        res2 *= base_2;
        --exp_2;
    }
    
    
	if(base_1==base_2)
	{
	    sum=base_1+base_2;
	    cout<<"Sum of the bases is: "<<sum<<endl;
	
	}
	
	return 0;
}
