```
#Perguntas:

Faça um programa que leia 6 valores. Estes valores serão somente negativos ou positivos 
(desconsidere os valores nulos). A seguir, mostre a quantidade de valores positivos digitados.
```

```
#Resposta:

Faça um programa que leia 6 valores. Estes valores serão somente negativos ou positivos 
(desconsidere os valores nulos). A seguir, mostre a quantidade de valores positivos digitados.

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
```