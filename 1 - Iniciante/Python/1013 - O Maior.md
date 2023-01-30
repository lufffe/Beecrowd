```
#Pergunta:

Faça um programa que leia três valores e apresente o maior dos três valores lidos seguido da mensagem “eh o maior”. 
Utilize a fórmula:
```

```
#Resposta:

a,b,c = input().split()
a,b,c = int(a),int(b),int(c)

if (a>c) and (a>b):
    print("{} eh o maior".format(a))
elif (b>c):
    print("{} eh o maior".format(b))
else:    
    print("{} eh o maior".format(c))
```