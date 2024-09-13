#ACTIVIDAD2
---
---

En el presente repositorio se ha agregado el código fuente de "snake" 
recuperado de: https://grantjenks.com/docs/freegames/snake.html . En el código original, podemos utilizar las flechas del teclado para movernos en el tablero, la comida está representada con el cuadrado verde mietras que la serpiente esta hecha a base de cuadrados negros. Al comer, la serpiente crece un cuadrado de tamaño y la comida aparecerá en ora parte del tablero. Al mismo tiempo, observamos que el juego imprime el puntaje actual del usuario. Al estrellarse con el mismo cuerpo de la serpiente o con los bordes del tablero aparecerá un cuadro rojo, donde representa que el jugador ha perdido.

Se nos ha pedido realizar lo siguiente:

1)La comida podrá moverse al azar un paso a la vez y no deberá de salirse de la ventana
-
2)Cada vez que se corra el juego, la víbora y la comida deberán tener colores diferentes entre sí, pero al azar, de una serie de 5 diferentes colores, excepto el rojo
-

Explicaciones
***


*Primer Caso:* 
Se asignan colores aleatorios a la víbora y a la comida cada vez que se ejecuta el juego, utilizando los valores generados por random.randint(0, 4), que eligen entre cinco colores diferentes (negro, morado, verde, azul y amarillo). Si el color asignado a la víbora es el mismo que el de la comida, se ajusta el color de la víbora incrementando o disminuyendo su valor para asegurar que ambos sean diferentes. Estos números aleatorios se convierten en nombres de colores mediante un diccionario. Así, se garantiza que la víbora y la comida siempre tengan colores distintos al comenzar el juego, excluyendo el rojo de las opciones disponibles

*Segundo Caso:* Importamos la librería "random" con la finalidad de poder asignar diferentes valores tanto al color de la serpiente (colorSnake) como al color de la comida (colorFood). Estos se les asignarán un valor de 0 a 4 (0: Negro, 1: Morado, 2:Azul, 3:Verde, 4: Amarillo), si ambos llegaran a coincidir en su valor numérico el programa se asegura que el color de la serpiente siempre será diferente. 
