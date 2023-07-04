![image](https://github.com/lufffe/Beecrowd/assets/90646635/e761a1da-ac16-4480-8f48-0193296b4aae)

>C
```C
#include<stdio.h>

int main()
{
	int valores[6],i;
	int par,impar,positivo,negativo;

	par=0;
	impar=0;
	positivo=0;
	negativo=0;

	for(i=0;i<5;i++)
	{
		scanf("%d",&valores[i]);
	
		if(valores[i]%2 == 0)
			par++;
		else
			impar ++;
	
	
		if(valores[i]>0)
			positivo++;
		else if(valores[i]<0)
			negativo++;
	}

	printf("%d valor(es) par(es)\n",par);
	printf("%d valor(es) impar(es)\n",impar);
	printf("%d valor(es) positivo(s)\n",positivo);
	printf("%d valor(es) negativo(s)\n",negativo);

	return 0;
}
```

>PYTHON 3.9
```Python 3.9
a = int(input())
b = int(input())
c = int(input())
d = int(input())
e = int(input())

lista = a,b,c,d,e
par=0
impar=0
positivo=0
negativo=0

for num in lista:
	if(num%2 == 0):
	par = par+1
	else:
	impar = impar+1

	if(num>0): 
	positivo = positivo + 1
	elif(num<0):
	negativo = negativo + 1

print(f"{par} valor(es) par(es)")
print(f"{impar} valor(es) impar(es)")
print(f"{positivo} valor(es) positivo(s)")
print(f"{negativo} valor(es) negativo(s)")
```
