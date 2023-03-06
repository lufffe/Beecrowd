```
#Pergunta:

Leia um valor inteiro N. Este valor será a quantidade de valores que serão lidos em seguida. Para cada valor lido, mostre uma mensagem em inglês dizendo se este valor lido é par (EVEN), ímpar (ODD), positivo (POSITIVE) ou negativo (NEGATIVE). No caso do valor ser igual a zero (0), embora a descrição correta seja (EVEN NULL), pois por definição zero é par, seu programa deverá imprimir apenas NULL.
```

```
#Resposta:

qtd = int(input())
i=0
lista=[]

if(qtd<10000):
    for i in range(i,qtd):
        valor = int(input())
        if(valor>0):
            if(valor%2==0):
                lista.append("EVEN POSITIVE")
            else:
                lista.append("ODD POSITIVE")
        elif(valor<0):
            if(valor%2==0):
                lista.append("EVEN NEGATIVE")
            else:
               lista.append("ODD NEGATIVE")
        else:
           lista.append("NULL")

for i in lista:
    print("{}".format(i))
``` 