![image](https://github.com/lufffe/Beecrowd/assets/90646635/2630992b-62b0-45ab-a75c-5c546c3e00cc)

>C
```C
#include<stdio.h>

int main()
{
	int A,B,C,D,soma1,soma2;

	scanf("%d %d %d %d",&A,&B,&C,&D);

	soma1=C+D;
	soma2=A+B;
	if (B>C && D>A && soma1>soma2 && C>=0 && D>=0 && A%2==0)
		printf("Valores aceitos\n");
	else
		printf("Valores nao aceitos\n");
}
```

>PYTHON 3.9
```Python 3.9
A,B,C,D = map(int,input().split())
soma1 = C + D
soma2 = A + B
if (B>C) and (D>A) and (soma1>soma2) and (C>=0) and (D>=0) and (A%2==0):       
	print("Valores aceitos")
else:    
	print("Valores nao aceitos")
```
