# Minicomputadora Didáctica
La idea del proyecto es realizar una minicomputadora didáctica que permita al usuario utilizar diferentes actividades relacionadas con letras, números, lógica y juegos

## Integrantes

Sebastian Obando

Julian Solano

Anthony Gamboa

Brandon Guido

## Objetivo

El objetivo es desarrollar una aplicación de consola utilizando Lucia donde el usuario pueda seleccionar diferentes actividades educativas

También se busca practicar el uso de funciones, condiciones, ciclos, validaciones y la organización del código

## Estructura del proyecto

```text
Akatsuki_tarea1

main.lucia

src
bosqueLetras.lucia
adivinaelnumero.lucia
cualSobra.lucia
letraintrusa.lucia
quegrande.lucia

README.md
```

El archivo `main.lucia` es el archivo principal del programa

La carpeta `src` se utiliza para guardar funcionalidades que se encuentran separadas del archivo principal

## Cómo ejecutar

Descargar o clonar el repositorio

Abrir Lucia Editor

Abrir la carpeta del proyecto

Verificar que el archivo principal sea `main.lucia`

Guardar los archivos

Ejecutar utilizando `F5`

También se debe tener configurada correctamente la ruta del ejecutable de Lucia dentro del editor

## Funcionalidades

El programa contiene las siguientes categorías

### Letras

Bosque de letras

Completa la palabra

Letra intrusa

### Números

Ordena los números

Mayor y menor

Adivina el número

### Lógica

Cuál sobra

### Juegos

Qué grande

## Menú principal

El programa muestra un menú donde el usuario puede seleccionar la categoría que desea utilizar

```text
------------------------------------
    MINICOMPUTADORA DIDACTICA
------------------------------------

Letras
Numeros
Logica
Juegos
Salir
```

También se incluye una opción para salir del programa

## Bosque de letras

En esta actividad el usuario debe escribir una letra

El programa muestra una palabra que inicia con la letra seleccionada

Ejemplo

```text
Digite una letra

M

M de MANZANA
```

También se valida que la entrada sea una letra

Ejemplo

```text
Digite una letra

123

Entrada invalida
Debe ingresar una letra
```

Esta funcionalidad se encuentra separada en el archivo

```text
src/bosqueLetras.lucia
```

## Completa la palabra

En esta actividad primero se muestra una palabra completa

Después se muestra nuevamente la palabra pero con una letra faltante

El usuario debe escribir la letra correcta

Ejemplo

```text
Palabra completa CASA

Completa la palabra

C _ S A

Digite la letra que falta

A

Excelente respuesta correcta
```

Se utilizan varias palabras diferentes para realizar la actividad


## Adivina el numero
En esta actividad se muestra una secuencia de 4 numeros generados de manera aleatoria

Uno de los numeros esta oculto y se representa con el simbolo ?

El usuario debe adivinar cual es el numero oculto

Ejemplo

```text
Ronda 1 de 3:
7 12 ? 3

Cual es el numero oculto?
9

Felicidades, acertaste!
```

Se generan 3 rondas con secuencias diferentes en cada partida

## Que grande

En esta actividad se muestran los nombres de tres animales

El usuario debe indicar cual de los tres animales es el mas grande

Ejemplo

```text
Ronda 1 de 3: cual es el animal mas grande?
1. Elefante
2. Perro
3. Hormiga

Escribe el numero de tu respuesta:
1

Felicidades, acertaste!
```

Se presentan 3 conjuntos de animales diferentes en cada partida

## Letra intrusa

En esta actividad se muestra una secuencia de 4 letras del alfabeto.

Las letras deberían seguir un orden correcto, pero una de ellas no pertenece a esa secuencia.

El usuario debe indicar cuál es la letra que no pertenece.

Ejemplo

Secuencia de letras: A-B-R-D

Digite cual es la letra que no pertenece a la secuencia

R

¡Excelente! respuesta correcta

Se presentan 3 secuencias diferentes para realizar la actividad

## Cual sobra?

En esta actividad se muestra una secuencia de 4 simbolos numerados.

Tres de los simbolos son iguales y uno es diferente.

El usuario debe indicar la posicion del simbolo que sobra.

Ejemplo

Secuencia de simbolos:
1- /, 2- /
3- =, 4- /

Digite la posicion del simbolo que sobra

3

¡Excelente! respuesta correcta

Se presentan 3 conjuntos de simbolos diferentes para realizar la actividad

### a. Ordena los números
Genera 4 números aleatorios entre 1 y 99 y se los muestra al usuario. El usuario debe
ingresar los 4 números en el orden que él cree correcto (de mayor a menor). Internamente,
el programa calcula el orden correcto usando un algoritmo de ordenamiento burbuja sobre
una copia de la lista original, y compara posición por posición contra lo que el usuario
digitó. Si coinciden todas las posiciones, gana; si no, se le indica que lo intente de nuevo.

### b. Mayor y menor
Genera 3 números aleatorios (A, B, C) y elige al azar si le va a preguntar por el mayor
o por el menor. El programa calcula ambos valores (mayor y menor) recorriendo los tres
números con comparaciones simples, guardando también la letra correspondiente en
mayúscula y minúscula para aceptar cualquiera de las dos formas como respuesta válida.
Compara la respuesta del usuario contra la letra correcta y muestra el resultado.

Ambas funciones devuelven un valor `bool` (`true` si el usuario ganó, `false` si no),
para que el menú principal pueda reutilizar ese resultado si se necesita más adelante.


## Organización del código

El proyecto utiliza `main.lucia` como archivo principal

Dentro del archivo principal se encuentran los menús de Letras, Números, Lógica y Juegos

Las funcionalidades que se quieran separar pueden colocarse dentro de la carpeta `src`

La idea es mantener el código organizado y que cada integrante pueda trabajar en una parte diferente sin modificar demasiado el código de los demás

## Validaciones

El programa valida diferentes entradas del usuario

Se revisan las opciones ingresadas en los menús

También se revisa si el usuario ingresa números o letras dependiendo de lo que solicita cada actividad

Cuando una entrada no es válida se muestra un mensaje al usuario

Ejemplo

```text
Seleccione una opcion

ABC

Debe ingresar un numero
```

## Pruebas

Se realizarán diferentes pruebas para comprobar que las actividades funcionen correctamente

Se probarán respuestas correctas

Respuestas incorrectas

Opciones no válidas

Entradas de texto donde se esperan números

Entradas numéricas donde se esperan letras

Navegación entre los diferentes menús

Salida correcta del programa

Los pantallazos de las pruebas se incluirán en el documento PDF solicitado para la entrega

## Diagrama de clases

El diagrama de clases se agregará posteriormente al proyecto

La imagen se guardará dentro de la carpeta `docs`


<img width="1212" height="742" alt="Clases lucia drawio" src="https://github.com/user-attachments/assets/041c97e9-b6d5-4989-b0b6-51dfad9a9df0" />



## Diagrama de casos de uso

El diagrama de casos de uso también se agregará posteriormente

La imagen se guardará dentro de la carpeta `docs`

<img width="1162" height="832" alt="Casos de uso Lucia drawio" src="https://github.com/user-attachments/assets/abf7e9a8-ddb3-4e0c-89a2-87e059973b88" />



## Mejoras para una versión 2.0

Agregar más palabras y ejercicios

Agregar diferentes niveles de dificultad

Agregar un sistema de puntos

Agregar más actividades

Seleccionar algunas preguntas de manera aleatoria

Guardar la cantidad de respuestas correctas e incorrectas

Agregar más validaciones

Mejorar la organización de los módulos

## Tecnologías utilizadas

Lucia

Lucia Editor

Git

GitHub

## Repositorio

El proyecto se encuentra en un repositorio público de GitHub

https://github.com/SebastianObandoR/Akatsuki_tarea1

## Estado del proyecto

El proyecto se encuentra completo con todos sus modulos
