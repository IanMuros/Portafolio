# ADA 01: Analizador de Expresiones Aritméticas (Pilas)

## 1. Descripción General
En esta actividad se desarrolló una aplicación en C++ que implementa la estructura de datos lineal **Pila (Stack)**. El propósito principal del software es procesar expresiones matemáticas complejas, convirtiéndolas de su notación habitual (Infija) a notación Polaca Inversa (Postfija) para su posterior evaluación computacional.

El programa es capaz de leer un archivo de texto (`infijas.txt`), analizar la jerarquía de operadores (parentesis, potencias, multiplicación/división, suma/resta) y calcular el resultado final.

## 2. Competencias Desarrolladas
* Implementación de la estructura de datos abstracta (TDA) tipo Pila.
* Comprensión del algoritmo de "Shunting Yard" o similares para el ordenamiento de tokens.
* Manejo de entrada y salida de archivos de texto en C++.

## 3. Estructura del Directorio
* `Problema01/InfijoAPostfijoApp.cpp`: Código fuente principal.
* `Problema01/infijas.txt`: Archivo de prueba con las expresiones matemáticas.

## 4. Reflexión Personal
**Aprendizajes clave:**
Durante el desarrollo de esta ADA, comprendí que las computadoras no leen las ecuaciones como nosotros (de izquierda a derecha buscando prioridades visualmente), sino que necesitan una estructura LIFO (Last In, First Out) para almacenar operadores temporalmente. Aprendí a manipular los métodos `push`, `pop` y `top`.

**Retos enfrentados:**
Uno de los mayores desafíos fue manejar correctamente los paréntesis anidados y asegurar que, al cerrar un paréntesis, se "desapilaran" los operadores correctos hasta encontrar el paréntesis de apertura correspondiente. También tuve que validar que la división por cero no cerrara el programa inesperadamente.
