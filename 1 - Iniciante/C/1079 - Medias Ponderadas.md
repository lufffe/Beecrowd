![image](https://github.com/lufffe/Beecrowd/assets/90646635/df95fc66-f65b-4f9c-b8e2-686c2f1af230)

>C

	#include<stdio.h>

	int main()
	{
	    int qtd,i;
	    float v1,v2,v3,total,resposta;

	    scanf("%d",&qtd);

		float lista[qtd];

		for(i=0;i<qtd;i++)
		{
			scanf("%f %f %f",&v1,&v2,&v3);

			total=((v1*2)+(v2*3)+(v3*5))/10;
			lista[i]=total;
		}    

	    for(i=0;i<qtd;i++)
		{
			printf("%.1f\n",lista[i]);
		}

	    return 0;
	}

>PYTHON 3.9

	qtd = float(input())
	i=0
	lista=[]
	while(i!=qtd):
	    valor1,valor2,valor3=map(float,input().split())

	    total=((valor1*2)+(valor2*3)+(valor3*5))/10
	    lista.append(total)
	    i=i+1

	for i in lista:
	    print(f"{i:.1f}")
