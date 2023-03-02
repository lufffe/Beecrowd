```
#Perguntas:

Leia 5 valores Inteiros. A seguir mostre quantos valores digitados foram pares, quantos valores digitados foram ímpares, 
quantos valores digitados foram positivos e quantos valores digitados foram negativos.
```

```
#Resposta:

#include<stdio.h>

int main()
{

int valores[6],i;
int par,impar,positivo,negativo;

par=0;
impar=0;
positivo=0;
negativo=0;

for(i=0;i<5;i++){
	scanf("%d",&valores[i]);
	
	if(valores[i]%2 == 0){
		par++;
	}else{
		impar ++;
	}
	
	if(valores[i]>0){
		positivo++;
	}else if(valores[i]<0){
		negativo++;
	}
}

printf("%d valor(es) par(es)\n",par);
printf("%d valor(es) impar(es)\n",impar);
printf("%d valor(es) positivo(s)\n",positivo);
printf("%d valor(es) negativo(s)\n",negativo);

	return 0;
}
```