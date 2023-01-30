```
#Pergunta:

Faça um programa que leia o nome de um vendedor, o seu salário fixo e o total de vendas efetuadas por ele no mês (em dinheiro). 
Sabendo que este vendedor ganha 15% de comissão sobre suas vendas efetuadas, informar o total a receber no final do mês, 
com duas casas decimais.
```

```
#Resposta:

#include <stdio.h>

int main(){
        
    char nome ;
    double salario_fixo, vendas ,total;
    
    scanf("%s",&nome);
    scanf("%lf",&salario_fixo);
    scanf("%lf",&vendas);
    total = salario_fixo + (vendas * 15 / 100);
    
    printf("TOTAL = R$ %.2lf\n",total);

}
```