```
#Pergunta:

Leia um valor inteiro X (1 <= X <= 1000). Em seguida mostre os ímpares de 1 até X, um valor por linha,
inclusive o X, se for o caso.
```

```
#Resposta:

int main()
{

int valores[6],i,valor;

scanf("%d",&valor);
if((valor>=1) && (valor<=1000)){
	for(i=0;i<=valor;i++)
	{
		if(i%2 != 0)
		{
			printf("%d\n",i);
		}
	}
}
	return 0;
}
```