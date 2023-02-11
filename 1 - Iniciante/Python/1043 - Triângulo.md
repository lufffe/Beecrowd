```
#Pergunta:

Leia 3 valores reais (A, B e C) e verifique se eles formam ou não um triângulo. 
Em caso positivo, calcule o perímetro do triângulo e apresente a mensagem:
Perimetro = XX.X
Em caso negativo, calcule a área do trapézio que tem A e B como base e C como altura, 
mostrando a mensagem
Area = XX.X

```

```
#Resposta:

a,b,c = map(float,input().split())

if(a>=b and a>=c):
    mai=a
    soma=b+c
elif(b>=a and b>=c):
    mai=b
    soma=a+c
elif(c>=a and c>=b):
    mai=c
    soma=(a+b)

perimetro = a+b+c
area = ((a+b)*c)/2

if(mai<soma):
    print("Perimetro = {:.1f}".format(perimetro))
else:
    print("Area = {:.1f}".format(area))
```