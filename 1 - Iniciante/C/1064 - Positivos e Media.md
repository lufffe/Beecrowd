![image](https://github.com/lufffe/Beecrowd/assets/90646635/56a54d89-32d8-4e06-82a3-405f9fe230a8)

>C

	#include<stdio.h>

	int main()
	{

		double total,media;
		float valor,valores[6];
		int contagem,i;

		total=0;
		contagem=0;

		for(i=0;i<6;i++)
		{
			scanf("%f",&valor);
			valores[i]=valor;
		}

		for(i=0;i<6;i++)
		{
			if(valores[i]>0)
			{
				contagem++;
				total=total+valores[i];
			}
		}

		media = total / contagem ;
		printf("%d valores positivos\n",contagem);
		printf("%.1f\n",media);

		return 0;
	}
	
>PYTHON 3.9

	a = float(input())
	b = float(input())
	c = float(input())
	d = float(input())
	e = float(input())
	f = float(input())

	lista = a,b,c,d,e,f 
	positivo = 0
	total=0

	for num in lista:
	    if(num>0):
		positivo = positivo + 1
		total = total + num

	media = total / positivo

	print(f"{positivo} valores positivos")
	print(f"{media:.1f}")
