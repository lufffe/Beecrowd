![image](https://github.com/lufffe/Beecrowd/assets/90646635/6102ce4c-8c0b-49b6-ac6c-614edcca9954)

>C

	#include<stdio.h>

	int main()
	{
		float x,y;

		scanf("%f %f",&x,&y);

		if(x>0)
		{
	    		if(y>0)
				printf("Q1\n");
	    		else if(y<0)
				printf("Q4\n");
	    		else if(y==0)
				printf("Eixo X\n");
		}
		else if(x<0)
		{
	    		if(y>0)
				printf("Q2\n");
	    		else if(y<0)
				printf("Q3\n");
	    		else if(y==0)
				printf("Eixo X\n");
		}
		else if(x==0)
		{
	    		if(y!=0)
				printf("Eixo Y\n");
	    		else
				printf("Origem\n");
		}
	    return 0;
	}

>PYTHON 3.9

	x,y = map(float,input().split())

	if(x>0):
	    if(y>0):
		print("Q1")
	    elif(y<0):
		print("Q4")
	    elif(y==0):
		print("Eixo X")
	elif(x<0):
	    if(y>0):
		print("Q2")
	    elif(y<0):
		print("Q3")
	    elif(y==0):
		print("Eixo X")
	elif(x==0):
	    if(y!=0):
		print("Eixo Y")
	    else:
		print("Origem")
