```
#Pergunta:

Leia quatro valores inteiros A, B, C e D. A seguir, calcule e mostre a diferença do produto de A e B pelo produto de C e D 
segundo a fórmula: DIFERENCA = (A * B - C * D).
```

```
#Resposta:

#include <stdio.h>

int main(){
    int a,b,c,d,dif;
    scanf("%i",&a);
    scanf("%i",&b);
    scanf("%i",&c);
    scanf("%i",&d);
    
    dif = ((a * b) - (c * d));
    printf("DIFERENCA = %i\n",dif);
}
```