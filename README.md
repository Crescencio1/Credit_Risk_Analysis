# 💳 Predicción de Riesgo Crediticio
Proyecto de Machine Learning para predecir el riesgo crediticio utilizando un modelo de supervisado (regresión logística) y uno no supervisado (K-means)
con Python y Scikit-learn.

## 📊 Descripción del Proyecto
El objetivo de este proyecto es construir un modelo de clasificación capaz de predecir si un solicitante de crédito representa un riesgo crediticio
alto o bajo, basado en su información financiera y demográfica disponible.

El proyecto incluye:

* 🔍 Análisis Exploratorio de Datos (EDA)
* 🧹 Preprocesamiento de datos
* 🔤 One-Hot Encoding para variables categóricas
* 📏 Escalado Min-Max para variables numéricas
* 🤖 Regresión Logística
* 🤖 Clasificación por K-means
* 🤖 Análisis de componentes principales (PCA)
* 📈 Evaluación de los modelos
* 🎯 Predicciones basadas en probabilidad

## 🛠️ Tecnologías

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 📓 Explora el Notebook
El análisis completo, los pasos de preprocesamiento, el entrenamiento y la evaluación del modelo están disponibles en el Jupyter Notebook:

### 👉 [Abre el primer Jupyter Notebook](./CreditRiskAnalysis.ipynb)
### 👉 [Abre el segundo Jupyter Notebook](./CreditRiskAnalysis-K-Means.ipynb)
Los notebooks pueden visualizarse directamente desde GitHub sin necesidad de instalar software adicional.

## 📁 Estructura del Proyecto

```text
Credit_Risk_Analysis/
│
├── CreditRiskAnalysis.ipynb
├── CreditRiskAnalysis-K-Means.ipynb
├── README.md
└── dataset/
    └── german.data
    └── german.doc
    └── german_data.csv
```

## 📌 Objetivo

Este proyecto demuestra un flujo de trabajo completo y reproducible de Machine Learning, desde el preprocesamiento de datos hasta la evaluación del modelo.
En el primer notebook utilizamos un algoritmo clásico de clasificación estadística, la Regresión Logística.
En el segundo notebook usamos una algoritmo no supervisado, K-means, para realizar un proceso de segmentación de clientes.

⭐ Siéntete libre de explorar los notebooks para ver el análisis completo y la implementación.