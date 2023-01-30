```
#Pergunta:

Leia um valor inteiro. A seguir, calcule o menor número de notas possíveis (cédulas) no qual o valor pode ser decomposto. As notas consideradas são de 100, 50, 20, 10, 5, 2 e 1. A seguir mostre o valor lido e a relação de notas necessárias.
```

```
#Resposta:

valor = int(input())
notas = [100,50,20,10,5,2,1]

print(valor)
for c in notas:
    if valor>=c:
        inteiro = valor // c
        print("{} nota(s) de R$ {},00".format(inteiro,c))
        valor = valor % c
    else:
        print("0 nota(s) de R$ {},00".format(c))
```