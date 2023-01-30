```
#Pergunta:

Leia um valor inteiro, que é o tempo de duração em segundos de um determinado evento em uma fábrica, 
e informe-o expresso no formato horas:minutos:segundos.
```

```
#Resposta:

#include <stdio.h>

int main(){
    int tempo,resto,horas,minutos,segundos;
    
    scanf("%d",&tempo);
    if(tempo>=3600){
        horas = tempo / 3600 ;
        resto = tempo % 3600 ;
        minutos = resto / 60 ;
        segundos = resto % 60;
        printf("%d:%d:%d\n",horas,minutos,segundos);
    }else if(tempo>=60){
		minutos = tempo / 60;
		segundos = tempo % 60 ;
		printf("0:%d:%d\n",minutos,segundos);
	}
	else
		printf("0:0:%d\n",tempo);
}
```