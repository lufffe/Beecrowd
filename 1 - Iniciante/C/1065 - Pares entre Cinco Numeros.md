```
#Pergunta:

Faça um programa que leia 5 valores inteiros. Conte quantos destes valores digitados são pares e mostre esta informação.
```

```
#Resposta:

#include<stdio.h>

int main()
{

int valores[6],i,par;

for(i=0;i<5;i++){
	scanf("%d",&valores[i]);
	
	if(valores[i]%2==0){
		par++;
		
	}
}

printf("%d valores pares\n",par);
	return 0;
}
```