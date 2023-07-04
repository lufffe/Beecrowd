![image](https://github.com/lufffe/Beecrowd/assets/90646635/8d32f9b9-1247-4e3e-8f24-916b5c2320ea)


>C
```C
#include <stdio.h>

int main()
{

	char nome;
	double salario_fixo, vendas ,total;

	scanf("%s",&nome);
	scanf("%lf",&salario_fixo);
	scanf("%lf",&vendas);
		
	total = salario_fixo + (vendas * 15 / 100);

	printf("TOTAL = R$ %.2lf\n",total);
}
```
>PYTHON 3.9
```Python 3.9
nome = input()
salario_fixo = float(input())
vendas = float(input())

total = salario_fixo + (vendas * 15 / 100)

print(f"TOTAL = R$ {total:.2f}")
```
