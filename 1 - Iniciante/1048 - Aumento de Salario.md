![image](https://github.com/lufffe/Beecrowd/assets/90646635/884165a5-344d-4949-9fc2-c0f862c3e50c)

>C

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

>PYTHON 3.9

	salario=float(input())

	if(salario<=400):
	    ajuste=salario*15/100
	    print(f"Novo salario: {salario+ajuste:.2f}")
	    print(f"Reajuste ganho: {ajuste:.2f}")
	    print("Em percentual: 15 %")
	elif(salario>400 and salario<=800):
	    ajuste=salario*12/100
	    print(f"Novo salario: {salario+ajuste:.2f}")
	    print(f"Reajuste ganho: {ajuste:.2f}")
	    print("Em percentual: 12 %")
	elif(salario>800 and salario<=1200):
	    ajuste=salario*10/100
	    print(f"Novo salario: {salario+ajuste:.2f}")
	    print(f"Reajuste ganho: {ajuste:.2f}")
	    print("Em percentual: 10 %")
	elif(salario>1200 and salario<=2000):
	    ajuste=salario*7/100
	    print(f"Novo salario: {salario+ajuste:.2f}")
	    print(f"Reajuste ganho: {ajuste:.2f}")
	    print("Em percentual: 7 %")
	elif(salario>2000):
	    ajuste=salario*4/100
	    print(f"Novo salario: {salario+ajuste:.2f}")
	    print(f"Reajuste ganho: {ajuste:.2f}")
	    print("Em percentual: 4 %")
