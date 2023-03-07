```
#Pergunta:

Leia 100 valores inteiros. Apresente então o maior valor lido e a posição dentre os 100 valores lidos.
```

```
#Resposta:

qtd=1
maior=0
pos=0

while(qtd!=101):
    valor=int(input())
    
    if(valor>maior):
        maior=valor
        pos=qtd
    
    qtd=qtd+1

print(maior)
print(pos)
```