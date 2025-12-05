# Práctica Final NLP - Análisis de Sentimiento en Reviews de Amazon

Este repositorio contiene la resolución de la práctica final de la asignatura de Procesamiento del Lenguaje Natural (NLP). [cite_start]El objetivo principal del proyecto es desarrollar un flujo de trabajo completo ("pipeline") para un problema de clasificación supervisada de sentimiento, enfrentando retos realistas similares a los de la industria[cite: 3, 4, 5].

## 📋 Descripción del Proyecto

[cite_start]El proyecto se estructura en cuatro etapas secuenciales que cubren el ciclo de vida clásico de un proyecto de NLP[cite: 9]: desde la descarga y exploración de datos hasta la evaluación de modelos predictivos. [cite_start]El enfoque principal es la clasificación binaria de reviews (positivas vs. negativas)[cite: 37].

[cite_start]No se busca únicamente un *performance* excelente, sino la justificación razonada de cada paso tomado durante el proceso.

## 📂 Estructura del Repositorio

[cite_start]La solución se divide en 4 notebooks de Jupyter, correspondientes a cada ejercicio de la práctica[cite: 51]:

### 1. Descarga y Análisis Exploratorio de Datos (EDA)
[cite_start]En esta etapa se descarga el corpus y se analizan sus características principales[cite: 17]. Se incluyen métricas y visualizaciones como:
* [cite_start]Cardinalidad del vocabulario[cite: 21].
* [cite_start]Distribución de reviews por estrellas y conteo de positivas/negativas[cite: 22, 23].
* [cite_start]Análisis de los **N-grams más frecuentes**[cite: 24].
* [cite_start]Nubes de palabras (Word Clouds)[cite: 25].
* [cite_start]Visualización 2D de Word Embeddings mediante Word2Vec[cite: 26].

### 2. Preprocesado de Texto
[cite_start]Se implementa una función en Python para la limpieza y normalización de las reviews, preparándolas para el entrenamiento[cite: 30, 32]. [cite_start]Las tareas incluyen eliminación de *stopwords*, signos de puntuación y adecuación de formato[cite: 33].

### 3. Entrenamiento y Testeo
[cite_start]Se aborda el problema como una clasificación binaria supervisada utilizando representaciones **Bag-of-Words (BoW)**[cite: 37, 38].
* [cite_start]Se entrenan y comparan **dos modelos distintos**[cite: 35].
* [cite_start]Se justifican los parámetros del vectorizador y el balanceo de clases[cite: 39].

### 4. Métricas y Conclusiones
[cite_start]Reporte final donde se selecciona el mejor modelo y se valida su bondad utilizando métricas como *precision*, *recall* y *f1-score*[cite: 36, 42]. [cite_start]Se incluyen las conclusiones finales del estudio[cite: 43].

## 📊 Dataset

[cite_start]Se han utilizado los **Amazon Product Data**, específicamente los subconjuntos "5-core" para asegurar la viabilidad computacional[cite: 45, 47, 48].
* [cite_start]**Fuente:** [Amazon Reviews (Julian McAuley)](http://jmcauley.ucsd.edu/data/amazon/)[cite: 49].
* [cite_start]**Variable objetivo:** Calificación por estrellas (utilizada para inferir el sentimiento)[cite: 46].

## 🛠️ Tecnologías

* [cite_start]**Lenguaje:** Python[cite: 51].
* **Entorno:** Jupyter Notebooks.
* **Librerías:** Herramientas estándar de NLP y Machine Learning vistas en la asignatura.

---
*Este proyecto fue realizado como parte de la evaluación final de NLP.*
