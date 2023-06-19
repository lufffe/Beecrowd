![image](https://github.com/lufffe/Beecrowd/assets/90646635/b421a704-6f14-4898-984d-7e5d4daa9840)

>C

	#include <stdio.h>
	#include <math.h>

	int main()
	{

		float a,b,c,menor,maior,medio;

		scanf("%f %f %f",&a,&b,&c);

		if(a>=b && a>=c)
		{
			if(b>=c)
			{
				maior=a;
				medio=b;
				menor=c;
			}
			else
			{
				maior=a;
				medio=c;
				menor=b;
			}
		}
		else if(b>=a && b>=c)
		{
			if(a>=c)
			{
				maior=b;
				medio=a;
				menor=c;
			}
			else
			{
				maior=b;
				medio=c;
				menor=a;
			}
		}
		else if(c>=a && c>=b)
		{
			if(a>=b)
			{
				maior=c;
				medio=a;
				menor=b;
			}
			else
			{
				maior=c;
				medio=b;
				menor=a;
			}
		}

		a=maior;
		b=medio;
		c=menor;

		if(a>=b+c)
		    printf("NAO FORMA TRIANGULO\n");
		else
		{
		    if(pow(a,2) == pow(b,2) + pow(c,2))
			printf("TRIANGULO RETANGULO\n");
		    if(pow(a,2) > pow(b,2) + pow(c,2))
			printf("TRIANGULO OBTUSANGULO\n");
		    if(pow(a,2)< pow(b,2) + pow(c,2))
			printf("TRIANGULO ACUTANGULO\n");
		    if(a==b && a==c)
			printf("TRIANGULO EQUILATERO\n");
		    if(a==b && a!=c || b==c && b!=a || a==c && a!=b)
			printf("TRIANGULO ISOSCELES\n");
		}	
			return 0;
	}

>PYTHON 3.9

	a,b,c = map(float,input().split())
	lista=[]

	lista = [a,b,c]
	listamaior = sorted(lista)

	c=listamaior[0]
	b=listamaior[1]
	a=listamaior[2]

	if(a>=b+c):
	    print("NAO FORMA TRIANGULO")
	else:

	    if((a**2)==(b**2 + c**2)):
		print("TRIANGULO RETANGULO")

	    if((a**2)>(b**2 + c**2)):
		print("TRIANGULO OBTUSANGULO")

	    if((a**2)<(b**2 + c**2)):
		print("TRIANGULO ACUTANGULO")

	    if(a==b==c):
		print("TRIANGULO EQUILATERO")

	    if(a==b and a!=c or b==c and b!=a or a==c and a!=b):
		print("TRIANGULO ISOSCELES")
