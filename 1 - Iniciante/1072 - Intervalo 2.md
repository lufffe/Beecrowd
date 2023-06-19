![image](https://github.com/lufffe/Beecrowd/assets/90646635/74f22326-a356-44ab-b3b8-a1a2fbe0df9a)

>C

	#include<stdio.h>

	int main()
	{

		int quant,total,valor;
		int dentro,fora,limitevalor;
		dentro=0;
		fora=0;
		limitevalor= pow(10,7);

		scanf("%d",&quant);

		if(quant<10000)
		{
			while(total!=quant)
			{
				scanf("%d",&valor);

				if((valor>-limitevalor) && (valor<limitevalor))
				{
					if((valor>=10) && (valor<=20))
					{
						dentro++;
					}
					else
					{
						fora++;
					}
				}
				total++;
			}
		}

		printf("%d in\n",dentro);
		printf("%d out\n",fora);

			return 0;
	}

>PYTHON 3.9

	quant = int(input())

	total= 0
	lista = []
	dentro=0 
	fora=0
	limitevalor=(10**7)
	if(quant<10000):

	    while(total!=quant):

		valor=int(input())

		if(valor>-limitevalor and valor<limitevalor):

		    if(valor>=10 and valor<=20):
			dentro = dentro +1
		    else:
			fora = fora+1

		total = total+1

	print(f"{dentro} in")
	print(f"{fora} out")
