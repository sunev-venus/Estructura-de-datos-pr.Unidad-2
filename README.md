# PROYECTO 2: DFS iterativo usando una pila propia

## Objetivo
Implementar una Búsqueda en Profundidad (DFS) sin utilizar recursión, haciendo uso de una estructura de datos tipo Pila (Stack) con implementación propia.
--
## Requisitos Implementados
El código cumple con los 5 requisitos solicitados para la evaluación:
1. **Clase Stack:** Implementación propia de una pila con las operaciones `push(x)`, `pop()`, `peek()`, `is_empty()` y `size()`.
2. **Estructura Graph:** Implementación de un grafo no dirigido usando listas de adyacencia.
3. **DFS Iterativo:** Método `dfs_iterative(start)` que regresa el orden exacto de visita de los nodos utilizando la pila personalizada.
4. **Componentes Conexas:** Método `connected_components()` que devuelve una lista de los componentes aislados dentro del grafo no dirigido.
5. **Detección de Ciclos:** Método `has_cycle_undirected()` que evalúa si el grafo no dirigido contiene al menos un ciclo y regresa `True` o `False`.
