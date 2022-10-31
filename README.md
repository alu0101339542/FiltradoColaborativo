# Explicación del código
  Para el desarrollo de esta aplicación web se han utilizado HTML, CSS y JavaScript, así como el framework de diseño MaterializeCSS. El código desarrollado consta en primer lugar de un bloque de código encargado de extraer la matriz del fichero de entrada una vez este ha sido cargado, y de una serie de funciones que se encargarán de la aplicación de los algoritmos correspondientes y su muestra final en la interfaz de la aplicación web. De esta forma se tienen las siguientes funciones:
  - medias(): Calcula las medias de las puntuaciones de cada vecino.
  - pearson(): Calcula la similaridad entre dos vecinos según la correlación de Pearson.
  - coseno(): Calcula la similaridad entre dos vecinos según la distancia coseno.
  - euclidea(): Calcula la similaridad entre dos vecinos según la distancia euclídea.
  - predSimple(): Calcula la predicción de la puntuación de un item basándose en los vecinos seleccionados.
  - diferenciaMedia(): Calcula la predicción de la puntuación de un item basándose en los vecinos seleccionados aplicando diferencia con la media.
  - sistemaRecomendación(): Realiza el cálculo completo del sistema de recomendación utilizando la métrica y predicción seleccionadas por el usuario.
  - run(): Es la función que inicia la ejecución del programa, es la encargada de llamar al sistema de recomendación y mostrar los resultados en la interfaz gráfica de la aplicación.
  
  En cuanto a su uso, a la aplicación se le debe dar como entrada un fichero con la matriz de utilidad que se quiere analizar, este fichero debe indicar en su primera línea, separados por un espacio, los valores mínimo y máximo de la matriz y, en las siguientes líneas, la propia matriz. Esta matriz tendrá valores sin determinar (-) que serán predecidos utilizando la mátrica, predicción y número de vecinos elegidos por el usuario. Está aplicación web ha sido desplegada a través de Github Pages y puede ser visitada a través del siguiente enlace: [Filtrado colaborativo](https://alu0101339542.github.io/FiltradoColaborativo.github.io/)

# Ejemplo del funcionamiento:
1. Elegir un fichero con el siguiente formato: </br>
  1 5</br>
  5 3 4 4 -</br>
  3 1 2 3 3</br>
  4 3 4 3 4</br>
  3 3 1 5 4</br>
  1 4 4 2 1</br>

 

2. Elegir una métrica:</br>
  Correlación de Pearson

3. Escoger el número de vecinos: </br>
  3
4. Tipo de predicción:</br>
  Predicción simple
  
  

![image](https://user-images.githubusercontent.com/72199884/198886502-748286df-f4c8-4899-8c0d-d48923d7be74.png)
