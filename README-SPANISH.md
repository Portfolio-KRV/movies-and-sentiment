# Movies and sentiment
Desarrollado en el curso de Introducción a la Ciencia de Datos por: Kevin Reyes.
## Objetivos
- Identificar el sentimiento positivo o negativo, en opiniones de películas utilizando métodos de aprendizaje automático y redes neuronales.
- Comparar métodos de vectorización del texto bag of words y tf-idf.
- Analizar la efectividad del método dropout en el problema de clasificación.
- Representar los textos utilizando word embeddings.
- Aplicar método T-SNE para visualizar la distribución de los embeddings.
- Clusterizar la distribución de embeddings obtenida con el método T-SNE.
- Evaluar la utilización de embeddings pre-entrenados.
## Descripción
Estudio comparativo de métodos de aprendizaje automático y redes neuronales con distintas variaciones aplicados a la clasificación de sentimientos de opiniones de películas.

## Conclusiones
- La aplicación de dropout disminuye el sobreajuste de las redes neuronales.
- Las redes con mayor cantidad de celdas LSTM aumentan el sobreajuste considerablemente.
- El conjunto de datos presenta un desbalance de tan solo un 2%, por lo que se puede hablar de un problema de clasificación balanceado.
- Al aumentar la fuerza de la regularización en los métodos tradicionales obtenemos mayor capacidad de generalización.
- Los modelos de aprendizaje automático tienen menos problemas de sobreajuste que los modelos de redes neuronales.

## Stack de tecnologías
- Numpy.
- Matplotlib.
- Scikit-learn.
- Tensorflow.
- Keras.
