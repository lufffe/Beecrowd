```
#Pergunta:

Leia um valor de ponto flutuante com duas casas decimais. Este valor representa um valor monetário. 
A seguir, calcule o menor número de notas e moedas possíveis no qual o valor pode ser decomposto. 
As notas consideradas são de 100, 50, 20, 10, 5, 2. As moedas possíveis são de 1, 0.50, 0.25, 0.10, 0.05 e 0.01.
A seguir mostre a relação de notas necessárias.

```
```
TEM ALGO DE ERRADO NA MINHA LOGICA, POIS NÃO CONSEGUIR APROXIMAR O VALOR DA VARIAVEL VALOR , PARA 2 CASAS DECIMAIS NO FLOAT, VOU TERMINAR OUTRAS E RETORNO PARA ESSE DESAFIO.
```

```
#Resposta:

#include <stdio.h>
#include <math.h>

int main()
{
	double notas[6] = {100,50,20,10,5,2};
	double moedas[6] = {1,0.50,0.25,0.10,0.05,0.01};
	double valor;
	int i,qtd;
	
	scanf("%lf",&valor);
	
	printf("NOTAS:\n");
	for (i=0;i<6;i++)
	{
		//printf("Valor: R$ %.2lf\n",valor);
		//printf("Notas: R$ %.2lf\n",notas[i]);
		if(valor>=notas[i])
		{
			qtd=valor/notas[i];
			printf("%d nota(s) de R$ %.2lf\n",qtd,notas[i]);
			valor=valor-qtd*notas[i];
		}
		else{
			printf("0 moeda(s) de R$ %.2lf\n",notas[i]);
		}
	}
	printf("Moedas:\n");
	for(i=0;i<6;i++)
	{
		if(valor>moedas[i])
		{
			if(moedas[i]==0.01)
			{
			qtd=valor*100;
				
			}
			else
			{
				qtd=valor/moedas[i];
				valor=valor-(qtd*moedas[i]);
			}
			printf("%d moeda(s) de R$ %.2f\n",qtd,moedas[i]);
		}
		else
		{
			printf("0 moeda(s) de R$ %.2f\n",moedas[i]);
		}
	}
}

```