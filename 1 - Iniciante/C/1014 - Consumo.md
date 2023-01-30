```
#Pergunta:

Calcule o consumo médio de um automóvel sendo fornecidos a distância total percorrida (em Km) 
e o total de combustível gasto (em litros).
``` 

```
#Resposta:

#include <stdio.h>
 
int main() {
 
    double distancia,consumo,total;
    
    scanf("%lf",&distancia);
    scanf("%lf",&consumo);
    
    total = (distancia/consumo);
    printf("%.3lf km/l\n",total);
 
    return 0;
}
```