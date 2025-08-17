---
tags: [Estructuras]
---

# Vectores

Un vector en $R^3$ es un elemento que se puede definir como $V = (a_1, a_2, a_3)$ en donde $a_1$, $a_2$ y $a_3$ corresponden a las coordenadas en los ejes $x, y, z$ respectivamente. Por medio de estructuras, implementaremos el modulo vector con algunas de sus operaciones mas comunes:

a) Cree la estructura `Vector`, que recibe tres componentes numéricas de nombres x, y, z . \
b) Cree una función llamada `esVector(X)`, que entregue `True` si el parámetro $V$ representa un Vector válido, y `False` en cualquier otro caso. \
c) Cree la función `aString(V)` que recibe un `Vector`, y retorna un string de la forma `"(x,y,z)"` donde x,y,z son las componentes del Vector. \
d) Cree una función llamada `suma(V1,V2)` que recibe dos Vectores y entrega un nuevo Vector con las componentes sumadas. \
e) Cree una función llamada `productoPunto(V1,V2)`, que recibe dos Vectores, y entrega el producto punto de estos dos. Recuerde que el producto punto entre dos vectores $v_1 = (x_1, y_1, z_1)$ y $v_2 =(x_2, y_2, z_2)$ esta dado por:

$$ v_1 \cdot v_2 = x_1x_2 + y_1y_2 + z_1z_2 $$

donde $x_𝑖, y_𝑖, z_𝑖$ son las componentes del vector i-esimo.

f) Cree una función llamada `norma(V)`, que use la función anterior, para calcular el módulo de un Vector. Recuerde que la norma de un vector esta dada por: $\lVert v \rVert = \sqrt{v \cdot v}$ \
g) **[Propuesto]** Cree una función llamada `productoCruz(V1,V2)`, que recibe dos Vectores, y entrega el Vector resultante de realizar el producto cruz entre ellos dos.