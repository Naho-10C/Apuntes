># **TEMA DE EVALUACION**
  *Llumiquinga Nahomy*

  **Fecha:** *23 de diciembre del 2022*

### **Crear una barra de loaging:**
---
    # incluir < iostream >
    # incluir < conio.h >
    # incluir < ventanas.h >
    # incluir < dos.h >
    utilizando el espacio de  nombres  estándar ;
    int principal ()
    {
    sistema ( " cls " );
        para ( int i= 1 ;i<= 50 ;i++)
            { sistema ( " cls " );
    cout<< " \t Cargando " << 2 *i<< " % \n\t " ; 
    para ( int j= 1 ;j<=i;j++)
    cout<< " \xB2 " ;
    SI (I> 1 && I< 20 )
    cout<< " \n\n\t\t creando archivos temporales " ;
    Si No (I> 20 && I< 40 )
    cout<< " \n\n\t\t Accediendo a la Memoria Principal " ;
    Si No (I> 40 && I< 48 )
    cout<< " \n\n\t\t Caché de Acceso " ;
    else cout<< " \n\n\t\t Completado. Presiona enter para continuar " ;
    Sueño ( 150 - i* 3 );
    }
    obtener ();
    devolver  0 ;
    }