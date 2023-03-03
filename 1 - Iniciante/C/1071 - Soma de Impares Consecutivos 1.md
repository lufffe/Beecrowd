```
#Pergunta:

Leia 2 valores inteiros X e Y. A seguir, calcule e mostre a soma dos números impares entre eles.
```

```
#Resposta:

#include<stdio.h>

int main()
{

int a,b,total,i;

scanf("%d",&a);
scanf("%d",&b);
total=0;

if(a<b){
	a=a+1;
	for(i=a;i<b;i++){
		if(i%2!=0)
		total=total+i;
	}
}else{
	b=b+1;
	for(i=b;i<a;i++){
		if(i%2!=0)
		total=total+i;
	}
}

printf("%d\n",total);

	return 0;
}
```