# Práctica Final NLP - Análisis de Sentimiento en Reviews de Amazon

Este repositorio contiene la resolución de la práctica final de la asignatura de Procesamiento del Lenguaje Natural (NLP). El objetivo principal del proyecto es desarrollar un flujo de trabajo completo para un problema de clasificación binaria de sentimiento.

## 📋 Descripción del Proyecto

El proyecto se estructura en cuatro etapas que cubren el ciclo de vida de un proyecto de NLP: desde la descarga y exploración de datos hasta la evaluación de modelos predictivos. El enfoque principal es la clasificación binaria de reviews (positivas vs. negativas).

## 📂 Estructura del Repositorio

La solución se divide en 4 notebooks, correspondientes a cada ejercicio de la práctica:

### 1. Descarga y Análisis Exploratorio de Datos (EDA)
En esta etapa se descarga el corpus y se analizan sus características principales. Se incluyen métricas y visualizaciones como:
* Cardinalidad del vocabulario.
* Análisis de los N-grams más frecuentes
* Nubes de palabras (Word Clouds)

### 2. Preprocesado de Texto
Se implementa una función en Python para la limpieza y normalización de las reviews, preparándolas para el entrenamiento. 
Las tareas incluyen eliminación de *stopwords*, signos de puntuación y adecuación de formato.

### 3. Entrenamiento y Testeo
Se aborda el problema como una clasificación binaria supervisada.
Se entrenan y comparan modelos distintos.
Se justifican los parámetros del vectorizador.

### 4. Métricas y Conclusiones
Reporte final donde se selecciona el mejor modelo y se valida su bondad utilizando métricas como *precision*, *recall* y *f1-score*. Se incluyen las conclusiones finales del estudio.

## 📊 Dataset

Se han utilizado los **Amazon Product Data**, específicamente los subconjuntos "5-core" de automatización. [Amazon Reviews (Julian McAuley)](http://jmcauley.ucsd.edu/data/amazon/)
