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
4. **DFS Iterativo:** Método `dfs_iterative(start)` que regresa el orden exacto de visita de los nodos utilizando la pila personalizada.
5. **Componentes Conexas:** Método `connected_components()` que devuelve una lista de los componentes aislados dentro del grafo no dirigido.
6. **Detección de Ciclos:** Método `has_cycle_undirected()` que evalúa si el grafo no dirigido contiene al menos un ciclo y regresa `True` o `False`.



## link del repositorio
https://colab.research.google.com/drive/1J4H-TxISWUuuYkPfA7Hv-PR-OVsVNZ0v?usp=sharing
