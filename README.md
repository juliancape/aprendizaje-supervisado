# aprendizaje-supervisado
Ejercicio real de aprendizaje supervisado en el que se determina si una persona es candidata para obtener un credito o no. <br>
En particular, se crean dos pipelines de transformación de características, uno para características numéricas y 
otro para características categóricas, que se combinan en un transformador de columna para crear un pipeline de transformación 
de características completo. Se crean tres pipelines de clasificación diferentes para 
<b>RandomForestClassifier, SVC y LogisticRegression</b>, 
cada uno de los cuales se aplica al pipeline de transformación de características completo para construir un modelo de clasificación. 
El código utiliza validación cruzada para comparar el desempeño de los modelos y seleccionar el mejor modelo basado en la media del 
puntaje de validación cruzada. Finalmente, el mejor modelo se ajusta con los datos de entrenamiento y se guarda, para posteriormente
cargar el modelo y evaluarlo con los datos de test, con metricas como Accuracy Score y Matriz de confusion.
![Resultados](https://github.com/juliancape/aprendizaje-supervisado/blob/master/supervisado-resultadosPNG.PNG)
