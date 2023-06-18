![image](https://github.com/lufffe/Beecrowd/assets/90646635/438ffd01-2d64-426a-87f5-3e2b532789c4)

>C

    #include<stdio.h>

    int main()
    {
        int numero_funcionario;
        double horas,valor_hora,salario;

        scanf("%i",&numero_funcionario);
        scanf("%lf",&horas);
        scanf("%lf",&valor_hora);
        salario = (horas * valor_hora);
        
        printf("NUMBER = %i\n",numero_funcionario);
        printf("SALARY = U$ %.2lf\n",salario);
    }

>PYTHON 3.9

    numero_funcionario = int(input())
    horas_funcionario = float(input())
    valor_horas = float(input())
    
    salario = ( horas_funcionario * valor_horas )

    print(f"NUMBER = {numero_funcionario}")
    print(f"SALARY = U$ {salario:.2f}")
