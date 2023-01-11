># **MATRIZ**
  *Llumiquinga Nahomy*

  **Fecha:** *13 de diciembre del 2022*

### **Matrices**
---
Puede almacenar varias variables del mismo tipo en una estructura de datos de matriz.

Puede ser una matriz unidimensional, multidimensional o escalonada.

![](imagenes\ma.PNG)

El número de dimensiones y la longitud de cada dimensión se establecen al crear la instancia de matriz. No se pueden cambiar estos valores durante la vigencia de la instancia.
### **Letra N**
---
    #include <stdio.h>

    int main()

    {
    int fila = 6, columna = 6;

    int mc[6][6]=  {
                         {0, 0, 0, 0, 0, 0}
                        ,{0, 0, 0, 0, 0, 0}
                        ,{0, 0, 0, 0, 0, 0}
                        ,{0, 0, 0, 0, 0, 0}
                        ,{0, 0, 0, 0, 0, 0}
                        ,{0, 0, 0, 0, 0, 0}
                
                    };
    printf("Letra N \n");
        for (int f = 0; f < fila; f++)
    {
        for (int c = 0; c < columna; c++)
            
            if (c == 0 || f == c || c == 5)
            printf("%i ",mc[f][c]);

            else
            printf("  ");
        printf(" \n");
        
    }
    }