```
#Pergunta:

Leia 6 valores. Em seguida, mostre quantos destes valores digitados foram positivos. Na próxima linha, 
deve-se mostrar a média de todos os valores positivos digitados, com um dígito após o ponto decimal.
```

```
#Resposta:

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
```