![image](https://github.com/lufffe/Beecrowd/assets/90646635/69c3229c-2aa1-42d4-869c-58c670332b6b)

>C
```C
#include <stdio.h>

int main()
{
	int cod1,cod2,num1,num2 ;
	double valor1,valor2,total;

	scanf("%d",&cod1);
	scanf("%d",&num1);
	scanf("%lf",&valor1);

	scanf("%d",&cod2);
	scanf("%d",&num2);
	scanf("%lf",&valor2);

	total = (num1 * valor1) + (num2 * valor2);

	printf("VALOR A PAGAR: R$ %.2lf\n",total);

}
```


>PYTHON
```Python 3.9
a,b,c = input('').split(' ')
d,e,f = input('').split(' ')

valor = int(b)*float(c) + int(e)*float(f)

print(f'VALOR A PAGAR: R$ {valor:.2f}')
```
