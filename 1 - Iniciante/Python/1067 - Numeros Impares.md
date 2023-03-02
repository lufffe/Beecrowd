```
#Pergunta:

Leia um valor inteiro X (1 <= X <= 1000). Em seguida mostre os ímpares de 1 até X, um valor por linha,
inclusive o X, se for o caso.
```

```
#Resposta:

valor = int(input())

lista=[]

if(valor>=1 and valor<=1000):

    for val in range(1,valor+1):

    if(val%2 != 0):
        print(val)
```