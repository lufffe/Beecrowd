```
#Pergunta:

Leia um valor inteiro. A seguir, calcule o menor número de notas possíveis (cédulas) no qual o valor pode ser decomposto. 
As notas consideradas são de 100, 50, 20, 10, 5, 2 e 1. A seguir mostre o valor lido e a relação de notas necessárias.
```

```
#Resposta:

#include <stdio.h>

int main(){
	int notas[7] = {100,50,20,10,5,2,1};
	int valor,i,cedula ;
	
	scanf("%d",&valor);
	
	printf("%d\n",valor);
	for ( i=0;i<7;i++)
	{
		if(valor>=notas[i])
		{
			printf("%d nota(s) de R$ %d,00\n",cedula = valor/notas[i] ,notas[i]);
			valor = valor % notas[i];			
		}
		else
			printf("0 nota(s) de R$ %d,00\n",notas[i]);
	}
}
```
