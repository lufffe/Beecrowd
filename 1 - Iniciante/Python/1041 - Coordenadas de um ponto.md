```
#Pergunta:

    Coordenadas de um ponto - Leia 2 valores com uma casa decimal (x e y), 
    que devem representar as coordenadas de um ponto em um plano. seguir, 
    determine qual o quadrante ao qual pertence o ponto, 
    ou se está sobre um dos eixos cartesianos ou na origem (x = y = 0).

    Se o ponto estiver na origem, escreva a mensagem “Origem”.
    Se o ponto estiver sobre um dos eixos escreva “Eixo X” ou “Eixo Y”, conforme for a situação.
```

```
#Resposta:

x,y = map(float,input().split())

if(x>0):
    if(y>0):
        print("Q1")
    elif(y<0):
        print("Q4")
    elif(y==0):
        print("Eixo X")
elif(x<0):
    if(y>0):
        print("Q2")
    elif(y<0):
        print("Q3")
    elif(y==0):
        print("Eixo X")
elif(x==0):
    if(y!=0):
        print("Eixo Y")
    else:
        print("Origem")
```