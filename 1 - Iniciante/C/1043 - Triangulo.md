```
#Pergunta:

Leia 3 valores reais (A, B e C) e verifique se eles formam ou não um triângulo. 
Em caso positivo, calcule o perímetro do triângulo e apresente a mensagem:
Perimetro = XX.X
Em caso negativo, calcule a área do trapézio que tem A e B como base e C como altura, 
mostrando a mensagem
Area = XX.X

```

```
#Resposta:

#include <stdio.h>

int main()
{
	
	float a,b,c,maior,soma,perimetro,area;
	scanf("%f %f %f",&a,&b,&c);
	
	if(a>=b && a>=c)
	{
		maior=a;
		soma=b+c;
	}
	else if(b>=a && b>=c)
    {
    	maior=b;
		soma=a+c;
	}
	else if(c>=a && c>=b)
    {
    	maior=c;
		soma=b+a;
	}
	
	perimetro=a+b+c;
	area=(((a+b)*c)/2);
	
	if(maior<soma){
		printf("Perimetro = %.1f\n",perimetro);
	}else{
		printf("Area = %.1f\n",area);
	}
	return 0;
}
```