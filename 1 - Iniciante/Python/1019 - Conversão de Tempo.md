```
#Pergunta:

Leia um valor inteiro, que é o tempo de duração em segundos de um determinado evento em uma fábrica, 
e informe-o expresso no formato horas:minutos:segundos.
```

```
#Resposta:

tempo = int(input())

if(tempo>3600):
    hora = tempo // 3600
    resto = tempo % 3600
    minutos = resto // 60
    segundos = resto % 60
    print("{}:{}:{}".format(hora,minutos,segundos))

elif(tempo>60):
    minuto = tempo // 60
    segundos = tempo % 60
    print("0:{}:{}".format(int(minuto),segundos))
else:
    print("0:0:{}".format(tempo))
```