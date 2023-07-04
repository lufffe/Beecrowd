![image](https://github.com/lufffe/Beecrowd/assets/90646635/931d557e-c963-4756-b0a1-82e2aae93dd4)

>C
```C
#include <stdio.h>

int main() 
{
   double distancia,consumo,total;

   scanf("%lf",&distancia);
   scanf("%lf",&consumo);

   total = (distancia/consumo);
   
   printf("%.3lf km/l\n",total);

   return 0;
}
```

>PYTHON 3.9
```Python 3.9
distancia = input()
combustivel = input()

total = float(distancia)/float(combustivel)

print(f"{total:.3f} km/l")
```
