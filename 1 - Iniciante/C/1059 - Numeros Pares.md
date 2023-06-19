![image](https://github.com/lufffe/Beecrowd/assets/90646635/3d5b04af-3fde-4682-8d40-3d6ac69c496b)

>C

	#include<stdio.h>

	int main()
	{
		int i;

	    for(i=0;i<=100;i++)
	    {
		if((i%2)==0)
		{
			if(i>0 && i<=100)
				printf("%d\n",i);
		}
	    }	
	    return 0;
	}

>PYTHON 3.9

	for i in range(0,101):
	    if((i%2)==0) and (i>0) and (i<=100):
		print(i)
