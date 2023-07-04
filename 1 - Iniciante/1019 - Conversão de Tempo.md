![image](https://github.com/lufffe/Beecrowd/assets/90646635/36e05ceb-e4ae-483b-b8b7-3d7712beaf54)

>C
```C
#include <stdio.h>

int main()
{
	int tempo,resto,horas,minutos,segundos;

	scanf("%d",&tempo);
	if(tempo>=3600)
	{
		horas = tempo / 3600 ;
		resto = tempo % 3600 ;
		minutos = resto / 60 ;
		segundos = resto % 60;
		printf("%d:%d:%d\n",horas,minutos,segundos);
	}
	else if(tempo>=60)
	{
		minutos = tempo / 60;
		segundos = tempo % 60 ;
		printf("0:%d:%d\n",minutos,segundos);
	}
	else
		printf("0:0:%d\n",tempo);
}
```

>PYTHON 3.9
```Python 3.9
tempo = int(input())

if(tempo>3600):
	hora = tempo // 3600
	resto = tempo % 3600
	minutos = resto // 60
	segundos = resto % 60
	print(f"{hora}:{minutos}:{segundos}")

elif(tempo>60):
	minuto = tempo // 60
	segundos = tempo % 60
	print(f"0:{int(minuto)}:{segundos}")
else:
	print(f"0:0:{tempo}")
```
