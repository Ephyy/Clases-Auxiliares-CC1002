---
tags: [Programa Interactivo]
---

# Sunset
Hay que implementar un programa interactivo que simule la compra de entradas para el evento
Sunset y la opción de agregar bebidas (muy sanas y sin ningún componente misterioso…).
El programa deberá interactuar con el usuario para recolectar la información necesaria y luego calcular
el costo total de la compra de la siguiente forma:

```
¿Cuál es tu nombre?
>> Arianne
Hola Arianne, ¡Bienvenido/a al sistema de compra de entradas para el Sunset!
¿Cuántas entradas quieres comprar?
>> 3
¿Cuántas bebidas quieres agregar?
>> 2
El total a pagar por 3 entrada(s) y 2 bebida(s) es: $19000
¡Gracias por tu compra, Arianne!
```

Para ello:

1. El programa debe comenzar pidiéndole al usuario su nombre y darle la bienvenida, mostrando un
mensaje como: 

```
Hola [nombre] ¡Bienvenido/a al sistema de compra de entradas para el Sunset! 
```

2. A continuación, el programa debe preguntar cuántas entradas desea comprar el usuario. Cada
entrada tiene un precio fijo de $5.000. Debe calcular el costo total de las entradas.
3. Luego, se pregunta si el usuario desea agregar bebidas a su compra. Cada bebida tiene un precio fijo
de $2.000.
4. Debe preguntar cuántas bebidas desea agregar el usuario (puede agregar 0) y calcular el costo total
de las bebidas.
5. Debe sumar el costo de las entradas y el costo de las bebidas para obtener el costo total de la compra,
mostrando un mensaje como: 
`El total a pagar por [cantidad de entradas] entrada(s) y [cantidad de
bebidas] bebida(s) es: $[total]`.