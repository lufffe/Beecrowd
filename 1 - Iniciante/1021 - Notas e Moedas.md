![image](https://github.com/lufffe/Beecrowd/assets/90646635/19418cf6-af68-4b23-9a56-038cd46526fc)

>PYTHON

    notas = [100,50,20,10,5,2]
    moedas =[1,0.50,0.25,0.10,0.05,0.01]
    valor = float(input())
    print("NOTAS:")
    for c in notas:   
        if(valor>=c):       
            qtd=valor//c        
            valor = valor%c        
            print(f"{int(qtd)} nota(s) de R$ {float(c):.2f}")    
        else:        
            print(f"0 nota(s) de R$ {c:.2f}")
    print("MOEDAS:")
    for c in moedas:    
        valor = float('%.2f'% valor)
        if(valor>=c):
            if(c == 0.01):
                qtd = valor * 100        
            else:            
                qtd=valor//c            
                valor = valor%c          
            print(f"{int(qtd)} moeda(s) de R$ {c:.2f}")    
        else:
            print(f"0 moeda(s) de R$ {c:.2f}")
