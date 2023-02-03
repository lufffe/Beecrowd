```
#Pergunta:

Com base na tabela abaixo, escreva um programa que leia o código de um item 
e a quantidade deste item. A seguir, calcule e mostre o valor da conta a pagar.
```

```
#Resposta:

#include<stdio.h>

int main()
{
	int codigo, qtd;
	float total;
	
	scanf("%d %d",&codigo,&qtd);
	
	if(codigo==1)
    	total=qtd*4;
	else if(codigo==2)
    	total=qtd*4.50;
	else if(codigo==3)
    	total=qtd*5;
	else if(codigo==4)
    	total=qtd*2;
	else if(codigo==5)
    	total=qtd*1.50;
    	
    printf("Total: R$ %.2f\n",total);
    return 0;
}
```