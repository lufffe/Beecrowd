```
#Pergunta:

Faça um programa que leia três valores e apresente o maior dos três valores lidos seguido da mensagem “eh o maior”. 
Utilize a fórmula:
```

```
#Resposta:

#include <stdio.h>
 
int main() 
{
 	int a,b,c ;
	scanf("%d",&a);
    	scanf("%d",&b);
    	scanf("%d",&c);
    
    	if(a>c && a>b)
    		printf("%d eh o maior\n",a);
	else if(b>c)
		printf("%d eh o maior\n",b);
	else if (c>b)
		printf("%d eh o maior\n",c);
	return 0;
}
```

