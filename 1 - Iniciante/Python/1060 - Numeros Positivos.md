```
#Perguntas:

Faça um programa que leia 6 valores. Estes valores serão somente negativos ou positivos 
(desconsidere os valores nulos). A seguir, mostre a quantidade de valores positivos digitados.
```

```
#Resposta:

a = float(input())
b = float(input())
c = float(input())
d = float(input())
e = float(input())
f = float(input())

lista = a,b,c,d,e,f 
positivo = 0

for num in lista:
    if(num>0):
        positivo = positivo + 1

print("{} valores positivos".format(positivo))
```