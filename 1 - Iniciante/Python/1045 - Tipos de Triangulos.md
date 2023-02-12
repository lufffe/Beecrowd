```
#Pergunta:

Leia 3 valores de ponto flutuante A, B e C e ordene-os em ordem decrescente, 
de modo que o lado A representa o maior dos 3 lados. A seguir, 
determine o tipo de triângulo que estes três lados formam,
 com base nos seguintes casos, sempre escrevendo uma mensagem adequada:
se A ≥ B+C, apresente a mensagem: NAO FORMA TRIANGULO
se A2 = B2 + C2, apresente a mensagem: TRIANGULO RETANGULO
se A2 > B2 + C2, apresente a mensagem: TRIANGULO OBTUSANGULO
se A2 < B2 + C2, apresente a mensagem: TRIANGULO ACUTANGULO
se os três lados forem iguais, apresente a mensagem: TRIANGULO EQUILATERO
se apenas dois dos lados forem iguais, apresente a mensagem: TRIANGULO ISOSCELES
```

```
#Resposta:

a,b,c = map(float,input().split())
lista=[]

lista = [a,b,c]
listamaior = sorted(lista)

c=listamaior[0]
b=listamaior[1]
a=listamaior[2]

if(a>=b+c):
    print("NAO FORMA TRIANGULO")
else:

    if((a**2)==(b**2 + c**2)):
        print("TRIANGULO RETANGULO")

    if((a**2)>(b**2 + c**2)):
        print("TRIANGULO OBTUSANGULO")

    if((a**2)<(b**2 + c**2)):
        print("TRIANGULO ACUTANGULO")
        
    if(a==b==c):
        print("TRIANGULO EQUILATERO")
        
    if(a==b and a!=c or b==c and b!=a or a==c and a!=b):
        print("TRIANGULO ISOSCELES")
```