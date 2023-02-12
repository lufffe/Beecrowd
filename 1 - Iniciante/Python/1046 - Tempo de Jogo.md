```
#Pergunta:

Leia a hora inicial e a hora final de um jogo. 
A seguir calcule a duração do jogo, 
sabendo que o mesmo pode começar em um dia e terminar em outro,
 tendo uma duração mínima de 1 hora e máxima de 24 horas.
```

```
#Pergunta:

a,b = map(int,input().split())

if(a==b):
    print("O JOGO DUROU 24 HORA(S)")
else:
    if(a<b):
        valor=b-a
        print("O JOGO DUROU {} HORA(S)".format(valor))
    else:
        valor=24-a
        valor=valor+b
        print("O JOGO DUROU {} HORA(S)".format(valor))
```