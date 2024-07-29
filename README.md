# predicción_series_temporales
RNN para entrenamiento de modelos de predicción de comportamiento de series temporales. En este caso, en un dataset de temperaturas para predicción de valores futuros. 
Dataset: https://raw.githubusercontent.com/jbrownlee/Datasets/master/daily-min-temperatures.csv

# 1. Objetivos del proyecto
Este proyecto puede ser utilizado para el mejoramiento de la precisión de los pronósticos del clima a corto y largo plazo, permitiendo proporcionar información más precisa, así también puede ser útil para la identificación de patrones de eventos climáticos extremos, olas de calor, tormentas o heladas. 
En otros ámbitos a ser utilizados, también es posible aplicar los modelos de predicción a las predicciones de demandas de productos y evaluación de riesgos asociados con diferentes factores. 

## 2. Proceso de elaboración del proyecto
-Descarga e importación del dataset

-Creación de variables de entrenamiento y validación, así como su partición

-Montaje de ejemplo de aplicación para verificación 

-Utilización de la técnica de ventana temporal para predicción de valores de serie temporal

-Diseño de red neuronal de aprendizaje profundo 

-Entrenamiento de la red neuronal

-Método callbacks para learning rate con LearningRateScheduler de Python

-Visualizaciones de las métricas de rendimiento
