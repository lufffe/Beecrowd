```
#Pergunta:

Leia um valor inteiro X. Em seguida apresente os 6 valores ímpares consecutivos a partir de X, 
um valor por linha, inclusive o X ser for o caso.
```

```
#Resposta:

valor = int(input())

lista=[]

for val in range(valor,valor+12):

    if(val%2 != 0):
        print(val)
```