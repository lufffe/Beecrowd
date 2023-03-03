```
#Pergunta:

Leia um valor inteiro N. Este valor será a quantidade de valores inteiros X que serão lidos em seguida.
Mostre quantos destes valores X estão dentro do intervalo [10,20] e quantos estão fora do intervalo, 
mostrando essas informações.
```

```
#Resposta:

quant = int(input())

total= 0
lista = []
dentro=0 
fora=0
limitevalor=(10**7)
if(quant<10000):

    while(total!=quant):

        valor=int(input())

        if(valor>-limitevalor and valor<limitevalor):

            if(valor>=10 and valor<=20):
                dentro = dentro +1
            else:
                fora = fora+1
        
        total = total+1
            
print("{} in".format(dentro))
print("{} out".format(fora))
```