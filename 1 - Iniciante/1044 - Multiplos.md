![image](https://github.com/lufffe/Beecrowd/assets/90646635/29d6250e-5d12-44e8-bdd8-c538e27814fc)

>C
```C
#include <stdio.h>

int main()
{
	int a,b;

	scanf("%d %d",&a,&b);

	if(a>b)
	{
		if((a%b)==0)
			printf("Sao Multiplos\n");
		else
			printf("Nao sao Multiplos\n");
	}
	else
	{
		if((b%a)==0)
			printf("Sao Multiplos\n");
		else
			printf("Nao sao Multiplos\n");
	}
	return 0;
}
```

>PYTHON 3.9
```Python 3.9
a,b = map(int,input().split())

resto = a%b

if(a>b):

	if((a%b)==0):
	print("Sao Multiplos")
	else:
	print("Nao sao Multiplos")
else:
	if((b%a)==0):
	print("Sao Multiplos")
	else:
	print("Nao sao Multiplos")   
```
