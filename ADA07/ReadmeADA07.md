# ADA 07: Árboles Binarios de Búsqueda (BST)

## 1. Descripción General
La actividad final del portafolio se centró en la implementación de **Árboles Binarios**. Esta estructura jerárquica consta de un nodo raíz donde cada nodo puede tener como máximo dos hijos (izquierdo y derecho).

Se desarrollaron algoritmos recursivos para:
1.  **Inserción:** Colocar valores menores a la izquierda y mayores a la derecha.
2.  **Recorridos:** Visualizar el árbol en Preorden, Inorden y Postorden.
3.  **Búsqueda:** Localizar valores eficientemente.

## 2. Estructura del Directorio
* `Problema01/ADA07_AP1.c++`: Implementación básica del Árbol y sus nodos.
* `Problema02/ADA07_AP2.C++`: Implementación de funcionalidades avanzadas y casos de prueba.

## 3. Reflexión Personal
**Aprendizajes clave:**
El concepto más importante fue la **recursividad**. Casi todas las operaciones en árboles se resuelven llamando a la misma función para el sub-árbol izquierdo y el derecho. Entendí cómo el recorrido "Inorden" en un árbol de búsqueda nos devuelve los datos ya ordenados automáticamente.

**Retos enfrentados:**
Visualizar la ejecución de las funciones recursivas fue complejo. Entender en qué momento la función "regresa" (backtracking) a la llamada anterior y cómo manejar los casos base (cuando se llega a una hoja nula) fue el mayor desafío de lógica en este curso.
