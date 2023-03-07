```
#Pergunta:

Leia 1 valor inteiro N, que representa o número de casos de teste que vem a seguir. Cada caso de teste consiste de 3 valores reais, cada um deles com uma casa decimal. Apresente a média ponderada para cada um destes conjuntos de 3 valores, sendo que o primeiro valor tem peso 2, o segundo valor tem peso 3 e o terceiro valor tem peso 5.
```

```
#Resposta:

#include<stdio.h>

int main()
{
    int qtd,i;
    float v1,v2,v3,total,resposta;
    
    scanf("%d",&qtd);
    
	float lista[qtd];

	for(i=0;i<qtd;i++)
	{
		scanf("%f %f %f",&v1,&v2,&v3);
		
		total=((v1*2)+(v2*3)+(v3*5))/10;
		lista[i]=total;
	}    
    
    for(i=0;i<qtd;i++)
	{
		printf("%.1f\n",lista[i]);
	}
    
    return 0;
}
```