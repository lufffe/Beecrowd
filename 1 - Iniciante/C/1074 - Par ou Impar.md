```
#Pergunta:

Leia um valor inteiro N. Este valor será a quantidade de valores que serão lidos em seguida. Para cada valor lido, mostre uma mensagem em inglês dizendo se este valor lido é par (EVEN), ímpar (ODD), positivo (POSITIVE) ou negativo (NEGATIVE). No caso do valor ser igual a zero (0), embora a descrição correta seja (EVEN NULL), pois por definição zero é par, seu programa deverá imprimir apenas NULL.
```

```
#Resposta:

#include<stdio.h>

int main()
{

	int qtd,i;
	
	scanf("%d",&qtd);
	
	int lista[qtd];
	
	if(qtd<10000){
		
		for(i=0;i<qtd;i++){
			
	        scanf("%d",&lista[i]);
	        
	        if(lista[i]>0){
	            if(lista[i]%2==0)
	                lista[i]="EVEN POSITIVE";
	            else
	                lista[i]="ODD POSITIVE";
	        }else if(lista[i]<0){
	        	
	            if(lista[i]%2==0)
	                lista[i]="EVEN NEGATIVE";
	            else
	               lista[i]="ODD NEGATIVE";
	        }else
	           lista[i]="NULL";
		}
	}
	for(i=0;i<qtd;i++){
		printf("%s\n",lista[i]);
	}
    	
	return 0;
}
``` 