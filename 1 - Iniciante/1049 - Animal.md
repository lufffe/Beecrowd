![image](https://github.com/lufffe/Beecrowd/assets/90646635/0bbeddb7-a307-4115-92e6-48e3b846a9a4)

>C

	#include<stdio.h>
	#include<string.h>

	int main()
	{
		char animal1[20];
		char animal2[20];
		char animal3[20];

		scanf("%s", animal1);
		scanf("%s", animal2);
		scanf("%s", animal3);

		if(strcmp(animal1, "vertebrado")==0)
		{
			if(strcmp(animal2, "ave")==0)
			{
				if(strcmp(animal3, "carnivoro")==0)
					printf("aguia\n");
				else
					printf("pomba\n");
			}
			else
			{
				if(strcmp(animal2, "mamifero")==0)
				{
					if(strcmp(animal3, "onivoro")==0)
						printf("homem\n");
					else
						printf("vaca\n");
				}
			}

		}
		else if(strcmp(animal1, "invertebrado")==0)
		{

			if(strcmp(animal2, "inseto")==0)
			{
				if(strcmp(animal3, "hematofago")==0)
					printf("pulga\n");
				else
					printf("lagarta\n");
			}
			else
			{
				if(strcmp(animal2, "anelideo")==0)
				{
					if(strcmp(animal3, "hematofago")==0)
						printf("sanguessuga\n");
					else
						printf("minhoca\n");
				}
			}
		}

		return 0;
	}

>PYTHON 3.9

	v1 = input()
	v2 = input()
	v3 = input()

	if(v1=='vertebrado'):
	    if(v2=='ave'):
		if(v3=='carnivoro'):
		    print("aguia")
		else:
		    print("pomba")
	    else:
		if(v3=='onivoro'):
		    print("homem")
		else:
		    print("vaca")
	else:
	    if(v2=='inseto'):
		if(v3=='hematofago'):
		    print("pulga")
		else:
		    print("lagarta")
	    else:
		if(v3=='hematofago'):
		    print("sanguessuga")
		else:
		    print("minhoca")
