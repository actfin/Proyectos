# Vehículo Inteligente dentro de una Planta Industrial

Este proyecto consiste en la implementación de un vehículo inteligente capaz de trasladarse de forma autónoma por una planta industrial y transportar productos desde el área de almacenamiento central hasta las diferentes zonas de manufactura.

A continuación anexamos el codigo en Python para realizarlo:

> [Codigo Vehículo Inteligente]()

Para lograrlo, se utilizaron los siguientes métodos de aprendizaje automático:

* Generación de datos aleatorios con Python para crear un conjunto de datos de 10,000 muestras con diferentes características.
* Árbol de decisión como algoritmo de aprendizaje supervisado para predecir el protocolo asignado a las muestras generadas.
* La función train_test_split de sklearn para dividir el conjunto de datos en conjuntos de entrenamiento y prueba.
* El algoritmo KMeans para crear un modelo de clustering no supervisado que ubica cada producto en uno de los tres distintos depósitos disponibles en la planta.
* Descomposición de valores singulares (SVD) para reducir la cantidad de valores singulares de la matriz de la imagen original en el algoritmo auxiliar para reducción de imágenes del vehículo.
* Lógica condicional para asignar cada muestra a un depósito en función de su ubicación geográfica y el clúster al que pertenece en el modelo de clustering.

Las librerías utilizadas principalmente fueron:

* Pandas
* Scikit-Learn para la manipulación y procesamiento de datos
* Matplotlib para la visualización de resultados.

Resultados:

Nuestro modelo fue capaz de realizar con éxito sus tareas tanto de clasificación como de asignación de productos a lo largo de la planta industrial, esto con un 95.7% de precisión, esto debido a que existen productos que no estaban contemplados, dando la oportunidad de seguir implementando algoritmos para estos datos atípicos.

* Adicionalmente se implementó un algoritmo auxiliar para reducir la resolución de las imágenes capturadas por el vehículo, lo que permite ahorrar espacio y optimizar el proceso. 
* Además, se determinó la ruta óptima que el vehículo debe seguir para distribuir los productos a lo largo de la planta, teniendo en cuenta las restricciones planteadas.

Finalmente, se creó un modelo de clustering utilizando el algoritmo KMeans para agrupar las muestras según sus características y asignar cada muestra a uno de los tres depósitos disponibles en la planta. En conclusión, este proyecto muestra cómo el aprendizaje automático puede ser utilizado para optimizar el transporte de productos en una planta industrial, reducir costos y mejorar la eficiencia del proceso.
