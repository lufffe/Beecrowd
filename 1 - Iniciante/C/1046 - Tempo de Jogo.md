```
#Pergunta:

Leia a hora inicial e a hora final de um jogo. 
A seguir calcule a duração do jogo, 
sabendo que o mesmo pode começar em um dia e terminar em outro,
 tendo uma duração mínima de 1 hora e máxima de 24 horas.
```

```
#Resposta:

#include <stdio.h>

int main()
{
	
	int a,b,valor;
	
	scanf("%d %d",&a,&b);
	
	if(a==b)
		printf("O JOGO DUROU 24 HORA(S)\n");
	else{
		if(a<b)
		{
			valor=b-a;
			printf("O JOGO DUROU %d HORA(S)\n",valor);
		}
		else
		{
			valor=24-a;
			valor=valor+b;
			printf("O JOGO DUROU %d HORA(S)\n",valor);
		}
	}

	return 0;
}
```
