```
#Pergunta:

Leia um valor inteiro X. Em seguida apresente os 6 valores ímpares consecutivos a partir de X, 
um valor por linha, inclusive o X ser for o caso.
```

```
#Resposta:

#include<stdio.h>

int main()
{

int valores[6],i,valor,limite;

scanf("%d",&valor);
limite = valor+11 ; 

for(i=valor;i<=limite;i++)
{
	if(i%2 != 0)
	{
		printf("%d\n",i);
	}
}

	return 0;
}
```