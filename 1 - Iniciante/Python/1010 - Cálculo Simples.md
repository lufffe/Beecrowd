```
#Pergunta:

Neste problema, deve-se ler o código de uma peça 1, o número de peças 1, o valor unitário de cada peça 1, 
o código de uma peça 2, o número de peças 2 e o valor unitário de cada peça 2. Após, calcule e mostre o valor a ser pago.
```

```
#Resposta:

a,b,c = input('').split(' ')
d,e,f = input('').split(' ')
valor = int(b)*float(c) + int(e)*float(f)

print('VALOR A PAGAR: R$ {:.2f}'.format(valor))
```