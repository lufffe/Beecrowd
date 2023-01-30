```
#Pergunta:

Escreva um programa que leia o número de um funcionário, seu número de horas trabalhadas, 
o valor que recebe por hora e calcula o salário desse funcionário. A seguir, 
mostre o número e o salário do funcionário, com duas casas decimais.
```

```
#Resposta:

#include<stdio.h>

int main(){
    int numero_funcionario ;
    double horas,valor_hora,salario;
    
    scanf("%i",&numero_funcionario);
    scanf("%lf",&horas);
    scanf("%lf",&valor_hora);
    
    salario = (horas * valor_hora);
    printf("NUMBER = %i\n",numero_funcionario);
    printf("SALARY = U$ %.2lf\n",salario);
}
```