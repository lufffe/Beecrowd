```
#Pergunta:

Neste problema, deve-se ler o código de uma peça 1, o número de peças 1, o valor unitário de cada peça 1, 
o código de uma peça 2, o número de peças 2 e o valor unitário de cada peça 2. Após, calcule e mostre o valor a ser pago.
```

```
#Resposta:

#include <stdio.h>

int main(){
    int cod1,cod2,num1,num2 ;
    double valor1,valor2,total;
    
    scanf("%d",&cod1);
    scanf("%d",&num1);
    scanf("%lf",&valor1);
    
    scanf("%d",&cod2);
    scanf("%d",&num2);
    scanf("%lf",&valor2);

    total = (num1 * valor1) + (num2 * valor2);
    printf("VALOR A PAGAR: R$ %.2lf\n",total);
    
}
```