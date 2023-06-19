![image](https://github.com/lufffe/Beecrowd/assets/90646635/45745c0f-42b0-48c9-8eba-99c777c78a22)

>C

	#include<stdio.h>

	int main()
	{
		float a,b,c,baixo,raiz,delta,r1,r2;

		scanf("%f %f %f",&a,&b,&c);
		delta = (pow(b,2)-4*a*c);
		if(delta<0)
			printf("Impossivel calcular\n");
		else
		{
			raiz=sqrt(delta);
			baixo = 2*a;
			if(a>0)
			{
				r1=(-b+raiz)/baixo;
				r2=(-b-raiz)/baixo;
				printf("R1 = %.5f\n",r1);
				printf("R2 = %.5f\n",r2);
			}
			else
				printf("Impossivel calcular\n");
		}
	    return 0;
	}

>PYTHON 3.9

	import math

	a,b,c = map(float,input().split())

	delta = (b**2)-4*a*c
	delta = float('%.2f'% delta)
	if(delta<0):
	    print("Impossivel calcular")
	else:
	    raiz=math.sqrt(delta)
	    raiz = float('%.5f'% raiz)
	    baixo = 2*a

	    if(a>0):
			r1 = (-b+raiz)/baixo
			r2 = (-b-raiz)/baixo
			print(f"R1 = {r1:.5f}")
			print(f"R2 = {r2:.5f}")
	    else:
			print("Impossivel calcular")
