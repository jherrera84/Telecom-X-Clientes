# TelecomX LATAM - Análisis de Evasión de Clientes

## Descripción

Este proyecto realiza un **Análisis Exploratorio de Datos (EDA)** sobre la evasión de clientes (*churn*) en **Telecom X LATAM**.  
El objetivo es identificar patrones de cancelación, variables asociadas al abandono del servicio y posibles oportunidades de retención.

El análisis fue desarrollado en un notebook de Jupyter/Colab e incluye:
- extracción de datos desde un archivo JSON,
- transformación y limpieza de datos,
- estandarización de nombres de columnas,
- análisis descriptivo,
- visualizaciones,
- conclusiones de negocio.

---

## Objetivo del proyecto

Analizar el comportamiento de cancelación de clientes para responder preguntas como:

- ¿Qué tipo de clientes cancelan más?
- ¿Qué servicios están asociados con mayor churn?
- ¿Qué métodos de pago o tipos de contrato representan mayor riesgo?
- ¿Qué segmentos podrían priorizarse en una estrategia de retención?

---

## Dataset

El notebook trabaja con un archivo en formato **JSON** llamado:

```bash
TelecomX_Data.json
```

Este archivo contiene información de clientes, servicios contratados, datos demográficos y variables relacionadas con la cancelación.

---

## Flujo del análisis

### 1. Extracción
Se cargan los datos desde un archivo JSON y se convierten a una estructura tabular para su análisis.

### 2. Transformación
Se realiza:
- normalización de datos,
- limpieza de valores,
- conversión de tipos,
- creación de variables derivadas,
- renombrado de columnas a nombres más claros en español.

### 3. Análisis exploratorio
Se generan estadísticas descriptivas y visualizaciones para analizar la relación entre la cancelación y variables como:
- tipo de contrato,
- método de pago,
- servicio de internet,
- antigüedad del cliente,
- cargos mensuales y totales,
- variables demográficas,
- servicios adicionales.

### 4. Informe final
Se sintetizan los principales hallazgos e insights accionables para negocio.

---

## Principales hallazgos

De acuerdo con el análisis realizado en el notebook:

- La tasa general de cancelación es de aproximadamente **26.5%**.
- Los clientes con contrato **mes a mes** presentan la mayor tasa de cancelación.
- El método de pago con **cheque electrónico** muestra mayor riesgo de churn.
- Los clientes con menor antigüedad tienen una mayor probabilidad de cancelar.
- La ausencia de servicios adicionales se relaciona con menor fidelización.
- Algunos clientes con **fibra óptica** presentan tasas de cancelación más elevadas, lo que puede sugerir problemas de precio, expectativa o calidad percibida.
- Existen segmentos demográficos con patrones diferenciados de cancelación que pueden explorarse en modelos posteriores.

---

## Tecnologías utilizadas

- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook / Google Colab**
- **JSON**

---

## Estructura esperada del proyecto

```bash
TelecomX-LATAM/
│
├── TelecomX_LATAM.ipynb
├── TelecomX_Data.json
└── README.md
```

---
