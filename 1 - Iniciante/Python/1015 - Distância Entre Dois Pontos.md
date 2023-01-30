```
#Pergunta:

Leia os quatro valores correspondentes aos eixos x e y de dois pontos quaisquer no plano, 
p1(x1,y1) e p2(x2,y2) e calcule a distância entre eles, mostrando 4 casas decimais após a vírgula, 
segundo a fórmula:
```

```
#Resposta:

import math
x1,y1 = input().split()x1,y1 = float(x1),float(y1)
x2,y2 = input().split()x2,y2 = float(x2),float(y2)
resultado = math.sqrt(((x2-x1)**2) + ((y2-y1)**2)) 
print("{:.4f}".format(resultado))
```