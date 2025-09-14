---
tags: [Listas Recursivas]
---

# Listas 📋
En clases se vio la estructura lista y algunas funciones que operan con listas. Ahora realizaremos mas funcionalidades que permiten extender la utilidad de esta estructura (y su módulo lista).

Para los ejemplos de enunciado, usaremos la siguiente lista:
```python
Lej = lista(5,lista(8,lista('manzana', lista(6,listaVacia))))
```

Se pide implementar lo siguiente:

a) Cree la función `aString(L)`, que recibe una lista de elementos, y entrega un string que muestra
todos los elementos de la lista, separados por un espacio. Ejemplo:
- `aString(Lej)` entrega `'5 8 manzana 6'`
  
b) Cree la función `agregarAlFinal(L,e)`, que recibe una lista y un elemento, y entrega una lista con este elemento agregado al final de la Lista. Ejemplo:
- `agregarAlFinal(Lej,3)` entrega `lista(5,lista(8,lista('manzana', lista(6,lista(3,listaVacia)))))`

c) Cree la función `agregarAlPrincipio(L,e)`, que recibe una lista y un elemento, y entrega una lista con este elemento agregado al principio de la Lista. Ejemplo:
- `agregarAlPrincipio(Lej,3)` entrega:
`lista(3, lista(5,lista(8,lista('manzana', lista(6, listaVacia))))`

d) Cree la función `posicion(L, e)`, que recibe una lista y un elemento, y entrega un numero entero, que indica la posición de la primera aparición del elemento en la lista. En caso de que el elemento no este presente en la lista, devolver un cero. Ejemplo:
- `posicion(Lej,6)` entrega: `4`
- `posicion(Lej,22)` entrega: `0`

Hint: Utilice la función `contiene()` vista en clases.

e) Cree la función `obtener(L, i)`, que recibe una lista y un número entero que indica una posición en la lista, y entrega el elemento que se encuentra en tal posición. En caso de que el número se
encuentre fuera del rango de la lista, entonces devuelve `None`. Ejemplo:
- `obtener(Lej,3)` entrega: `'manzana'`
- `obtener(Lej,7)` entrega: `None`

f) Cree la función `invertir(L)`, que recibe una lista y entrega una lista, con los elementos en orden
inverso. Ejemplo:
- `invertir(Lej)` entrega: `lista(6,lista('manzana',lista(8,lista(5,listaVacia))))`

g) Cree la función `ultimo(L)`, que recibe una lista y entrega el último elemento de la lista. Ejemplo:
- `ultimo(Lej)` entrega: `6`