```
#Pergunta:

Quadrao de Pares - Leia um valor inteiro N. Apresente o quadrado de cada um dos valores pares, de 1 até N, inclusive N, se for o caso.
```

```
#Resposta:

#include<stdio.h>

int main()
{

int valor,i,total;

scanf("%d",&valor);

if(valor>5 && valor<2000){
	for (i=1;i<=valor;i++){
		if(i%2==0){
			total = pow(i,2);
			printf("%d^2 = %d\n",i,total);
		}
	}
}
	return 0;
}
```