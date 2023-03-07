```
#Pergunta:

Leia 1 valor inteiro N (2 < N < 1000). A seguir, mostre a tabuada de N:      
1 x N = N      2 x N = 2N        ...       10 x N = 10N
```

```
#Resposta:

valor = int(input())

if(valor>2 and valor<10000):
    for i in range(1,11):
        print("{} x {} = {}".format(i,valor,i*valor))
```