![image](https://github.com/lufffe/Beecrowd/assets/90646635/fec41fd2-6609-4f17-8e2b-0386badad65e)

>C

	#include<stdio.h>

	int main()
	{

		float valor;
		float valores[6];
		int contagem,i;

		for(i=0;i<6;i++)
		{
			scanf("%f",&valor);
			valores[i]=valor;
		}

		for(i=0;i<6;i++)
		{
			if(valores[i]>0)
				contagem++;
		}

		printf("%d valores positivos\n",contagem);

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

	for num in lista:
	    if(num>0):
		positivo = positivo + 1

	print(f"{positivo} valores positivos")
