![image](https://github.com/lufffe/Beecrowd/assets/90646635/8c313c8e-6b3b-410d-a1df-e2caed8b90ab)

    #include <stdio.h>

    int main() 
    {
        int tempo,vm;
        float litros;

        scanf("%d",&tempo);
        scanf("%d",&vm);
        
        litros = ((vm*tempo)/12.00);

        printf("%.3f\n",litros);

        return 0;
    }

>PYTHON 

    tempo = int(input())
    vm = int(input())
    auto = 12

    litros = (vm * tempo)/auto

    print(f"{litros:.3f}")
