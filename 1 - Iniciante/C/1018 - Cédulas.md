![image](https://github.com/lufffe/Beecrowd/assets/90646635/4f3e3140-c8cb-41e0-bbc5-880b0f2877b7)

>C

	#include <stdio.h>

	int main(){
		int notas[7] = {100,50,20,10,5,2,1};
		int valor,i,cedula ;

		scanf("%d",&valor);

		printf("%d\n",valor);
		for ( i=0;i<7;i++)
		{
			if(valor>=notas[i])
			{
				printf("%d nota(s) de R$ %d,00\n",cedula = valor/notas[i] ,notas[i]);
				valor = valor % notas[i];			
			}
			else
				printf("0 nota(s) de R$ %d,00\n",notas[i]);
		}
	}

>PYTHON 3.9

	valor = int(input())
	notas = [100,50,20,10,5,2,1]

	print(valor)
	for c in notas:
	    if valor>=c:
		inteiro = valor // c
		print(f"{inteiro} nota(s) de R$ {c},00")
		valor = valor % c
	    else:
		print(f"0 nota(s) de R$ {c},00")
