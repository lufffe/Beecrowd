![image](https://github.com/lufffe/Beecrowd/assets/90646635/0a71604e-dfc3-4343-b10b-6638c5dfa556)

>C
```C
#include<stdio.h>

int main()
{
	int valores[6],i,par;

	for(i=0;i<5;i++)
	{
		scanf("%d",&valores[i]);
	
		if(valores[i]%2==0)
		{
			par++;
	
		}
	}

	printf("%d valores pares\n",par);
	return 0;
}
```

>PYTHON 3.9
```Python 3.9
a = float(input())
b = float(input())
c = float(input())
d = float(input())
e = float(input())

lista = a,b,c,d,e
cont=0

for num in lista:
	valor=num%2
	if(valor==0):
	cont = cont + 1

print(f"{cont} valores pares")
```
