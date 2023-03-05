# ph-ng-tr-nh-b-c-hai
phương trình bậc hai
#include <iostream>
#include <conio.h>
#include <math.h>
using namespace std;

int main()
{
	float a, b, c, d, x1, x2;
	cout << "Nh?p h? s? a, b, c c?a phuong tr?nh b?c 2 tuong ?ng: " << endl;
	cin >> a >> b >> c;
	if (!a)
	{
		if (!b)
			cout << "C? a v? b kh?ng th? c?ng b?ng 0 trong phuong tr?nh ax^2 + bx + c = 0" << "\n";
		else
		{
			d = -c / b;
			cout << "Phuong tr?nh c? nghi?m duy nh?t : " << d << endl;
		}
	}
	else
	{
		d = b *b - 4 *a * c;
		if (d > 0){
			x1 = (-b + sqrt(d)) / (2 *a);
		x2 = (-b - sqrt(d)) / (2 *a);
		cout << "Nghi?m th? nh?t x1 = " << x1 << endl;
		cout << "Nghi?m th? hai x2 = " << x2 << endl;}
		else cout<<" phuong trinh vo nghiem"<<endl;
	}

	
	return 0;
}
