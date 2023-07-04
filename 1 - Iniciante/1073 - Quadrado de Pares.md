![image](https://github.com/lufffe/Beecrowd/assets/90646635/18585433-7cd5-4f3e-a162-d0165ca14f36)


>C
```C
#include<stdio.h>

int main()
{
	int valor,i,total;

	scanf("%d",&valor);

	if(valor>5 && valor<2000)
	{
		for (i=1;i<=valor;i++)
		{
			if(i%2==0)
			{
				total = pow(i,2);
				printf("%d^2 = %d\n",i,total);
			}
		}
	}
	return 0;
}
```

>PYTHON 3.9 
```Python 3.9
valor = int(input())

if(valor>5 and valor <2000):
	for i in range(1,valor+1):
		if(i%2==0):
			print(f"{i}^2 = {i**2}")
```
