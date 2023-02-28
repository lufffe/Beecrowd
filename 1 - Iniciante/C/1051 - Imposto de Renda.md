```
#Pergunta:

Em um país imaginário denominado Lisarb, todos os habitantes ficam felizes em pagar seus impostos, 
pois sabem que nele não existem políticos corruptos e os recursos arrecadados são utilizados em benefício da população, 
sem qualquer desvio. A moeda deste país é o Rombus, cujo símbolo é o R$.

Leia um valor com duas casas decimais, equivalente ao salário de uma pessoa de Lisarb. Em seguida, 
calcule e mostre o valor que esta pessoa deve pagar de Imposto de Renda, segundo a tabela abaixo.
```

```
#Resposta:

#include<stdio.h>

int main(){
	
	double salario,imposto;

	scanf("%lf", &salario);
	
if(salario>0 && salario<=2000)
	printf("Isento\n");

else if(salario>2000 && salario<=3000)
{
	imposto = (salario - 2000.0)*0.08 ;
	printf("R$ %.2lf\n",imposto);
}
else if(salario>3000 && salario<=4500)
{
	imposto = (salario - 3000.0)*0.18 + (1000*0.08);
	printf("R$ %.2lf\n",imposto);
}
else if(salario>4500)
{
	imposto = ((salario - 4500)*0.28 + (1500*0.18) + (1000*0.08));
	printf("R$ %.2lf\n",imposto);
}
	return 0;
}
```