```
#Pergunta:

Leia 3 valores de ponto flutuante e efetue o cálculo das raízes da equação de Bhaskara. 
Se não for possível calcular as raízes, mostre a mensagem correspondente “Impossivel calcular”, 
caso haja uma divisão por 0 ou raiz de numero negativo.
```

```
#Resposta:

#include<stdio.h>

int main()
{
	float a,b,c,baixo,raiz,delta,r1,r2;
	
	scanf("%f %f %f",&a,&b,&c);
	delta = (pow(b,2)-4*a*c);
	if(delta<0)
		printf("Impossivel calcular\n");
	else{
		raiz=sqrt(delta);
		baixo = 2*a;
		if(a>0){
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
```
