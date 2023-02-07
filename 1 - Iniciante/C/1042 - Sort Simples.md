```
#Pergunta:

Leia 3 valores inteiros e ordene-os em ordem crescente. No final, mostre os valores em ordem crescente,
 uma linha em branco e em seguida, os valores na sequência como foram lidos.
```

```
#Resposta:

a,b,c = map(int,input().split())

lista = [a,b,c]
listamaior = sorted(lista)

for i in listamaior:
    print(i)
print("\n")
for i in lista:
    print(i)
```