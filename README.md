# **Ahorcado**

## Análisis de la clase Dios

En base a los principios SOLID, en esta primera etapa del juego, se pueden observar varios errores de diseño, los cuales nombraré a continuación.

- **S** - Single Responsibility Principle

     En Juego.cs se puede observar que tiene varias responsabilidades, lo cual rompe con este principio, considerándose de esta forma una clase Dios, por lo que la forma de corregir esto es dividiéndolo en varias clases, cada una con una sola responsabilidad. 

- **O** - Open/Closed Principle

