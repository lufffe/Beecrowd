```
#Pergunta:

Com base na tabela abaixo, escreva um programa que leia o código de um item 
e a quantidade deste item. A seguir, calcule e mostre o valor da conta a pagar.
```

```
#Resposta:

codigo,qtd=map(int,input().split())

if(codigo==1):
    total=qtd*4
elif(codigo==2):
    total=qtd*4.50
elif(codigo==3):
    total=qtd*5
elif(codigo==4):
    total=qtd*2
elif(codigo==5):
    total=qtd*1.50
print("Total: R$ {:.2f}".format(total))
```