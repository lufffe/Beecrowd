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
