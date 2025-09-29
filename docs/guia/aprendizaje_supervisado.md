# V. Aprendizaje supervisado

```{figure} ../_static/img5.png
:alt: representacion
:fig-align: center
:width: 300px

```

El _aprendizaje supervisado_ es una rama de **Machine Learning** donde el modelo aprende a partir de datos etiquetados. Es decir, cada instancia de entrenamiento incluye tanto las características (features) como la etiqueta o resultado esperado (target).

## Diferencias entre modelos supervisados: clasificación y regresión

_Los modelos supervisados_ se dividen principalmente en dos grandes tipos: **clasificación** y **regresión**. Ambos aprenden a partir de datos etiquetados (pares de entrada y salida), pero difieren en el tipo de variable objetivo que predicen y en cómo se evalúa su desempeño.

### 🔹 Clasificación

- **Objetivo:** Predecir una **etiqueta discreta** o categoría.  
  Ejemplo: ¿un correo es _spam_ o _no spam_? ¿una imagen es un _gato_, un _perro_ o un _pájaro_?

- **Salida:** Una clase entre un conjunto finito de posibilidades.  
  Puede ser:

  - **Binaria** (dos clases, p. ej. sí/no).
  - **Multiclase** (más de dos categorías).
  - **Multietiqueta** (varias categorías al mismo tiempo).

- **Métricas comunes:** Exactitud (accuracy), precisión, recall, F1-score, matriz de confusión, AUC-ROC.

#### 🔹 Regresión

- **Objetivo:** Predecir un **valor numérico continuo**.  
  Ejemplo: predecir el precio de una casa, la temperatura de mañana, o el salario esperado de una persona.

- **Salida:** Un número real, no una categoría.

- **Métricas comunes:** Error cuadrático medio (MSE), raíz del error cuadrático medio (RMSE), error absoluto medio (MAE), R² (coeficiente de determinación).

#### Diferencias principales

| Aspecto                | Clasificación                                                            | Regresión                                                                |
| ---------------------- | ------------------------------------------------------------------------ | ------------------------------------------------------------------------ |
| **Tipo de salida**     | Categórica (discreta)                                                    | Numérica (continua)                                                      |
| **Ejemplo**            | Diagnóstico: sano/enfermo                                                | Nivel de glucosa en sangre (mg/dL)                                       |
| **Algoritmos típicos** | Árboles de decisión, Naive Bayes, SVM, Redes neuronales de clasificación | Regresión lineal, polinómica, redes neuronales de regresión              |
| **Métricas**           | Exactitud, F1, AUC                                                       | MSE, RMSE, MAE, R²                                                       |
| **Aplicaciones**       | Detección de fraude, reconocimiento de voz, clasificación de imágenes    | Predicción de ventas, series temporales, análisis de riesgos financieros |

## Objetivos

- Entender los conceptos básicos del aprendizaje supervisado.
- Familiarizarse con algoritmos comunes para _clasificación_ como regresión logística y árboles de decisión.
- Aprender a evaluar el rendimiento de los modelos utilizando métricas adecuadas.

## Temas

1. Aprendizaje supervisado
2. Modelos para clasificación
3. Evaluación de modelos

## Datos

Trabajaremos con el siguiente conjunto de datos:

[![Descargar datos](https://img.shields.io/badge/descargar-datos-yellow)](../datos/student_lim.xlsx)

El diccionario de datos es el siguiente:

[![Diccionario de datos](https://img.shields.io/badge/diccionario-de_datos-blue)](../datos/diccionario_columnas_completo.xlsx)

El conjunto de datos original lo puedes consultar en el siguiente enlace: [Student Performance Dataset](https://archive.ics.uci.edu/dataset/320/student+performance)

## Contenidos de esta sesión

En esta sesión estaremos trabajando con este cuaderno de trabajo:

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/patymunoz/curso-machine-learning-python/blob/main/notebooks/aprendizaje_supervisado.ipynb)
