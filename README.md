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

*Segundo Caso:* Importamos la librería "random" con la finalidad de poder asignar diferentes valores tanto al color de la serpiente (colorSnake) como al color de la comida (colorFood). Estos se les asignarán un valor de 0 a 4 (0: Negro, 1: Morado, 2:Azul, 3:Verde, 4: Amarillo), si ambos llegaran a coincidir en su valor numérico el programa se asegura que el color de la serpiente siempre será diferente. 
