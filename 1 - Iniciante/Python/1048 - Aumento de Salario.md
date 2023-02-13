```
#Pergunta:

A empresa ABC resolveu conceder um aumento de salários a seus funcionários de acordo com a tabela abaixo:
```

```
#Resposta:

salario=float(input())

if(salario<=400):
    ajuste=salario*15/100
    print("Novo salario: {:.2f}".format(salario+ajuste))
    print("Reajuste ganho: {:.2f}".format(ajuste))
    print("Em percentual: 15 %")
elif(salario>400 and salario<=800):
    ajuste=salario*12/100
    print("Novo salario: {:.2f}".format(salario+ajuste))
    print("Reajuste ganho: {:.2f}".format(ajuste))
    print("Em percentual: 12 %")
elif(salario>800 and salario<=1200):
    ajuste=salario*10/100
    print("Novo salario: {:.2f}".format(salario+ajuste))
    print("Reajuste ganho: {:.2f}".format(ajuste))
    print("Em percentual: 10 %")
elif(salario>1200 and salario<=2000):
    ajuste=salario*7/100
    print("Novo salario: {:.2f}".format(salario+ajuste))
    print("Reajuste ganho: {:.2f}".format(ajuste))
    print("Em percentual: 7 %")
elif(salario>2000):
    ajuste=salario*4/100
    print("Novo salario: {:.2f}".format(salario+ajuste))
    print("Reajuste ganho: {:.2f}".format(ajuste))
    print("Em percentual: 4 %")
```