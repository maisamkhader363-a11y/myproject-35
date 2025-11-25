#include<iostream>
#include<cctype>
using namespace std;
 
int isFunction(int x) {
	return x*x + 2*x - 4;
}
int main()
{
	int n, m;
	cout << "please enter number one(n) " << endl;
	cin >> n;
	cout << " f(" << n << ")=" << isFunction(n) << endl;
	long long result1 = isFunction(n);
	cout << "The result of n dividing on 2.0 =f(" << n << ")/2.0=" << result1 / 2.0 << endl;
	cout << "please enter number two" << endl;
	cin >> m;
	cout << "f(" << m << ")=" << isFunction(m) << endl;
	long long result2 = isFunction(m);
	cout << "the result of m dividing on 2.0 =f("<<m<<")/2.0" << result2 / 2.0 << endl;
}
