# Cuaderno

#### Fecha: 21 - 11 - 2022

# Lenguaje C
* Su compilador hace análisis sintácticos y semánticos.
    * Sintactico: Plabras reservadas, comandos.
    * Semático: Que tenga sentido.
* En la parte superior, en la cabecera del archivo, van las librerias.
* Extensión de las librerias: lib (*.h)
* Hay librerias integradas (vienen con el propio lenguaje), también librerias de terceros, o incluso, las puedo crear yo.
* <> se usa para llamar al as librerias.
* Debajo de las librerias van las variables globales/declaraciones de funciones o procesos.
* Siempre debe ir el main()
    * El main es una función.
    * Dentro de los paréntesis van los parámetros de la función.


# Variables en C
### Nombres de las variables
* El nombre puede contener letras, dígitos o guión bajo.
* El primer carácter del nombre debe ser una letra o guión bajo, no un número.
* No se pueden usar nombres de palabras reservadas.
* Tiene importancia el uso de mayúsculas o minúsculas.
---
---

#### Fecha: 21 - 11 - 2022
# Sumar 2 números
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

1. Pseudocódigo.
2. Diagrama de flujo.
3. Codificar/Programar C.
4. Trace/Seguimiento.

# Conocer el Área de un rectángulo
* Conocer como resolver el problema antes de codear
1. Realizar el pseudocódigo
    * Imprimir por pantalla: "Ingrese la base del rectángulo"
    * Leer base
    * Imprimir por pantalla: "Ingrese la altura del rectángulo"
    * Area = base * altura
    * Imprimir por pantalla: "El área es: Area"
2. Diagrama de Flujo.
3. Codificar el programa.
4. Realizar el trace.
---
---

#### Fecha: 23 - 11 - 2022

# El mayor de 2 números

``` C

```
---
---

#### Fecha: 06 - 12 - 2022

# Área de un rectángulo 

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



