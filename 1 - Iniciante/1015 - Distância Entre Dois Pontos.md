![image](https://github.com/lufffe/Beecrowd/assets/90646635/2adb24d5-7ac9-47d7-9007-20fc88932b51)

>C
```C

#include <stdio.h>
#include <math.h>

int main() 
{

	double x1,x2,y1,y2,resultado;

	scanf("%lf %lf",&x1,&y1);
	scanf("%lf %lf",&x2,&y2);

	resultado = sqrt(pow((x2-x1),2) + pow((y2-y1),2));

	printf("%.4lf\n",resultado);

	return 0;
}
```
