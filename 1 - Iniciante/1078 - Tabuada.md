![image](https://github.com/lufffe/Beecrowd/assets/90646635/2a2a32f7-db3c-4cbf-ba60-d4454d1df2dd)

>C
```C
	#include<stdio.h>

	int main()
	{
	    int valor,i;

	    scanf("%d",&valor);
	    if(valor>2 && valor<10000)
	    {
			for(i=1;i<=10;i++)
			{
				printf("%d x %d = %d\n",i,valor,i*valor);
			}
		}
	    return 0;
	}
```

>PYTHON 3.9
```Python 3.9
valor = int(input())

if(valor>2 and valor<10000):
	for i in range(1,11):
		print(f"{i} x {valor} = {i*valor}")
```
