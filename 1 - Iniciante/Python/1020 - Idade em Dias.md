```
#Pergunta:

Leia um valor inteiro correspondente à idade de uma pessoa em dias e informe-a em anos, meses e dias
```

```
#Resposta:

dias = input()
dias = int(dias)

if(dias>=365):
    ano = dias // 365
    resto = dias % 365
    meses = resto // 30
    dias = resto % 30
    print("{} ano(s)\n{} mes(es)\n{} dia(s)".format(ano,meses,dias))

elif(dias>=30):
    meses = dias // 30
    dias = dias % 30
    print("0 ano(s)\n{} mes(es)\n{} dia(s)".format(meses,dias))
else:
    print("0 ano(s)\n0 mes(es)\n{} dia(s)".format(dias))
```