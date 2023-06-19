![image](https://github.com/lufffe/Beecrowd/assets/90646635/235b383a-1683-499d-81ce-e36f782afb93)

>C

	int main()
	{
	    int valores[6],i,valor;

	    scanf("%d",&valor);
	    if((valor>=1) && (valor<=1000))
	    {
		for(i=0;i<=valor;i++)
		{
			if(i%2 != 0)
				printf("%d\n",i);
		}
	    }
		return 0;
	}

>PYTHON 3.9

	valor = int(input())

	lista=[]

	if(valor>=1 and valor<=1000):

	    for val in range(1,valor+1):

		if(val%2 != 0):
		    print(val)
