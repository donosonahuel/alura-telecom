# Desafio Alura - Telecom X

<p>El objetivo de este challenge es usar todos los conocimientos fundamentales en el analisis exploratorio de datos (EDA) centrado en identificar los factores clave para comprender los patrones de comportamientos y así desarrollar estrategias según la situación utilizando visualizaciones inluido.</p>

Enlace al proyecto: [Google Colab](https://colab.research.google.com/drive/1PrRG8H-Wf5IZ3m0c0XKgzp5eo2WPTAtz?usp=sharing)

## En desarrollo:
- Extracción: ✅
- Transformación: ✅
- Carga y analisis: ✅
- Informe final: ✅

## 📦 Datos del Proyecto

Los datos iniciales para este análisis se encuentran en formato JSON.

* **`TelecomX_Data.json`**: Contiene la información inicial de los clientes, incluyendo sus detalles de cuenta y servicios.

## 🛠️ Dependencias

El notebook utiliza las siguientes librerías de Python:

* `pandas`
* `matplotlib`
* `seaborn`

Estas librerías ya están preinstaladas en Google Colab.

## 📊 Visualizaciones y Análisis Clave

El análisis se basa en diversas visualizaciones, incluyendo:

* **Distribución de Churn:** Proporción de clientes que han evadido.
* **Churn por Tipo de Contrato:** Impacto de la duración del contrato en la tasa de fuga.
* **Churn por Facturación Sin Papel:** Relación entre el método de facturación y la propensión a la fuga.
* **Churn por Método de Pago:** Influencia de los diferentes métodos de pago en el churn.
* **Cargos Mensuales vs. Churn:** Comparación de las distribuciones de cargos mensuales entre clientes activos y churned.
* **Cargos Totales vs. Churn:** Análisis de los cargos totales acumulados en relación con el churn.
* **Cuentas Diarias vs. Churn:** Evaluación de la actividad diaria del cliente y su impacto en la fuga.

Cada visualización va acompañada de un análisis detallado y observaciones.

## 💡 Conclusiones Destacadas

Las principales conclusiones giran en torno a:
* **Impacto de los contratos mes a mes:** Alta correlación con la fuga de clientes.
* **Valor Percibido del Servicio:** Los clientes que churnean tienden a tener cargos mensuales más altos, lo que sugiere una insatisfacción con el costo en relación con el valor recibido.
* **Fuga temprana:** El churn ocurre con mayor frecuencia en las etapas iniciales de la relación con el cliente (menores cargos totales acumulados).


## ✍️ Autor

Nahuel Donoso
