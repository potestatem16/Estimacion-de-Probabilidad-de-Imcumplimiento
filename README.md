# Estimacion de Probabilidad de Imcumplimiento

## Descripción
Este proyecto se centra en desarrollar modelos de machine learning para predecir la probabilidad de incumplimiento de clientes. Utilizando la base de datos "MDT_prueba.csv", que contiene 100 campos por cliente, incluyendo la variable objetivo 'BGI_max', se busca identificar clientes con riesgo de incumplimiento en un periodo de 12 meses tras la cosecha.

## Objetivo
El objetivo principal es estimar la probabilidad de incumplimiento de un cliente, utilizando técnicas avanzadas de modelado y análisis de datos para manejar un conjunto de datos con clases desbalanceadas.

## Metodología
Se implementaron varios modelos de clasificación, incluyendo Regresión Logística, XGBoost, LightGBM, CatBoost y AdaBoost, cada uno con un enfoque específico para manejar el desequilibrio de clases. El proceso general incluyó:

* Preprocesamiento de Datos: Limpieza y preparación de datos para el modelado.
* Manejo de Clases Desequilibradas: Uso de técnicas como ponderación de clases para abordar el desequilibrio en los datos.
* Selección de Hiperparámetros: Optimización de modelos mediante GridSearchCV para encontrar la mejor combinación de hiperparámetros.
* Selección de Características: Aplicación de RFECV para identificar las características más relevantes.
* Entrenamiento y Evaluación de Modelos: Uso de métricas como ROC AUC, precisión, recall y f1-score para evaluar el rendimiento de los modelos.

