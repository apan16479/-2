#include <iostream>
using namespace std;

int main() {
	float a, b, h; 
	cin >> a;
	cin >> b;
	cin >> h;
	cout << "사다리꼴의 넓이 : " << (a + b) * h / 2 << endl;
	cout << "원의 넓이 : " << (a*a) * 3.14<<endl;
	cout << "원기둥의의 부피 : " << (a * a) * 3.14 * h;
	return 0;
}
