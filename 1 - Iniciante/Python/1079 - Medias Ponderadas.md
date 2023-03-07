```
#Pergunta:

Leia 1 valor inteiro N, que representa o número de casos de teste que vem a seguir. Cada caso de teste consiste de 3 valores reais, cada um deles com uma casa decimal. Apresente a média ponderada para cada um destes conjuntos de 3 valores, sendo que o primeiro valor tem peso 2, o segundo valor tem peso 3 e o terceiro valor tem peso 5.
```

```
#Resposta:

qtd = float(input())
i=0
lista=[]
while(i!=qtd):
    valor1,valor2,valor3=map(float,input().split())

    total=((valor1*2)+(valor2*3)+(valor3*5))/10
    lista.append(total)
    i=i+1

for i in lista:
    print("{:.1f}".format(i))
```