```
#Pergunta:

Neste problema, você deverá ler 3 palavras que definem o tipo de animal possível segundo o esquema abaixo, 
da esquerda para a direita.  Em seguida conclua qual dos animais seguintes foi escolhido, 
através das três palavras fornecidas.
```

```
#Resposta:

#include<stdio.h>
#include<string.h>

int main(){
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
			{
				printf("aguia\n");
			}
			else
			{
				printf("pomba\n");
			}
		}
		else
		{
			if(strcmp(animal2, "mamifero")==0)
			{
				if(strcmp(animal3, "onivoro")==0)
				{
					printf("homem\n");
				}
				else
				{
					printf("vaca\n");
				}
			}
		}
		
	}
	else if(strcmp(animal1, "invertebrado")==0)
	{
	
		if(strcmp(animal2, "inseto")==0)
		{
			if(strcmp(animal3, "hematofago")==0)
			{
				printf("pulga\n");
			}
			else
			{
				printf("lagarta\n");
			}
		}
		else
		{
			if(strcmp(animal2, "anelideo")==0)
			{
				if(strcmp(animal3, "hematofago")==0)
				{
					printf("sanguessuga\n");
				}
				else
				{
					printf("minhoca\n");
				}
			}
		}
	}
	
	return 0;
}
```
