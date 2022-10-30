# Explicación del código
  Nos encontramos ante un códico en Java Script al cual se le pasa un fichero con una matriz, la cual su primer elemento es el valor mínimo de esta y el segundo el valor máximo, esta matriz tiene valores sin determinar (-) que usando diferentes algoritmos se podrá predecir su valor. Esta matriz representa un conjunto de usuarios y la puntuación que estos le otorgan a ciertos items. Los valores que no se conocen serán predecidos utilizando alguna de las siguientes métricas:</br>
  -Correlación de Pearson </br>
  -Distancia coseno</br>
  -Distancia euclídea</br>
  

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
