># **CORRECCION WORKSHOP**
  *Llumiquinga Nahomy*

  **Fecha:** *20 de diciembre del 2022*

---
    #include <stdio.h>
    #include <stdlib.h>
    #define MAXTALLA 10
    #define PI 3.14
    int len = 0;
    int getNumber(char label[])
    {
    char numero[10];
    int n=0;
    do{
        printf("%s ", label);
        gets(numero);
    sscanf(numero,"%i \n", &n);
    }while (n <= 5);
    devolver n;
    }
    void DrawA(int tam, char caracter)
    {
    for (int f = 0; f < tam; f++)
    {
        for (int c = 0; c < tam; c++)
            if (c==0 || f ==0 || tam/2==f || c ==(tam -1))
                printf("%c",caracter);
    más
                printf(" ",c);
        printf("\n"); 
    }
    }
    void DrawL(int tam, char caracter, char m[][len])
    {
    for (int f = 0; f < tam; f++)
    {
        for (int c = 0; c < tam; c++)
    si (c==0 || f ==(tam -1))
    m[f][c]=caracter; printf("%c",caracter);
    más
    m[f][c]=' '; printf(" ",c);
    printf("\n"); 
    }
    }
    void DrawE(int tam, char caracter, char m[][len])
    {
    for (int f = 0; f < tam; f++)
    {
        for (int c = 0; c < tam; c++)
            if(f ==0 || c==0 || tam/2 == f || f== tam -1)
    m[f][c]= caracter; printf("%c ",caracter);
    más
    m[f][c]=' '; printf(" ");
    printf("\n");
    }
    }
    void DrawO(int tam, char caracter, char m[][len])
    {
    for (int f = 0; f < tam; f++)
    {
        for (int c = 0; c < tam; c++)
            if(f ==0 || c==0 || c== tam -1 || f== tam -1)
    m[f][c]= caracter; printf("%c ",caracter);
    más
    m[f][c]= ' '; printf(" ");
    printf("\n");
    }
    }
    void main( )
    { //PI = 3,1416;
    len = 12;
    len = getNumber("Ingresa un numeros mayor a 5 : ");
    char caracter = '+';
    char mL[len][len];
    char mE[len][len];
    char mO[len][len];
    DrawL(len, caracter, mL);
    DrawE(len, caracter, mE);
    DrawO(len, caracter, mO);
    sistema("clear");
    for (int f = 0; f < len; f++)
    {
        for (int c = 0; c < len; c++)
            printf("%c ",mL[f][c]);
        printf(" ");
       
        for (int c = 0; c < len; c++)
            printf("%c ",mE[f][c]);
        printf(" ");
        
        for (int c = 0; c < len; c++)
            printf("%c ",mO[f][c]);
        printf("\n");
    }
    sistema("pausa");
    }