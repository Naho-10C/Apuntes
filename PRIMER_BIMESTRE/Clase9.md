># **DETERMINAR EL AREA DE UN RECTANGULO**
  *Llumiquinga Nahomy*

  **Fecha:** *23 de noviembre del 2022*

### **Algoritmia**
---  
Ejemplo ejecutado en clase
![](imagenes\rec.PNG)

### **Código**
---  
    #include <stdio.h>

    int main()
    {
    int base, altura, area;

    printf("\n <<Area del rectangulo>> \n");
    printf("Base del rectangulo: ");
    scanf("%i", &base);

    printf("Altura del rectangulo: ");
    scanf("%i", &altura);

    area = altura * base;

    printf("El area del rectangulo es: %i",area);

    return 0;

    }