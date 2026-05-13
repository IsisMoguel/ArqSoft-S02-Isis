# **Ahorcado**

## Análisis de la clase Dios

En base a los principios SOLID, en esta primera etapa del juego, se pueden observar varios errores de diseño, los cuales nombraré a continuación.

- **S** - Single Responsibility Principle

     En Juego.cs se puede observar que tiene varias responsabilidades, lo cual rompe con este principio, considerándose de esta forma una clase Dios, por lo que la forma de corregir esto es dividiéndolo en varias clases, cada una con una sola responsabilidad. 

- **O** - Open/Closed Principle

    Se puede observar el manejo de IF para las acciones del juego, en caso de que se requiera agregar más funciones para mostrar en el juego, habría que modificar mucho el código, lo cual no es lo ideal, en su lugar se deberían crear clases especificas para cada uno, y luego llamarlas mediante metodos.

En este proyecto, se observan estos dos principios que impiden que el juego sea escalable.

