```
#Pergunta:

Neste problema, você deverá ler 3 palavras que definem o tipo de animal possível segundo o esquema abaixo, da esquerda para a direita.  Em seguida conclua qual dos animais seguintes foi escolhido, através das três palavras fornecidas.
```

```
#Resposta:

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
```