🔐 Minería de Datos – Proyecto de Ciberseguridad

Repositorio correspondiente a la materia Minería de Datos de la Tecnicatura en Inteligencia Artificial y Ciencia de Datos del Instituto Superior Santo Domingo.

📚 Descripción del proyecto

En este trabajo se aplicaron diferentes técnicas de minería de datos y Machine Learning para analizar conexiones de red e identificar posibles ataques informáticos.

Se utilizó el dataset NSL-KDD, que contiene registros de tráfico de red clasificados como conexiones normales o ataques.

El objetivo fue preparar y analizar los datos, entrenar distintos modelos y comparar sus resultados para determinar cuál funcionaba mejor en la detección de intrusiones.

🛠️ Tecnologías utilizadas

Python

Google Colab

Pandas

NumPy

Matplotlib

Scikit-learn

📊 Desarrollo del proyecto

1. Análisis exploratorio y preprocesamiento

Exploración del dataset NSL-KDD.

Análisis de las características y distribución de los datos.

Identificación de valores nulos y duplicados.

Limpieza y transformación de variables.

Aplicación de Label Encoding y One-Hot Encoding.

Normalización de datos con MinMaxScaler.

2. Aplicación de algoritmos

Se trabajó con cuatro algoritmos:

K-Nearest Neighbors (KNN): clasificación de conexiones según su similitud con otros registros.

Árbol de decisión: clasificación de conexiones mediante reglas de decisión.

K-Means: agrupamiento de conexiones según sus características, sin utilizar las etiquetas durante el entrenamiento.

Naive Bayes: clasificación probabilística de las conexiones.

3. Evaluación de los modelos

Se utilizaron diferentes métricas para evaluar y comparar los resultados:

Exactitud (Accuracy).

Precisión (Precision).

Sensibilidad (Recall).

Especificidad.

F1-score.

AUC-ROC.

Matrices de confusión.

📈 Resultados

Los principales resultados obtenidos fueron:

| Modelo | Exactitud | F1-score |
|---|---|---|
| KNN | 77,3 % | 76,7 % |
| Árbol de decisión | 81,6 % | 81,3 % |
| Naive Bayes | 56,5 % | 38,6 % |

El árbol de decisión obtuvo los mejores resultados generales entre los modelos de clasificación evaluados.

También se utilizó K-Means para explorar agrupamientos de conexiones y analizar su relación con los tipos de tráfico.

💡 Conclusión

Este proyecto me permitió aplicar diferentes técnicas de minería de datos a un problema relacionado con la ciberseguridad.

Pude trabajar con un dataset real, realizar su limpieza y preprocesamiento, entrenar distintos algoritmos y comparar sus resultados.

Además, comprendí la importancia de utilizar diferentes métricas para evaluar los modelos, ya que una mayor exactitud no siempre significa una mejor detección de ataques.

El trabajo tiene fines académicos y no constituye un sistema de seguridad implementado en una red real.

👩‍💻 Autora

Julia Belén Carrillo

Estudiante de Inteligencia Artificial y Ciencia de Datos.
