```
#Pergunta:

A empresa ABC resolveu conceder um aumento de salários a seus funcionários de acordo com a tabela abaixo:

```

```
#Resposta:

#include <stdio.h>
#include <math.h>

int main()
{
	
	float salario,ajuste;
	
	scanf("%f",&salario);
	
	
	if(salario<=400)
	{
	    ajuste=salario*15/100;
	    printf("Novo salario: %.2f\n",salario+ajuste);
	    printf("Reajuste ganho: %.2f\n",ajuste);
	    printf("Em percentual: 15 %%\n");
	}
	else if(salario>400 && salario<=800)
	{
	    ajuste=salario*12/100;
	    printf("Novo salario: %.2f\n",salario+ajuste);
	    printf("Reajuste ganho: %.2f\n",ajuste);
	    printf("Em percentual: 12 %%\n");
	}
	else if(salario>800 && salario<=1200)
	{
	    ajuste=salario*10/100;
	    printf("Novo salario: %.2f\n",salario+ajuste);
	    printf("Reajuste ganho: %.2f\n",ajuste);
	    printf("Em percentual: 10 %%\n");
	}
	else if(salario>1200 && salario<=2000)
	{
	    ajuste=salario*7/100;
	    printf("Novo salario: %.2f\n",salario+ajuste);
	    printf("Reajuste ganho: %.2f\n",ajuste);
	    printf("Em percentual: 7 %%\n");
	}
	else if(salario>2000)
	{
	    ajuste=salario*4/100;
	    printf("Novo salario: %.2f\n",salario+ajuste);
	    printf("Reajuste ganho: %.2f\n",ajuste);
	    printf("Em percentual: 4 %\n");
	}

	return 0;
}
```