```
#Pergunta:
Área do Circulo - A fórmula para calcular a área de uma circunferência é: area = π . raio2. 
Considerando para este problema que π = 3.14159:
Efetue o cálculo da área, elevando o valor de raio ao quadrado e multiplicando por π.
```

```
#Resposta:
#include <stdio.h>

int main(){
	double pi,raio,A ;
	
	scanf("%lf",&raio);
	pi = 3.14159 ;
	A = (pi * pow(raio,2));
	
	printf("A=%.4lf\n",A);
}
```