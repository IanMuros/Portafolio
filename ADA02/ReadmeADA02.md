# ADA 02: Manejo de Memoria y Apuntadores en C

## 1. Descripción General
El objetivo fundamental de esta práctica fue profundizar en el manejo de **memoria dinámica** y el uso de **punteros (pointers)** en el lenguaje C. Estas herramientas son la base para construir estructuras de datos complejas (como listas y árboles) donde el tamaño de la información no se conoce en tiempo de compilación.

Se realizaron ejercicios prácticos para manipular direcciones de memoria, paso de parámetros por referencia y aritmética de punteros.

## 2. Detalles Técnicos
* **Lenguaje:** C Estándar.
* **Conceptos:** Punteros, `malloc`, `free`, Arreglos dinámicos.

## 3. Estructura del Directorio
* `Problema01/ADA02.c`: Archivo de código fuente con la resolución de los ejercicios.

## 4. Reflexión Personal
**Aprendizajes clave:**
Entendí la diferencia crucial entre trabajar con una copia de una variable (paso por valor) y trabajar con la dirección original de la variable (paso por referencia). Esto me permite crear funciones más eficientes que modifican los datos directamente en memoria sin necesidad de duplicarlos.

**Retos enfrentados:**
Al principio fue confuso diferenciar entre el operador de dirección (`&`) y el de indirección (`*`). También enfrenté errores de "Segmentation Fault" al intentar acceder a memoria que no había sido reservada correctamente o que ya había sido liberada.
