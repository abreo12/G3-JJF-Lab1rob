# G3-JJF-Lab1rob

### Nombres
-Jaime Andrés Sánchez Peralta

-Juan José Rojas Álvarez

-Fabian Stiven Abreo Cubides

### Solución del problema
El objetivo del laboratorio es de representar las letras iniciales de los nombres de cada integrante por grupo.
La solución planteada consiste en una herramienta con un ángulo de 45° para evitar problemas por un posible alineamiento de ejes al momento de mover el brazo, se creó un modelo de las letras a escribir en Autodesk Inventor y se exportó al ambiente virtual de Robot Studio. También se acercó el brazo robótico mediante un movimiento de juntas a una posición cercana a las letras previamente mencionadas para evitar dicho alineamiento o singularidad en en movimiento de acercamiento. Las rutas diseñadas para las letras consisten de un offset en su posición inicial, seguido de la trayectoria que rodea las letras, para volver a un mismo offset y poder dirigirse a la siguiente letra sin rayar el tablero. Se diseñaron dos rutas distintas, una en x(+)y(+), rotadas respecto al centro y otra en x(+)y(-), siendo esta segunda más cercana al 0 en y.

El resultado del laboratorio se encuentra en la siguiente carpeta de Drive:
[Imagen de resultado final](https://drive.google.com/file/d/1lQ5JUMA3xT-8_DehqiqwM6muVTgrXkPd/view?usp=share_link)

En el repositorio se encuentran: 

-videos de las simulaciones y de la práctica en el laboratorio, encontrados en el link que se muestra a continuación [Video Laboratorio 1](https://youtu.be/TSpJmbPzFIQ).

-Codigo RAPID del centro y de la esquina, para las dos posiciones en las que se realizó el marcado de los nombres.

-el modelo CAD de la herramienta, aunque es tan sólo por propósitos visuales, debido a que no fue utilizado en las simulaciones del ejercicio.
### conclusiones
Se recomienda para una próxima práctica el uso de una herramienta con un resorte incluido, debido a que permite mayor flexibilidad al momento de mantener la posición en los tableros, que no se encuentran completamente en el mismo plano.
Modelando la herramienta en CAD y usando un angulo de inclinacion en la herramienta evitamos que los ejes se alineen y presenten errores de singularidad al simular.
Para esta practica no era necesario tener una herramienta modelada en 3D dado que en caso de error era dificil reemplazar por eso usamos un soporte en madera y un codo de 1/2 pulgada para que en caso de ruptura fuera facilmente reemplazable.
