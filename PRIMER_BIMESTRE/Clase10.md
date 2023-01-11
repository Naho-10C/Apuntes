># **BUCLES**
  *Llumiquinga Nahomy*

  **Fecha:** *06 de diciembre del 2022*

### **Bucle FOR**
---
![](imagenes\for.PNG)
### **Cuadrado utilizando el Bucle FOR**
---
    #include <stdio.h>

    int main()
    {
    int signo;

    printf("Dimension del cuadrado: ");
    scanf("%i", &signo);
    printf("\n");
    for (int f = 1; f <= signo; f++)
    {
        for (int c = 1; c <= signo; c++)
        {
            
            if (f==1||c==1||f==signo||c==signo)
            {
                if (c%2==0){
                    
                    if(f%2==0){printf("+ ");}
                    else{printf("- ");  }
                    }
                else{
                         if (f%2==0) { printf("- ");}
                        else{  printf("+ ");  }
                    }
            
                    
            } 
             else {printf("  ");}      
        }
       printf("\n");         
    }
    
    }