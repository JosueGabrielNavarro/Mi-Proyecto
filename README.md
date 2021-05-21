# Mi-Proyecto
Hola, voy a mostrar mi mini proyecto. Empece hace poco a c++ y solo es un programa que calcula el IVA de un producto pequeño.


/*Escibir un programa que:
1. Lea de la entrada estandar el precio de un producto
2. Muestre en la salida estandar el precio del producto aplicandole el IVA (El Impuesto de valor agregado).
en mi pais si quieres calcular un precio sin IVA*/

#include <iostream>

using namespace std;

int main()
{
    float pdt = 0;    //PDT es el producto que agregare.
    float IVA = 0.07; // Para no agregar otro numero y agregar mas espacio agrego el IVA con su respectiva ecuacion.

    cout << "Agrege el precio del producto: ";
    cin >> pdt; //pido el precio del producto

    float IvA = pdt * IVA;
    float rst = pdt + IvA;

    cout << "El precio de el producto con IVA agregado es de: " << rst;

    return 0;
}
