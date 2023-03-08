```
Maria acabou de iniciar seu curso de graduação na faculdade de medicina e precisa de sua ajuda para organizar os experimentos
de um laboratório o qual ela é responsável. Ela quer saber no final do ano, quantas cobaias foram utilizadas no laboratório 
e o percentual de cada tipo de cobaia utilizada.

Este laboratório em especial utiliza três tipos de cobaias: sapos, ratos e coelhos. Para obter estas informações, 
ela sabe exatamente o número de experimentos que foram realizados, o tipo de cobaia utilizada e 
a quantidade de cobaias utilizadas em cada experimento.

Entrada
A primeira linha de entrada contém um valor inteiro N que indica os vários casos de teste que vem a seguir. 
Cada caso de teste contém um inteiro Quantia (1 ≤ Quantia ≤ 15) 
que representa a quantidade de cobaias utilizadas e um caractere Tipo ('C', 'R' ou 'S'), 
indicando o tipo de cobaia (R:Rato S:Sapo C:Coelho).

Saída
Apresente o total de cobaias utilizadas, o total de cada tipo de cobaia utilizada e 
o percentual de cada uma em relação ao total de cobaias utilizadas, sendo que o percentual 
deve ser apresentado com dois dígitos após o ponto.
```

```
qtd = int(input())
i=0
coelho=0
ratos=0
sapos=0
total=0

while(i!=qtd):
    valor,tipo=input().split()
    valor=int(valor)
    tipo=str(tipo)
    
    if(tipo=='C'):
        coelho=coelho+valor
    elif(tipo=='R'):
        ratos=ratos+valor
    elif(tipo=='S'):
        sapos=sapos+valor

    total=total+valor

    i=i+1


print("Total: {} cobaias".format(total))
print("Total de coelhos: {}".format(coelho))
print("Total de ratos: {}".format(ratos))
print("Total de sapos: {}".format(sapos))
print("Percentual de coelhos: {:.2f} %".format(coelho/total*100))
print("Percentual de ratos: {:.2f} %".format(ratos/total*100))
print("Percentual de sapos: {:.2f} %".format(sapos/total*100))
```
