```C++
/* ch5 goto1.c */

#include <stdio.h> 
#include <stdlib.h>
int main () {
int x , y;
char p;
float s;
scanf("%d%c%d",&x,&p,&y);
switch(p){
		case '+':
	s = x +y;
	break;
		case '-':
	s = x - y;
	break;
		case '*':
	s = x * y;
	break;
		case '/':
	s = (float) x / y;
	break;
}
printf("答案%f",s);
	system("PAUSE");
	return 0;
}
```C++
	
