## Liza Tipanova
## Student of VSU named after P. M. Masherov
### Contact information
#### *Phone* : +375291113530
#### *E-mail* : liza.tipanova@mail.ru
#### *Telegram* : @Krovavaya_merri
---
### Briefly about myself:
##### I was born in Vitebsk in the Republic of Belarus. Now I am a first-year student of the faculty of Mathemathics and Information technologies. My profession will be economist-manager of information systems. I have skills in writting code at C++ and my future I want to connect with programming and economics.
--- 
### Skills and Proficiency:
* C++ 
* HTML
* Adobe Photoshop
* Inkcscape

---
### Code example:
``` c++
#include "stdafx.h"
#include <iostream>
using namespace std;
const double pi = 3.14;

int main(int argc, char*argv[])
{
	double r, so, st, h, l, sp, a, b;
	if (argc == 2) {
		char*number = argv[1];
		switch (*number) {
		case 'B':
			cout << "Enter radius of circle: ";
			cin >> r;
			if (r <= 0) {
				cout << "error ";
				cerr << "error ";
				exit(-1);
			}
			else 
				so = pi*r*r;
			cout << "square: " << so;
			break;
		case 'D':
			cout << "Enter height and middle line of trapezoid: ";
			cin >> h >> l;
			if (h <= 0 || l <= 0) {
				cout << "error ";
				cerr << "error ";
				exit(-1);
			}
			else 
			st = 0.5*l*h;
			cout << "square: "<< st;
			break;
		case 'E':
			cout << "Enter width and lenght of rectangle: ";
			cin >> a >> b;
			if (a <= 0 || b <= 0) {
				cout << "error ";
				cerr << "error ";
				exit(-1);
			}
			else
				sp = a*b;
				cout << "square: " << sp;
			break;
		default:
			cout << "no tasks ";
			cerr << "no tasks ";
			break;
		}
	}
	else {
		cout << "program needs parametr ";
		cerr << "program needs parametr ";
	}
	system("pause");
	return 0;

}
```
