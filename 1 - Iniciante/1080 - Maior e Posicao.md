![image](https://github.com/lufffe/Beecrowd/assets/90646635/87757371-670e-4fe1-a1b7-b4b97f3d5cea)

>C
```C
#include<stdio.h>

int main()
{
	int i,valor,posicao,maior;

	for(i=1;i<=100;i++)
	{
		scanf("%d",&valor);
	
		if(valor>maior)
		{
			maior=valor;
			posicao=i;
		}
	}
	printf("%d\n",maior);
	printf("%d\n",posicao);

	return 0;
}
```

>PYTHON 3.9
```Python 3.9
qtd=1
maior=0
pos=0

while(qtd!=101):
	valor=int(input())

	if(valor>maior):
		maior=valor
		pos=qtd
	
	qtd=qtd+1

print(maior)
print(pos)
```
