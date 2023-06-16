![image](https://github.com/lufffe/Beecrowd/assets/90646635/8d7bac37-9a33-4425-aa41-ae40c0ba79d9)

>C

 	#include <stdio.h>
	
	int main()
	{
		double pi,raio,A ;
		
		scanf("%lf",&raio);
		pi = 3.14159 ;
		A = (pi * pow(raio,2));
		
		printf("A=%.4lf\n",A);
		
		return 0;
	}
	
>PYTHON 3
	
	pi = 3.14159
	raio = float(input())
	
	A = (pi * (raio ** 2))
	
	print("A={:.4f}".format(A))
