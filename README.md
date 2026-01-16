# Customer-Value-Prediction – Retail Sales
## 📌 Objetivo del proyecto

Este proyecto tiene como objetivo analizar el comportamiento de compra de clientes y clasificar su nivel de gasto utilizando técnicas de análisis de datos y machine learning, a partir de un dataset de ventas retail.

El proyecto cubre todo el flujo de un proyecto de ciencia de datos:

- Preparación y limpieza de datos

- Definición de una variable objetivo con sentido de negocio

- Entrenamiento y comparación de modelos de Machine Learning

- Evaluación de métricas y toma de decisiones basada en datos

- Exportación del modelo final para reutilización

## 🎯 Objetivo de negocio

Segmentar a los clientes según su nivel de gasto (Bajo, Medio, Alto) para:

- Apoyar estrategias de marketing segmentado

- Identificar clientes de mayor valor

- Facilitar la toma de decisiones comerciales basada en datos

## 📊 Dataset

Fuente: Customer Shopping Dataset – Retail Sales Data (Kaggle)

Principales variables:

- Demográficas: edad, género

- Transaccionales: categoría de producto, cantidad, precio

- Operativas: método de pago, centro comercial

- Temporal: fecha de compra

## 📂 Estructura del proyecto

data/

    raw/ # Datos originales

    processed/ # Dataset limpio para modelado

notebooks/
    
    01_preparacion_datos.ipynb

    02_modelo_clasificacion.ipynb

models/

    modelo_logistic_regression.pkl

requirements.txt

README.md

## 📘 Notebooks
🔹 Notebook 1 – Preparación de Datos

- Exploración y limpieza del dataset

- Construcción del gasto total del cliente

- Definición de la variable objetivo Nivel_Gasto

- Exportación del dataset final listo para ML

📌 Resultado: dataset limpio, consistente y alineado con objetivos de negocio.

🔹 Notebook 2 – Modelado de Machine Learning

- Entrenamiento y evaluación de múltiples modelos:

    Logistic Regression

    Random Forest

- Comparación de métricas (accuracy)

- Evaluación del impacto del Feature Engineering

- Selección del modelo final basada en desempeño y simplicidad

📌 Modelo final seleccionado:
👉 Logistic Regression, por ofrecer el mejor balance entre desempeño (~0.72 accuracy) e interpretabilidad.

## 📊 Resultados Clave

- El dataset presenta clases balanceadas, permitiendo usar accuracy como métrica principal.

- Modelos más complejos no superaron al modelo lineal, lo que evidencia que:

    La información disponible limita el desempeño predictivo.

    La complejidad del modelo no siempre implica mejores resultados.

    El Feature Engineering fue evaluado empíricamente y descartado cuando degradó el desempeño.

## 🛠️ Instalación y Uso

pip install -r requirements.txt

Ejecutar los notebooks en orden:

1. 01_preparacion_datos.ipynb

2. 02_modelado_ml.ipynb

## 📌 Autor

Silvio Guillén
