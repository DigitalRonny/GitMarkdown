# Cuaderno

#### Fecha: 21 - 11 - 2022

# Lenguaje C
* Su compilador hace an�lisis sint�cticos y sem�nticos.
    * Sintactico: Plabras reservadas, comandos.
    * Sem�tico: Que tenga sentido.
* En la parte superior, en la cabecera del archivo, van las librerias.
* Extensi�n de las librerias: lib (*.h)
* Hay librerias integradas (vienen con el propio lenguaje), tambi�n librerias de terceros, o incluso, las puedo crear yo.
* <> se usa para llamar al as librerias.
* Debajo de las librerias van las variables globales/declaraciones de funciones o procesos.
* Siempre debe ir el main()
    * El main es una funci�n.
    * Dentro de los par�ntesis van los par�metros de la funci�n.


# Variables en C
### Nombres de las variables
* El nombre puede contener letras, d�gitos o gui�n bajo.
* El primer car�cter del nombre debe ser una letra o gui�n bajo, no un n�mero.
* No se pueden usar nombres de palabras reservadas.
* Tiene importancia el uso de may�sculas o min�sculas.
---
---

#### Fecha: 21 - 11 - 2022
# Sumar 2 n�meros
``` C
#include <stdio.h>
void main()
{
    int n1, n2, respuesta;
    n1=0;
    n2=0;
    respuesta = n1 + n2;
    printf("La suma es:%i",rta)
}
```
# Algoritmia
* Procedimiento paso a paso para conseguir un fin o resolver un problema.

1. Pseudoc�digo.
2. Diagrama de flujo.
3. Codificar/Programar C.
4. Trace/Seguimiento.

# Conocer el �rea de un rect�ngulo
* Conocer como resolver el problema antes de codear
1. Realizar el pseudoc�digo
    * Imprimir por pantalla: "Ingrese la base del rect�ngulo"
    * Leer base
    * Imprimir por pantalla: "Ingrese la altura del rect�ngulo"
    * Area = base * altura
    * Imprimir por pantalla: "El �rea es: Area"
2. Diagrama de Flujo.
3. Codificar el programa.
4. Realizar el trace.
---
---

#### Fecha: 23 - 11 - 2022

# El mayor de 2 n�meros

``` C

```
---
---

#### Fecha: 06 - 12 - 2022

# �rea de un rect�ngulo 

```C
#include <stdio.h>

/*
* @autor    : DigitalRonny
* @date     : 6.dic.2022
* @details  : Determinar el area de un rectangulo
*/

int main()
{   //declaras e inicializar las variables

    int longitud = 0, ancho = 0, area_rectangulo = 0;

	printf("Ingrese la longitud: ");
    scanf("%i", &longitud);

    printf("Ingrese el ancho: ");
    scanf("%i", &ancho);

    area_rectangulo = longitud * ancho;

    printf("El area del rectangulo es: %i \n", area_rectangulo);
    printf("El area del rectangulo de ancho %i ylongitud %i es %i", ancho,longitud, area_rectangulo);

	return (0);
}
```



