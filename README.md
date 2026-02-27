# PROYECTO 2: DFS iterativo usando una pila propia

## Objetivo
Implementar una Búsqueda en Profundidad (DFS) sin utilizar recursión, haciendo uso de una estructura de datos tipo Pila (Stack) con implementación propia.
--
## Requisitos Implementados
El código cumple con los 5 requisitos solicitados para la evaluación:
1. **Clase Stack:** Implementación propia de una pila con las operaciones 
Una pila funciona bajo el principio LIFO (LAST IN-FIRST OUT) y por ende tenemos los siguientes métodos:
* `push(x)`:agrega un elemento a la cima
* `pop()`: saca y devuelve el elemento de la cima
* `peek()`: observa el elemento de la cima sin sacarla
* `is_empty()`: verifica si la pila está vacia 
* `size()`: devuelve el numero de elementos
  
3. **Estructura Graph:** Implementación de un grafo no dirigido usando listas de adyacencia.
Definimos la clase Graph y utilizamos un diccionario para implementar una lista de adyacencia, donde una llave es un vertice y su valor es un conjunto con sus vertices vecinos.

5. **`dfs_iterative(start)`** lo que hace es explorar el grafo. Ordena los vecinos al reves antes de meterlos a la pila, garantizamos que el recorrido visite los nodos en orden alfabético. 
6. **`connected_components()`** recorre todo el mapa buscando nodos que no hayan sido visitados para encontrar listas separadas.
7. **`has_cycle_undirected()`:** utiliza una lista modificada que guarda pares `(Nodo_Actual, Nodo_Padre)`para detectar si el recorrido se encuentra en un nodo ya visitado.  

## Pruebas de los algoritmos 
1. **Prueba DFS sin ciclo:** se crea un frafo lineal simple y se imprimer el de visita.
2. **Prueba de ciclo:** se crea un grafo cerrado en forma de traingulo para que el algoritmo detecte el ciclo y devuelva `True`.
3. **Prueba de componentes conexas:** se crea un grafo ártido en tres secciones independientes para comprobar que el algoritmo encuentra 3 listas diferentes.

## link del repositorio
https://colab.research.google.com/drive/1J4H-TxISWUuuYkPfA7Hv-PR-OVsVNZ0v?usp=sharing
