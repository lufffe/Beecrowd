![image](https://github.com/lufffe/Beecrowd/assets/90646635/70dea0a8-fd9c-4292-8fd7-2926611ed9f7)

>C
```C
#include<stdio.h>

int main()
{
	int codigo, qtd;
	float total;

	scanf("%d %d",&codigo,&qtd);

	if(codigo==1)
		total=qtd*4;
	else if(codigo==2)
		total=qtd*4.50;
	else if(codigo==3)
		total=qtd*5;
	else if(codigo==4)
		total=qtd*2;
	else if(codigo==5)
		total=qtd*1.50;

	printf("Total: R$ %.2f\n",total);
	
	return 0;
}
```

>PYTHON 3.9
```Python 3.9
codigo,qtd=map(int,input().split())

if(codigo==1):
	total=qtd*4
elif(codigo==2):
	total=qtd*4.50
elif(codigo==3):
	total=qtd*5
elif(codigo==4):
	total=qtd*2
elif(codigo==5):
	total=qtd*1.50
	    
print(f"Total: R$ {total:.2f}")
```
