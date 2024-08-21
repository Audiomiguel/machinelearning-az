# Idea de los Bosques Aleatorios

### Aprendizaje Conjunto

* Es una version mejorada del arbol de regresion con aprendizaje conjunto.

### Pasos del algoritmo

1. Elegir un numero aleatorio *K* puntos de datos del Conjunto del Entrenamiento
2. Se construye un **Arbol de Decision** asociado a esos *K* puntos de datos (subconjunto de datos globales, lo que hace que cada arbol no tiene una vision global)
3. Elegir el numero **Ntree** de arboles que queremos construir y repetimos los PASOS 1 y 2 , cada uno tiene diferentes puntos
4. Cada uno de los arboles que se ha construido hara una prediccion de cual deberia ser segun ese arbol el arbol que va a predecir. Luego, promediamos todos los resultados

Entonces, observamos que cuando lo convertimos en un bosque, se ve mejorado ya que reduce la posibilidad que sea erroneo la prediccion

Lo que actua en este caso el conjunto.

### Por ejemplo

Tienes un frasco de canicas de diferentes de colores

* La idea del juego es ser capaz de adivinar cuantas canicas existen y el premio puede ser un carro

Entonces es la misma idea, si tu preguntas a cada persona que adivine cuantas canicas hay en ese tarro, tu preguntas su resultado y apuntas.

Cuando ya vayas 1000 personas, lo que haces es la media , del mismo modo como el algoritmo.

* Como podria ser que la media quedar un poco mal, podriamos tomar la **mediana** en vez de la media
