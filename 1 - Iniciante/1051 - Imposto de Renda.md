![image](https://github.com/lufffe/Beecrowd/assets/90646635/5db99fd6-588c-4a21-a139-199fe6ff6f22)

>C
```C
#include<stdio.h>

int main()
{
	double salario,imposto;

	scanf("%lf", &salario);

	if(salario>0 && salario<=2000)
		printf("Isento\n");

	else if(salario>2000 && salario<=3000)
	{
		imposto = (salario - 2000.0)*0.08 ;
		printf("R$ %.2lf\n",imposto);
	}
	else if(salario>3000 && salario<=4500)
	{
		imposto = (salario - 3000.0)*0.18 + (1000*0.08);
		printf("R$ %.2lf\n",imposto);
	}
	else if(salario>4500)
	{
		imposto = ((salario - 4500)*0.28 + (1500*0.18) + (1000*0.08));
		printf("R$ %.2lf\n",imposto);
	}
	return 0;
}
```

>PYTHON 3.9 
```Python 3.9
salario = float(input())

if(salario>0) and (salario<=2000):
	print("Isento")

elif(salario>2000) and (salario<=3000):
	imposto = (salario - 2000.0)*0.08
	print(f"R$ {imposto:.2f}")

elif(salario>3000) and (salario<=4500):
	imposto = (salario - 3000.0)*0.18 + (1000*0.08)
	print(f"R$ {imposto:.2f}")

elif(salario>4500):
	imposto = ((salario - 4500)*0.28 + (1500*0.18) + (1000*0.08))
	print(f"R$ {imposto:.2f}")
```
