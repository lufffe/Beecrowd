```
#Pergunta:

Leia um valor inteiro correspondente à idade de uma pessoa em dias e informe-a em anos, meses e dias
```

```
#Resposta:

#include <stdio.h>

int main(){
    int dias,resto,anos,meses;
    
    scanf("%d",&dias);
    
    if(dias>=365){
        anos = dias / 365 ;
        resto = dias % 365 ;
        meses = resto / 30 ;
        dias = resto % 30;
        printf("%d ano(s)\n%d mes(es)\n%d dia(s)\n",anos,meses,dias);
    }else if(dias>=30){
		meses = dias / 30;
		dias = dias % 30 ;
		printf("0 ano(s)\n%d mes(es)\n%d dia(s)\n",meses,dias);
	}
	else
		printf("0 ano(s)\n0 mes(es)\n%d dia(s)\n",dias);
}
```