# practica-1poligono
Práctica: Dibujo de un Polígono

Este proyecto explica cómo dibujar un polígono regular utilizando programación. Un polígono es una figura geométrica plana compuesta por segmentos rectos consecutivos.

Conceptos Básicos

Para dibujar cualquier polígono de  lados, debemos considerar que la suma de los ángulos exteriores de cualquier polígono simple siempre es 360°. Por lo tanto, el ángulo de giro para cada vértice se calcula con la fórmula:

Donde  es el número de lados (ej.  para un triángulo,  para un cuadrado).

 Pasos para realizar la práctica:

1. Definir el número de lados: Elige cuántos lados tendrá tu figura.
2. Calcular el ángulo: Divide 360 entre el número de lados.
3. Bucle de dibujo:
* Mover hacia adelante una distancia .
* Girar el ángulo calculado.
* Repetir este proceso  veces.
