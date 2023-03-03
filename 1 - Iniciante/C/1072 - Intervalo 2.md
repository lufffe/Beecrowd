```
#Pergunta:

Leia um valor inteiro N. Este valor será a quantidade de valores inteiros X que serão lidos em seguida.
Mostre quantos destes valores X estão dentro do intervalo [10,20] e quantos estão fora do intervalo, 
mostrando essas informações.
```

```
#Resposta:

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
```