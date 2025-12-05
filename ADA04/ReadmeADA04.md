# ADA 04: Listas Enlazadas (Linked Lists)

## 1. Descripción General
En esta ADA se implementó una **Lista Enlazada Simple**, una de las estructuras de datos dinámicas más importantes. A diferencia de un arreglo estático, una lista enlazada permite que los elementos (nodos) estén dispersos en la memoria, conectados únicamente por punteros.

El programa permite realizar las operaciones CRUD básicas: Crear nodos, insertar al inicio o final, buscar elementos y eliminar nodos liberando la memoria correctamente.

## 2. Detalles Técnicos
* **Estructura del Nodo:** Datos + Puntero `next`.
* **Gestión de Memoria:** Asignación dinámica para cada nuevo nodo insertado.

## 3. Estructura del Directorio
* `Problema01/ADA04_E04.c`: Implementación de la lista en C.

## 4. Reflexión Personal
**Aprendizajes clave:**
Descubrí la flexibilidad de las listas enlazadas. A diferencia de los arrays, no necesito definir un tamaño límite al principio. Aprendí a "recorrer" la lista usando un puntero auxiliar que salta de nodo en nodo hasta llegar a `NULL`.

**Retos enfrentados:**
La lógica de los punteros es delicada. Tuve dificultades al implementar la función de eliminar un nodo intermedio, ya que es necesario conectar el nodo anterior con el siguiente antes de borrar el actual; si no se hace en ese orden, se pierde el resto de la lista (memory leak).
