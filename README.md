# practica-1poligono
Práctica de Dibujo de un Polígono en Blender

Este repositorio contiene la explicación detallada para crear un polígono regular utilizando el software de modelado 3D Blender.

 Procedimiento Técnico

En Blender, la creación de polígonos se basa en la generación de una primitiva de tipo Círculo, donde el número de vértices determina la forma final.

Pasos para realizar la práctica:

1. Limpieza de Escena: Eliminar el cubo inicial presionando `X` y seleccionando Delete.
2. Generación de la Malla:
    Presionar el atajo `Shift + A`.
   Seleccionar Mesh> Circle.
3. Configuración del Polígono:
     Antes de mover nada, abrir el panel "Add Circle" que aparece en la esquina inferior izquierda.
   Vertices: Cambiar el valor al número de lados deseado (ej. 3 para triángulo, 5 para pentágono, 8 para octágono).
   Fill Type: Cambiar de "Nothing" a "NGon" para que el polígono tenga una cara sólida.
4. Finalización: El polígono queda centrado en las coordenadas (0, 0, 0) con lados de longitud uniforme.

Fundamento Geométrico
Blender distribuye los vértices de manera equidistante en un radio de 360 grados. La distancia entre cada vértice es constante, lo que garantiza que el polígono sea regular.
También se incluye un script de Python para automatizar la creación del polígono desde la pestaña de Scripting en Blender.
