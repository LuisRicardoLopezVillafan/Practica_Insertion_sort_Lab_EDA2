# Practica 1. Algoritmos de ordenamiento.
## Insertion Sort
La práctica consta de un ejercicio, las instrucciones del cual se presentan a continuación. 
**Fecha de entrega: Viernes 22 de agosto de 2025**
 
### Ejercicio 1 
Se quiere definir un programa que, dada una matriz cuadrada con valores enteros, se devuelva una permutación de los valores de modo que cada renglón está ordenado _de menor a mayor_, y de forma que los todos los elementos del segundo renglón (de arriba para abajo) sean mayores que los del primer renglón, los del tercero más grandes que los del segundo, etc. La condición que se debe de satisfacer es la siguiente: Cuando se ordenan los elementos de un renglón, por cada elemento de dicho arreglo lineal, se mueven todos los correspondientes elementos que se encuentran por debajo en la misma columna.

Finalmente, se pueden ordenar las columnas de manera individual (es decir, sin afectar a las otras columnas) para lograr que se cumpla la condición del orden entre renglones diferentes.

---

### Ejemplo

Supongamos la matriz inicial:

$$
\begin{bmatrix}
9 & 2 & 7 \\
4 & 6 & 3 \\
5 & 1 & 8
\end{bmatrix}
$$

Primero ordenamos el primer renglón (moviendo consigo los elementos de la misma columna):

$$
\begin{bmatrix}
2 & 7 & 9 \\
6 & 3 & 4 \\
1 & 8 & 5
\end{bmatrix}
$$

Luego ordenamos el segundo renglón bajo la misma regla:

$$
\begin{bmatrix}
2 & 7 & 9 \\
3 & 4 & 6 \\
8 & 5 & 1
\end{bmatrix}
$$

Finalmente, ordenamos el tercer renglón:

$$
\begin{bmatrix}
2 & 7 & 9 \\
3 & 4 & 6 \\
1 & 5 & 8
\end{bmatrix}
$$

El resultado buscado es que cada renglón está ordenado de menor a mayor, y los elementos de un renglón son menores que los del siguiente.

---
Trabaja sobre el documento "main.c" que se encuentra en este repositorio para la implementación de tu algoritmo.
