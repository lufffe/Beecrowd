```
#Pergunta:

Faça um programa que leia 5 valores inteiros. Conte quantos destes valores digitados são pares e mostre esta informação.
```

```
#Resposta:

a = float(input())
b = float(input())
c = float(input())
d = float(input())
e = float(input())

lista = a,b,c,d,e
cont=0

for num in lista:
    valor=num%2
    if(valor==0):
        cont = cont + 1

print("{} valores pares".format(cont))
```