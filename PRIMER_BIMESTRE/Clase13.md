># **ARRAYS PROCEDIMIENTOS Y FUNCIONES**
  *Llumiquinga Nahomy*

  **Fecha:** *12 de diciembre del 2022*

### **Ejemplo**
---

    #include <stdio.h>
    #include <string.h>
    int suma();
    int sumaInt(int a, int b);
    void showConsola(int rta);
    flotador sumafloat(flotador a, flotador b);
    int sumaFantasma();
    int ValidarClave(char clave[])
    {
	char claveSecreta = "1234231";
	if(strcmp(clave, claveSecreta )==0)
    retorno 1;
    devolver 0;
    }
    void ValidarClaveArray( )
    {
	char contrasena[]="pato";
	char clave[]="pat1";
	int validador=1;
	for (int i = 0; i < sizeof(clave); i++)
		if (clave[i]!=contrasena[i])
			validador= 0;
	
	if(validador ==1)
    printf("clave correcta \n\n");
    más
    printf("clave incorrecta \n\n");
    }
    int main()
    {
	//ValidarClaveArray( );
	char key[]="1234231";
	if(ValidarClave(key)==0)
    printf("clave correcta \n\n");
    más
    printf("clave incorrecta \n\n");
	////////////////////////////////////////
	int rta = suma();
	printf("La suma es: %i \n", rta  );
	rta = sumaInt(5,8);
	printf("La suma es: %i \n", rta  );
	printf("La suma es: %.2f \n", sumafloat(5.5,8.12354)  );
	showConsola(sumaInt(5,8));
	
    retorno (0);
    }
    //procedimiento
    void showConsola(int rta)
    {
	printf("La suma es: %i \n", rta  );
    }
    //función
    int suma()
    {
	int a =10,b=20, r =0;
	r= a+b;
     retorno r;
    }
    int sumaInt(int a, int b)
    {
    devolver a+b;
    }
    float sumafloat(float a, float b)
    {
    devolver a+b;
    }

