```
#Pergunta:

Leia 1 valor inteiro N (2 < N < 1000). A seguir, mostre a tabuada de N:      
1 x N = N      2 x N = 2N        ...       10 x N = 10N
```

```
#Resposta:

#include<stdio.h>

int main(){
    int valor,i;
    
    scanf("%d",&valor);
    if(valor>2 && valor<10000){
    	for(i=1;i<=10;i++){
    		printf("%d x %d = %d\n",i,valor,i*valor);
		}
	}
    
    return 0;
}
```