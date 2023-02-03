```
#Pergunta:
    Leia 3 valores de ponto flutuante e efetue o cálculo das raízes da equação de Bhaskara. 
    Se não for possível calcular as raízes, mostre a mensagem correspondente “Impossivel calcular”, 
    caso haja uma divisão por 0 ou raiz de numero negativo.
```

```
#Resposta:

import math

a,b,c = map(float,input().split())

delta = (b**2)-4*a*c
delta = float('%.2f'% delta)
if(delta<0):
    print("Impossivel calcular")
else:
    raiz=math.sqrt(delta)
    raiz = float('%.5f'% raiz)
    baixo = 2*a

    if(a>0):
        r1 = (-b+raiz)/baixo
        r2 = (-b-raiz)/baixo
        print("R1 = {:.5f}".format(r1))
        print("R2 = {:.5f}".format(r2))
    else:
        print("Impossivel calcular")
```