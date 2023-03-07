```
#Pergunta:

Leia 100 valores inteiros. Apresente então o maior valor lido e a posição dentre os 100 valores lidos.
```

```
#Resposta:

#include<stdio.h>

int main()
{
    int i,valor,posicao,maior;
    
    for(i=1;i<=100;i++)
    {
    	scanf("%d",&valor);
    	
    	if(valor>maior)
    	{
    	    maior=valor;
			posicao=i;
    	}
	}
	printf("%d\n",maior);
	printf("%d\n",posicao);
    
    return 0;
}
```