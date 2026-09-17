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

## Funcionalidades pendientes

Todavía quedan por desarrollar las siguientes actividades

Letra intrusa

Ordena los números

Mayor y menor

Adivina el número

Cuál sobra

Qué grande

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


<img width="969" height="709" alt="image" src="https://github.com/user-attachments/assets/ef0ad1d8-975a-4b5f-8ae2-8058cb61ae53" />



## Diagrama de casos de uso

El diagrama de casos de uso también se agregará posteriormente

La imagen se guardará dentro de la carpeta `docs`


<img width="875" height="808" alt="image" src="https://github.com/user-attachments/assets/4cc68475-ac46-45cb-910a-ac122ef63263" />



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
