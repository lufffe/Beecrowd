```
#Pergunta:

Você deve fazer um programa que apresente a sequencia conforme o exemplo abaixo.
```

```
#Resposta:

j=7
i=1
total=1

lista=7

for total in range(1,10):

    if(total%2!=0):
        for i in range(0,3):
           print("I={} J={}".format(total,lista-i))
           
        lista=lista+2
```
