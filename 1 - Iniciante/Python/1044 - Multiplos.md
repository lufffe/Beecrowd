```
#Pergunta:

Leiia 2 valores inteiros (A e B). Após, o programa deve mostrar uma mensagem 
"Sao Multiplos" ou "Nao sao Multiplos", 
indicando se os valores lidos são múltiplos entre si.
```

```
#Resposta:

a,b = map(int,input().split())

resto = a%b

if(a>b):

    if((a%b)==0):
        print("Sao Multiplos")
    else:
        print("Nao sao Multiplos")
else:
    if((b%a)==0):
        print("Sao Multiplos")
    else:
        print("Nao sao Multiplos")   
```