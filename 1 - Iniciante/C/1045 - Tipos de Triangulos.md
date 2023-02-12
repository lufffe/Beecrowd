```
#Pergunta:

Leia 3 valores de ponto flutuante A, B e C e ordene-os em ordem decrescente, 
de modo que o lado A representa o maior dos 3 lados. A seguir, 
determine o tipo de triângulo que estes três lados formam,
 com base nos seguintes casos, sempre escrevendo uma mensagem adequada:
se A ≥ B+C, apresente a mensagem: NAO FORMA TRIANGULO
se A2 = B2 + C2, apresente a mensagem: TRIANGULO RETANGULO
se A2 > B2 + C2, apresente a mensagem: TRIANGULO OBTUSANGULO
se A2 < B2 + C2, apresente a mensagem: TRIANGULO ACUTANGULO
se os três lados forem iguais, apresente a mensagem: TRIANGULO EQUILATERO
se apenas dois dos lados forem iguais, apresente a mensagem: TRIANGULO ISOSCELES
```

```
#Resposta:

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
```