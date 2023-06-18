![image](https://github.com/lufffe/Beecrowd/assets/90646635/f14f71f5-fd00-44dd-a317-4fcc7fbb9832)

>C

	#include <stdio.h>

	int main()
	{
	    int dias,resto,anos,meses;

	    scanf("%d",&dias);

	    if(dias>=365)
	    {
		anos = dias / 365 ;
		resto = dias % 365 ;
		meses = resto / 30 ;
		dias = resto % 30;
		printf("%d ano(s)\n%d mes(es)\n%d dia(s)\n",anos,meses,dias);
	    }else if(dias>=30)
	    {
			meses = dias / 30;
			dias = dias % 30 ;
			printf("0 ano(s)\n%d mes(es)\n%d dia(s)\n",meses,dias);
		}
		else
			printf("0 ano(s)\n0 mes(es)\n%d dia(s)\n",dias);
	}

>PYTHON

	dias = input()
	dias = int(dias)

	if(dias>=365):
	    ano = dias // 365
	    resto = dias % 365
	    meses = resto // 30
	    dias = resto % 30
	    print(f"{ano} ano(s)\n{meses} mes(es)\n{dias} dia(s)")

	elif(dias>=30):
	    meses = dias // 30
	    dias = dias % 30
	    print(f"0 ano(s)\n{meses} mes(es)\n{dias} dia(s)")
	else:
	    print(f"0 ano(s)\n0 mes(es)\n{dias} dia(s)")
