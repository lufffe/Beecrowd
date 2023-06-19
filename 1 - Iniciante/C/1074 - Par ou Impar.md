![image](https://github.com/lufffe/Beecrowd/assets/90646635/f1b87200-2130-4bfc-84c6-00de4a8c52f8)

>C

	#include<stdio.h>

	int main()
	{

		int qtd,i;

		scanf("%d",&qtd);

		int lista[qtd];

		if(qtd<10000){

			for(i=0;i<qtd;i++){

			scanf("%d",&lista[i]);

			if(lista[i]>0){
			    if(lista[i]%2==0)
				lista[i]="EVEN POSITIVE";
			    else
				lista[i]="ODD POSITIVE";
			}else if(lista[i]<0){

			    if(lista[i]%2==0)
				lista[i]="EVEN NEGATIVE";
			    else
			       lista[i]="ODD NEGATIVE";
			}else
			   lista[i]="NULL";
			}
		}
		for(i=0;i<qtd;i++){
			printf("%s\n",lista[i]);
		}

		return 0;
	}
	
>PYTHON 3.9

	qtd = int(input())
	i=0
	lista=[]

	if(qtd<10000):
	    for i in range(i,qtd):
		valor = int(input())
		if(valor>0):
		    if(valor%2==0):
			lista.append("EVEN POSITIVE")
		    else:
			lista.append("ODD POSITIVE")
		elif(valor<0):
		    if(valor%2==0):
			lista.append("EVEN NEGATIVE")
		    else:
		       lista.append("ODD NEGATIVE")
		else:
		   lista.append("NULL")

	for i in lista:
	    print(f"{i}")
