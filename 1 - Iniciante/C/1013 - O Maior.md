![image](https://github.com/lufffe/Beecrowd/assets/90646635/7bed0051-cf4c-4562-852a-07f4bced2144)

>C

	#include <stdio.h>

	int main() 
	{
		int a,b,c ;
		scanf("%d",&a);
		scanf("%d",&b);
		scanf("%d",&c);

		if(a>c && a>b)
			printf("%d eh o maior\n",a);
		else if(b>c)
			printf("%d eh o maior\n",b);
		else if (c>b)
			printf("%d eh o maior\n",c);
		return 0;
	}

>PYTHON

	a,b,c = input().split()
	a,b,c = int(a),int(b),int(c)

	if (a>c) and (a>b):
	    print(f"{a} eh o maior")
	elif (b>c):
	    print(f"{b} eh o maior")
	else:    
	    print(f"{c} eh o maior")
