![image](https://github.com/lufffe/Beecrowd/assets/90646635/4f7d5cad-66d0-4c95-89f3-0e49657d5097)

>C

	#include<stdio.h>

	int main()
	{
		int a,b,c,menor,medio,maior;

		scanf("%d %d %d",&a,&b,&c);

		if(a<b && a<c )
		{
			menor=a;
			if(b<c)
			{
				medio=b;
				maior=c;
			}
			else
			{
				medio=c;
				maior=b;
			}
		}
		else if(b<a && b<c )
		{
			menor=b;
			if(a<c)
			{
				medio=a;
				maior=c;
			}
			else
			{
				medio=c;
				maior=a;
			}
		}
		else if (c<a && c<b )
		{
			menor=c;
			if(b<a)
			{
				medio=b;
				maior=a;
			}
			else
			{
				medio=a;
				maior=b;
			}
		}
		printf("%d\n",menor);
		printf("%d\n",medio);
		printf("%d\n",maior);
		printf("\n");
		printf("%d\n",a);
		printf("%d\n",b);
		printf("%d\n",c);
	    return 0;
	}

>PYTHON 3.9

	a,b,c = map(int,input().split())

	lista = [a,b,c]
	listamaior = sorted(lista)

	for i in listamaior:
	    print(i)
	print("")
	for i in lista:
	    print(i)
