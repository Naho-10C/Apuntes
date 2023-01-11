># **TIENDA DE MASCOTAS**
  *Llumiquinga Nahomy*

  **Fecha:** *04 de enero del 2023*

### **Crear un menu C++**
---
### **Primera parte:**


    #include<iostream>
    #include<stdlib.h>
    #include<.. /lib/utility.h>
    #include<.. /lib/color.h> //se utlizaron librerias propias.
    utilizando el espacio de nombres std;
    void menu(){
    sistema("borrar")
    cout<<"COLOR_RED   "texto RED!;
    cout<<"------PET-SHOP-------"<<endl;
    cout<<"1. Agregar mascota"<<endl;
    cout<<"2. Lista de mascotas"<<endl;
    cout<<"3. Vender mascota"<<endl;
    cout<<"0. Salir"<<endl;
    do{
        opc=getNumber("Ingresa tu opc: ");
    }while (opc>3);
    opc de devolución;
    }
    void agregarPet(){cout<<"agregaPet...!"}
    void ListaPet(){cout<<"listaPet...!"}
    void venderPet(){cout<<"venderPet...!"}
    int main(){
    switch(menu()){
    Caso 1:
    }
    devolver 0;
    }
    void agregarPet(){
    cadena s;
    ifstream f (tatiananay);
    if(!f.is_open())
        cerr<<"error de abrir el archivo de mascotas"<<endl;
    más
    hacer
        {
            getline(f,s)
            cout<<s<<endl;
    } while (!f,eof());
    f.close();
        
    }
    void leerarchivo()
