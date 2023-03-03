```
#Pergunta:

Leia 2 valores inteiros X e Y. A seguir, calcule e mostre a soma dos números impares entre eles.
```

```
#Resposta:

a = int(input())
b = int(input())
total= 0

if(a<b):
    for val in range(a+1,b):
        if(val%2 != 0):
            total = total +val

else:
    for val in range(b+1,a):
        if(val%2 != 0):
            total = total +val

print(total)
```