# VI. Aprendizaje no supervisado

```{figure} ../_static/img6.png
:alt: representacion
:fig-align: center
:width: 300px
```

## 🔹 No supervisado

- **Objetivo:** Descubrir **patrones ocultos** en los datos sin etiquetas.

- **Ejemplos típicos:**

  - **Clustering:** Agrupar datos similares (ej. segmentación de clientes).
  - **Reducción de dimensionalidad:** Simplificar datos manteniendo la mayor información posible (ej. PCA, t-SNE).
  - **Detección de anomalías:** Encontrar valores atípicos en datos (fraude, fallos en sensores).
  - **Aprendizaje de reglas de asociación:** Descubrir relaciones entre elementos (ej. análisis de cesta de la compra).

- **Métricas:** No hay etiquetas, así que se usan medidas como silhouette, inercia, distancia intra/inter-cluster, varianza explicada.

- **Algoritmos comunes:**
  - K-Means, DBSCAN, Gaussian Mixture Models (clustering).
  - PCA, t-SNE, UMAP (reducción de dimensionalidad).

El _aprendizaje no supervisado_ es una rama de **Machine Learning** donde el modelo aprende a partir de datos no etiquetados. A diferencia del aprendizaje supervisado, aquí no se proporciona una etiqueta o resultado esperado para cada instancia de entrenamiento.

## Objetivos

- Entender los conceptos básicos del aprendizaje no supervisado.
- Familiarizarse con algoritmos comunes como k-means.
- Aprender a evaluar el rendimiento de los modelos utilizando métricas adecuadas.

## Temas

1. Aprendizaje no supervisado
2. Modelos para agrupamiento
3. Evaluación de modelos

## Datos

Trabajaremos con el siguiente conjunto de datos:

[![Descargar datos](https://img.shields.io/badge/descargar-datos-yellow)](../datos/wine.csv)

## Contenidos de esta sesión

En esta sesión estaremos trabajando con este cuaderno de trabajo:

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/patymunoz/curso-machine-learning-python/blob/main/notebooks/aprendizaje_no_supervisado.ipynb)
