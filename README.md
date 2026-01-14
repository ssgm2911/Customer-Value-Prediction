# Customer-Value-Prediction
## 📌 Objetivo del proyecto

Desarrollar un modelo de Machine Learning que permita identificar clientes de alto valor, con el fin de apoyar decisiones de segmentación, retención y optimización de campañas comerciales.

El proyecto demuestra cómo un modelo sencillo puede generar impacto real en el negocio, priorizando clientes con mayor probabilidad de generar ingresos.

## 🧠 Problema de negocio

Las empresas no pueden invertir el mismo presupuesto en todos los clientes.
Este proyecto busca responder la pregunta:

¿Podemos identificar clientes con alta probabilidad de generar mayores ingresos a partir de su historial de compras?

La solución permite:

- Priorizar campañas de marketing

- Mejorar estrategias de retención

- Optimizar el uso del presupuesto comercial

## 📊 Dataset

El dataset proviene de transacciones de ventas retail y fue agregado a nivel cliente para el entrenamiento del modelo.

Variables utilizadas:

- Edad promedio del cliente

- Género

- Total de compras

- Cantidad total de productos comprados

- Gasto total

- Ticket promedio

Variable objetivo:

- cliente_alto_valor (binaria)

    1 → Cliente con gasto total dentro del top 30%

    0 → Resto de clientes

## ⚙️ Tecnologías y herramientas

- Python

- pandas, numpy

- scikit-learn

- matplotlib, seaborn

- Jupyter Notebook

- Git & GitHub

## 🧪 Metodología

1️⃣ Limpieza y preparación de datos

2️⃣ Feature engineering a nivel cliente

3️⃣ Definición de la variable objetivo

4️⃣ División entrenamiento / prueba

5️⃣ Entrenamiento del modelo

6️⃣ Evaluación e interpretación de resultados

## 🤖 Modelo de Machine Learning

- Tipo: Clasificación supervisada

- Modelo utilizado: Random Forest Classifier

- Motivo de elección:

    Buen desempeño con datos tabulares

    Fácil interpretación de importancia de variables

    Robustez ante outliers

## 📈 Métricas de evaluación

El modelo fue evaluado utilizando:

- Accuracy

- Precision

- Recall

- Matriz de confusión

📌 El enfoque principal está en la interpretación del modelo y su utilidad para el negocio, más que en maximizar métricas.

## 🧠 Interpretación de negocio

El modelo permite identificar clientes con alta probabilidad de generar mayores ingresos, lo que facilita:

- Enfocar campañas de fidelización

- Diseñar promociones personalizadas

- Reducir costos en campañas poco efectivas

- Mejorar el retorno de inversión (ROI)

## 📂 Estructura del proyecto

data/

    raw/

        ventas.csv

    processed/

        clientes_features.csv

notebooks/
    
        01_preparacion_datos.ipynb

        02_modelo_clasificacion.ipynb

models/

        modelo_cliente_valor.pkl

requirements.txt

README.md

## 🚀 Próximos pasos

- Probar otros modelos de clasificación

- Ajustar el umbral de clasificación según objetivos de negocio

- Analizar la evolución del valor del cliente en el tiempo

- Integrar el modelo en un dashboard de seguimiento

## 📌 Autor

Silvio Guillén
