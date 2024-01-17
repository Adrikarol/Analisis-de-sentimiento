# Proyecto de Análisis de Sentimientos en Reseñas de Películas

Este repositorio contiene el código y análisis realizados para un proyecto de análisis de sentimientos en reseñas de películas. El objetivo principal es comprender y predecir el sentimiento asociado a las reseñas, utilizando diferentes modelos y técnicas de procesamiento de lenguaje natural.

## Contenido del Proyecto

El proyecto se organiza en varias secciones, cada una abordando aspectos específicos del análisis de sentimientos y la construcción de modelos predictivos. A continuación, se presenta un resumen de las secciones clave:

### Preprocesamiento de Datos

En esta sección, se realiza la limpieza y preprocesamiento de las reseñas de películas. Las operaciones incluyen la eliminación de caracteres especiales, tokenización, lematización y la conversión de texto a vectores mediante TF-IDF.

### Modelos de Análisis de Sentimientos

Se exploran diferentes modelos para analizar el sentimiento de las reseñas. Se utilizan modelos basados en algoritmos de Regresión Logística, LightGBM y BERT. Además, se analizan las predicciones de cada modelo y se evalúa su rendimiento en un conjunto de reseñas de prueba.

### Análisis de Errores y Mejoras

Esta sección incluye el análisis de errores cometidos por los modelos, identificando patrones y casos específicos en los que los modelos pueden fallar. Se proponen posibles mejoras y ajustes para abordar estos desafíos.

### Comparación de Modelos y Resultados

Se comparan los resultados de diferentes modelos en términos de métricas de evaluación, como F1-score. Se destaca la eficacia y las limitaciones de cada modelo para proporcionar una visión completa del rendimiento.

## Estructura del Repositorio

- **src/**: Contiene los scripts y notebooks de código fuente utilizados para realizar el análisis y entrenar los modelos.
- **data/**: Almacena el conjunto de datos original y las reseñas de prueba.
- **README.md**: Este archivo, que proporciona una guía detallada sobre el proyecto, sus objetivos y la estructura del repositorio.
