```
#Pergunta:

Faça um programa que mostre os números pares entre 1 e 100, inclusive.
```

```
#Resposta:

#include<stdio.h>

int main(){
	int i;
	
for(i=0;i<=100;i++)
{
	if((i%2)==0)
	{
		if(i>0 && i<=100)
			printf("%d\n",i);
	}
}	
return 0;
}
```
