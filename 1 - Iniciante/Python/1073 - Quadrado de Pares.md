```
#Pergunta:

Quadrao de Pares - Leia um valor inteiro N. Apresente o quadrado de cada um dos valores pares, de 1 até N, inclusive N, se for o caso.
```

```
#Resposta:

valor = int(input())

if(valor>5 and valor <2000):
    for i in range(1,valor+1):
        if(i%2==0):
            print("{}^2 = {}".format(i,i**2))
```