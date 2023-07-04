![image](https://github.com/lufffe/Beecrowd/assets/90646635/5875f85f-b890-4f5e-aa6f-216bb94c147a)

>C
```C
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

>PYTHON 3.9
```Python 3.9
a,b = map(int,input().split())

if(a==b):
	print("O JOGO DUROU 24 HORA(S)")
else:
	if(a<b):
		valor=b-a
		print(f"O JOGO DUROU {valor} HORA(S)")
	else:
		valor=24-a
		valor=valor+b
		print(f"O JOGO DUROU {valor} HORA(S)")
```
