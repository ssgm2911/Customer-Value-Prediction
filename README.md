# Customer-Value-Prediction
📌 Objetivo del proyecto

Desarrollar un modelo de Machine Learning que permita identificar clientes de alto valor, con el fin de apoyar decisiones de segmentación, retención y optimización de campañas comerciales.

El proyecto demuestra cómo un modelo sencillo puede generar impacto real en el negocio, priorizando clientes con mayor probabilidad de generar ingresos.

🧠 Problema de negocio

Las empresas no pueden invertir el mismo presupuesto en todos los clientes.
Este proyecto busca responder la pregunta:

¿Podemos identificar clientes con alta probabilidad de generar mayores ingresos a partir de su historial de compras?

La solución permite:

- Priorizar campañas de marketing

- Mejorar estrategias de retención

- Optimizar el uso del presupuesto comercial

📊 Dataset

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
