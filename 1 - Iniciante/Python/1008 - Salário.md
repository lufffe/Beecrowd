```
#Pergunta:

Escreva um programa que leia o número de um funcionário, seu número de horas trabalhadas, 
o valor que recebe por hora e calcula o salário desse funcionário. A seguir, 
mostre o número e o salário do funcionário, com duas casas decimais.
```

```
#Resposta:

numero_funcionario = int(input())
horas_funcionario = float(input())
valor_horas = float(input())
salario = ( horas_funcionario * valor_horas )

print("NUMBER = {}".format(numero_funcionario))
print("SALARY = U$ {:.2f}".format(salario))
```