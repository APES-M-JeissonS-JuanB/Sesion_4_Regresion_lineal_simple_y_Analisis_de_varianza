# 📊 Aprendizaje Estadístico

[![Python](https://img.shields.io/badge/Python-3.10-3776AB?style=for-the-badge&logo=python&logoColor=white)]()
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)]()
[![Pandas](https://img.shields.io/badge/Pandas-Análisis%20de%20Datos-150458?style=for-the-badge&logo=pandas&logoColor=white)]()
[![scikit-learn](https://img.shields.io/badge/scikit--learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)]()
[![Git](https://img.shields.io/badge/Git-Control%20de%20Versiones-F05032?style=for-the-badge&logo=git&logoColor=white)]()
[![License](https://img.shields.io/badge/Licencia-MIT-black?style=for-the-badge)]()

## Sesión 4 — Regresión Lineal Simple (Taller 3)


## 📌 Descripción General

Este repositorio contiene el desarrollo del **Taller 3: Regresión Lineal Simple**, correspondiente a la Sesión 4 del curso. El taller aborda la construcción, evaluación e interpretación de modelos de regresión lineal simple utilizando tanto `scikit-learn` como `statsmodels`, aplicados sobre datos simulados y sobre conjuntos de datos reales (`iris`, `tips`, `wine`).

A lo largo del taller se desarrollaron ejercicios orientados a responder preguntas concretas sobre el ajuste de modelos, tales como:

- ¿Cómo se ajusta e interpreta una recta de regresión lineal simple?
- ¿Qué tan bien se comportan los residuos de un modelo y qué indica su distribución?
- ¿Cuál es la incertidumbre asociada a los parámetros estimados de un modelo?
- ¿Cómo se traduce un modelo ajustado en una predicción concreta sobre datos reales?
- ¿Producen `scikit-learn` y `statsmodels` los mismos parámetros al ajustar el mismo modelo?

El trabajo se desarrolló íntegramente en un **Jupyter Notebook** (Google Colab), combinando código, salidas (numéricas y gráficas) y celdas de interpretación.

------------------------------------------------------------------------

## 👨‍💻 Integrantes

- **Juan Daniel Bogotá Fuentes**
- **Jeisson David Sanchez Gomez**

------------------------------------------------------------------------

## 🧠 Estructura del Análisis (Notebook)

### Punto 1 — Introducción a la Regresión Lineal Simple
Generación de un conjunto de datos aleatorios de 20 puntos, ajuste de un modelo de regresión lineal simple con `scikit-learn`, y visualización de los puntos junto con la línea de regresión ajustada.

### Punto 2 — Análisis de Residuos
Regresión lineal simple sobre el conjunto de datos `iris` (ancho del pétalo en función de su longitud), cálculo de los residuos del modelo y análisis de su distribución mediante un histograma.

### Punto 3 — Intervalos de Confianza
Generación de un conjunto de datos aleatorios de 50 puntos, ajuste de un modelo de regresión lineal simple con `statsmodels`, y cálculo e interpretación de los intervalos de confianza al 95% para el intercepto y la pendiente del modelo.

### Punto 4 — Predicción en un Conjunto de Datos Real
Regresión lineal simple sobre el conjunto de datos `tips` (propina en función del total de la factura), con predicción puntual de la propina esperada para una factura de $50.

### Punto 5 — Comparación de Modelos
Regresión lineal simple sobre el conjunto de datos `wine` (contenido de alcohol en función de otro atributo), ajustada primero con `scikit-learn` y luego con `statsmodels`, comparando los parámetros (intercepto y pendiente) obtenidos por ambos métodos.

------------------------------------------------------------------------

## 📁 Estructura del Proyecto

    📦 Sesion_4_Regresion_Lineal_Simple_Taller3
     ├── README.md
     ├── Sanchez_Jeisson_y_Bogota_Juan_CasoEstudio_sesion4.ipynb
     ├── Sesión_4_Análisis_de_varianza.ipynb
     ├── Sesión_4_Regresion_lineal_simple_P1.ipynb
     └── Taller_3_MOET.docx.pdf

### 📖 Contenido

- **Desarrollo del taller** en Jupyter Notebook (Google Colab / VS Code):
  `Sanchez_Jeisson_y_Bogota_Juan_CasoEstudio_sesion4.ipynb`
- **Enunciado del taller**:
  `Taller_3_MOET.docx.pdf`
- **Recursos de la Sesión 4** (material de clase):
  `Sesión_4_Análisis_de_varianza.ipynb`
  `Sesión_4_Regresion_lineal_simple_P1.ipynb`

------------------------------------------------------------------------

## 🛠 Tecnologías

- Python
- Pandas / NumPy
- scikit-learn (ajuste de modelos y predicción)
- statsmodels (inferencia estadística e intervalos de confianza)
- Seaborn (datasets `iris`, `tips`)
- Matplotlib (visualización)
- Jupyter Notebook / Google Colab / VS Code
- Git y GitHub

------------------------------------------------------------------------

## 📈 Aprendizajes Obtenidos

A través de este taller se desarrollaron las siguientes competencias:

- Ajuste e interpretación de modelos de regresión lineal simple con `scikit-learn`.
- Diagnóstico de un modelo mediante el análisis de la distribución de sus residuos.
- Construcción e interpretación de intervalos de confianza para los parámetros de un modelo con `statsmodels`.
- Uso de un modelo de regresión ajustado para generar predicciones puntuales sobre datos nuevos.
- Comparación crítica entre `scikit-learn` y `statsmodels`, reconociendo cuándo priorizar predicción y cuándo priorizar inferencia estadística.
- Trabajo colaborativo mediante Git y GitHub.

------------------------------------------------------------------------

## 👨‍💻 Autores

[![GitHub](https://img.shields.io/badge/GitHub-JeissonS02-181717?style=for-the-badge&logo=github)](https://github.com/JeissonS02)
[![GitHub](https://img.shields.io/badge/GitHub-JuanBogota-181717?style=for-the-badge&logo=github)](https://github.com/JuanBogota)
