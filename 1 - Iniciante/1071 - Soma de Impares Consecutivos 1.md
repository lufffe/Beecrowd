![image](https://github.com/lufffe/Beecrowd/assets/90646635/43bc19b3-f0fe-45df-b5a2-50e1b4443aad)

>C

	#include<stdio.h>

	int main()
	{
	    int a,b,total,i;

	    scanf("%d",&a);
	    scanf("%d",&b);
	    total=0;

	    if(a<b)
	    {
		a=a+1;
		for(i=a;i<b;i++)
		{
			if(i%2!=0)
			    total=total+i;
		}
	    }
	    else
	    {
		b=b+1;
		for(i=b;i<a;i++)
		{
			if(i%2!=0)
			    total=total+i;
		}
	    }

	    printf("%d\n",total);

		return 0;
	}
	
>PYTHON 3.9

	a = int(input())
	b = int(input())
	total= 0

	if(a<b):
	    for val in range(a+1,b):
		if(val%2 != 0):
		    total = total +val
	else:
	    for val in range(b+1,a):
		if(val%2 != 0):
		    total = total +val
		    
	print(total)
