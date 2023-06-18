```
#Pergunta:

Leia um valor de ponto flutuante com duas casas decimais. Este valor representa um valor monetário. 
A seguir, calcule o menor número de notas e moedas possíveis no qual o valor pode ser decomposto. 
As notas consideradas são de 100, 50, 20, 10, 5, 2. As moedas possíveis são de 1, 0.50, 0.25, 0.10, 0.05 e 0.01.
A seguir mostre a relação de notas necessárias.
```

```
#Resposta:

notas = [100,50,20,10,5,2]
moedas =[1,0.50,0.25,0.10,0.05,0.01]
valor = float(input())
print("NOTAS:")
for c in notas:   
    if(valor>=c):       
        qtd=valor//c        
        valor = valor%c        
        print("{} nota(s) de R$ {:.2f}".format(int(qtd),float(c)))    
    else:        
        print("0 nota(s) de R$ {:.2f}".format(c))
print("MOEDAS:")
for c in moedas:    
    valor = float('%.2f'% valor)
    if(valor>=c):
        if(c == 0.01):
            qtd = valor * 100        
        else:            
            qtd=valor//c            
            valor = valor%c          
        print("{} moeda(s) de R$ {:.2f}".format(int(qtd),float(c)))    
    else:
        print("0 moeda(s) de R$ {:.2f}".format(c))
```