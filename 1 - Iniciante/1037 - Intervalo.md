![image](https://github.com/lufffe/Beecrowd/assets/90646635/04dabfcc-ccd4-493b-b527-561585583a88)

>C
```C
#include<stdio.h>

int main()
{
	float valor;

	scanf("%f",&valor);

	if(valor>=0 && valor<=25)
		printf("Intervalo [0,25]\n");
	else if(valor>25 && valor <=50)
		printf("Intervalo (25,50]\n");
	else if(valor>50 && valor <=75)
		printf("Intervalo (50,75]\n");
	else if(valor>75 && valor <=100)
		printf("Intervalo (75,100]\n");
	else
		printf("Fora de intervalo\n");
	return 0;
}
```

>PYTHON 3.9
```Python 3.9
valor = float(input())

if(valor>=0 and valor <=25):   
	print("Intervalo [0,25]")
elif(valor>25 and valor <=50):    
	print("Intervalo (25,50]")
elif(valor>50 and valor <=75):    
	print("Intervalo (50,75]")
elif(valor>75 and valor<=100):    
	print("Intervalo (75,100]")
else:    
	print("Fora de intervalo")
```
