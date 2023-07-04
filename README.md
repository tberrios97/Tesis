# Predicción agregada de contaminación por ozono usando CNNs sobre transformaciones serie-imagen

## Introducción

El proposito de este repositorio es ilustrar sobre el trabajo realizado para en la tesis "Predicción agregada de contaminación por ozono usando CNNs sobre transformaciones serie-imagen". Para este trabajo se realizó un trabajo de predicción de los índices de contaminación del ozono troposférico a lo largo de Santiago de Chile, en donde se realizó una técnica de transformación de serie a imagen, utilizando algoritmos tales como *Gramian Angular Field*(GAF) y *Markov Transition Field*(MTF), para pasar de una serie en una dimensión a una imagen representativa de la serie a través de los distintos algoritmos. Una vez con los distintos datos transformados, se realiza una predicción utilizando un modelo con una arquitectura de una CNN para predecir en un horizonte de tiempo, el comportamineto del ozono dado el input.

## Distribución del repositorio

Este repositorio esta repartido de la siguiente forma. Se encuentra la ruta **datasets-ozono**, en la cual se encuentran los distintos datasets de los indices de contaminación de ozono al rededor de Santiago, esto siendo proporcionado a través del SINCA. El archivo **Testing.ipynb** consiste en el trabajo preliminar de la Tesis, en el cual se en la investigación y trabajo sobre los datos para obtener resultados y planificar los modelos finales a probar; en este archivo se encuentra la arquitectura base a lo que serán los siguientes modelos finales para probar la eficacia de la predicción del ozono en base a distintos factores. Y finalmente, en la ruta **Models**, se encuentra segmentado en distintas rutas con los modelos finales a probar dado las distintas características a experimentar; en donde se realiza un trabajo de ajustes de hiperparámetros y buscar el mejor modelo posible.



## Características del ambiente de trabajo

El desarrollo de este proyecto fue realizado a través de un ambiente virtual creado en Anaconda3, en la cual sus principales librerías implementadas son:

* Tensorflow 2.6
* Keras 2.6
* Scikit-learn 1.1.1
* Scipy 1.7.3
* Numpy 1.21.5
* Pandas 1.4.4
* Seaborn 0.12.0
* Matplotlib 3.6.0
* Pyts 0.12.0

