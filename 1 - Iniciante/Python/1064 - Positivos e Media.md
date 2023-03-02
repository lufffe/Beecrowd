```
#Pergunta:

Leia 6 valores. Em seguida, mostre quantos destes valores digitados foram positivos. Na próxima linha, 
deve-se mostrar a média de todos os valores positivos digitados, com um dígito após o ponto decimal.
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
total=0

for num in lista:
    if(num>0):
        positivo = positivo + 1
        total = total + num

media = total / positivo

print("{} valores positivos".format(positivo))
print("{:.1f}".format(media))
```