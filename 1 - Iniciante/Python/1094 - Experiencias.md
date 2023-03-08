```

```

```
qtd = int(input())
i=0
coelho=0
ratos=0
sapos=0
total=0

while(i!=qtd):
    valor,tipo=input().split()
    valor=int(valor)
    tipo=str(tipo)
    
    if(tipo=='C'):
        coelho=coelho+valor
    elif(tipo=='R'):
        ratos=ratos+valor
    elif(tipo=='S'):
        sapos=sapos+valor

    total=total+valor

    i=i+1


print("Total: {} cobaias".format(total))
print("Total de coelhos: {}".format(coelho))
print("Total de ratos: {}".format(ratos))
print("Total de sapos: {}".format(sapos))
print("Percentual de coelhos: {:.2f} %".format(coelho/total*100))
print("Percentual de ratos: {:.2f} %".format(ratos/total*100))
print("Percentual de sapos: {:.2f} %".format(sapos/total*100))
```