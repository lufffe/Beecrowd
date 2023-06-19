![image](https://github.com/lufffe/Beecrowd/assets/90646635/52a3a791-ff33-45f7-9702-e521359b59b3)

>C

	#include<stdio.h>

	int main()
	{

	    int valores[6],i,valor,limite;

	    scanf("%d",&valor);

	    limite = valor+11 ; 

	    for(i=valor;i<=limite;i++)
	    {
		if(i%2 != 0)
			printf("%d\n",i);
	    }

		return 0;
	}
