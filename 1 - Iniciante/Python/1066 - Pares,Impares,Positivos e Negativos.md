```
#Perguntas:

Leia 5 valores Inteiros. A seguir mostre quantos valores digitados foram pares, quantos valores digitados foram ímpares, 
quantos valores digitados foram positivos e quantos valores digitados foram negativos.
```

```
#Resposta:

a = int(input())
b = int(input())
c = int(input())
d = int(input())
e = int(input())

lista = a,b,c,d,e
par=0
impar=0
positivo=0
negativo=0

for num in lista:
    if(num%2 == 0):
        par = par+1
    else:
        impar = impar+1

    if(num>0): 
        positivo = positivo + 1
    elif(num<0):
        negativo = negativo + 1

print("{} valor(es) par(es)".format(par))
print("{} valor(es) impar(es)".format(impar))
print("{} valor(es) positivo(s)".format(positivo))
print("{} valor(es) negativo(s)".format(negativo))
```