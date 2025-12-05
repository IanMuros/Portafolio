# ADA 03: Procesamiento de Datos y Archivos CSV

## 1. Descripción General
Esta actividad se centró en la persistencia de datos y la manipulación de grandes volúmenes de información. Se implementó un programa en C++ capaz de leer una base de datos de películas almacenada en formato **CSV (Comma Separated Values)**.

El sistema lee el archivo `Movies.csv`, realiza el "parsing" (análisis sintáctico) de cada línea separando los campos por comas, y carga la información en estructuras de datos en memoria (Structs o Clases) para permitir búsquedas y ordenamientos.

## 2. Competencias Desarrolladas
* Uso de la librería `fstream` para lectura/escritura de archivos.
* Manipulación de cadenas (`string`, `stringstream`).
* Algoritmos de búsqueda y ordenamiento aplicados a registros.

## 3. Estructura del Directorio
* `Problema01/ADA03.cpp`: Código fuente del gestor de películas.
* `Problema01/Movies.csv`: Base de datos de prueba.

## 4. Reflexión Personal
**Aprendizajes clave:**
Aprendí cómo los sistemas reales interactúan con bases de datos planas. Fue interesante ver cómo se transforma una línea de texto simple en un objeto con atributos (Título, Año, Género) dentro del código.

**Retos enfrentados:**
El mayor problema fue la limpieza de datos (Data Sanitization). Algunas películas contenían comas dentro de sus títulos, lo que rompía la lógica de separación por comas del CSV. Tuve que implementar una lógica especial para ignorar comas que estuvieran dentro de comillas.
