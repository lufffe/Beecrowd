```
#Pergunta:

Leia 3 valores inteiros e ordene-os em ordem crescente. No final, mostre os valores em ordem crescente,
 uma linha em branco e em seguida, os valores na sequência como foram lidos.
```

```
#Resposta:

#include<stdio.h>

int main()
{
	int a,b,c,menor,medio,maior;
	
	scanf("%d %d %d",&a,&b,&c);

	if(a<b && a<c ){
		menor=a;
		if(b<c)
		{
			medio=b;
			maior=c;
		}
		else
		{
			medio=c;
			maior=b;
		}
	}
	else if(b<a && b<c )
	{
		menor=b;
		if(a<c)
		{
			medio=a;
			maior=c;
		}
		else
		{
			medio=c;
			maior=a;
		}
	}
	else if (c<a && c<b )
	{
		menor=c;
		if(b<a)
		{
			medio=b;
			maior=a;
		}
		else
		{
			medio=a;
			maior=b;
		}
	}
	printf("%d\n",menor);
	printf("%d\n",medio);
	printf("%d\n",maior);
	printf("\n");
	printf("%d\n",a);
	printf("%d\n",b);
	printf("%d\n",c);
    return 0;
}
```
