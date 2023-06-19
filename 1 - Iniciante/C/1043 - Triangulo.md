![image](https://github.com/lufffe/Beecrowd/assets/90646635/d363857b-122c-4856-aafe-314db80ba8d0)

>C

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

		if(maior<soma)
			printf("Perimetro = %.1f\n",perimetro);
		else
			printf("Area = %.1f\n",area);
		return 0;
	}
	
>PYTHON 3.9 

	a,b,c = map(float,input().split())

	if(a>=b and a>=c):
	    mai=a
	    soma=b+c
	elif(b>=a and b>=c):
	    mai=b
	    soma=a+c
	elif(c>=a and c>=b):
	    mai=c
	    soma=(a+b)

	perimetro = a+b+c
	area = ((a+b)*c)/2

	if(mai<soma):
	    print(f"Perimetro = {perimetro:.1f}")
	else:
	    print(f"Area = {area:.1f}")
