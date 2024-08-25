# Juego de navegacion por el laberinto

El objetivo de este proyecto es desarrollar un entorno de laberinto simple y aplicar un algoritmo de **Aprendizaje por reforzamiento** para enseñar a una **IA** a navegar desde un punto inicial hasta uno final. 

Dada la naturaleza de este proyecto, considero que el algoritmo más adecuado para este tipo de problemas es **Q-Learning**, por su facilidad de implementación y comprensión, su estabilidad y su relación entre la exploración y la explotación.

### Descripción del Laberinto:
El laberinto se representa como una matriz de dos dimensiones, donde cada elemento puede ser:
+ un camino libre (0)
+ un obstáculo (1)
+ el objetivo (G)

![robot](https://github.com/user-attachments/assets/710469e3-63df-4846-a24d-602dacc4216a)
