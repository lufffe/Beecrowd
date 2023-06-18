![image](https://github.com/lufffe/Beecrowd/assets/90646635/f9d45db7-ab01-4823-a759-45f4d2fb360c)

>C

    #include <stdio.h>

    int main() 
    {
       double pi,r,volume;

       scanf("%lf",&r);
       pi = 3.14159;
       volume = ((4/3.0)*pi*pow(r,3));
       
       printf("VOLUME = %.3lf\n",volume);

       return 0;
    }


>PYTHON

    pi = 3.14159
    raio = float(input())
    area = (4/3)*pi*(raio**3)

    print(f"VOLUME = {area:.3f}")
